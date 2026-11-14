# RANCANGAN ARTIKEL SEO — P2-C3 (`cara merekap absen kelas`)

- **ID Klaster:** Pilar 2 — Cluster 2.3 (P2-C3)
- **Tipe Halaman:** Artikel Cluster (Panduan Kerja Wali Kelas & Konsolidasi Lintas Mapel)
- **Target Slug URL:** `/blog/cara-merekap-absen-kelas-wali-kelas/`
- **Primary Keyword:** `cara merekap absen kelas` (Vol: 260, SD: 29)
- **Secondary / LSI Keywords:**
  - `cara rekap absen kelas` (Vol: 140, SD: 29)
  - `contoh rekap absen kelas` (Vol: 140, SD: 27)
- **Outbound Internal Link Target:** P2-HUB (`rekap absen`), `/harga/` (`buat absen online`), `/kontak/` (`buat absen kelas`)
- **Target Gaya Bahasa:** Santai, hangat, empatik ke wali kelas yang sering lembur jelang rapor, kalimat ringkas & paragraf pendek (maksimal 2–3 baris per `<p>`).

---

## LANGKAH 1: Membedah Search Intent & Value Add (Sebelum Menulis)

### 1. Profil Pembaca & Search Intent
- **Siapa Pembacanya:** Wali Kelas SD, SMP, SMA/SMK, Ketua Jurusan SMK, dan Koordinator Piket / Kurikulum.
- **Apa yang Mereka Cari:** Alur kerja langkah demi langkah (*workflow*) untuk membereskan rekap kehadiran satu rombongan belajar (30–36 siswa) dari kumpulan buku absen harian, surat izin di WA, dan jurnal guru mata pelajaran tanpa harus lembur bermalam-malam di minggu rapor.

### 2. Pain Points Nyata di Sekolah
1. **Data izin berceceran di banyak tempat:** Ada yang di buku piket, ada yang di chat WhatsApp pribadi wali kelas, ada yang cuma dicatat di jurnal guru mapel jam ke-4.
2. **Bolak-balik mengulang hitungan manual:** Begitu ketemu satu kesalahan tanggal di minggu kedua, seluruh baris ke samping harus dihitung ulang lagi.
3. **Deadline rapor bertabrakan dengan koreksi ujian:** Di saat harus mengoreksi nilai ulangan akhir semester, wali kelas masih harus begadang menyusun persentase absen kelas.

### 3. Aset Konkret (Information Gain / Nilai Tambah) yang Wajib Ada di Artikel
1. **Alur Kerja 4 Langkah Merekap Absen Kelas yang Antiacak-acakan:** Urutan kerja praktis dari mengumpulkan jurnal harian/surat izin, validasi kode `H/S/I/A`, penerapan blok rumus cepat (manual & Excel `COUNTIF`), hingga kunci finalisasi sebelum input rapor.
2. **Blok Rumus Cepat Rekap Kelas (Manual & Excel `COUNTIF`):** Menampilkan rumus `% Hadir`, `% Alpa`, serta rumus Excel `=COUNTIF(D5:AH5; "H")` dan `=(I5/25)*100%` agar wali kelas mudah menghitung satu rombel sekaligus.
3. **Tabel HTML Simulasi Contoh Rekap Absen Kelas Lintas Mata Pelajaran:** Memuat seluruh kolom wajib (`No`, `Nama Siswa`, `Hari Efektif`, `Hadir (H)`, `Sakit (S)`, `Izin (I)`, `Alpa (A)`, `Persentase Kehadiran (%)`) ditambah kolom pengecekan status lintas mapel (`Bolos Jam Tengah` / `Sinkron`).
4. **Tabel Perbandingan Waktu Kerja (Manual vs Web Presensi Otomatis):** Perbandingan konkret estimasi durasi kerja wali kelas dalam 1 semester (jam lembur vs hitungan detik).
5. **Kotak CTA & Penawaran "Terima Beres":** Mengajak wali kelas dan pengelola sekolah beralih ke sistem absen online yang otomatis mengirim laporan dan gratis dibantu input seluruh data siswa.

---

## LANGKAH 2: Menyusun Kerangka Heading Semantik & Pemetaan Keyword

Artikel ini disusun agar **ringkas, santai, empatik, dan gampang langsung dipraktikkan** (estimasi ~1.000–1.200 kata, paragraf maksimal 2–3 baris), berfokus penuh pada efisiensi *workflow* Wali Kelas saat mengumpulkan data satu kelas tanpa begadang.

