# RANCANGAN ARTIKEL SEO — P2-C2 (`contoh rekap absen siswa per bulan`)

- **ID Klaster:** Pilar 2 — Cluster 2.2 (P2-C2)
- **Tipe Halaman:** Artikel Cluster (Edukatif & Contoh Format Siap Pakai)
- **Target Slug URL:** `/blog/contoh-rekap-absen-siswa-per-bulan-dan-semester/`
- **Primary Keyword:** `contoh rekap absen siswa per bulan` (Vol: 390, SD: 26)
- **Secondary / LSI Keywords:**
  - `contoh rekap absen siswa per bulan manual` (Vol: 260, SD: 18)
  - `cara menghitung absen siswa per bulan` (Vol: 140, SD: 26)
  - `cara menghitung persentase absen siswa per bulan` (Vol: 140, SD: 18)
  - `contoh rekap absen siswa per semester` (Vol: 140, SD: 18)
- **Outbound Internal Link Target:** P2-HUB (`contoh rekapitulasi absen siswa`), `/fitur/` (`rekap absen siswa per bulan`), `/` (`aplikasi absen siswa`)
- **Target Gaya Bahasa:** Santai, ramah (*humanized*), empatik terhadap beban administrasi menjelang rapor, kalimat ringkas & paragraf pendek (maksimal 2–3 baris per `<p>`).

---

## LANGKAH 1: Membedah Search Intent & Value Add (Sebelum Menulis)

### 1. Profil Pembaca & Search Intent
- **Siapa Pembacanya:** Wali Kelas, Guru Mata Pelajaran, Guru BK, Wakasek Kurikulum, dan Operator/Staf TU (SD, SMP, SMA/SMK).
- **Apa yang Mereka Cari:** Contoh nyata bentuk tabel rekap absensi bulanan dan akumulasi semester untuk laporan ke Kepala Sekolah, pembinaan Guru BK, serta input nilai kedisiplinan di e-Rapor/Rapor Semester. Mereka tidak sekadar ingin teori, melainkan contoh tabel siap tiru beserta cara menjumlahkan rekapnya per bulan.

### 2. Pain Points Nyata di Sekolah
1. **Format antar-bulan sering tidak konsisten:** Bulan ini hari efektifnya 22 hari, bulan depan 19 hari karena ujian/libur—saat direkap ke semester, angka pembaginya suka salah.
2. **Menyalin ulang 6 bulan kertas ke lembar semester:** Wali kelas harus memindahkan angka S, I, A dari enam lembar bulanan yang berbeda lalu menjumlahkannya satu per satu jelang pembagian rapor.
3. **Sulit menggabungkan data guru mapel:** Catatan kehadiran dari banyak guru mata pelajaran menumpuk dan kadang berbeda dengan catatan harian piket kelas.

### 3. Aset Konkret (Information Gain / Nilai Tambah) yang Wajib Ada di Artikel
1. **Tabel HTML Simulasi 1 — Contoh Rekap Absen Siswa Per Bulan Manual (5 Siswa):** Memuat seluruh kolom wajib (`No`, `Nama Siswa`, `Hari Efektif`, `Hadir (H)`, `Sakit (S)`, `Izin (I)`, `Alpa (A)`, dan `Persentase Kehadiran (%)`) dalam skala 1 bulan penuh (22 hari efektif).
2. **Blok Rumus Cepat Perhitungan Bulanan & Excel (`COUNTIF`):** Rumus `Persentase Hadir (%)`, `Persentase Alpa (%)`, serta rumus Excel `=COUNTIF(D5:AH5; "H")` dan `=(I5/25)*100%` agar guru tinggal tempel saat menyusun laporan bulanan.
3. **Tabel HTML Simulasi 2 — Contoh Rekap Absen Siswa Per Semester untuk Rapor & BK (6 Bulan):** Menampilkan kolom ringkas akumulasi Juli–Desember (`Total Hari Efektif`, `Total H`, `Total S`, `Total I`, `Total A`, `Persentase Kehadiran (%)`, dan `Status Pembinaan BK / Rapor`) sebagai nilai tambah konkret bagi wali kelas.
4. **Checklist Validasi Data Lintas Guru Mapel Sebelum Cetak Rapor:** Poin cepat mengecek kecocokan izin sakit dan alpa sebelum rapor dicetak dan ditandatangani Kepala Sekolah.
5. **Kotak CTA & Solusi Otomasi Sekali Klik:** Mengarahkan pembaca ke **Web Absen Mapel Sekolah "Terima Beres"** (ekspor PDF/Excel otomatis bulanan & semester, termasuk domain, hosting, dan gratis input data siswa dari Excel).

