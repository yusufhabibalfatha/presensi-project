# DOKUMENTASI FAKTA & SPESIFIKASI APLIKASI
> **Tujuan Dokumen:** Referensi tunggal (*single source of truth*) fakta teknis, fitur, arsitektur, dan alur kerja aplikasi untuk instruksi AI berikutnya dalam menyusun konten halaman website pemasaran SEO.

---

## 1. Identitas Sistem & Model Bisnis

* **Kategori Produk:** Sistem Informasi Presensi Siswa Per Jam Pelajaran, Jurnal Mengajar Digital Guru, dan Otomatisasi Notifikasi WhatsApp Gateway.
* **Arsitektur Teknis:** Headless Web App terpisah (*Decoupled*):
  * **Backend:** Direktori `bubsv2` (PHP 8+, CodeIgniter 4 RESTful API, MySQL/MariaDB).
  * **Frontend:** Direktori `frontend-absensi` (Vue 3 Composition API, Vite, Neo-Brutalism Design System).
* **Model Penjualan / Distribusi (Managed Private SaaS / All-in-One Solution):**
  * **Bukan Penjualan Source Code Mentah:** Klien (sekolah/yayasan) tidak diberikan source code aplikasi.
  * **Sistem Terima Beres (White-Glove Service):** Klien membeli paket all-in-one yang sudah mencakup:
    1. **Penyediaan Server Hosting & Domain Khusus Sekolah** (misal: `presensi.sekolah.sch.id` atau domain mandiri).
    2. **Instalasi Awal & Konfigurasi Penuh** (Setup database, migrasi tabel, linking frontend-backend, dan integrasi token WhatsApp Gateway).
    3. **Pendampingan Onboarding:** Sekolah tinggal menggunakan aplikasi tanpa memerlukan staf IT/DevOps internal.
  * **Keunggulan Privasi Data:** Data siswa, guru, dan nilai bersifat privat di server masing-masing sekolah, bukan multi-tenant bersama yang dicampur aduk dengan sekolah lain.

---

## 2. Arsitektur & Spesifikasi Teknologi

### A. Backend (`bubsv2`)
* **Framework:** CodeIgniter 4 (PHP 8+).
* **Basis Data:** MySQL / MariaDB dengan skema tabel relasional (InnoDB, Foreign Keys, Timestamp otomatis).
* **Kebutuhan Server:** Sangat ringan dan efisien, dapat berjalan mulus di cPanel Hosting, Cloud Hosting, maupun VPS Linux standar tanpa perlu dependensi rumit Node.js server.
* **Integrasi Eksternal:** Fonnte WhatsApp Gateway API (`https://api.fonnte.com/send`):
  * Mendukung mekanisme *Bulk Sending* via cURL JSON payload.
  * Otentikasi berbasis *Bearer/Authorization Token* per unit sekolah.
  * Pencatatan log lengkap: status kirim (`berhasil`, `gagal`, `pending`), target nomor/ID grup, pesan ID Fonnte, dan alasan error (*reason*).

