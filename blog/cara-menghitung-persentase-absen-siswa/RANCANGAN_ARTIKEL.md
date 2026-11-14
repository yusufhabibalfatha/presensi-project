# RANCANGAN ARTIKEL SEO — P2-C1 (`cara menghitung absen siswa`)

- **ID Konten:** P2-C1 (Cluster 2.1 dari Pilar 2)
- **Target Slug URL:** `/blog/cara-menghitung-persentase-absen-siswa/`
- **Primary Keyword:** `cara menghitung absen siswa` (Vol: 590, SD: 26)
- **Secondary / LSI Keywords:**
  - `cara menghitung persentase absen siswa` (Vol: 320, SD: 25)
  - `cara menghitung absen kehadiran siswa` (Vol: 210, SD: 25)
  - `menghitung absen siswa` (Vol: 170, SD: 27)
  - `rumus persentase absen siswa manual` (Vol: 170, SD: 22)
  - `rumus menghitung absen siswa manual` (Vol: 110, SD: 25)
- **Target Internal Link Keluar (Zero Cannibalization):**
  - Ke **P2-HUB** (`../panduan-cara-rekap-absen-siswa/`) dengan anchor text `cara rekap absen` *(catatan: pastikan slug P2-HUB terhubung konsisten saat hub dibangun)*
  - Ke **Fitur** (`../../fitur/`) dengan anchor text `persentase absen siswa` atau `rekapitulasi absen siswa`
- **Aturan Gaya Penulisan (Konsisten):**
  - **Ringkas & Padat:** Artikel tidak terlalu panjang, langsung menjawab inti rumus & contoh angka.
  - **Humanize & Santai:** Bahasa ringan ala obrolan sesama guru/wali kelas, ramah mata, paragraf maksimal 2–3 baris per `<p>`.

---

## LANGKAH 1: Membedah Search Intent & Value Add (Sebelum Menulis)

### 1. Profil Pembaca (Siapa yang mengetik keyword ini?)
- **Persona Utama:** **Wali Kelas (SD–SMK), Guru Mata Pelajaran, Guru BK, serta Staf Tata Usaha (TU)**.
- **Situasi & Kondisi Mereka:**
  - Mereka sedang dikejar waktu tutup bulan, rapat pleno kenaikan kelas, atau tenggat input nilai ke e-Rapor.
  - Mereka tidak butuh penjelasan teori panjang lebar soal sejarah absensi—mereka langsung butuh **rumus matematika yang pasti benar**, contoh hitungan dengan angka nyata, dan rumus Excel yang tinggal disalin.

### 2. Masalah Utama (Pain Points) yang Membuat Mereka Mencari Keyword Ini
1. **Bingung Menentukan Angka Pembagi:** Masih sering ragu saat menghitung manual—apakah dibagi 30 hari kalender, dibagi jumlah hari efektif KBM (misal 22 atau 25 hari), atau dibagi total jam pertemuan tatap muka guru mapel.
2. **Salah Membedakan Persentase Hadir vs Ketidakhadiran:** Sering bingung menghitung persentase **Alpa** vs **Hadir** untuk menentukan apakah siswa memenuhi syarat minimal ikut Sumatif Akhir Semester (biasanya 75%–80%).
3. **Capek Menghitung Satu-Satu Pakai Kalkulator:** Untuk 1 rombel berisi 32 anak saja butuh memencet kalkulator berkali-kali, apalagi bagi guru mapel yang mengampu 6–10 kelas berbeda tiap semester.

### 3. Aset Konkret (Information Gain / Nilai Tambah) yang Wajib Ada di Artikel
1. **Kotak Rumus Matematika Manual (Visual & Jelas):**
   - Rumus Persentase Hadir (`% Hadir`)
   - Rumus Persentase Alpa / Ketidakhadiran (`% Alpa`)
   - Penjelasan perbedaan angka pembagi (Wali Kelas vs Guru Mapel).