### 1. Hierarki Heading Semantik (`H1` – `H3`)

- **`H1`:** **Cara Merekap Absen Kelas** dengan Cepat Tanpa Lembur Bagi Wali Kelas
  - *Intro PAS (3 paragraf pendek, ~90–110 kata):* Menggambarkan suasana minggu tenang jelang pembagian rapor saat koreksi nilai bertabrakan dengan tumpukan rekap absen, lalu menawarkan alur kerja cepatnya.
- **`H2`:** Mengapa Proses Rekapitulasi Akhir Semester Selalu Menguras Waktu Guru?
  - 3 penyebab utama di lapangan (izin via WhatsApp yang belum tersalin ke buku kelas, perbedaan catatan piket dengan jurnal guru mapel, serta kesalahan hitung ulang satu kolom tanggal).
- **`H2`:** 4 Langkah **Cara Rekap Absen Kelas** yang Rapi dari Jurnal Harian
  - Panduan 4 tahap berturut-turut (*Kumpulkan Berkas & Chat WA* -> *Seragamkan Kode & Hari Efektif* -> *Hitung Cepat dengan Rumus/Excel* -> *Kunci Sebelum Cetak Rapor*).
  - Disertai **Kotak Rumus Cepat Rekap Kelas** (`Persentase Hadir (%)`, `Persentase Alpa (%)`, serta rumus Excel `=COUNTIF(D5:AH5; "H")` & `=(I5/25)*100%`).
- *(Penempatan Mid-Content CTA Box di Langkah 4)*
- **`H2`:** Format & Tabel **Contoh Rekap Absen Kelas** Lintas Mata Pelajaran
  - Penjelasan singkat cara wali kelas mengecek siswa yang hadir pagi tapi kosong di jam pelajaran siang.
  - **Tabel HTML Simulasi 1 (5 Siswa — Kelas XI-IPA 1, 22 Hari Efektif):** Memuat kolom wajib (`No`, `Nama Siswa`, `Hari Efektif`, `Hadir (H)`, `Sakit (S)`, `Izin (I)`, `Alpa (A)`, `Persentase Kehadiran (%)`) plus kolom pengecekan `Validasi Lintas Mapel`.
- **`H2`:** Perbandingan Waktu: Rekap Buku Manual vs Sistem Web Presensi Otomatis
  - **Tabel HTML Simulasi 2 (Perbandingan Efisiensi Waktu Wali Kelas per Semester):** Mengadu durasi pengumpulan data, hitung persentase, cek bolos jam tengah, hingga ekspor rapor antara cara tulis tangan dan sistem web.
- **`H2`:** Beralih ke Sistem Absen Kelas Online Terima Beres (Gratis Input Data Siswa!)
  - Penjelasan solusi *managed* **Presensi Project** (domain, cloud hosting privat, dan tim kami yang menginput seluruh daftar siswa & jadwal dari file Excel sekolah) + jembatan ke End CTA.
- **`H2`:** Pertanyaan Umum Seputar **Cara Merekap Absen Kelas** (FAQ)
  - **`H3`:** Kapan waktu terbaik bagi wali kelas mulai merekap absen agar tidak menumpuk?
  - **`H3`:** Bagaimana cara menyatukan izin siswa lewat WhatsApp dengan buku absen kelas?
  - **`H3`:** Apa syarat supaya sekolah bisa dibantu setup dan input data siswa dari Excel secara gratis?

### 2. Pemetaan Target Keyword (Zero Keyword Stuffing)

| Kategori | Keyword Target | Penempatan Utama |
| --- | --- | --- |
| **Primary Keyword** | `cara merekap absen kelas` | `<title>`, `H1`, Intro paragraf 1, `H2` FAQ & Penutup |
| **Secondary 1** | `cara rekap absen kelas` | Meta description, `H2 #2` ("4 Langkah Cara Rekap Absen Kelas...") |
| **Secondary 2** | `contoh rekap absen kelas` | Meta description, `H2 #3` ("Format & Tabel Contoh Rekap Absen Kelas...") |