---

## LANGKAH 2: Menyusun Kerangka Heading Semantik & Pemetaan Keyword

Agar artikel tetap **ringkas, santai, mudah dipindai, dan langsung bisa dipraktikkan** (estimasi ~1.050–1.250 kata, paragraf maksimal 2–3 baris), struktur *heading* mengikuti alur nyata guru dari menyiapkan rekap bulanan hingga menggabungkannya untuk rapor semester.

### 1. Hierarki Heading Semantik (`H1` – `H3`)

- **`H1`:** **Contoh Rekap Absen Siswa Per Bulan** & Per Semester Lengkap untuk Rapor
  - *Intro PAS (3 paragraf pendek, ~90–115 kata):* Menyapa kerepotan wali kelas di tanggal tutup buku bulanan dan jelang pembagian rapor, serta merangkum contoh tabel & rumus yang dibahas di panduan ini.
- **`H2`:** Format & Tabel **Contoh Rekap Absen Siswa Per Bulan Manual**
  - Penjelasan singkat kolom wajib pada lembar rekap akhir bulan (kop kelas, hari efektif KBM, total `H/S/I/A`, persentase hadir, tanda tangan).
  - **Tabel HTML Simulasi 1 (5 Siswa — 22 Hari Efektif):** Memuat kolom `No`, `Nama Siswa`, `Hari Efektif`, `Hadir (H)`, `Sakit (S)`, `Izin (I)`, `Alpa (A)`, dan `Persentase Kehadiran (%)`.
- **`H2`:** Panduan **Cara Menghitung Absen Siswa Per Bulan** Berdasarkan Hari Efektif KBM
  - Penjelasan singkat cara menetapkan angka pembagi berdasarkan **Hari Efektif Kalender Pendidikan** (membedakan hari KBM aktif dengan tanggal merah/ujian/libur).
  - **`H3`:** **Cara Menghitung Persentase Absen Siswa Per Bulan** Secara Akurat
    - Blok visual rumus matematika (`Persentase Hadir (%)` & `Persentase Alpa (%)`) + kotak rumus Excel siap pakai (`=COUNTIF(D5:AH5; "H")` dan `=(I5/25)*100%`) dengan tips pemisah `;` vs `,`.
- *(Penempatan Mid-Content CTA Box di Langkah 4)*
- **`H2`:** Tabel **Contoh Rekap Absen Siswa Per Semester** untuk Pengisian Rapor & BK
  - **Tabel HTML Simulasi 2 (5 Siswa — Akumulasi 6 Bulan Juli–Desember):** Menampilkan rincian jumlah tidak hadir tiap bulan dan akumulasi total `H`, `S`, `I`, `A`, `Persentase Kehadiran (%)`, serta kolom catatan tindak lanjut Guru BK / e-Rapor.
  - Tips singkat cara menjumlahkan 6 lembar bulanan tanpa keliru pembagi semester (misal total 118 hari efektif dalam 1 semester).
- **`H2`:** Kendala Menggabungkan Rekap Bulanan dari Banyak Guru Mapel
  - 3 masalah klasik (perbedaan catatan piket vs guru mapel, kertas terselip, salah salin ke e-Rapor) + *checklist* validasi cepat sebelum rapor ditandatangani Kepala Sekolah.
- **`H2`:** Unduh Rekap Bulanan & Semester Sekali Klik dengan Web Presensi Sekolah
  - Penjelasan solusi otomatis **Web Absen Mapel Sekolah "Terima Beres"** (ekspor PDF berkop sekolah & Excel dalam 1 klik tanpa menumpuk berkas bulanan) + jembatan ke End CTA.