2. **Simulasi Hitung Angka Nyata (Step-by-Step):** Contoh kasus 1 siswa dengan angka riil (misal 22 hari efektif: 19 H, 1 S, 2 A) lengkap dengan cara membaginya pakai kalkulator agar pembaca langsung paham dalam 10 detik.
3. **Tabel HTML Simulasi Rekap 1 Kelas (5 Siswa):** Menampilkan kolom `No`, `Nama Siswa`, `Hari Efektif`, `Hadir (H)`, `Sakit (S)`, `Izin (I)`, `Alpa (A)`, dan `Persentase Kehadiran (%)`.
4. **Kotak Rumus Excel Copy-Paste:** Rumus `=COUNTIF(...)` dan pembagian persentase otomatis yang tinggal tempel di laptop.
5. **Kotak CTA & Perbandingan Singkat:** Jembatan halus menuju **Web Absen Mapel Sekolah "Terima Beres"** agar guru tidak perlu lagi lembur menghitung manual tiap bulan.

---

## LANGKAH 2: Menyusun Kerangka Heading Semantik & Pemetaan Keyword

Agar artikel tetap **ringkas, santai, mudah dipindai, dan tepat sasaran** (estimasi ~1.000–1.250 kata, paragraf maksimal 2–3 baris), struktur *heading* disusun mengikuti alur praktik guru dari konsep paling dasar hingga otomasi.

### 1. Hierarki Heading Semantik (`H1` – `H3`)

- **`H1`:** Rumus & **Cara Menghitung Absen Siswa** (Manual, Excel, dan Otomatis)
  - *Intro PAS (3 paragraf pendek, total ~90–120 kata):* Menyapa kelelahan guru saat rekap bulanan, menegaskan kenapa angka pembagi sering bikin selisih, dan memberi pratinjau isi panduan ini.
- **`H2`:** Konsep Dasar dalam **Menghitung Absen Siswa** (Hari Efektif vs Jam Pelajaran)
  - Penjelasan singkat perbedaan angka pembagi untuk Wali Kelas (Hari Efektif) vs Guru Mapel (Total Pertemuan Tatap Muka), serta cara memperlakukan status `H`, `S`, `I`, dan `A`.
- **`H2`:** **Rumus Persentase Absen Siswa Manual** (Hadir, Sakit, Izin, Alpa)
  - Kotak visual rumus `% Hadir` & `% Alpa` + simulasi hitung cepat 1 siswa dengan angka riil (22 hari efektif: 19 H, 1 S, 2 A).
  - **`H3`:** Simulasi & **Cara Menghitung Persentase Absen Siswa** untuk 1 Kelas
    - Tabel HTML simulasi 5 siswa (`No`, `Nama Siswa`, `Hari Efektif`, `Hadir (H)`, `Sakit (S)`, `Izin (I)`, `Alpa (A)`, `Persentase Kehadiran (%)`).
- *(Penempatan Mid-Content CTA Box di Langkah 4)*
- **`H2`:** **Rumus Menghitung Absen Siswa Manual** vs Menggunakan Rumus `COUNTIF` di Excel
  - Kotak rumus Excel siap *copy-paste* (`=COUNTIF(...)` & rumus persentase), tips praktis perbedaan pemisah `;` vs `,` di Excel, serta perbandingan cepat hitung manual vs Excel.
- **`H2`:** **Cara Menghitung Absen Kehadiran Siswa** Khusus Guru Mata Pelajaran
  - Cara praktis menghitung persentase per tatap muka mapel (2–4 JP per minggu) agar rekap tetap akurat di banyak kelas paralel, sekaligus jembatan ke panduan rekap dan halaman fitur.
- **`H2`:** Solusi Anti Pusing: Hitung Persentase Kehadiran Otomatis 100% Tanpa Kalkulator!
  - Penjelasan ringkas alur sistem Web Absen Mapel Sekolah "Terima Beres" (klik hadir di HP -> persentase langsung jadi) + penawaran End CTA.
