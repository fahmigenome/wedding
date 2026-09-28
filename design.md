# 🌿 Spesifikasi Desain Undangan Pernikahan
## *Botanical Glassmorphism & Gunungan Wayang (Quiet Luxury)*

---

## 1. Filosofi Desain & Arah Visual

Undangan ini memadukan **Keanggunan Tradisional Nusantara (Gunungan / Kayon Wayang)** dengan estetika modern **Botanical Frosted Glassmorphism (Leafora Style)**:
- **Quiet Luxury (Bebas Warna Gold)**: Menggunakan palet gelap alami (*deep forest charcoal* `#0a1411`), tipografi putih bersih (*pure white* `#f5f7f5`), serta aksen hijau sage lembut (*pastel sage green* `#d8ead6` ke `#a2c3a0`). Tidak menggunakan warna emas/kuning mencolok agar kesan sakral, tenang, dan dewasa tetap terjaga.
- **Kaca Buram Transparan (*Frosted Glass*)**: Kartu-kartu kontainer dengan *heavy backdrop-blur (18px - 20px)*, sudut melengkung modern (22px - 26px), dan garis tepi kaca tipis (*hairline border 1px*) yang bersih.
- **Tombol Pill Kapsul Sage Green**: Tombol aksi utama (*Buka Undangan, Save The Date, Kirim Ucapan, Buka Rekening*) mengadopsi bentuk kapsul penuh (*full pill*) berwarna sage green dengan tipografi tegas dan elegan.

---

## 2. Strategi Aset Universal (100% Berbasis Aset yang Sudah Ada)

Sesuai prinsip desain, **undangan ini TIDAK menggunakan foto wajah orang lain / orang asing**, melainkan mengoptimalkan **aset universal yang sudah tersedia secara lokal** di dalam repositori:

| Aset Lokal | Tipe Visual | Peruntukan / Penempatan | Makna & Kesan Filosofis |
| :--- | :--- | :--- | :--- |
| `assets/images/couple-main.jpg` | Gunungan Wayang Daun & Bunga Hijau | Background Cover, Foto Utama, Hero & Mempelai | **Pohon Hayat (Tree of Life)**: Simbol sakral dimulainya babak kehidupan baru, bersatu dalam harmoni alam dan doa. |
| `assets/images/couple-opening.webp` | Ukiran 3D Gunungan Kayon Emas Antik | Aksen Pembuka / Maskot Budaya Universal | Melambangkan gerbang restu (*gapura*) dan kehormatan penyambutan tamu undangan. |
| `assets/images/story-photo.webp` | Buket Bunga Mawar Putih & Eukaliptus | Foto Seksi Love Story & Perjalanan Cinta | Simbol ketulusan cinta, keabadian janji suci, dan nuansa botani yang anggun. |
| `assets/images/foliage-leaf.png` | Ilustrasi Dedaunan & Mawar Vintage | Ornamen Seksi & Latar Botani Halus | Memperkuat identitas *botanical couture* yang tenang dan alami. |
| `assets/images/frame-ornament.png` | Ornamen Ukiran Garis Putih Klasik | Pembatas Header & Penghubung Seksi | Memberikan sentuhan simetri estetis yang rapi dan elegan. |
| `assets/images/divider-ornament.png`| Garis Pemisah Klasik Floral | Pemisah antar detail acara (Akad & Resepsi) | Transisi informasi yang bersih tanpa membebani mata. |
| `assets/images/bank-seabank.svg` | Logo Resmi SeaBank (Vektor Bersih) | Amplop Digital / Kartu Rekening | Keterbacaan instan dan profesional untuk transfer hadiah cashless. |
| `assets/images/chip-atm.png` | Chip Kartu Pintar Realistis | Kartu Rekening Matte Obsidian | Memberikan tekstur nyata kartu VIP modern yang eksklusif. |
| `assets/audio/howls-moving.mp3` | Musik Latar Akustik Sinematik | Pemutar Musik Mengambang (*Floating Vinyl*) | Membangun suasana romantis, khidmat, dan mendalam saat tamu membaca undangan. |

> **Catatan Penting**: Desain ini mandiri dan tidak memerlukan penambahan foto wajah eksternal atau gambar stok yang tidak relevan. Aset yang ada sudah sangat lengkap dan saling mengunci tema *Dark Forest Gunungan Botanical*.

---

## 3. Desain Komponen & Interaktivitas

### A. Layar Pembuka (Cover Gate)
- **Cover Kolom**: Latar belakang Gunungan Wayang gelap (`couple-main.jpg`) dengan pencahayaan radial lembut.
- **Nama Tamu**: Kapsul kaca transparan dengan border tipis dan tipografi jelas (`tamu-undangan-marker`).
- **Tombol "Buka Undangan"**: Kapsul sage green dengan transisi hover meluncur halus (`→`) yang membuka tirai undangan secara sinematik (`cubic-bezier(0.77, 0, 0.175, 1)`).

### B. Profil Mempelai (Pria & Wanita)
- **Bingkai Gambar**: Menggunakan bingkai melengkung modern (26px) berbingkai garis kaca tipis dengan bayangan lembut, membungkus motif Gunungan Hayat universal yang sakral.
- **Tautan Instagram**: Pill kaca minimalis dengan ikon Instagram untuk membuka profil media sosial kedua mempelai.

### C. Seksi Acara (Akad Nikah & Resepsi)
- **Kartu Kaca Frosted (`.acara-con`)**: Dua kartu acara utama dengan background kaca buram gelap, tipografi tanggal yang kontras, dan penataan waktu yang rapi.
- **Tombol "Lihat Lokasi"**: Pill kapsul transparan dengan ikon pin peta untuk langsung membuka navigasi rute Google Maps.
- **Fitur 1-Klik Kalender**: Kemudahan menyimpan jadwal langsung ke Google Calendar atau Apple iCal agar tamu mendapatkan alarm pengingat otomatis.

### D. Amplop Digital & Kirim Hadiah
- **Kartu Rekening Bank**: Kartu bernuansa *Matte Obsidian VIP* dengan chip ATM, logo SeaBank resmi, nomor rekening monospace tebal, dan tombol *"Copy"* yang memicu toast konfirmasi.
- **Pengiriman Kado Fisik**: Informasi penerima kado dengan alamat jelas dan tombol praktis untuk menyalin alamat tujuan kurir/marketplace.

### E. RSVP & Ucapan Doa Tamu
- **Formulir Interaktif**: Input nama, pesan doa, dan pill kehadiran (*Hadir* hijau pastel, *Tidak Hadir* koral lembut) yang tersinkronisasi langsung ke database Cloudflare D1.
- **Daftar Ucapan**: Kartu kaca gelap berbaris rapi dengan avatar inisial berwarna sage muda dan indikator waktu relatif (*timeAgo*).

### F. Pemutar Musik Mengambang
- Disc piringan hitam di pojok kanan bawah yang berputar saat musik aktif dan otomatis berhenti sementara (*auto-pause*) saat tamu meminimalkan jendela browser.

---

## 4. Keselarasan Teknis (Berdasarkan Web Saat Ini)

Semua struktur dan nama kelas CSS dalam spesifikasi ini 100% selaras dengan kode nyata di `index.html` dan `config.js`:
- Seluruh data binding dinamis (`[data-bind]`, `[data-bind-img]`, `[data-bind-html]`, `[data-bind-href]`) tetap utuh.
- Tidak ada dependensi pustaka berat baru; performa tetap cepat dan responsif di semua perangkat mobile (iOS Safari & Android Chrome).