- **`H2`:** Pertanyaan Umum Seputar Rekap Absen Bulanan & Semester (FAQ)
  - **`H3`:** Apakah jumlah hari efektif setiap bulan selalu sama saat membuat rekap absen?
  - **`H3`:** Bagaimana cara mengubah rekap bulanan menjadi rekap semester untuk e-Rapor?
  - **`H3`:** Bisa tidak sekolah langsung dapat file rekap PDF dan Excel bulanan secara otomatis?

### 2. Pemetaan Target Keyword (Zero Keyword Stuffing)

| Kategori | Keyword Target | Penempatan Utama |
| --- | --- | --- |
| **Primary Keyword** | `contoh rekap absen siswa per bulan` | `<title>`, `H1`, Intro paragraf 1, Penutup |
| **Secondary 1** | `contoh rekap absen siswa per bulan manual` | Meta description, `H2 #1`, pengantar Tabel Simulasi 1 |
| **Secondary 2** | `cara menghitung absen siswa per bulan` | `H2 #2` & paragraf pembuka Hari Efektif KBM |
| **Secondary 3** | `cara menghitung persentase absen siswa per bulan` | `H3` di bawah `H2 #2` & paragraf rumus |
| **Secondary 4** | `contoh rekap absen siswa per semester` | Meta description, `H2 #3`, pengantar Tabel Simulasi 2 |

### 3. Rencana Pemetaan Internal Link & CTA (Disiapkan untuk Langkah 4)
- **Ke P2-HUB (Upward Link):** `../panduan-cara-rekap-absen-siswa/` dengan anchor exact `contoh rekapitulasi absen siswa`.
- **Ke Money Page `/fitur/`:** `../../fitur/` dengan anchor exact `rekap absen siswa per bulan`.
- **Ke Money Page `/` (Beranda):** `../../` dengan anchor exact `aplikasi absen siswa`.
- **Cross-link kontekstual ke P2-C1:** `../cara-menghitung-persentase-absen-siswa/` (untuk pembaca yang ingin pendalaman khusus hitung manual vs mapel).
- **Anti-Kanibalisasi:** Artikel ini berfokus pada **struktur tabel & konsolidasi laporan per bulan menjadi per semester** untuk Rapor/BK, bukan panduan langkah kerja harian wali kelas (P2-C3) ataupun rumus hitung dasar semata (P2-C1).

---

## LANGKAH 3: Menulis Konten per Bagian (Chunking & Gaya Humanized)

> **Catatan Gaya Bahasa:** Paragraf pendek maksimal 2–3 baris, ringan dan mengalir layaknya sesama wali kelas berbagi format rapor, bebas basa-basi kaku. Penempatan *internal link* dan 2 blok CTA disuntikkan secara terstruktur pada Langkah 4.

### Bagian 1: Heading Utama & Intro (PAS Ringkas)

**`H1`: Contoh Rekap Absen Siswa Per Bulan & Per Semester Lengkap untuk Rapor**

Begitu kalender masuk minggu terakhir, biasanya wali kelas mulai sibuk membuka tumpukan lembar daftar hadir harian. Memang paling enak kalau dari awal sudah punya **contoh rekap absen siswa per bulan** yang kolomnya rapi dan langsung nyambung ke format rapor.

Soalnya, kalau catatan bulanan masih tercecer di lembaran terpisah, pas akhir semester nanti Bapak/Ibu bakal kerja dua kali. Menyalin ulang data Sakit, Izin, dan Alpa enam bulan sekaligus itu capeknya bukan main.

Di halaman ini, sudah kami siapkan contoh tabel rekap bulanan manual, cara hitung hari efektifnya, hingga tabel akumulasi semester siap pakai untuk BK dan e-Rapor.

---

### Bagian 2: Format & Tabel Contoh Rekap Bulanan Manual

**`H2`: Format & Tabel Contoh Rekap Absen Siswa Per Bulan Manual**

Pada praktiknya, sebuah **contoh rekap absen siswa per bulan manual** yang rapi tidak perlu terlalu ramai hiasan. Yang penting, pengawas sekolah, Guru BK, dan orang tua bisa langsung membaca total ketidakhadiran tanpa harus membuka halaman harian lagi.

Pastikan bagian kepala (*kop*) lembar rekap mencantumkan Nama Sekolah, Kelas/Rombel, Bulan, serta jumlah **Hari Efektif KBM**. Lalu di isi tabel, pakai susunan kolom berikut (simulasi Bulan November, 22 Hari Efektif):