### 3. Rencana Pemetaan Internal Link & CTA (Disiapkan untuk Langkah 4)
- **Ke P2-HUB (Upward Link):** `../panduan-cara-rekap-absen-siswa/` dengan anchor exact `rekap absen`.
- **Ke Money Page `/harga/`:** `../../harga/` dengan anchor exact `buat absen online`.
- **Ke Money Page `/kontak/`:** `../../kontak/` dengan anchor exact `buat absen kelas`.
- **Cross-link opsional ke P2-C2:** `../contoh-rekap-absen-siswa-per-bulan-dan-semester/` (bila pembaca butuh templat tabel akumulasi 6 bulan untuk e-Rapor).
- **Anti-Kanibalisasi:** Artikel ini berfokus pada **alur kerja (*workflow*) wali kelas & rekonsiliasi lintas mapel agar tidak lembur**, tanpa menduplikasi detail pembagian rumus matematika dasar (P2-C1) atau struktur 6 bulan semesteran (P2-C2).

---

## LANGKAH 3: Menulis Konten per Bagian (Chunking & Gaya Humanized)

> **Catatan Gaya Bahasa:** Santai, hangat, empatik terhadap wali kelas yang harus berbagi fokus antara koreksi nilai ujian dan administrasi kelas, paragraf pendek maksimal 2–3 baris. Penempatan *internal link* dan 2 blok CTA disuntikkan secara khusus pada Langkah 4.

### Bagian 1: Heading Utama & Intro (PAS Ringkas)

**`H1`: Cara Merekap Absen Kelas dengan Cepat Tanpa Lembur Bagi Wali Kelas**

Memasuki minggu tenang sebelum pembagian rapor, pemandangan di ruang guru hampir selalu sama. Meja penuh kertas ulangan yang butuh dikoreksi, sementara buku absen satu kelas juga menuntut beres hari itu juga.

Kalau tidak punya pola kerja yang rapi, mencari tahu **cara merekap absen kelas** sering berujung begadang di rumah. Apalagi kalau harus mencocokkan izin dari grup WhatsApp orang tua dengan jurnal puluhan guru mapel.

Di panduan ini, kita bahas alur kerja praktis dari meja wali kelas: mulai dari membereskan catatan harian tanpa bolak-balik, contoh tabel sinkronisasi lintas mapel, sampai cara bikin laporan tinggal sekali klik.

---

### Bagian 2: Akar Masalah Rekap Akhir Semester

**`H2`: Mengapa Proses Rekapitulasi Akhir Semester Selalu Menguras Waktu Guru?**

Sebenarnya bukan menghitungnya yang lama, melainkan beres-beres data yang berceceran. Ada tiga biang kerok yang bikin rekap kelas terasa berat tiap akhir semester:

- **Izin siswa numpuk di WhatsApp pribadi:** Orang tua sering mengirim surat sakit atau izin lewat chat WA, tapi wali kelas lupa memindahkannya ke buku absen fisik di kelas.
- **Catatan piket vs guru mapel tidak sinkron:** Siswa tercatat hadir saat jam pertama, lalu diam-diam menghilang di jam ke-6 dan cuma ditulis "A" oleh guru mapel sore.
- **Harus menyalin ulang dari nol saat rapor:** Karena buku harian dicoret atau pakai tanda berbeda, wali kelas terpaksa menghitung ulang ratusan kotak untuk 32–36 anak sekaligus.

---

### Bagian 3: 4 Langkah Kerja Rekap Absen Kelas + Kotak Rumus Cepat

**`H2`: 4 Langkah Cara Rekap Absen Kelas yang Rapi dari Jurnal Harian**

Supaya tidak kerja dua kali, terapkan urutan **cara rekap absen kelas** berikut ini—paling nyaman kalau dikerjakan setiap Jumat sore atau minimal sebulan sekali:

1. **Kumpulkan Chat Izin WA & Surat Fisik di Satu Map/Folder:** Setiap ada wali murid izin lewat WA, langsung beri label tanggal dan pindahkan ke buku catatan atau spreadsheet di hari yang sama.
2. **Seragamkan Kode Huruf & Hari Efektif:** Pakai huruf kapital tunggal yang seragam: **H** (Hadir), **S** (Sakit), **I** (Izin), **A** (Alpa), lalu kunci angka **Hari Efektif KBM** sesuai Kalender Pendidikan bulan berjalan.
3. **Gunakan Rumus Hitung Cepat (Manual atau Excel):** Jangan menjumlah dengan cara melingkari kotak satu per satu. Pakai rumus standar di bawah ini agar hitungan satu kelas selesai dalam hitungan menit:

> **Blok Rumus Cepat Rekap Kelas (Manual & Excel):**
> - **Persentase Hadir (%)** = `(Jumlah Hari/Jam Hadir ÷ Total Hari/Jam Efektif) × 100%`
> - **Persentase Alpa (%)** = `(Jumlah Alpa ÷ Total Hari/Jam Efektif) × 100%`
> - **Rumus Excel Dasar (baris siswa ke-5, kolom tanggal `D5:AH5`):**
>   - Hitung jumlah Hadir (`I5`): `=COUNTIF(D5:AH5; "H")` *(ganti `;` menjadi `,` bila Excel memakai setelan bahasa Inggris)*
>   - Hitung persentase dari 25 hari efektif: `=(I5/25)*100%`

4. **Kunci & Verifikasi Jumlah `H + S + I + A`:** Sebelum ditutup, pastikan total keempat status tersebut sama persis dengan jumlah hari efektif. Kalau ada selisih satu angka saja, langsung ketahuan ada tanggal yang bolong.

*(Sisipan Mid-Content CTA di Langkah 4)*

---

### Bagian 4: Contoh Rekap Absen Kelas Lintas Mata Pelajaran

**`H2`: Format & Tabel Contoh Rekap Absen Kelas Lintas Mata Pelajaran**

Bagi wali kelas SMP, SMA, atau SMK, rekap tidak cukup hanya mengandalkan absen apel pagi. Anda perlu mengecek sinkronisasi dengan catatan guru mapel supaya siswa yang sering bolos di jam tengah tetap terpantau sebelum pembagian rapor.

Berikut format **contoh rekap absen kelas** untuk 5 siswa dalam **22 Hari Efektif** dengan tambahan kolom pengecekan lintas mapel:

| No | Nama Siswa | Hari Efektif | Hadir (H) | Sakit (S) | Izin (I) | Alpa (A) | Persentase Kehadiran (%) | Status Lintas Mapel |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| 1 | Anisa Rahmawati | 22 | 22 | 0 | 0 | 0 | **100%** | Sinkron (Penuh) |
| 2 | Bima Satria Putra | 22 | 20 | 1 | 1 | 0 | **90,9%** | Sinkron (Surat/WA Lengkap) |
| 3 | Chandra Wijaya | 22 | 19 | 0 | 1 | 2 | **86,4%** | Cek: Bolos 2x Jam Siang |
| 4 | Dhea Kartikasari | 22 | 18 | 2 | 1 | 1 | **81,8%** | Sinkron (Surat Dokter) |
| 5 | Eko Prasetyo | 22 | 16 | 1 | 1 | 4 | **72,7%** | Prioritas Panggil BK |

Perhatikan baris Chandra: di absen pagi mungkin terlihat aman, tapi laporan lintas guru mapel mendeteksi ia absen dua kali pada jam siang. Catatan singkat di kolom ujung kanan ini langsung membantu Wali Kelas dan Guru BK mengambil tindakan lebih cepat.

---

### Bagian 5: Perbandingan Waktu Kerja Manual vs Otomatis

**`H2`: Perbandingan Waktu: Rekap Buku Manual vs Sistem Web Presensi Otomatis**

Seberapa jauh bedanya kalau wali kelas tetap memakai buku tulis dibanding memakai web presensi otomatis sekolah? Mari kita bandingkan estimasi waktu kerjanya untuk satu kelas berisi 35 siswa:

| Tahap Pekerjaan Wali Kelas | Cara Buku Tulis Manual | Sistem Web Presensi Otomatis |
| :--- | :--- | :--- |
| Mengumpulkan izin WA & jurnal piket | 1–2 jam per bulan | **0 menit** *(langsung tersimpan di web)* |
| Menghitung total H, S, I, A & persentase | 2–3 jam per kelas | **0 detik** *(terhitung real-time)* |
| Mengecek siswa bolos jam pelajaran tengah | Sulit, sering ketahuan telat | **Otomatis muncul** di hari yang sama |
| Cetak rekap PDF & Excel jelang rapor | Harus ketik ulang berjam-jam | **10 detik** *(tinggal klik Unduh)* |

Selisih waktu tersebut belum termasuk ketenangan pikiran Bapak/Ibu karena terhindar dari risiko buku absen terselip atau salah hitung persentase saat deadline mepet.

---

