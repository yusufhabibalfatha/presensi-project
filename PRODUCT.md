# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML5 with Tailwind CSS v4 (CLI)

## Users

- **Primer (Pengambil Keputusan & Pembeli):** Kepala Sekolah, Ketua Yayasan Pendidikan, dan Komite Sekolah (SD/MI, SMP/MTs, SMA/MA, SMK swasta dan pesantren terpadu). Mereka mencari solusi efisiensi operasional, peningkatan transparansi ke wali murid, dan biaya langganan yang masuk akal tanpa beban per-siswa.
- **Sekunder (Pengguna Operasional):** Guru Pengampu Mata Pelajaran (mengabsen di kelas via smartphone), Wali Kelas & Tim Kurikulum/BK (memantau jurnal dan rekap kehadiran), serta Staf Tata Usaha (manajemen data master siswa & jadwal).

## Product Purpose

Presensi Project hadir untuk mendigitalkan sistem presensi siswa per jam pelajaran dan jurnal mengajar guru secara paperless, terhubung langsung dengan notifikasi otomatis WhatsApp Grup Kelas melalui Fonnte Gateway. Layanan ini didistribusikan dengan skema *all-in-one managed solution* ("terima beres"), mencakup penyediaan domain, hosting server privat, migrasi data siswa awal, dan pendampingan tanpa membebani sekolah dengan infrastruktur teknis yang rumit.

## Positioning

Solusi terkelola privat (*Managed Private SaaS*) all-in-one untuk institusi pendidikan. Berbeda dengan sistem absen gerbang biasa (yang gagal mendeteksi siswa bolos di jam siang) dan software SaaS publik yang membebankan biaya per-siswa yang membengkak, Presensi Project memberikan database dan server privat per sekolah, kuota siswa/guru tak terbatas, biaya tetap tahunan yang hemat, dan integrasi WhatsApp instan per mapel.

## Operating Context

- **Di Ruang Kelas:** Guru membuka aplikasi via peramban smartphone saat KBM berlangsung, mencatat presensi 5 kategori (Hadir, Terlambat, Izin, Sakit, Alpa) dan wajib mengisi materi jurnal mengajar sebelum menyimpan.
- **Di Grup WhatsApp Kelas:** Begitu absensi disimpan, rekapitulasi KBM langsung terkirim otomatis ke grup WhatsApp wali murid dan wali kelas secara real-time.
- **Di Ruang TU & Rapat Kurikulum:** Wali kelas dan staf kurikulum mengakses rekap persentase presensi dan rekap jurnal mengajar tanpa perlu input manual di spreadsheet Excel.

## Capabilities and Constraints

- **Website Pemasaran Saat Ini:** Kumpulan halaman web statis HTML5 responsif dengan Tailwind CSS v4 ([index.html](file:///Users/yusufhabib/Documents/learn/website_statis/index.html), [fitur/index.html](file:///Users/yusufhabib/Documents/learn/website_statis/fitur/index.html), [harga/index.html](file:///Users/yusufhabib/Documents/learn/website_statis/harga/index.html), [demo/index.html](file:///Users/yusufhabib/Documents/learn/website_statis/demo/index.html), [tentang-kami/index.html](file:///Users/yusufhabib/Documents/learn/website_statis/tentang-kami/index.html), [kontak/index.html](file:///Users/yusufhabib/Documents/learn/website_statis/kontak/index.html), [blog/index.html](file:///Users/yusufhabib/Documents/learn/website_statis/blog/index.html)).
- **Aplikasi Frontend Produk:** Vue 3 Composition API, Vite, mobile-first touch-friendly design.
- **Backend & Database Produk:** CodeIgniter 4 (PHP 8+), MySQL/MariaDB terisolasi per sekolah, integrasi Fonnte WhatsApp Gateway API.
- **Model Distribusi:** Bukan penjualan lisensi source code terbuka; sistem terima beres dengan server dan domain khusus sekolah.

## Brand Commitments

- **Nama Brand Resmi:** Presensi Project.
- **Gaya Komunikasi (Tone of Voice):** Edukatif, profesional, terpercaya, transparan, dan solutif bagi manajemen sekolah. Menghindari istilah teknis berbelit-belit yang mengaburkan nilai manfaat langsung bagi pengurus yayasan.

## Evidence on Hand

- Dokumen spesifikasi teknis dan fitur riil: [PROFIL_DAN_FAKTA_APLIKASI.md](file:///Users/yusufhabib/Documents/learn/website_statis/PROFIL_DAN_FAKTA_APLIKASI.md).
- Halaman konten yang sudah ada di repositori: [index.html](file:///Users/yusufhabib/Documents/learn/website_statis/index.html), [fitur/index.html](file:///Users/yusufhabib/Documents/learn/website_statis/fitur/index.html), [harga/index.html](file:///Users/yusufhabib/Documents/learn/website_statis/harga/index.html), [demo/index.html](file:///Users/yusufhabib/Documents/learn/website_statis/demo/index.html), [kontak/index.html](file:///Users/yusufhabib/Documents/learn/website_statis/kontak/index.html), [tentang-kami/index.html](file:///Users/yusufhabib/Documents/learn/website_statis/tentang-kami/index.html), [blog/index.html](file:///Users/yusufhabib/Documents/learn/website_statis/blog/index.html).
- Komitmen keaslian data: Tidak menampilkan testimoni fiktif atau angka metrik palsu.

## Product Principles

1. **Penyelesaian Masalah KBM Nyata:** Presensi berbasis per jam pelajaran untuk mengatasi siswa bolos di tengah hari dan mewajibkan jurnal KBM digital guna meniadakan kebiasaan jurnal rapelan.
2. **Otomatisasi Tanpa Repot:** Broadcast WhatsApp grup kelas terkirim otomatis dalam sekali klik tanpa menuntut guru menyusun pesan manual.
3. **Kedaulatan & Keamanan Data Sekolah:** Data siswa dan sekolah tersimpan di server privat masing-masing tanpa risiko kebocoran multi-tenant.
4. **Bebas Beban Teknis (*Zero IT Friction*):** Layanan terima beres (domain, hosting, konfigurasi awal, dan setup master data) sehingga sekolah dapat langsung merasakan manfaat tanpa tim IT khusus.

## Accessibility & Inclusion

- Hierarki informasi jelas, keterbacaan tinggi (*high legibility*) dan kontras warna yang nyaman untuk pengguna dari berbagai rentang usia (pimpinan yayasan hingga staf guru).
- Desain antarmuka web pemasaran ramah mobile (*mobile-responsive*).
