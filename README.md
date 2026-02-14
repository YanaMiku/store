# YanaMiku - Website Store Digital Marketing

![YanaMiku Preview](https://images.unsplash.com/photo-1581291518633-83b4ebd1d83e?w=1200&auto=format)

## 📋 Daftar Isi
- [Deskripsi Proyek](#-deskripsi-proyek)
- [Identitas Siswa](#-identitas-siswa)
- [Fitur Website](#-fitur-website)
- [Teknologi yang Digunakan](#-teknologi-yang-digunakan)
- [Struktur Website](#-struktur-website)
- [Cara Menjalankan](#-cara-menjalankan)
- [Screenshot](#-screenshot)
- [Credits](#-credits)

## 🎯 Deskripsi Proyek
Website **YanaMiku** adalah sebuah platform digital store yang menyediakan layanan jasa pembuatan website dan penjualan script siap pakai. Website ini dibuat sebagai tugas mata pelajaran **Digital Marketing** dengan konsep modern, profesional, dan interaktif.

### Tujuan Website:
- Menampilkan portofolio layanan pembuatan website
- Menjual script website siap pakai
- Menyediakan script bot WhatsApp
- Layanan pembuatan bot WhatsApp custom
- Memudahkan calon klien untuk menghubungi via WhatsApp

## 👤 Identitas Siswa
| Data | Keterangan |
|------|------------|
| **Nama** | Fawwaz Gilang Pradana |
| **Absen** | 11 |
| **Kelas** | XI - TKJ 2 |
| **Mapel** | Digital Marketing |
| **Tugas** | Membuat Website Store |
| **Pembimbing** | Catur Eko Raharjo - SMIK |

## ✨ Fitur Website

### 1. **Welcome Popup**
- Muncul otomatis saat pertama kali membuka website
- Menampilkan identitas siswa (Nama, Kelas, Tugas, dll)
- Tombol close (X) untuk menutup
- Selalu muncul setiap refresh (tanpa session)

### 2. **Header & Navigasi**
- Logo animasi GIF (letter-y.gif)
- Menu navigasi: Beranda, Layanan, Katalog Script, Portfolio
- Dropdown menu dengan animasi smooth
- Tombol WhatsApp langsung mengarah ke kontak

### 3. **Hero Section**
- Judul dengan efek Typewriter
- Teks berganti otomatis
- Cursor berkedip (|)
- Tombol CTA "Lihat Script" dan "Konsultasi Gratis"

### 4. **Layanan Unggulan**
4 Kartu layanan utama:
- 💻 Jasa Website
- 📄 Script Website SIAP PAKAI
- 🤖 Script Bot WhatsApp
- ⚙️ Jasa Bot WhatsApp

### 5. **Katalog Produk**
- **Search Bar** dengan ikon kaca pembesar
- **Filter Kategori** (Semua, Script Website, Script Bot, Jasa Website, Jasa Bot)
- **Product Cards** dengan:
  - Icon sesuai nama produk (FontAwesome)
  - Nama produk
  - Deskripsi singkat
  - Harga
  - Tombol Detail (membuka modal)
  - Tombol Ambil (langsung ke WhatsApp)

### 6. **Modal Detail Produk**
- Menampilkan informasi lengkap produk
- Icon besar sesuai kategori
- Deskripsi detail
- Harga dan kategori
- Tombol Order via WhatsApp

### 7. **Footer**
- Copyright dengan tahun real-time (otomatis berganti)
- Social Media Links:
  - Instagram: @yanamiku.shop
  - GitHub: YanaMiku
  - YouTube: @IyuzakiYanagi
  - Portfolio: yanamiku.github.io

### 8. **Fitur Tambahan**
- **Particle Background** (animasi partikel bergerak)
- **Scrollbar kustom** dengan tema gradasi ungu
- **Smooth Scroll** untuk navigasi
- **Glassmorphism effect** pada semua container
- **Responsive Design** (Mobile, Tablet, Desktop)
- **Hover animations** pada cards

## 🛠 Teknologi yang Digunakan

| Teknologi | Kegunaan |
|-----------|----------|
| **HTML5** | Struktur website |
| **Tailwind CSS** | Styling dan layout |
| **CSS3 Custom** | Animasi, glassmorphism, scrollbar |
| **JavaScript Vanilla** | Interaktivitas (filter, search, modal, typewriter) |
| **Font Awesome 6** | Ikon-ikon pada website |
| **Google Fonts** | Font Inter dan Syne (premium) |
| **Particles.js** | Background animasi partikel |

## 📁 Struktur Website

```
YanaMiku-Store/
│
├── 📄 index.html              # File utama website
├── 🖼️ letter-y.gif            # Logo animasi (perlu ditambahkan)
│
└── 📄 README.md               # Dokumentasi proyek
```

## 🚀 Cara Menjalankan

### Prasyarat
- Web browser modern (Chrome, Firefox, Edge, dll)
- Koneksi internet (untuk CDN)

### Langkah-langkah:
1. **Download** file `index.html`
2. **Siapkan** file logo `letter-y.gif` (letakkan di folder yang sama)
3. **Buka** file `index.html` menggunakan web browser
4. Website siap digunakan!

> **Catatan**: Jika tidak memiliki file `letter-y.gif`, website tetap berjalan dengan icon crown default.

## 📸 Screenshot

### Halaman Utama
| Bagian | Tampilan |
|--------|----------|
| **Hero + Typewriter** | Judul dengan efek mengetik otomatis |
| **Layanan Unggulan** | 4 kartu layanan profesional |
| **Katalog Produk** | Grid produk dengan filter dan search |
| **Modal Detail** | Popup informasi lengkap produk |

### Fitur Interaktif
- ✅ **Welcome Popup** - Muncul saat pertama buka
- ✅ **Real-time Search** - Filter produk langsung
- ✅ **Category Filter** - Tab filter kategori
- ✅ **WhatsApp Integration** - Semua tombol terhubung ke WA
- ✅ **Smooth Scroll** - Animasi scroll halus

## 🎨 Konsep Desain

### Warna Dominan
- **Ungu Gradasi**: #b88eff, #c28eff, #a56aff
- **Background Gelap**: #0d0b1a, #1e1a3a, #2a1f3c
- **Aksen**: Hijau untuk tombol WhatsApp

### Efek Visual
- **Glassmorphism**: Background semi-transparan dengan blur
- **Neon Glow**: Efek cahaya pada icon dan border
- **Particle Background**: Animasi partikel bergerak
- **Hover Scale**: Kartu membesar saat dihover

## 💡 Fitur JavaScript

### 1. Typewriter Effect
```javascript
// Teks berganti otomatis
const phrases = ['Website Profesional', 'Script Siap Pakai', 
                  'Bot WhatsApp Custom', 'Solusi Digital'];
```
- Mengetik dan menghapus otomatis
- Cursor berkedip (|)
- Posisi teks terkunci (tidak naik-turun)

### 2. Filter Produk
- **Search** berdasarkan nama produk
- **Category filter** dengan tab interaktif
- Kombinasi search + filter

### 3. Modal System
- Membuka detail produk
- Menampilkan icon besar
- Tombol WhatsApp langsung

### 4. Tahun Real-time
```javascript
document.getElementById('currentYear').textContent = new Date().getFullYear();
```
- Otomatis berganti setiap tahun

## 📱 Responsive Design

Website dioptimalkan untuk:
- **Mobile** (320px - 640px)
- **Tablet** (641px - 1024px)
- **Desktop** (1025px ke atas)

### Penyesuaian Mobile:
- Grid produk menjadi 1 kolom
- Ukuran font menyesuaikan
- Tombol diperkecil
- Tata letak harga tetap 1 baris

## 🔗 Link Penting

- **Portfolio**: [yanamiku.github.io](https://yanamiku.github.io)
- **Instagram**: [@yanamiku.shop](https://instagram.com/yanamiku.shop)
- **GitHub**: [YanaMiku](https://github.com/YanaMiku)
- **YouTube**: [@IyuzakiYanagi](https://youtube.com/@IyuzakiYanagi)
- **WhatsApp**: 6285793589243

## 🙏 Credits

- **Pembimbing**: Catur Eko Raharjo - SMIK
- **Font**: Google Fonts (Inter, Syne)
- **Icons**: Font Awesome 6
- **Particles**: particles.js
- **Images**: Unsplash (placeholder)

---

## 📝 Catatan Penting

1. File `letter-y.gif` perlu disiapkan sendiri untuk logo animasi
2. Nomor WhatsApp sudah terisi dengan kontak yang benar
3. Semua link sosial media aktif dan mengarah ke akun resmi
4. Website dapat dihosting di GitHub Pages

---

**Dibuat oleh: Fawwaz Gilang Pradana**  
**Kelas XI - TKJ 2**  
**Tugas Digital Marketing - 2025**