### Bagian 6: Solusi Terima Beres & Penutup

**`H2`: Beralih ke Sistem Absen Kelas Online Terima Beres (Gratis Input Data Siswa!)**

Sebenarnya banyak sekolah sudah ingin punya absensi digital yang praktis, tapi mundur duluan karena takut staf TU dan guru repot mengurus *setting* awal atau menginput ratusan data siswa.

Di **Presensi Project**, sekolah tidak perlu pusing urusan teknis itu. Konsepnya murni **Terima Beres**: harga paket tahunan sudah mencakup domain sekolah, cloud hosting privat, dan **gratis bantuan input seluruh data master siswa, rombel, serta jadwal guru dari file Excel Anda**.

Begitu sistem aktif, setiap kali guru mengabsen lewat HP di kelas, laporan harian hingga rekap rapor wali kelas langsung jadi otomatis tanpa perlu menyentuh kalkulator atau mengetik ulang satu nama pun.

*(Sisipan End-Content CTA di Langkah 4)*

---

### Bagian 7: FAQ Singkat (Schema-Ready)

**`H2`: Pertanyaan Umum Seputar Cara Merekap Absen Kelas**

**`H3`: Kapan waktu terbaik bagi wali kelas mulai merekap absen agar tidak menumpuk?**
Waktu paling ideal adalah sepekan sekali setiap hari Jumat atau maksimal di akhir bulan. Kebiasaan mencicil per pekan membuat Anda tidak perlu mengecek ratusan baris kertas sekaligus menjelang pembagian rapor.

**`H3`: Bagaimana cara menyatukan izin siswa lewat WhatsApp dengan buku absen kelas?**
Biasakan langsung menandai nama siswa bersangkutan di daftar hadir atau grup koordinasi piket pada pagi hari itu juga. Jika memakai sistem web absensi online, status Sakit atau Izin bisa langsung diklik lewat HP dalam hitungan detik sehingga seluruh guru mapel langsung melihatnya.

**`H3`: Apa syarat supaya sekolah bisa dibantu setup dan input data siswa dari Excel secara gratis?**
Cukup siapkan file Excel daftar siswa aktif, pembagian rombongan belajar (rombel), serta daftar guru mata pelajaran sekolah Anda. Tim Presensi Project akan menginputkan seluruh data tersebut dan menyiapkan website absen sekolah hingga siap pakai tanpa biaya tambahan.

---

## LANGKAH 4: Menyuntikkan Internal Link Kontekstual & 2 Kotak CTA Strategis

### 1. Peta Penempatan Internal Link (Zero Cannibalization)

| Lokasi Penempatan | Anchor Text Exact | URL Tujuan | Fungsi SEO & UX |
| --- | --- | --- | --- |
| **Bagian 2** *(Penutup Akar Masalah)* | `rekap absen` | `../panduan-cara-rekap-absen-siswa/` | *Upward link* wajib ke **P2-HUB** bagi pembaca yang ingin melihat perbandingan seluruh metode rekap. |
| **Bagian 4** *(Setelah Tabel Simulasi Lintas Mapel)* | `contoh rekap absen siswa per semester` | `../contoh-rekap-absen-siswa-per-bulan-dan-semester/` | Tautan lintas *cluster* live (**P2-C2**) bagi wali kelas yang butuh format akumulasi 6 bulan untuk e-Rapor. |
| **Bagian 6** *(Paragraf Paket Terima Beres)* | `buat absen online` | `../../harga/` | Mendorong trafik berniat transaksi ke **Money Page `/harga/`** sesuai ketentuan blueprint Pilar 2. |
| **Bagian 6** *(Ajakan Konsultasi Sekolah)* | `buat absen kelas` | `../../kontak/` | Mengarahkan pembaca ke **Money Page `/kontak/`** untuk pengajuan onboarding sekolah. |