- **`H2`:** Pertanyaan Umum Seputar **Cara Menghitung Persentase Absen Siswa** (FAQ)
  - **`H3`:** Bagaimana rumus menghitung persentase kehadiran siswa untuk nilai rapor?
  - **`H3`:** Apakah siswa yang Sakit (S) atau Izin (I) mengurangi persentase kehadiran?
  - **`H3`:** Kenapa rumus `COUNTIF` di Excel saya error saat menghitung absen?

### 2. Pemetaan Target Keyword (Zero Keyword Stuffing)

| Kategori | Keyword Target | Penempatan Utama |
| --- | --- | --- |
| **Primary Keyword** | `cara menghitung absen siswa` | `<title>`, `H1`, Intro paragraf 1, Kesimpulan/Penutup |
| **Secondary 1** | `cara menghitung persentase absen siswa` | Meta description, `H3` Simulasi Kelas, `H2` FAQ |
| **Secondary 2** | `cara menghitung absen kehadiran siswa` | `H2` Khusus Guru Mapel & paragraf pembukanya |
| **Secondary 3** | `menghitung absen siswa` | `H2` Konsep Dasar & FAQ pertama |
| **Secondary 4** | `rumus persentase absen siswa manual` | `H2` Rumus Manual & kotak rumus matematika |
| **Secondary 5** | `rumus menghitung absen siswa manual` | `H2` Perbandingan Manual vs Excel `COUNTIF` |

### 3. Rencana Pemetaan Internal Link & CTA (Disiapkan untuk Langkah 4)
- **Ke P2-HUB (Upward Link):** `/blog/panduan-cara-rekap-absen-siswa/` dengan anchor natural `cara rekap absen`.
- **Ke Money Page `/fitur/`:** dengan anchor `persentase absen siswa` / `rekapitulasi absen siswa`.
- **Anti-Kanibalisasi:** Artikel ini fokus penuh pada **rumus & kalkulasi angka/persentase (`%`)**. Artikel ini tidak mengambil alih topik pembagian file Excel mentah (P1-C1), tata cara merekap buku bulanan wali kelas (P2-C3), maupun panduan rekap induk (P2-HUB).

---

## LANGKAH 3: Menulis Konten per Bagian (Chunking & Gaya Humanized)

> **Catatan Gaya Bahasa:** Paragraf pendek maksimal 2–3 baris, santai seperti obrolan guru di ruang piket, to the point, dan bebas bahasa kaku. Penempatan *internal link* dan 2 blok CTA disuntikkan secara khusus pada Langkah 4.

### Bagian 1: Heading Utama & Intro (PAS Ringkas)

**`H1`: Rumus & Cara Menghitung Absen Siswa (Manual, Excel, dan Otomatis)**

Pernah pusing pas akhir bulan karena angka persentase kehadiran siswa nggak ketemu bulatannya? Tenang, Bapak/Ibu nggak sendirian. Hampir semua wali kelas dan guru mapel mengalami hal ini saat tanggal tutup buku tiba.

Masalah paling sering bukan salah tekan kalkulator, melainkan bingung menentukan angka pembaginya. Alhasil, **cara menghitung absen siswa** jadi terasa ribet dan makan waktu istirahat.

Di panduan singkat ini, kita bahas rumus paling simpelnya. Mulai dari hitungan manual pakai kalkulator, rumus Excel anti-ribet, sampai cara otomatis biar tinggal klik saja.

---

### Bagian 2: Konsep Dasar Pembagi & Status Absen

**`H2`: Konsep Dasar dalam Menghitung Absen Siswa (Hari Efektif vs Jam Pelajaran)**

Sebelum masuk ke rumus, samakan dulu patokan pembaginya. Kesalahan paling umum saat **menghitung absen siswa** muncul karena mencampur hitungan wali kelas dan guru mata pelajaran.

Agar angkanya adil dan valid untuk rapor, pakai patokan ini:

