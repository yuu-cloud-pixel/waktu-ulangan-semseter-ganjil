# Hitung Mundur Tugas

Aplikasi hitung mundur untuk ulangan, tugas, dan acara. Bisa diinstal sebagai aplikasi desktop (PWA) dan berjalan offline.

## Isi folder

- `index.html` – aplikasi utama
- `manifest.webmanifest` – data aplikasi (nama, ikon, warna)
- `sw.js` – service worker agar bisa dipakai offline
- `icons/` – ikon aplikasi

## Hosting di GitHub Pages

1. Buat repository baru di GitHub, misalnya `hitung-mundur`.
2. Unggah semua isi folder ini ke repository (`index.html` harus ada di folder paling atas).
3. Buka **Settings → Pages**.
4. Di **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
5. Tunggu 1–2 menit. Alamatnya: `https://USERNAME.github.io/hitung-mundur/`

## Instal sebagai aplikasi desktop

Buka alamat GitHub Pages di Chrome atau Edge, lalu klik ikon **Instal** di kolom alamat (atau menu ⋮ → **Instal Hitung Mundur Tugas**). Aplikasi akan punya jendela sendiri dan pintasan di desktop atau menu Start.

## Catatan

- Daftar pengingat tersimpan di browser (localStorage) di perangkat yang sama.
- Jika kamu mengubah file, naikkan nama cache di `sw.js` (`hitung-mundur-v1` → `v2`) agar pembaruan terpasang.