| No | Nama Siswa | Hari Efektif | Hadir (H) | Sakit (S) | Izin (I) | Alpa (A) | Persentase Kehadiran (%) |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | Alya Putri Maharani | 22 | 22 | 0 | 0 | 0 | **100%** |
| 2 | Bagas Pratama | 22 | 20 | 2 | 0 | 0 | **90,9%** |
| 3 | Dina Kusumawardani | 22 | 19 | 1 | 1 | 1 | **86,4%** |
| 4 | Farhan Ramadhan | 22 | 17 | 1 | 2 | 2 | **77,3%** |
| 5 | Nadia Sari Dewi | 22 | 15 | 2 | 1 | 4 | **68,2%** |

Di bagian paling bawah kertas rekap bulanan, cukup beri tempat tanda tangan Wali Kelas di sisi kanan dan mengetahui Kepala Sekolah di sisi kiri. Format seperti ini sudah sangat layak dilampirkan sebagai laporan bulanan resmi kelas.

---

### Bagian 3: Panduan Hitung Hari Efektif & Rumus Persentase Bulanan

**`H2`: Panduan Cara Menghitung Absen Siswa Per Bulan Berdasarkan Hari Efektif KBM**

Hal paling sering bikin selisih angka saat **cara menghitung absen siswa per bulan** dilakukan oleh beda guru adalah patokan hari efektifnya. Jangan sampai sebulan dianggap rata 25 atau 30 hari terus.

Cara benarnya, hitung dulu jumlah hari saat kegiatan belajar mengajar (KBM) benar-benar berjalan di kalender pendidikan bulan itu. Hari Minggu, tanggal merah nasional, cuti bersama, dan libur khusus sekolah wajib dikeluarkan dari pembagi.

Misalnya bulan Juli cuma aktif **16 hari efektif** karena ada libur awal tahun dan MPLS, sedangkan bulan November penuh **22 hari efektif**. Nah, angka hari aktif inilah yang menjadi pembagi resmi tiap bulan.

**`H3`: Cara Menghitung Persentase Absen Siswa Per Bulan Secara Akurat**

Setelah total **H, S, I, dan A** dalam satu bulan ketemu, lanjutkan **cara menghitung persentase absen siswa per bulan** memakai rumus sederhana berikut ini:

> **Rumus Manual & Excel Rekap Bulanan:**
> - **Persentase Hadir (%)** = `(Jumlah Hari/Jam Hadir ÷ Total Hari/Jam Efektif) × 100%`
> - **Persentase Alpa (%)** = `(Jumlah Alpa ÷ Total Hari/Jam Efektif) × 100%`
> - **Rumus Excel Dasar (baris ke-5, kolom tanggal `D5:AH5`):**
>   - Hitung total Hadir (`I5`): `=COUNTIF(D5:AH5; "H")` *(pakai koma `,` bila laptop setelan bahasa Inggris)*
>   - Hitung persentase dari 25 hari efektif: `=(I5/25)*100%` *(sesuaikan angka `25` dengan hari efektif bulan berjalan)*

Contoh gampangnya pada baris Bagas di atas: karena hadir 20 kali dari 22 hari efektif November, hitungannya `(20 ÷ 22) × 100% = 90,9%`. Sedangkan Nadia yang alpa 4 hari memiliki persentase Alpa `(4 ÷ 22) × 100% = 18,2%`.

*(Sisipan Mid-Content CTA di Langkah 4)*

---

### Bagian 4: Tabel Rekap Semester untuk Rapor & Guru BK

**`H2`: Tabel Contoh Rekap Absen Siswa Per Semester untuk Pengisian Rapor & BK**

Saat musim pembagian rapor tiba, wali kelas tinggal menjumlahkan rekap 6 bulan menjadi satu lembar **contoh rekap absen siswa per semester**. Pembaginya pun berganti menjadi **Total Hari Efektif 1 Semester** (misalnya Juli 16 + Agt 21 + Sep 21 + Okt 22 + Nov 22 + Des 16 = **118 hari efektif**).

Berikut contoh tabel ringkasan satu semester agar kolom e-Rapor dan pantauan Guru BK langsung siap isi:

| No | Nama Siswa | Hari Efektif (1 Smst) | Hadir (H) | Sakit (S) | Izin (I) | Alpa (A) | Persentase Kehadiran (%) | Catatan Rapor / BK |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 1 | Alya Putri Maharani | 118 | 117 | 1 | 0 | 0 | **99,2%** | Aman / Teladan |
| 2 | Bagas Pratama | 118 | 111 | 4 | 2 | 1 | **94,1%** | Aman (Sesuai Surat) |
| 3 | Dina Kusumawardani | 118 | 106 | 4 | 4 | 4 | **89,8%** | Pantau Wali Kelas |
| 4 | Farhan Ramadhan | 118 | 98 | 5 | 6 | 9 | **83,1%** | Panggil Orang Tua I |
| 5 | Nadia Sari Dewi | 118 | 88 | 6 | 5 | 19 | **74,6%** | Wajib Pembinaan BK |

Dengan menaruh kolom catatan di ujung kanan, Guru BK langsung punya bukti kuat sebelum rapat kenaikan kelas dimulai. Orang tua juga bisa menerima data yang jelas, bukan sekadar perkiraan.

---

### Bagian 5: Kendala Gabung Data Mapel & Checklist Validasi

**`H2`: Kendala Menggabungkan Rekap Bulanan dari Banyak Guru Mapel**

Di jenjang SMP, SMA, dan SMK, wali kelas sering pusing karena harus menyinkronkan catatan piket pagi dengan jurnal belasan guru mata pelajaran. Ada saja kejadian siswa pagi hadir saat apel, eh pas jam pelajaran ke-5 malah tidak ada di kelas.

Supaya tidak salah ketik saat memindahkan ke e-Rapor, cek dulu 4 hal singkat ini sebelum berkas dicetak:

1. **Samakan total H + S + I + A setiap siswa:** Pastikan jumlah keempatnya persis sama dengan angka Hari Efektif bulan atau semester itu (contoh: `98 + 5 + 6 + 9 = 118`). Kalau kurang satu hari saja, berarti ada tanggal yang kelewat diisi.
2. **Cocokkan surat dokter dan izin WA orang tua:** Jangan sampai anak yang izin lewat wali kelas malah ditulis Alpa (A) di rekap guru mapel.
3. **Konfirmasi siswa dengan Alpa beruntun ke Guru BK:** Koordinasikan lebih awal sebelum angka Alpa menembus batas aturan tata tertib sekolah.
4. **Pisahkan status Dispen / Lomba sekolah:** Siswa yang ikut kegiatan lomba atau OSIS tetap dihitung **Hadir (H)** atau diberi keterangan khusus, jangan dimasukkan ke Izin/Alpa.

---

### Bagian 6: Solusi Sekali Klik & Penutup

**`H2`: Unduh Rekap Bulanan & Semester Sekali Klik dengan Web Presensi Sekolah**

Menyiapkan tabel manual maupun Excel tiap akhir bulan memang bisa dikerjakan. Namun kalau wali kelas memegang 36 siswa dan sekolah punya belasan rombel, mengulang rekap bulanan hingga semesteran jelas memakan jam mengajar dan waktu keluarga di rumah.

Bayangkan kalau guru mapel dan wali kelas cukup absen lewat HP di dalam kelas, lalu rekap bulanan serta semester otomatis tersusun sendiri tanpa perlu menjumlahkan kertas lagi.

Dengan **Web Absen Mapel Sekolah "Terima Beres"**, seluruh catatan harian langsung berubah menjadi laporan bulanan dan semester siap cetak (PDF berkop sekolah & Excel) hanya dengan sekali klik.

*(Sisipan End-Content CTA di Langkah 4)*

---

### Bagian 7: FAQ Singkat (Schema-Ready)

**`H2`: Pertanyaan Umum Seputar Rekap Absen Bulanan & Semester**

**`H3`: Apakah jumlah hari efektif setiap bulan selalu sama saat membuat rekap absen?**
Tidak. Setiap bulan memiliki jumlah hari efektif KBM yang berbeda tergantung libur nasional, cuti bersama, atau jadwal ujian sekolah. Selalu cek Kalender Pendidikan sebelum mengisi angka pembagi persentase.