### B. Frontend (`frontend-absensi`)
* **Framework:** Vue 3 (Script Setup), Vue Router 4, Axios, Vite.
* **Design System & Tampilan:** **Neo-Brutalism Style** (kontur border hitam tebal, bayangan tegas/*hard shadow*, warna kontras tinggi, palet cerah kuning/biru/hijau/merah).
* **Karakteristik Tampilan:**
  * **Mobile-First Responsive:** Didesain khusus untuk layar *smartphone* guru agar mudah dioperasikan di dalam kelas hanya dengan satu tangan.
  * **Touch-Friendly:** Tombol-tombol besar (*thumb-friendly*), indikator status visual dengan badge warna tegas.
  * **Penyimpanan Draft Sesi:** Memanfaatkan `sessionStorage` (`presensi_draft_jadwal`) sehingga data kelas/mapel/guru tidak hilang saat berpindah antar halaman.

---

## 3. Fitur-Fitur Faktual Aplikasi

### Modul 1: Presensi Siswa Berbasis Jam Pelajaran (Per-Mapel)
* **Bukan Sekadar Absen Gerbang Pagi:** Presensi dilakukan **per mata pelajaran dan jam pelajaran**, menyelesaikan masalah siswa yang hadir di awal pagi namun bolos di jam pelajaran siang/tengah.
* **Wizard 4 Langkah Cepat (Pilih Jadwal):**
  1. *Langkah 1:* Pilih Kelas (terfilter sesuai tahun ajaran aktif).
  2. *Langkah 2:* Pilih Mata Pelajaran.
  3. *Langkah 3:* Pilih Jam Pelajaran (Jam Ke, Jam Mulai, Jam Selesai).
  4. *Langkah 4:* Pilih Guru Pengampu (mendukung penugasan guru lintas jenjang).
* **Status Presensi 5 Kategori:**
  * `Hadir` (Hijau)
  * `Terlambat` (Kuning)
  * `Izin` (Biru)
  * `Sakit` (Oranye)
  * `Alpa` / Bolos (Merah)
* **Fitur Aksi Cepat (Quick Actions):**
  * Tombol **"Tandai Semua Hadir"** (1 klik untuk mengubah seluruh siswa menjadi status Hadir).
  * Tombol **"Reset Status"** untuk mengosongkan status seluruh siswa.
  * Batalkan status perorangan dengan 1 klik.
* **Modal Detail Tambahan Per Siswa:**
  * Input nilai harian / nilai tugas siswa pada pertemuan tersebut.
  * Input keterangan khusus (misal: "Izin dinas OSIS", "Sakit demam surat terlampir").
  * Input catatan perilaku siswa di kelas.

### Modul 2: Jurnal Mengajar Digital Terintegrasi
* **Validasi Wajib Isi Materi:** Form absensi memvalidasi bahwa kolom **Materi Pembelajaran wajib diisi** sebelum tombol simpan dapat ditekan. Guru tidak bisa menyimpan absensi kosong tanpa mencatat apa yang diajarkan.
* **Catatan Jurnal KBM:** Tersedia kolom catatan guru untuk mencatat kejadian kelas, progres bab/tugas, atau pekerjaan rumah (PR).
* **Digitalisasi Paperless:** Menggantikan buku jurnal kertas fisik yang rawan hilang, basah, rusak, atau baru diisi rapelan di akhir semester saat supervisi kurikulum.

### Modul 3: Otomatisasi Notifikasi WhatsApp Gateway (Fonnte)
* **Broadcast Otomatis Sekali Klik:** Saat guru menekan *"Simpan Absensi & Kirim ke Grup WA Kelas"*, backend secara otomatis menyusun format laporan rapi ber-emoji dan menembakkannya langsung ke WhatsApp Grup Kelas.
* **Format Pesan Ringkasan Presensi:**
  * Header: Nama Kelas, Hari/Tanggal (Bahasa Indonesia), Mata Pelajaran, Rentang Jam, Nama Guru Pengampu, dan Materi Pembelajaran.
  * Rincian Siswa: Dikelompokkan rapi per kategori (Hadir, Terlambat, Izin, Sakit, Alpa) lengkap dengan alasan/keterangan jika ada.
  * Footer: Total jumlah siswa terdaftar di kelas.
* **Monitoring Log WhatsApp Gateway:**
  * Halaman khusus pelacakan log pengiriman WhatsApp dengan filter tanggal dan status.
  * Deteksi status real-time: `berhasil`, `gagal`, `pending`.
  * **Fitur Resend Tunggal:** Mengirim ulang pesan tertentu yang gagal.
  * **Fitur Bulk Resend ("Kirim Ulang Semua Gagal"):** Mengirim ulang seluruh pesan yang gagal/pending pada tanggal terpilih secara massal dalam 1 kali klik.

### Modul 4: Dashboard Utama & Statistik Harian
* **Hero Welcome:** Menampilkan informasi hari aktif dan tanggal otomatis.
* **Ringkasan Master Data:** Total guru aktif, total kelas aktif, dan total siswa aktif di tahun ajaran berjalan.
* **Ringkasan Jurnal Hari Ini:** Menghitung berapa sesi KBM/jurnal yang telah selesai diisi pada tanggal terpilih.
* **Statistik Kehadiran Hari Ini:** Menampilkan total akumulasi siswa yang Hadir, Terlambat, Izin, Sakit, dan Alpa secara real-time.
* **Status WhatsApp Gateway Hari Ini:** Menampilkan indikator performa pesan WA (Pesan Terkirim vs Pesan Gagal/Pending).

### Modul 5: Rekapitulasi & Laporan (Tanpa Excel Manual)
* **Tab 1 - Riwayat Jurnal:** Menampilkan log seluruh jurnal mengajar dengan filter tanggal, jenjang, kelas, dan guru pengampu. Dilengkapi modal detail untuk melihat daftar absensi siswa di setiap pertemuan.
* **Tab 2 - Rekap Persentase Siswa:** Menghitung otomatis persentase kehadiran siswa per kelas dalam rentang periode tertentu. Memudahkan tim kurikulum/BK dan wali kelas saat pembagian rapor.

### Modul 6: Master Data & Manajemen Multi-Sekolah
* **Manajemen Multi-Jenjang/Sekolah:** Mendukung satu naungan yayasan dengan banyak unit (misal: SMP dan SMA) dalam satu sistem terintegrasi.
* **Master Sekolah & Token WhatsApp:** Pengaturan nama sekolah, alamat, toggle on/off fitur WhatsApp, dan token API Fonnte per unit sekolah.
* **Master Kelas & Penautan Grup WA:** Data kelas dilengkapi kolom `ID Grup WhatsApp` agar pesan otomatis mendarat di grup yang tepat.
* **Master Siswa & Penempatan Siswa-Kelas:** Manajemen data siswa (NIS/NISN, nama, jenis kelamin) dan penempatan rombel kelas per tahun ajaran.
* **Master Guru:** Pencatatan nama guru, NIP, no HP/WhatsApp, dan status aktif.
* **Master Mata Pelajaran & Tahun Ajaran:** Manajemen daftar mata pelajaran serta penentuan tahun ajaran aktif dan semester (Ganjil/Genap).

---

## 4. Fitur Ekstra yang Sudah Tersedia di Backend (`bubsv2`)

Selain modul presensi mapel siswa, backend `bubsv2` sudah memiliki skema database dan controller matang untuk modul tambahan:

1. **Modul Absensi Guru Berbasis Lokasi GPS:**
   * Validasi posisi guru menggunakan koordinat Latitude & Longitude sekolah dengan formula jarak Haversine (menghitung radius meter guru dari pusat sekolah).
   * Deteksi jam masuk dan jam pulang guru.
   * Notifikasi otomatis ke Grup WhatsApp Guru / Kepala Sekolah mengenai kehadiran guru (status Hadir/Terlambat, jarak meter dari kampus, dan waktu absen).
2. **Modul Manajemen Keuangan & SPP Siswa:**
   * Pengaturan Pos Tagihan (SPP bulanan, uang gedung, seragam, dll.).
   * Generate tagihan massal per kelas/angkatan.
   * Pencatatan transaksi pembayaran siswa dan cetak kuitansi.
   * Matriks rekapitulasi pembayaran per kelas.
   * Fitur Reminder Tagihan via WhatsApp langsung ke nomor wali murid.
   * Keamanan ekstra dengan verifikasi PIN Keuangan.

---

## 5. Masalah Nyata yang Dipecahkan (Pain Points & Solutions)

| Masalah Sekolah Konvensional | Solusi yang Dihadirkan Aplikasi Ini |
| :--- | :--- |
| **Siswa Bolos di Jam Pelajaran Siang** (Hadir apel pagi, lalu kabur di jam ke-4 atau setelah istirahat). | Presensi dicatat **per mata pelajaran dan jam pelajaran**, bukan sekadar absen gerbang pagi. |
| **Buku Jurnal Fisik Rusak / Sering Tidak Diisi** (Guru baru mencatat jurnal secara rapelan saat ada supervisi). | Sistem memvalidasi input materi KBM secara digital sebelum absensi bisa disimpan. |
| **Wali Murid Tidak Mengetahui Kondisi Anak di Kelas** (Guru malas mengirim WA satu per satu ke orang tua). | Sistem mengirimkan laporan otomatis ke WhatsApp Grup Kelas begitu guru selesai mengabsen dalam hitungan detik. |
| **Rekapitulasi Manual Menyita Waktu Guru/TU** (Menghitung ribuan baris di Excel setiap akhir semester). | Dashboard rekapitulasi otomatis menghitung persentase kehadiran dan riwayat KBM secara instan. |
| **Biaya SaaS Mahal Berbasis Jumlah Siswa** (Biaya Rp 2.000–Rp 5.000/siswa/bulan sangat membebani kas sekolah). | Model Managed Solution dengan paket server & domain sendiri: **biaya tetap tahunan, kuota siswa & guru tak terbatas**. |
| **Kekhawatiran Keamanan Data Siswa** (Data sekolah tersimpan di server pihak ketiga bersama ratusan sekolah lain). | Server hosting dan database bersifat privat milik sekolah masing-masing, data tidak digabung atau dijual. |

---

## 6. Target Pengguna & Segmen Pasar

1. **Sekolah Swasta & Madrasah (SD/MI, SMP/MTs, SMA/MA, SMK):**
   * Sangat membutuhkan peningkatan nilai jual (*branding*) dan transparansi ke wali murid untuk meningkatkan penerimaan siswa baru.
2. **Yayasan Pendidikan Islam / Pesantren Terpadu:**
   * Memerlukan integrasi multi-unit (SMP & SMA) dan pengawasan santri yang ketat pada jam KBM.
3. **Sekolah Negeri yang Menginginkan Digitalisasi Cepat:**
   * Membutuhkan sistem yang siap pakai tanpa birokrasi penyediaan tim teknis IT rumit.

---
*Dokumen ini disusun untuk menjadi bahan acuan pembuatan konten halaman website (Beranda, Fitur, Harga, Demo, Blog, Tentang Kami, dan Kontak).*
