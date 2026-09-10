# WONY Floral Dashboard V2

Redesain Home yang mengikuti komposisi referensi: sidebar kiri, dashboard editorial di tengah, serta profil dan Flower Shop di kanan.

## Isi
- `index.html` — prototipe lengkap dengan responsive UI dan motion
- `assets/hero-fairy-house.jpg` — ilustrasi hero baru, dibuat khusus
- `assets/profile-vine.jpg` — ilustrasi tanaman sidebar baru, dibuat khusus
- ikon, logo, petal, avatar art, dan dekorasi lain dibuat langsung melalui SVG/CSS di `index.html`
- `vercel.json` — konfigurasi deployment statis

## Deploy ke Vercel
Unggah isi folder ini ke root repository GitHub, lalu import repository di Vercel dengan Framework Preset `Other`. Tidak perlu build command.

## Tampilan yang diuji
- Desktop 16:9 — 1440 × 810
- Desktop mode vertikal 9:16 — 923 × 1640
- Mobile — 390 × 844

## Motion
Petal ambience, hero breathing/parallax, vine sway, shimmer, hover lift, dan press feedback. `prefers-reduced-motion` didukung.