**`H3`: Bagaimana cara mengubah rekap bulanan menjadi rekap semester untuk e-Rapor?**
Cukup jumlahkan kolom total Hadir, Sakit, Izin, dan Alpa dari keenam lembar bulanan (misalnya Juli sampai Desember), lalu bagi dengan total hari efektif selama satu semester tersebut. Pastikan jumlah `H + S + I + A` cocok dengan total hari efektifnya.

**`H3`: Bisa tidak sekolah langsung dapat file rekap PDF dan Excel bulanan secara otomatis?**
Bisa. Melalui layanan Web Absen Mapel Sekolah Terima Beres dari Presensi Project, laporan rekap harian, bulanan, hingga akumulasi semester langsung terhitung otomatis dan bisa diunduh dalam format PDF maupun Excel kapan saja.

---

## LANGKAH 4: Menyuntikkan Internal Link Kontekstual & 2 Kotak CTA Strategis

### 1. Peta Penempatan Internal Link (Zero Cannibalization)

| Lokasi Penempatan | Anchor Text Exact | URL Tujuan | Fungsi SEO & UX |
| --- | --- | --- | --- |
| **Bagian 2** *(Penutup Tabel Bulanan)* | `contoh rekapitulasi absen siswa` | `../panduan-cara-rekap-absen-siswa/` | *Upward link* wajib ke **P2-HUB** bagi pembaca yang ingin mempelajari alur rekap induk menyeluruh. |
| **Bagian 3** *(Setelah Rumus Bulanan & Excel)* | `cara menghitung absen siswa` | `../cara-menghitung-persentase-absen-siswa/` | Tautan lintas *cluster* live (**P2-C1**) bagi guru yang ingin melihat simulasi hitung per mapel lebih rinci. |
| **Bagian 6** *(Paragraf Solusi Rekap)* | `rekap absen siswa per bulan` | `../../fitur/` | Mendorong klik ke **Money Page `/fitur/`** sesuai ketentuan blueprint Pilar 2. |
| **Bagian 6** *(Menuju End-CTA / Penutup)* | `aplikasi absen siswa` | `../../` | Menguatkan otoritas halaman **Beranda (`/`)** untuk kata kunci produk inti. |

*Contoh Kalimat Penyisipan Natural:*
- **Bagian 2:** *"Kalau ingin melihat alur lengkap penyusunan daftar hadir harian sampai menjadi laporan induk kelas, Bapak/Ibu bisa membaca panduan [contoh rekapitulasi absen siswa](../panduan-cara-rekap-absen-siswa/) dari awal."*
- **Bagian 3:** *"Ingin rincian langkah pembagian kalkulator dan contoh kasus khusus guru mata pelajaran yang jam tatap mukanya berbeda tiap rombel? Simak panduan [cara menghitung absen siswa](../cara-menghitung-persentase-absen-siswa/) yang sudah kami bahas terpisah."*
- **Bagian 6:** *"Lewat [aplikasi absen siswa](../../) berbasis web dari Presensi Project, data kehadiran yang diinput guru langsung diolah menjadi laporan [rekap absen siswa per bulan](../../fitur/) hingga semesteran siap unduh."*

---

### 2. Penempatan 2 Kotak CTA (`<aside class="cta-box">`)

#### A. Mid-Content CTA (Disisipkan tepat setelah Bagian 3 — selesai membahas rumus manual & Excel `COUNTIF`)
- **Sudut Pandang:** Menjawab langsung kelelahan setelah melihat rumus manual dan Excel (sesuai *hook* wajib blueprint Pilar 2).
- **Draft Copy:**
  - **Label:** `Otomasi Rekap Bulanan`
  - **Judul:** `Capek Menghitung Rumus Persentase Kehadiran Setiap Akhir Bulan?`
  - **Paragraf:** *"Dengan **Web Absen Mapel Sekolah**, seluruh rekap harian, bulanan, dan semester terhitung otomatis 100% secara real-time. Harga paket tahunan sudah termasuk Domain Sekolah, Cloud Hosting Privat, serta **Gratis Bantuan Input Data Master Siswa dari Excel**!"*
  - **Tombol Aksi:**
    - Primary: `Lihat Fitur Rekap Otomatis` -> `../../fitur/`
    - Secondary: `Coba Demo di HP` -> `../../demo/`

