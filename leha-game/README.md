# Leha Birthday Game — Vercel Prototype

Prototype aplikasi web berdasarkan Blueprint Revisi Game Ulang Tahun Leha.

## Fitur prototype
- Scene 1–41 tersedia dan bisa dinavigasi.
- Scene 2: Leha playable, Hikam locked.
- Character presence + idle animation.
- Ambient animation: cloud, trees, sun, ground.
- Interaksi object berbentuk aksi karakter (prototype trigger).
- Chapter map untuk lompat scene saat development.
- Struktur mudah di-adjust lewat `src/main.jsx` dan styling di `src/style.css`.
- Vercel-ready dengan Vite.

## Jalankan lokal
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## Deploy ke Vercel
Upload repository ini ke GitHub, lalu import repository di Vercel. Framework akan terdeteksi sebagai Vite. Build command: `npm run build`; output: `dist`.

## Catatan
Ini adalah functional prototype / vertical slice UI, bukan asset-final production game. Sprite, background, audio, dialog final, puzzle logic, save system, dan asset spesifik dapat ditambahkan tanpa mengganti struktur dasar.
