# WONY Home — Motion Prototype

Konsep pertama Home yang menyatukan dashboard dan profil, mengikuti struktur referensi: sidebar kiri, pusat aktivitas, dan ringkasan profil di kanan.

## Menjalankan

Buka `index.html` di browser. Seluruh aset utama sudah berada di folder `assets/` dan tidak membutuhkan build step.

## Vercel

Folder ini bisa diunggah sebagai proyek statis untuk review visual. Implementasi produksi berikutnya akan dipindahkan ke Next.js + TypeScript dan disambungkan ke autentikasi, database, inventory, gacha, marketplace, serta API game.

## Motion

- Petal ambience
- Hero background drift dan pointer parallax
- Orbit sparkle
- Progress reveal
- Hover lift, press feedback, dan navigation states
- `prefers-reduced-motion` didukung

## Responsive

- Desktop: sidebar + dashboard + profile rail
- Tablet: profile menjadi panel bawah
- Mobile: single-column + floating bottom navigation