#### B. End-Content CTA (Disisipkan tepat setelah Bagian 6 sebelum FAQ)
- **Sudut Pandang:** Penutup konversi **Terima Beres** bagi sekolah yang ingin langsung meninggalkan kerja lembur rekap rapor semester.
- **Draft Copy:**
  - **Label:** `Paket Sekolah Terima Beres`
  - **Judul:** `Siap Cetak Rekap Bulanan & Semester Tanpa Lembur Menjelang Rapor?`
  - **Paragraf:** *"Cukup kirimkan file Excel daftar siswa, rombel, dan jadwal mapel sekolah Bapak/Ibu. Tim kami menyiapkan sistemnya sampai siap pakai oleh seluruh guru—sudah lengkap export PDF berkop sekolah, Excel rekap semester, domain, dan hosting privat."*
  - **Tombol Aksi:**
    - Primary: `Konsultasi via WhatsApp` -> `https://wa.me/6287865712625?text=Halo%20Admin%20Presensi%20Project%2C%20saya%20ingin%20konsultasi%20aplikasi%20rekap%20absen%20bulanan%20dan%20semester%20sekolah`
    - Secondary: `Lihat Paket Harga` -> `../../harga/`

---

## LANGKAH 5: Merakit Metadata `<head>` & Schema JSON-LD (`@graph`)

### 1. Metadata `<head>` & Optimasi SERP / WhatsApp Share
- **`<title>` (57 karakter):** `Contoh Rekap Absen Siswa Per Bulan & Semester untuk Rapor`
- **`<meta name="description">` (147 karakter):** `Contoh rekap absen siswa per bulan manual & contoh rekap absen siswa per semester siap cetak. Cek cara menghitung persentase absen siswa per bulan!`
- **Canonical URL:** `https://presensiproject.online/blog/contoh-rekap-absen-siswa-per-bulan-dan-semester/`
- **OG Title:** `Contoh Rekap Absen Siswa Per Bulan & Semester untuk Rapor`
- **OG Image:** `https://presensiproject.online/assets/og-contoh-rekap-absen-siswa-per-bulan-dan-semester.jpg`
- **Article Section:** `Rekap Bulanan & Rapor Semester`

### 2. Schema Markup JSON-LD (`@graph`)
Menggabungkan 3 entitas dalam satu blok `<script type="application/ld+json">` yang sinkron dengan isi artikel HTML:

```json
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "BlogPosting",
      "@id": "https://presensiproject.online/blog/contoh-rekap-absen-siswa-per-bulan-dan-semester/#article",
      "headline": "Contoh Rekap Absen Siswa Per Bulan & Per Semester Lengkap untuk Rapor",
      "description": "Contoh rekap absen siswa per bulan manual & contoh rekap absen siswa per semester siap cetak. Cek cara menghitung persentase absen siswa per bulan!",
      "image": "https://presensiproject.online/assets/og-contoh-rekap-absen-siswa-per-bulan-dan-semester.jpg",
      "datePublished": "2026-11-14",
      "dateModified": "2026-11-14",
      "inLanguage": "id-ID",
      "author": {
        "@type": "Organization",
        "name": "Tim Litbang Presensi Project",
        "url": "https://presensiproject.online/tentang-kami/"
      },
      "publisher": {
        "@type": "Organization",
        "name": "Presensi Project",
        "url": "https://presensiproject.online/",
        "logo": {
          "@type": "ImageObject",
          "url": "https://presensiproject.online/favicon.svg"
        }
      },
      "mainEntityOfPage": {
        "@type": "WebPage",
        "@id": "https://presensiproject.online/blog/contoh-rekap-absen-siswa-per-bulan-dan-semester/"
      },
      "keywords": [
        "contoh rekap absen siswa per bulan",
        "contoh rekap absen siswa per bulan manual",
        "cara menghitung absen siswa per bulan",
        "cara menghitung persentase absen siswa per bulan",
        "contoh rekap absen siswa per semester"
      ]
    },
    {
      "@type": "BreadcrumbList",
      "@id": "https://presensiproject.online/blog/contoh-rekap-absen-siswa-per-bulan-dan-semester/#breadcrumb",
      "itemListElement": [
        {
          "@type": "ListItem",
          "position": 1,
          "name": "Beranda",
          "item": "https://presensiproject.online/"
        },
        {
          "@type": "ListItem",
          "position": 2,
          "name": "Blog",
          "item": "https://presensiproject.online/blog/"
        },
        {
          "@type": "ListItem",
          "position": 3,
          "name": "Contoh Rekap Absen Per Bulan & Semester",
          "item": "https://presensiproject.online/blog/contoh-rekap-absen-siswa-per-bulan-dan-semester/"
        }
      ]
    },
    {
      "@type": "FAQPage",
      "@id": "https://presensiproject.online/blog/contoh-rekap-absen-siswa-per-bulan-dan-semester/#faq",
      "mainEntity": [
        {
          "@type": "Question",
          "name": "Apakah jumlah hari efektif setiap bulan selalu sama saat membuat rekap absen?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Tidak. Setiap bulan memiliki jumlah hari efektif KBM yang berbeda tergantung libur nasional, cuti bersama, atau jadwal ujian sekolah. Selalu cek Kalender Pendidikan sebelum mengisi angka pembagi persentase."
          }
        },
        {
          "@type": "Question",
          "name": "Bagaimana cara mengubah rekap bulanan menjadi rekap semester untuk e-Rapor?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Cukup jumlahkan kolom total Hadir, Sakit, Izin, dan Alpa dari keenam lembar bulanan (misalnya Juli sampai Desember), lalu bagi dengan total hari efektif selama satu semester tersebut. Pastikan jumlah H + S + I + A cocok dengan total hari efektifnya."
          }
        },
        {
          "@type": "Question",
          "name": "Bisa tidak sekolah langsung dapat file rekap PDF dan Excel bulanan secara otomatis?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Bisa. Melalui layanan Web Absen Mapel Sekolah Terima Beres dari Presensi Project, laporan rekap harian, bulanan, hingga akumulasi semester langsung terhitung otomatis dan bisa diunduh dalam format PDF maupun Excel kapan saja."
          }
        }
      ]
    }
  ]
}
```

---

## LANGKAH 6: Perakitan HTML Final, Update Indeks/Sitemap & Audit Quality Control

### 1. File yang Dibuat & Diperbarui
- **Halaman Artikel Final:** `/blog/contoh-rekap-absen-siswa-per-bulan-dan-semester/index.html`
- **Indeks Blog:** `/blog/index.html` *(penambahan kartu artikel P2-C2)*
- **Peta Situs XML:** `/sitemap.xml` *(penambahan URL kanonis `/blog/contoh-rekap-absen-siswa-per-bulan-dan-semester/`)*
- **Stylesheet Terkompilasi:** `/dist/output.css` *(dijalankan via `npm run build:css`)*

### 2. Checklist Audit Quality Control
- [x] **Panjang `<title>`:** `57 karakter` *(ideal 50–60 karakter).*
- [x] **Panjang `<meta name="description">`:** `147 karakter` *(ideal 140–155 karakter).*
- [x] **Hierarki Heading:** `1` H1, `6` H2, `4` H3 *(1 sub-bagian rumus + 3 FAQ)* tanpa loncat level.
- [x] **Aset Konkret:** 2 Tabel HTML simulasi (Rekap Per Bulan 22 hari & Rekap Per Semester 118 hari yang angkanya konsisten), blok rumus manual + Excel `COUNTIF`, dan 4 checklist validasi guru mapel.
- [x] **Internal Link & CTA:** 4 tautan kontekstual (`contoh rekapitulasi absen siswa` -> P2-HUB, `cara menghitung absen siswa` -> P2-C1, `rekap absen siswa per bulan` -> `/fitur/`, `aplikasi absen siswa` -> `/`), 2 `<aside class="cta-box">`, WA resmi `6287865712625`.
- [x] **Build & Validasi Teknis:** Lolos `npm run build:css` (`266ms`), JSON-LD `@graph` valid (`BlogPosting`, `BreadcrumbList`, `FAQPage`), & XML `sitemap.xml` valid (`OK`).
- [ ] **Publikasi Git:** Menunggu perintah `terbitkan` untuk commit & push ke `origin/main`.
