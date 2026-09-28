# Latihan Quiz - Shoes Store

Nama : Juan Andre Wicaksono Wibowo
NIM : 123250111
Plug : IF-D

Proyek ini adalah tugas pembuatan tampilan landing page toko sepatu sederhana bernama **SHOES.** menggunakan HTML, CSS, dan JavaScript.

---

## Ketentuan Tugas

1. **Teknologi**:
   * HTML, CSS, dan JavaScript. (Penggunaan PHP diperbolehkan, namun tidak ada nilai tambah).
   * Framework CSS bebas (Bootstrap, TailwindCSS, CSS Murni, dsb.).
2. **Fokus Penilaian**:
   * Kemiripan tampilan dengan desain referensi.
   * Kerapian layout.
   * Efek/interaksi sederhana.

---

## Panduan Desain & Palet Warna

### Font Family
`Arial, sans-serif`

### Color Palette
* `#EEEEEE` - Background halaman
* `#FFFFFF` - Background navbar dan product card
* `#DDDDDD` - Background area gambar & background card saat warna **Hitam** dipilih
* `#000000` - Text utama dan button
* `#444444` - Button saat di-hover
* `#777777` - Text kategori
* `#666666` - Text deskripsi
* `#CFE2FF` - Background card saat warna **Biru** dipilih
* `#F5E6CC` - Background card saat warna **Cream** dipilih

---

## Komponen Tampilan Website

### 1. Navbar
* Logo: `SHOES.`
* Menu: `Home`, `Products`, `About`

### 2. Product Card
* **Gambar Produk**: Sepatu
* **Kategori**: `RUNNING SHOES`
* **Nama Produk**: `Air Runner`
* **Deskripsi Produk**: *Sepatu ringan dan nyaman untuk digunakan saat berolahraga maupun aktivitas sehari-hari.*
* **Harga**: `Rp 899.000`
* **Pilihan Warna**: 3 pilihan warna (Hitam, Biru, Cream)
* **Button**: `Add to Cart`

---

## Penggunaan JavaScript

Ketika tombol pilihan warna diklik, warna *background product card* akan berubah sesuai dengan warna yang dipilih:

* **Klik Black** -> Background card berubah menjadi `#DDDDDD`
* **Klik Blue** -> Background card berubah menjadi `#CFE2FF`
* **Klik Cream** -> Background card berubah menjadi `#F5E6CC`

### Ketentuan Minimal Kode JavaScript:
- [x] `getElementById()`
- [x] `onclick`
- [x] `Function`
- [x] Manipulasi style (DOM)

---

## Struktur File

-index.html
-style.css
-script.js
-README.md