# presensi-project

Website statis institusional dan portal pemasaran sistem presensi siswa per mata pelajaran berbasis web (**Presensi Project** — *Sistem Presensi Sekolah Terima Beres*).

Dirancang khusus untuk Kepala Sekolah, Wakasek Kurikulum, dan Pengurus Yayasan (SD/MI, SMP/MTs, SMA/MA, SMK swasta, dan pesantren terpadu) di seluruh Indonesia.

---

## 🌟 Fitur Utama Website

- **Clean Directory Routing (SEO Modern):** Setiap halaman berada pada subfolder tersendiri dengan `index.html` dan berakhiran slash (`/`, `/fitur/`, `/harga/`, `/demo/`, `/kontak/`, `/tentang-kami/`, `/blog/`).
- **Command Center Design System:** Dibangun dengan Tailwind CSS v4, rasio kontras tinggi WCAG AA ($\ge 4.5:1$), tipografi terkalibrasi (`text-pretty`, `text-balance`, `max-w-[50ch]`), dan 100% bebas dari anti-pattern AI (*Zero AI Slop*).
- **Simulator Presensi Interaktif di Browser (`/demo/#simulator-presensi`):** Memungkinkan calon pelanggan mencoba langsung 3 langkah alur kerja (Pilih Sesi Jadwal &rarr; Presensi Siswa & Jurnal KBM &rarr; Pratinjau Broadcast WhatsApp Gateway).
- **SEO Teknis Lengkap:** Dilengkapi `sitemap.xml`, `robots.txt`, `favicon.svg`, Open Graph, Twitter Cards, serta Schema.org JSON-LD structured data.

---

## 📂 Struktur Direktori Proyek

```
.
├── index.html                  # Halaman Beranda Utama
├── fitur/
│   └── index.html              # Halaman Detail Fitur Sistem KBM
├── harga/
│   └── index.html              # Halaman Paket Harga & Komparasi Biaya
├── demo/
│   └── index.html              # Panduan & Simulator Presensi Interaktif
├── kontak/
│   └── index.html              # Konsultasi & Formulir Pengajuan Proposal
├── tentang-kami/
│   └── index.html              # Profil Layanan & Misi Presensi Project
├── blog/
│   ├── index.html              # Indeks Artikel Edukasi
│   └── contoh-artikel/
│       └── index.html          # Contoh Artikel Edukasi KBM
├── dist/
│   └── output.css              # Hasil Kompilasi Tailwind CSS (Minified)
├── src/
│   └── input.css               # Berkas Sumber Tailwind CSS v4
├── sitemap.xml                 # Peta Situs XML Standar Schema 0.9
├── robots.txt                  # Aturan Crawler Mesin Pencari
├── favicon.svg                 # Favicon Vektor Perisai Emerald
├── package.json                # Skrip & Dependensi Proyek
└── .github/
    └── workflows/
        └── deploy-pages.yml    # Alur Kerja Otomatis GitHub Pages
```

---

## 🚀 Panduan Membuka & Mengembangkan Proyek Lokal

### 1. Prasyarat
- Node.js versi 18 ke atas
- npm (Node Package Manager)

### 2. Instalasi Dependensi
```bash
npm install
```

### 3. Kompilasi Tailwind CSS
```bash
# Kompilasi sekali untuk produksi (minified)
npm run build:css

# Mode pengembangan (watch changes)
npm run dev:css
```

### 4. Menjalankan Web Server Lokal
```bash
npm start
```
Buka browser di alamat: **`http://localhost:3000`**

---

## 🌐 Deployment ke GitHub Pages

Proyek ini telah dikonfigurasi dengan GitHub Actions (`.github/workflows/deploy-pages.yml`):

1. Masuk ke repository GitHub: `https://github.com/yusufhabibalfatha/presensi-project`
2. Buka menu **Settings** &rarr; **Pages**
3. Pada bagian **Build and deployment > Source**, pilih opsi: **GitHub Actions**
4. Setiap push ke branch `main` akan otomatis memicu build Tailwind CSS dan mempublikasikan situs ke GitHub Pages!

---

## 📄 Lisensi
Hak Cipta &copy; 2026 Presensi Project. Seluruh Hak Cipta Dilindungi Undang-Undang.