- **Untuk Wali Kelas (Harian):** Gunakan **Total Hari Efektif Sekolah** dalam satu bulan atau satu semester. Misalnya bulan ini sekolah aktif 22 hari (di luar Minggu dan tanggal merah), maka pembaginya adalah `22`.
- **Untuk Guru Mata Pelajaran:** Gunakan **Total Pertemuan Tatap Muka Efektif** kelas tersebut. Kalau jadwal mapel Anda seminggu sekali dan dalam sebulan efektif bertemu 4 kali, maka pembaginya `4` (atau `18` kali dalam satu semester).

Lalu, bagaimana nasib siswa yang **Sakit (S)** atau **Izin (I)**? Dalam hitungan murni persentase kehadiran fisik, yang dihitung sebagai pembilang hanyalah status **Hadir (H)** saja. Catatan `S` dan `I` tetap dipisahkan kolomnya agar menjadi bahan pertimbangan kebijakan wali kelas di akhir semester.

---

### Bagian 3: Rumus Manual & Tabel Simulasi 1 Kelas

**`H2`: Rumus Persentase Absen Siswa Manual (Hadir, Sakit, Izin, Alpa)**

Kalau di meja cuma ada buku absen fisik dan kalkulator HP, nggak perlu bingung. Pakai saja **rumus persentase absen siswa manual** berikut ini:

> **Rumus Wajib Rekap Kehadiran:**
> - **Persentase Hadir (%)** = `(Jumlah Hadir ÷ Total Hari/Pertemuan Efektif) × 100%`
> - **Persentase Alpa (%)** = `(Jumlah Alpa ÷ Total Hari/Pertemuan Efektif) × 100%`
> *(Catatan: Untuk mencari `% Sakit` atau `% Izin`, tinggal ganti pembilangnya saja dengan jumlah `S` atau `I`.)*

Supaya langsung kebayang, mari kita hitung satu contoh nyata. Misalkan dalam **22 hari efektif**, seorang siswa bernama Dimas tercatat **19 kali Hadir**, **1 kali Sakit**, dan **2 kali Alpa**:

1. Hitung hadirnya: `(19 ÷ 22) × 100% = 0,8636 × 100%` = **`86,4%`** *(dibulatkan 1 angka di belakang koma)*.
2. Hitung alpanya: `(2 ÷ 22) × 100% = 0,0909 × 100%` = **`9,1%`**.

Gampang kan? Kalau dihitung untuk satu anak memang terasa cepat, tapi tantangannya mulai terasa kalau satu kelas isinya 32 sampai 36 siswa.

**`H3`: Simulasi & Cara Menghitung Persentase Absen Siswa untuk 1 Kelas**

Berikut gambaran hasil **cara menghitung persentase absen siswa** untuk 5 siswa dalam bulan yang memiliki **22 hari efektif** sekolah:

| No | Nama Siswa | Hari Efektif | Hadir (H) | Sakit (S) | Izin (I) | Alpa (A) | Persentase Kehadiran (%) |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | Ahmad Fauzi | 22 | 22 | 0 | 0 | 0 | **100%** |
| 2 | Bela Kartika | 22 | 20 | 2 | 0 | 0 | **90,9%** |
| 3 | Dimas Pratama | 22 | 19 | 1 | 0 | 2 | **86,4%** |
| 4 | Citra Lestari | 22 | 18 | 1 | 2 | 1 | **81,8%** |
| 5 | Rizky Ramadhan | 22 | 16 | 1 | 1 | 4 | **72,7%** |

Dari tabel sederhana seperti ini, Bapak/Ibu bisa langsung mendeteksi siapa anak yang kehadirannya mulai turun di bawah batas minimal sekolah (misalnya di bawah 80% atau 85%) sebelum telat dibina.

*(Sisipan Mid-Content CTA di Langkah 4)*

---

### Bagian 4: Rumus Excel `COUNTIF` Anti Salah Hitung

**`H2`: Rumus Menghitung Absen Siswa Manual vs Menggunakan Rumus `COUNTIF` di Excel**

Kalau sudah memegang laptop, tinggalkan cara pencet kalkulator satu per satu. Mengandalkan **rumus menghitung absen siswa manual** berisiko bikin mata lelah dan rawan salah ketik angka.