*Contoh Kalimat Penyisipan Natural:*
- **Bagian 2:** *"Untuk membandingkan metode paling ringan sejak awal tahun ajaran, Bapak/Ibu dapat membaca panduan lengkap [rekap absen](../panduan-cara-rekap-absen-siswa/) dari metode buku manual, Excel, hingga sistem web otomatis."*
- **Bagian 4:** *"Bila lembar lintas mapel bulanan sudah rapi dan Anda perlu menggabungkannya ke format enam bulanan untuk e-Rapor, silakan tiru tabel pada artikel [contoh rekap absen siswa per semester](../contoh-rekap-absen-siswa-per-bulan-dan-semester/) yang sudah kami siapkan."*
- **Bagian 6:** *"Lewat layanan [buat absen online](../../harga/) berbasis Terima Beres dari Presensi Project, harga paket tahunan sudah mencakup domain sekolah, cloud hosting privat, dan gratis bantuan input seluruh data master siswa dari file Excel Anda. Cukup hubungi tim kami untuk mulai [buat absen kelas](../../kontak/) khusus sekolah Bapak/Ibu sampai siap dipakai."*

---

### 2. Penempatan 2 Kotak CTA (`<aside class="cta-box">`)

#### A. Mid-Content CTA (Disisipkan tepat setelah Bagian 3 — selesai membahas 4 langkah & rumus `COUNTIF`)
- **Sudut Pandang:** Empati setelah guru melihat deretan langkah & rumus manual/Excel (memakai *hook* wajib blueprint Pilar 2).
- **Draft Copy:**
  - **Label:** `Otomasi Tugas Wali Kelas`
  - **Judul:** `Capek Menghitung Rumus Persentase Kehadiran Setiap Akhir Bulan?`
  - **Paragraf:** *"Dengan **Web Absen Mapel Sekolah**, seluruh rekap harian, bulanan, dan semester terhitung otomatis 100% secara real-time. Harga paket tahunan sudah termasuk Domain Sekolah, Hosting, dan **Gratis Bantuan Input Data Master Siswa dari Excel**!"*
  - **Tombol Aksi:**
    - Primary: `Lihat Paket Terima Beres` -> `../../harga/`
    - Secondary: `Coba Demo di HP` -> `../../demo/`

#### B. End-Content CTA (Disisipkan tepat setelah Bagian 6 sebelum FAQ)
- **Sudut Pandang:** Penutup konversi langsung ke konsultasi WhatsApp (`6287865712625`) dan halaman Kontak.
- **Draft Copy:**
  - **Label:** `Gratis Setup & Input Data Siswa`
  - **Judul:** `Siap Lepas dari Kerja Lembur Rekap Absen Kelas Tiap Akhir Semester?`
  - **Paragraf:** *"Cukup kirimkan file Excel daftar siswa, rombel, dan jadwal mengajar sekolah Bapak/Ibu. Tim Presensi Project membantu setup website hingga seluruh wali kelas dan guru mapel tinggal klik absen dari HP masing-masing."*
  - **Tombol Aksi:**
    - Primary: `Konsultasi Gratis via WhatsApp` -> `https://wa.me/6287865712625?text=Halo%20Admin%20Presensi%20Project%2C%20saya%20ingin%20konsultasi%20buat%20absen%20kelas%20online%20untuk%20sekolah%20kami`
    - Secondary: `Hubungi Tim Onboarding` -> `../../kontak/`

---

## LANGKAH 5: Merakit Metadata `<head>` & Schema JSON-LD (`@graph`)

### 1. Metadata `<head>` & Optimasi SERP / WhatsApp Share
- **`<title>` (54 karakter):** `Cara Merekap Absen Kelas untuk Wali Kelas Tanpa Lembur`
- **`<meta name="description">` (148 karakter):** `Tips praktis cara merekap absen kelas dan contoh rekap absen kelas bagi Wali Kelas & Guru Mapel. Hemat waktu rekapitulasi menjelang pembagian rapor!`
- **Canonical URL:** `https://presensiproject.online/blog/cara-merekap-absen-kelas-wali-kelas/`
- **OG Title:** `Cara Merekap Absen Kelas untuk Wali Kelas Tanpa Lembur`
- **OG Image:** `https://presensiproject.online/assets/og-cara-merekap-absen-kelas-wali-kelas.jpg`
- **Article Section:** `Panduan Kerja Wali Kelas`

### 2. Schema Markup JSON-LD (`@graph`)
Menggabungkan 3 entitas dalam satu blok `<script type="application/ld+json">` yang sinkron dengan isi artikel HTML:

```json
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "BlogPosting",
      "@id": "https://presensiproject.online/blog/cara-merekap-absen-kelas-wali-kelas/#article",
      "headline": "Cara Merekap Absen Kelas dengan Cepat Tanpa Lembur Bagi Wali Kelas",
      "description": "Tips praktis cara merekap absen kelas dan contoh rekap absen kelas bagi Wali Kelas & Guru Mapel. Hemat waktu rekapitulasi menjelang pembagian rapor!",
      "image": "https://presensiproject.online/assets/og-cara-merekap-absen-kelas-wali-kelas.jpg",
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
        "@id": "https://presensiproject.online/blog/cara-merekap-absen-kelas-wali-kelas/"
      },
      "keywords": [
        "cara merekap absen kelas",
        "cara rekap absen kelas",
        "contoh rekap absen kelas"
      ]
    },
    {
      "@type": "BreadcrumbList",
      "@id": "https://presensiproject.online/blog/cara-merekap-absen-kelas-wali-kelas/#breadcrumb",
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
          "name": "Cara Merekap Absen Kelas Wali Kelas",
          "item": "https://presensiproject.online/blog/cara-merekap-absen-kelas-wali-kelas/"
        }
      ]
    },
    {
      "@type": "FAQPage",
      "@id": "https://presensiproject.online/blog/cara-merekap-absen-kelas-wali-kelas/#faq",
      "mainEntity": [
        {
          "@type": "Question",
          "name": "Kapan waktu terbaik bagi wali kelas mulai merekap absen agar tidak menumpuk?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Waktu paling ideal adalah sepekan sekali setiap hari Jumat atau maksimal di akhir bulan. Kebiasaan mencicil per pekan membuat Anda tidak perlu mengecek ratusan baris kertas sekaligus menjelang pembagian rapor."
          }
        },
        {
          "@type": "Question",
          "name": "Bagaimana cara menyatukan izin siswa lewat WhatsApp dengan buku absen kelas?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Biasakan langsung menandai nama siswa bersangkutan di daftar hadir atau grup koordinasi piket pada pagi hari itu juga. Jika memakai sistem web absensi online, status Sakit atau Izin bisa langsung diklik lewat HP dalam hitungan detik sehingga seluruh guru mapel langsung melihatnya."
          }
        },
        {
          "@type": "Question",
          "name": "Apa syarat supaya sekolah bisa dibantu setup dan input data siswa dari Excel secara gratis?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Cukup siapkan file Excel daftar siswa aktif, pembagian rombongan belajar (rombel), serta daftar guru mata pelajaran sekolah Anda. Tim Presensi Project akan menginputkan seluruh data tersebut dan menyiapkan website absen sekolah hingga siap pakai tanpa biaya tambahan."
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
- **Halaman Artikel Final:** `/blog/cara-merekap-absen-kelas-wali-kelas/index.html`
- **Indeks Blog:** `/blog/index.html` *(penambahan kartu artikel P2-C3)*
- **Peta Situs XML:** `/sitemap.xml` *(penambahan URL kanonis `/blog/cara-merekap-absen-kelas-wali-kelas/`)*
- **Stylesheet Terkompilasi:** `/dist/output.css` *(dijalankan via `npm run build:css`)*

### 2. Checklist Audit Quality Control
- [x] **Panjang `<title>`:** `54 karakter` *(ideal 50–60 karakter).*
- [x] **Panjang `<meta name="description">`:** `148 karakter` *(ideal 140–155 karakter).*
- [x] **Hierarki Heading:** `1` H1, `6` H2, `3` H3 *(FAQ)* tanpa loncat level.
- [x] **Aset Konkret:** Alur kerja 4 langkah wali kelas, Blok Rumus Cepat (`% Hadir`, `% Alpa`, Excel `COUNTIF`), Tabel HTML 1 Rekap Lintas Mapel (5 siswa, 8 kolom wajib + *Status Lintas Mapel*), dan Tabel HTML 2 Perbandingan Waktu Kerja.
- [x] **Internal Link & CTA:** 4 tautan kontekstual (`rekap absen` -> P2-HUB, `contoh rekap absen siswa per semester` -> P2-C2, `buat absen online` -> `/harga/`, `buat absen kelas` -> `/kontak/`), 2 `<aside class="cta-box">`, WA resmi `6287865712625`.
- [x] **Build & Validasi Teknis:** Lolos `npm run build:css` (`262ms`), JSON-LD `@graph` valid (`BlogPosting`, `BreadcrumbList`, `FAQPage`), & XML `sitemap.xml` valid (`OK`).
- [ ] **Publikasi Git:** Menunggu perintah `terbitkan` untuk commit & push ke `origin/main`.
