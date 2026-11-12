---
name: Presensi Project
description: Sistem Informasi Presensi Siswa Per Jam Pelajaran & Jurnal KBM Digital Terintegrasi WhatsApp
colors:
  primary: "#0f172a"
  primary-hover: "#1e293b"
  accent-wa: "#047857"
  accent-wa-hover: "#059669"
  surface-bg: "#f8fafc"
  surface-card: "#ffffff"
  text-primary: "#0f172a"
  text-secondary: "#475569"
  border-subtle: "#e2e8f0"
  status-hadir: "#065f46"
  status-izin: "#0369a1"
  status-sakit: "#c2410c"
  status-alpa: "#be123c"
typography:
  display:
    fontFamily: "ui-sans-serif, system-ui, sans-serif"
    fontSize: "3rem"
    fontWeight: 800
    lineHeight: 1.15
  body:
    fontFamily: "ui-sans-serif, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
rounded:
  sm: "6px"
  md: "8px"
  lg: "12px"
  xl: "16px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
---

# Design System: Command Center Sekolah Modern

## Overview
Design system untuk Presensi Project memadukan ketegasan dan wibawa institusi pendidikan (Deep Academic Navy) dengan kejelasan status operasional real-time (Emerald WhatsApp & Status Badges). Desain ditujukan untuk meyakinkan pimpinan yayasan dan kepala sekolah mengenai akuntabilitas, kemudahan pakai bagi guru senior di kelas, dan efisiensi biaya.

## Colors
- **Deep Academic Navy (`#0f172a`):** Warna primer untuk header, tombol utama, dan panel command center.
- **Academic Slate Ground (`#f8fafc`):** Latar belakang halaman yang sejuk dan nyaman di mata untuk sesi kerja panjang.
- **Clean Surface (`#ffffff`):** Latar kartu dan panel konten dengan hairline border halus (`#e2e8f0`).
- **Emerald WhatsApp (`#047857` / `#059669`):** Aksen identitas notifikasi WhatsApp dan indikator kesuksesan.
- **Kategori Status 5 Warna:**
  - Hadir: Emerald (`#065f46`)
  - Izin: Sky (`#0369a1`)
  - Sakit: Amber/Orange (`#c2410c`)
  - Alpa: Rose/Red (`#be123c`)

## Typography
- Menggunakan sistem hierarki font sans-serif modern (`ui-sans-serif, system-ui, -apple-system`).
- Judul (`h1`, `h2`, `h3`): `font-extrabold` / `font-bold` dengan `text-wrap: balance` untuk keteraturan visual baris.
- Paragraf isi: Ukuran 15–18px dengan batas lebar optimal `65ch`–`70ch` dan `text-wrap: pretty` untuk mencegah kata gantung (*widows/stragglers*).
- Angka data: Menggunakan fitur `font-variant-numeric: tabular-nums` pada jadwal jam dan rekapitulasi.

## Layout
- **Container Utama:** Lebar maksimal `max-w-7xl` (1280px) dengan padding responsif `px-4 sm:px-6 lg:px-8`.
- **First Viewport (Split Hero):** Rasio 60% teks bernilai tinggi + CTA ganda, dan 40% panel interaktif status KBM kelas.
- **Spasi Vertikal:** Pemisahan section berjarak teratur `py-16 sm:py-20` dengan hairline border bawah `border-slate-200`.

## Elevation & Depth
- Menghindari bayangan hitam tebal (*hard offset shadows*) dan halo glow neon artifisial.
- Kedalaman dibangun melalui hirarki kontras warna latar (`#ffffff` di atas `#f8fafc`), hairline borders `border-slate-200`, dan `shadow-xs` / `shadow-sm` lembut.

## Shapes
- Sudut lengkung terstandarisasi:
  - Tombol & Badge: `rounded-lg` (8px).
  - Kartu & Panel: `rounded-xl` (12px).
  - Container Luar Mockup: `rounded-2xl` (16px).

## Components
- **Navbar Institusional:** Menampilkan logo perisai akademik, navigasi clean, indikator aktif `bg-slate-100`, dan mobile drawer menu yang aksesibel (`aria-expanded`).
- **Dual CTA:** Tombol primer gelap solid (`bg-slate-900`) dipadukan dengan tombol sekunder berbingkai bersih (`bg-white border-slate-300`).
- **Tabular Status List:** Daftar nama siswa dan kehadiran tanpa nested cards berlebihan; mengandalkan garis pemisah tipis `divide-y divide-slate-800` dan badge 5 warna.
- **Accordion FAQ:** Menggunakan native semantik `<details>` dan `<summary>` dengan SVG chevron yang berotasi otomatis saat dibuka.

## Do's and Don'ts
- **DO:** Gunakan icon SVG presisi yang terintegrasi langsung di samping teks judul.
- **DO:** Pertahankan rasio kontras teks minimal 4.5:1 terhadap latar belakang.
- **DON'T:** Menggunakan gradient text, kicker/eyebrow klise di atas judul, atau pulsing dot animasi dekoratif tanpa data streaming nyata.
- **DON'T:** Menumpuk card di dalam card (*nested cards*) yang memicu visual noise.