Di Microsoft Excel atau Google Sheets, Bapak/Ibu cukup pakai kombinasi rumus `COUNTIF` untuk menghitung total `H`, `S`, `I`, dan `A` secara otomatis dari deretan kolom tanggal.

> **Rumus Excel Siap Copy-Paste (Contoh Baris Siswa ke-5, Tanggal di Kolom `D5` sampai `AH5`):**
> - **Hitung Jumlah Hadir (`I5`):** `=COUNTIF(D5:AH5; "H")`
> - **Hitung Jumlah Sakit (`J5`):** `=COUNTIF(D5:AH5; "S")`
> - **Hitung Persentase Hadir (jika 25 hari efektif):** `=(I5/25)*100%` *(atau ketik `=I5/25` lalu klik ikon `%` di menu Excel)*

**Tips anti-error:** Jika setelah menekan Enter rumus Excel malah muncul peringatan error, coba ganti tanda titik koma (`;`) menjadi koma (`,`), misalnya `=COUNTIF(D5:AH5, "H")`. Pengaturan bahasa di beberapa laptop memang memakai koma sebagai pemisah rumus.

Singkatnya, hitung manual cocok kalau hanya mengecek 1–2 siswa bermasalah, sedangkan Excel jauh lebih hemat tenaga untuk merekap satu kelas sekaligus dalam hitungan menit.

---

### Bagian 5: Khusus Guru Mata Pelajaran

**`H2`: Cara Menghitung Absen Kehadiran Siswa Khusus Guru Mata Pelajaran**

Mengajar 8 sampai 12 kelas paralel punya tantangan berbeda dibanding wali kelas. Dalam **cara menghitung absen kehadiran siswa** khusus guru mapel, angka pembagi tidak boleh disamakan pukul rata antar kelas.

Misalnya, kelas VII-A punya **18 kali pertemuan** efektif karena jarang terpotong libur nasional, sementara kelas VII-C hanya sempat tatap muka **16 kali** karena sering bertepatan dengan tanggal merah atau acara sekolah.

Oleh karena itu, catat dulu total tatap muka riil per kelas di pojok buku jurnal mengajar Anda. Jika seorang siswa di kelas VII-C hadir 14 kali dari 16 pertemuan, persentasenya tetap dihitung `(14 ÷ 16) × 100% = 87,5%`, bukan dibagi 18.

---

### Bagian 6: Solusi Otomatis Tanpa Kalkulator & Penutup

**`H2`: Solusi Anti Pusing: Hitung Persentase Kehadiran Otomatis 100% Tanpa Kalkulator!**

Jujur saja, rumus manual maupun Excel tetap butuh ketelitian ekstra. Satu kali salah geser sel Excel atau lupa mengisi satu kolom tanggal, seluruh persentase di bawahnya ikut berantakan.

Bayangkan kalau setiap kali Bapak/Ibu mengetuk status hadir anak di HP saat berada di kelas, sistem langsung menjumlahkan `H`, `S`, `I`, `A` sekaligus menampilkan persentase kehadirannya secara *real-time*.

Dengan **Web Absen Mapel Sekolah "Terima Beres"**, guru nggak perlu lagi membuka rumus `COUNTIF` atau pusing mengurutkan hari efektif per kelas. Di akhir bulan, laporan persentase kehadiran per siswa maupun per kelas tinggal diunduh rapi dalam sekali klik.

*(Sisipan End-Content CTA di Langkah 4)*

---

### Bagian 7: FAQ Singkat (Schema-Ready)

**`H2`: Pertanyaan Umum Seputar Cara Menghitung Persentase Absen Siswa**

**`H3`: Bagaimana rumus menghitung persentase kehadiran siswa untuk nilai rapor?**
Gunakan rumus dasar `(Total Hadir ÷ Total Hari Efektif atau Pertemuan Mapel) × 100%`. Pastikan pembagi untuk wali kelas memakai hari efektif sekolah, sedangkan guru mapel memakai total pertemuan riil di kelas tersebut.

