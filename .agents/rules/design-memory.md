# Wedding Invitation Design Memory & Guidelines

File referensi utama: `design.md`

## Inti Prinsip Desain:
1. **Tema Visual (Botanical Glassmorphism - Leafora Style)**:
   - Warna dasar: Dark forest / deep charcoal (`#0a1411`, `#12221b`).
   - Aksen & tombol: Pastel sage green (`#d8ead6` ke `#a2c3a0`) berbentuk kapsul (*full pill*).
   - Tipografi: Putih bersih (`#f5f7f5`) dan muted sage (`#9cb1a6`).
   - **Zero Gold**: Dilarang menambahkan warna emas/kuning emas mencolok atau ornamen berlebihan.
   - Efek kartu: Frosted glass buram (*backdrop-blur 18px-20px*) dengan garis tepi tipis (*hairline border 1px*).

2. **Penggunaan Aset (100% Menggunakan Aset Lokal yang Sudah Ada)**:
   - **DILARANG menggunakan foto wajah orang lain / orang asing**.
   - **DILARANG menambahkan atau mengunduh aset gambar eksternal yang tidak perlu**.
   - Gunakan aset universal lokal yang sudah tersedia di `assets/images/`:
     - `assets/images/couple-main.jpg`: Gunungan Wayang Daun & Bunga Hijau (Pohon Hayat / Tree of Life) untuk cover, hero, dan avatar mempelai.
     - `assets/images/couple-opening.webp`: Ukiran 3D Gunungan Kayon untuk aksen pembuka gerbang budaya.
     - `assets/images/story-photo.webp`: Buket bunga mawar putih & eukaliptus untuk seksi Love Story.
     - `assets/images/foliage-leaf.png`: Ilustrasi dedaunan & mawar vintage untuk ornamen pendukung.
     - `assets/images/frame-ornament.png` & `assets/images/divider-ornament.png`: Garis dan ornamen pemisah klasik.
     - `assets/images/bank-seabank.svg` & `assets/images/chip-atm.png`: Visual resmi kartu amplop digital SeaBank.
     - `assets/audio/howls-moving.mp3`: Musik latar pernikahan.

3. **Struktur Teknis & Komponen**:
   - Seluruh integrasi tetap mempertahankan kompatibilitas dengan Cloudflare D1 worker dan skrip dinamis `config.js` (data binding).
