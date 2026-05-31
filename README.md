# E-Portfolio PPG Prajabatan PJOK

Website E-Portfolio untuk mahasiswa PPG Prajabatan Jurusan Pendidikan Jasmani Olahraga dan Kesehatan (PJOK). Website ini dirancang untuk mendokumentasikan perjalanan pembelajaran dan perkembangan kompetensi calon guru profesional.

## 🚀 Fitur Utama

### 📋 Profil Mahasiswa
- Informasi lengkap profil mahasiswa
- Narasi tentang asal daerah dan keunikannya
- Inspirasi dan tujuan menjadi guru profesional
- Kutipan motivasi yang memperkuat profil

### 📚 Artefak Produk Pembelajaran
- **RPP (Rencana Pelaksanaan Pembelajaran)**: Dokumen perencanaan pembelajaran komprehensif
- **Media Pembelajaran**: Kumpulan media inovatif untuk mendukung proses belajar mengajar
- **Hasil Kerja Siswa**: Dokumentasi hasil kerja sebagai bukti keberhasilan pembelajaran
- **Penilaian GP dan DPL**: Evaluasi dari Guru Pamong dan Dosen Pembimbing Lapangan
- **Video Pembelajaran**: Rekaman praktik mengajar untuk bahan refleksi

### 📊 Instrumen Penilaian
- **Lampiran 7**: Instrumen Penilaian Penyusunan Perangkat Pembelajaran
- **Lampiran 8**: Instrumen Penilaian Praktik Mengajar Mahasiswa
- Hasil penilaian dari Guru Pamong untuk 3 siklus PPL Terbimbing

### 🎯 Model Guru yang Dituju
- Misi dan visi menjadi guru profesional
- Kompetensi yang ingin dikembangkan:
  - Kompetensi Pedagogik
  - Kompetensi Sosial
  - Kompetensi Profesional
  - Karakter guru yang inspiratif

### 📸 Dokumentasi
- Galeri foto praktik mengajar
- Dokumentasi kegiatan ekstrakurikuler
- Prestasi siswa dalam kompetisi olahraga
- Filter kategori untuk kemudahan navigasi

## 🛠️ Cara Menggunakan

### 1. Buka Website di Localhost
```bash
# Buka file index.html di browser favorit Anda
# Atau gunakan live server jika tersedia
```

### 2. Personalisasi Profil
Edit file `script.js` untuk mengubah data mahasiswa:
```javascript
const studentData = {
    name: "Nama Anda",
    nim: "NIM Anda",
    origin: "Asal Daerah Anda",
    about: "Tentang Anda...",
    inspiration: "Inspirasi Anda...",
    quote: "Kutipan motivasi..."
};
```

### 3. Tambahkan Artefak
Edit file `script.js` pada bagian `artifactData` untuk menambahkan artefak baru:
```javascript
const artifactData = {
    rpp: {
        title: "Judul Artefak",
        content: "Konten artefak dalam format HTML"
    }
};
```

### 4. Update Dokumentasi
Ganti placeholder gambar dengan foto dokumentasi Anda:
- Cari kode `https://via.placeholder.com/...` di file `index.html`
- Ganti dengan path foto Anda (misalnya: `images/foto1.jpg`)

## 🎨 Desain & Tema

Website menggunakan tema olahraga yang modern dan menarik:
- **Warna Utama**: Oranye (#FF6B35) dan Biru Tua (#004E89)
- **Font**: Poppins untuk keterbacaan yang optimal
- **Animasi**: Smooth scrolling dan hover effects
- **Responsive**: Optimal di desktop, tablet, dan mobile

## 📱 Responsive Design

Website sepenuhnya responsive:
- **Desktop**: Layout grid dengan sidebar navigasi
- **Tablet**: Layout 2 kolom dengan menu yang disesuaikan
- **Mobile**: Layout single column dengan hamburger menu

## 🔧 Teknologi yang Digunakan

- **HTML5**: Semantic markup untuk struktur yang baik
- **CSS3**: Flexbox dan Grid untuk layout modern
- **JavaScript Vanilla**: Interaktivitas tanpa dependencies
- **Font Awesome**: Icons untuk visual yang menarik
- **Google Fonts**: Typography yang profesional

## 📂 Struktur File

```
E-Portfolio/
├── index.html          # Halaman utama
├── styles.css          # Stylesheet utama
├── script.js           # JavaScript untuk interaktivitas
├── README.md           # Dokumentasi ini
└── images/             # Folder untuk foto dokumentasi
    ├── praktik-mengajar/
    ├── kegiatan/
    └── prestasi/
```

## 🌟 Fitur Interaktif

### Navigation
- Smooth scrolling antar section
- Active state indicator
- Mobile-friendly hamburger menu

### Gallery
- Filter berdasarkan kategori
- Hover effects dengan overlay informasi
- Modal view untuk detail artefak

### Animations
- Fade-in effects saat scroll
- Progress bar animations
- Counter animations untuk skor
- Floating sports icons di hero section

## 📝 Konten Dinamis

### Profil Mahasiswa
Konten profil dapat dengan mudah diedit melalui objek `studentData` di `script.js`:
- Nama dan NIM
- Asal daerah
- Narasi personal
- Kutipan motivasi

### Artefak Pembelajaran
Setiap artefak memiliki analisis mendalam:
- Konteks pembelajaran
- Tujuan pembelajaran
- Kelebihan dan kekurangan
- Analisis berdasarkan teori pendidikan

## 🎯 Target Pengguna

Website ini dirancang untuk:
- Mahasiswa PPG Prajabatan PJOK
- Dosen Pembimbing Lapangan (DPL)
- Guru Pamong
- Pihak institusi pendidikan
- Komite penilaian portfolio

## 📈 Penilaian & Evaluasi

Website mencakup instrumen penilaian lengkap:
- Penilaian perangkat pembelajaran (Lampiran 7)
- Penilaian praktik mengajar (Lampiran 8)
- Tracking progress per siklus
- Feedback dari GP dan DPL

## 🔒 Keamanan & Privasi

- Tidak ada pengumpulan data pribadi
- Tidak menggunakan eksternal API
- Konten sepenuhnya client-side
- Aman untuk digunakan di local environment

## 🚀 Deployment

Untuk deployment ke production:
1. Upload semua file ke web hosting
2. Pastikan semua path gambar benar
3. Test semua fungsi interaktif
4. Optimize gambar untuk loading cepat

## 📞 Kontak & Support

Untuk bantuan atau pertanyaan:
- Email: email@example.com
- Phone: +62 812-3456-7890

---

**© 2024 E-Portfolio PPG Prajabatan PJOK. All rights reserved.**