**`H3`: Apakah siswa yang Sakit (S) atau Izin (I) mengurangi persentase kehadiran?**
Secara hitungan matematis kehadiran fisik, ya, karena rumus persentase hadir hanya menghitung jumlah `H` (Hadir). Namun pada praktiknya di rapor, sekolah umumnya membedakan antara ketidakhadiran berizin (`S`/`I`) dengan tanpa keterangan (`A`/Alpa) saat menentukan kenaikan kelas.

**`H3`: Kenapa rumus `COUNTIF` di Excel saya error saat menghitung absen?**
Penyebab paling sering hanyalah perbedaan karakter pemisah antara titik koma (`;`) dan koma (`,`), tergantung pengaturan regional Windows atau Mac Anda. Cukup ubah `=COUNTIF(D5:AH5; "H")` menjadi `=COUNTIF(D5:AH5, "H")`, lalu pastikan tulisan huruf `"H"` diapit tanda kutip ganda.

---

## LANGKAH 4: Menyuntikkan Internal Link Kontekstual & 2 Kotak CTA Strategis

### 1. Peta Penempatan Internal Link (Zero Cannibalization)

| Lokasi Penempatan | Anchor Text Exact | URL Tujuan | Fungsi SEO & UX |
| --- | --- | --- | --- |
| **Bagian 2** *(Kalimat penutup Konsep Dasar)* | `cara rekap absen` | `../panduan-cara-rekap-absen-siswa/` | *Upward link* wajib ke **P2-HUB** untuk pembaca yang butuh alur rekap bulanan utuh selain hitung `%`. |
| **Bagian 4** *(Setelah Tips Excel `COUNTIF`)* | `format absen siswa Excel` | `../download-format-absen-siswa-excel/` | Menghubungkan ke aset file `.xlsx` live (P1-C1) agar guru tak perlu membuat tabel dari nol. |
| **Bagian 5** *(Dalam bahasan Guru Mapel)* | `format absen guru mata pelajaran` | `../format-absen-guru-mata-pelajaran/` | Memperkuat otoritas topik guru mapel tanpa mengambil kata kunci jurnal mengajar (P1-C3). |
| **Bagian 6** *(Menjelang End CTA)* | `persentase absen siswa` | `../../fitur/` | Mendorong trafik berniat transaksi ke **Money Page `/fitur/`** sesuai blueprint Pilar 2. |

*Contoh Kalimat Penyisipan Natural:*
- **Bagian 2:** *"Untuk alur penyusunan tabel induknya dari awal bulan sampai tanda tangan kepala sekolah, Bapak/Ibu bisa menyimak panduan lengkap [cara rekap absen](../panduan-cara-rekap-absen-siswa/) agar datanya langsung siap dihitung."*
- **Bagian 4:** *"Belum punya file lembar kerjanya di laptop? Langsung saja unduh template siap rumus di artikel [format absen siswa Excel](../download-format-absen-siswa-excel/) lalu tinggal sesuaikan daftar nama siswanya."*
- **Bagian 5:** *"Supaya catatan tatap muka per kelas rapi sebelum dihitung, pastikan Bapak/Ibu juga memakai [format absen guru mata pelajaran](../format-absen-guru-mata-pelajaran/) yang memisahkan pertemuan tiap rombel."*
- **Bagian 6:** *"Lewat sistem ini, kalkulasi [persentase absen siswa](../../fitur/) langsung tersaji otomatis per hari, per bulan, maupun per semester tanpa perlu mengetik ulang satu rumus pun."*

---

### 2. Penempatan 2 Kotak CTA (`<aside class="cta-box">`)

#### A. Mid-Content CTA (Disisipkan tepat setelah Tabel Simulasi 1 Kelas di Bagian 3)
- **Sudut Pandang:** Empati ringan saat pembaca melihat angka 5 siswa dan membayangkan harus menghitung 36 anak × beberapa kelas.
- **Draft Copy:**
  - **Label:** `Hemat Waktu Akhir Bulan`
  - **Judul:** `Hitung 5 Siswa Cepat, Bagaimana Kalau 300+ Siswa?`
  - **Paragraf:** *"Mengisi tabel dan mengetuk kalkulator untuk 1–2 anak memang ringan. Tapi kalau harus merekap puluhan kelas tiap bulan, biar sistem yang mengerjakan hitungannya secara otomatis."*
  - **Tombol Aksi:**
    - Primary: `Lihat Cara Kerja Sistem Otomatis` -> `../../fitur/`
    - Secondary: `Tanya Admin via WhatsApp` -> `https://wa.me/6287865712625?text=Halo%20Admin%20Presensi%20Project%2C%20saya%20ingin%20tahu%20cara%20hitung%20persentase%20absen%20otomatis`

#### B. End-Content CTA (Disisipkan tepat setelah Bagian 6 sebelum FAQ)
- **Sudut Pandang:** Konversi langsung menggunakan *hook* wajib blueprint Pilar 2 + jaminan **Terima Beres**.
- **Draft Copy:**
  - **Label:** `Solusi Sekolah Terima Beres`
  - **Judul:** `Capek Menghitung Rumus Persentase Kehadiran Setiap Akhir Bulan?`
  - **Paragraf:** *"Saatnya beralih ke Web Absen Mapel Sekolah dari Presensi Project. Perhitungan persentase `H`, `S`, `I`, dan `A` berjalan **100% real-time otomatis** tanpa rumus Excel—sudah termasuk domain sekolah, hosting, serta **gratis bantuan input data master siswa dari Excel**."*
  - **Tombol Aksi:**
    - Primary: `Konsultasi Gratis via WhatsApp` -> `https://wa.me/6287865712625?text=Halo%20Admin%20Presensi%20Project%2C%20saya%20ingin%20konsultasi%20aplikasi%20absensi%20siswa%20yang%20hitung%20persentase%20otomatis`
    - Secondary: `Cek Biaya Paket Sekolah` -> `../../harga/`

---

## LANGKAH 5: Merakit Metadata `<head>` & Schema JSON-LD (`@graph`)

### 1. Metadata `<head>` & Optimasi SERP / WhatsApp Share
- **`<title>` (52 karakter):** `Rumus & Cara Menghitung Absen Siswa (Manual & Excel)`
- **`<meta name="description">` (149 karakter):** `Bingung cara menghitung absen siswa di akhir bulan? Simak rumus persentase absen siswa manual & rumus Excel lengkap dengan contoh simulasi hitungnya!`
- **Canonical URL:** `https://presensiproject.online/blog/cara-menghitung-persentase-absen-siswa/`
- **OG Title:** `Rumus & Cara Menghitung Absen Siswa (Manual & Excel)`
- **OG Image:** `https://presensiproject.online/assets/og-cara-menghitung-persentase-absen-siswa.jpg`
- **Article Section:** `Rekap & Perhitungan Presensi`

### 2. Schema Markup JSON-LD (`@graph`)
Menggabungkan 3 entitas dalam satu blok `<script type="application/ld+json">` yang sinkron dengan isi artikel HTML:

```json
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "BlogPosting",
      "@id": "https://presensiproject.online/blog/cara-menghitung-persentase-absen-siswa/#article",
      "headline": "Rumus & Cara Menghitung Absen Siswa (Manual, Excel, dan Otomatis)",
      "description": "Bingung cara menghitung absen siswa di akhir bulan? Simak rumus persentase absen siswa manual & rumus Excel lengkap dengan contoh simulasi hitungnya!",
      "image": "https://presensiproject.online/assets/og-cara-menghitung-persentase-absen-siswa.jpg",
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
        "@id": "https://presensiproject.online/blog/cara-menghitung-persentase-absen-siswa/"
      },
      "keywords": [
        "cara menghitung absen siswa",
        "cara menghitung persentase absen siswa",
        "cara menghitung absen kehadiran siswa",
        "menghitung absen siswa",
        "rumus persentase absen siswa manual",
        "rumus menghitung absen siswa manual"
      ]
    },
    {
      "@type": "BreadcrumbList",
      "@id": "https://presensiproject.online/blog/cara-menghitung-persentase-absen-siswa/#breadcrumb",
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
          "name": "Cara Menghitung Persentase Absen Siswa",
          "item": "https://presensiproject.online/blog/cara-menghitung-persentase-absen-siswa/"
        }
      ]
    },
    {
      "@type": "FAQPage",
      "@id": "https://presensiproject.online/blog/cara-menghitung-persentase-absen-siswa/#faq",
      "mainEntity": [
        {
          "@type": "Question",
          "name": "Bagaimana rumus menghitung persentase kehadiran siswa untuk nilai rapor?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Gunakan rumus dasar (Total Hadir dibagi Total Hari Efektif atau Pertemuan Mapel) dikali 100%. Pembagi untuk wali kelas memakai hari efektif sekolah, sedangkan guru mapel memakai total pertemuan riil di kelas tersebut."
          }
        },
        {
          "@type": "Question",
          "name": "Apakah siswa yang Sakit (S) atau Izin (I) mengurangi persentase kehadiran?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Secara hitungan matematis kehadiran fisik, ya, karena rumus persentase hadir hanya menghitung jumlah H (Hadir). Namun di rapor, sekolah umumnya membedakan ketidakhadiran berizin (S/I) dengan tanpa keterangan (A/Alpa)."
          }
        },
        {
          "@type": "Question",
          "name": "Kenapa rumus COUNTIF di Excel saya error saat menghitung absen?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Penyebab paling sering adalah perbedaan karakter pemisah antara titik koma (;) dan koma (,) sesuai pengaturan regional laptop. Ubah =COUNTIF(D5:AH5; \"H\") menjadi =COUNTIF(D5:AH5, \"H\") dan pastikan kode huruf diapit tanda kutip ganda."
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
- **Halaman Artikel Final:** `/blog/cara-menghitung-persentase-absen-siswa/index.html`
- **Indeks Blog:** `/blog/index.html` *(penambahan kartu artikel P2-C1)*
- **Peta Situs XML:** `/sitemap.xml` *(penambahan URL kanonis `/blog/cara-menghitung-persentase-absen-siswa/`)*
- **Stylesheet Terkompilasi:** `/dist/output.css` *(dijalankan via `npm run build:css`)*

### 2. Checklist Audit Quality Control (Terverifikasi)
- [x] **Panjang `<title>`:** `52 karakter` *(ideal 50–60 karakter, bebas pemotongan SERP).*
- [x] **Panjang `<meta name="description">`:** `149 karakter` *(ideal 140–155 karakter, memuat keyword target).*
- [x] **Hierarki Heading & Scannability:** `1` H1, `6` H2, `4` H3 *(1 tabel simulasi + 3 FAQ)* tanpa lompatan level heading. Paragraf singkat 2–3 baris dan santai.
- [x] **Aset Konkret:** Kotak Rumus Manual (`% Hadir` & `% Alpa`), contoh hitung 1 siswa (`19/22 = 86,4%`), Tabel HTML simulasi 5 siswa (8 kolom lengkap), dan Kotak Rumus Excel `COUNTIF` + tips pemisah `;` vs `,`.
- [x] **Internal Link & CTA:** 4 tautan kontekstual terpasang (`cara rekap absen` -> P2-HUB, `format absen siswa Excel` -> P1-C1, `format absen guru mata pelajaran` -> P1-C3, `persentase absen siswa` -> `/fitur/`), 2 kotak `<aside class="cta-box">`, dan nomor WhatsApp resmi `6287865712625`.
- [x] **Validasi Teknis:** JSON-LD `@graph` (`BlogPosting`, `BreadcrumbList`, `FAQPage`) valid, `sitemap.xml` XML valid, `npm run build:css` sukses tanpa error (`214ms`).
- [ ] **Publikasi Git:** Menunggu perintah `terbitkan` untuk commit & push ke `origin/main`.
