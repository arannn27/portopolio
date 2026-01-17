# 📖 Tata Cara Pemakaian Website Portfolio

Panduan lengkap untuk menggunakan website portfolio ini dengan mudah dan efektif.

## 🚀 Cara Memulai

### 1. Membuka Website

- **Cara 1**: Buka file `index.html` langsung di browser (Chrome, Firefox, Edge, dll)
- **Cara 2**: Gunakan Live Server di VS Code:
  - Klik kanan pada `index.html`
  - Pilih "Open with Live Server"
  - Website akan terbuka di browser dengan URL lokal

### 2. Persyaratan Browser

- Gunakan browser modern (Chrome, Firefox, Edge, Safari versi terbaru)
- Pastikan JavaScript diaktifkan
- Koneksi internet diperlukan untuk:
  - Memuat Google Fonts
  - Memuat Font Awesome icons
  - Fitur Chat Room (Firebase)

## 🧭 Cara Navigasi

### Navigasi Desktop

1. **Navbar Atas**:

   - Klik menu di bagian atas untuk langsung scroll ke section yang diinginkan
   - Menu akan highlight otomatis saat scroll ke section tertentu

2. **Navigasi dengan Keyboard**:
   - Gunakan tombol `↑` dan `↓` untuk scroll
   - Tekan `Home` untuk kembali ke atas
   - Tekan `End` untuk ke bawah halaman

### Navigasi Mobile

1. **Hamburger Menu**:

   - Klik ikon menu (☰) di pojok kanan atas
   - Pilih section yang ingin dikunjungi
   - Menu akan tertutup otomatis setelah memilih

2. **Bottom Navigation**:
   - Scroll ke bawah untuk melihat floating navigation di bagian bawah
   - Klik ikon untuk navigasi cepat

## 🎯 Cara Menggunakan Fitur-Fitur

### 1. Home Section

- **Tombol "Lihat Portfolio"**: Klik untuk scroll otomatis ke section Projects
- **Tombol "Hubungi Saya"**: Klik untuk scroll ke section Contact
- **Music Player**:
  - Klik ikon musik di pojok kanan bawah untuk membuka player
  - Gunakan tombol play/pause untuk mengontrol musik
  - Klik tombol next untuk lagu berikutnya
  - Drag slider untuk mengatur volume

### 2. About Section

- **Statistik**: Lihat informasi statistik seperti jumlah project, sertifikat, dll
- **Scroll ke bawah** untuk melihat informasi lebih lengkap tentang profil

### 3. Tools & Technologies Section

- **Hover pada tool**: Arahkan mouse ke tool untuk melihat efek hover
- **Grid layout**: Tools ditampilkan dalam grid yang responsif

### 4. Certificates Section

- **Klik sertifikat**: Klik gambar sertifikat untuk membuka modal popup
- **Navigasi di Modal**:
  - Klik tombol `←` untuk sertifikat sebelumnya
  - Klik tombol `→` untuk sertifikat berikutnya
  - Klik tombol `✕` atau area di luar gambar untuk menutup modal
  - Gunakan tombol keyboard `←` dan `→` untuk navigasi

### 5. Projects Section

- **Scroll otomatis**: Section ini memiliki infinite scroll
- **Klik project card**:
  - Klik tombol "Lihat Project" untuk membuka GitHub repository
  - Klik tombol "Live Demo" untuk melihat demo project
- **Hover effect**: Arahkan mouse ke card untuk melihat animasi

### 6. Chat Room Section

**Catatan**: Fitur ini memerlukan konfigurasi Firebase terlebih dahulu.

- **Login**:
  - Klik tombol "Login dengan Google"
  - Pilih akun Google untuk login
- **Mengirim Pesan**:
  - Ketik pesan di input box
  - Tekan `Enter` atau klik tombol kirim
- **Melihat Pesan**:
  - Pesan akan muncul secara real-time
  - Scroll ke atas untuk melihat pesan lama
- **Logout**: Klik tombol logout untuk keluar

### 7. Contact Section

- **Form Kontak**:
  - Isi nama, email, dan pesan
  - Klik tombol "Kirim Pesan" (perlu konfigurasi backend)
- **Social Media Links**:
  - Klik ikon sosial media untuk membuka profil
  - Link akan terbuka di tab baru

## 🎵 Menggunakan Music Player

1. **Membuka Player**:

   - Klik ikon musik di pojok kanan bawah
   - Player akan muncul dengan animasi

2. **Kontrol Musik**:

   - ▶️/⏸️: Play/Pause musik
   - ⏭️: Next song
   - 🔊: Atur volume (drag slider)
   - ⏹️: Stop musik

3. **Menutup Player**:
   - Klik ikon musik lagi untuk menutup
   - Atau klik area di luar player

## 💡 Tips & Trik

### Tips Navigasi

- Gunakan scroll halus untuk pengalaman yang lebih baik
- Klik logo di navbar untuk kembali ke Home section
- Gunakan bottom navigation untuk navigasi cepat di mobile

### Tips Interaksi

- Hover pada elemen interaktif untuk melihat efek animasi
- Klik dengan hati-hati pada modal agar tidak menutup secara tidak sengaja
- Gunakan keyboard untuk navigasi yang lebih cepat

### Tips Performa

- Jika website lambat, pastikan koneksi internet stabil
- Refresh halaman jika ada elemen yang tidak dimuat
- Nonaktifkan ekstensi browser yang mungkin mengganggu

## ❓ Troubleshooting

### Website Tidak Buka

- Pastikan file `index.html` ada di folder root
- Pastikan semua file CSS dan JS terhubung dengan benar
- Cek console browser (F12) untuk melihat error

### Animasi Tidak Berfungsi

- Pastikan JavaScript diaktifkan
- Pastikan GSAP library terload dengan benar
- Refresh halaman

### Chat Room Tidak Bekerja

- Pastikan Firebase sudah dikonfigurasi
- Cek file `components/chat-room/firebase-config.js`
- Pastikan koneksi internet aktif

### Gambar Tidak Muncul

- Pastikan folder `assets/img/` ada dan berisi gambar
- Cek path gambar di kode
- Pastikan format gambar didukung (jpg, png, webp, gif)

### Music Player Tidak Berfungsi

- Pastikan file musik ada di folder `assets/songs/`
- Pastikan format audio didukung (mp3, wav, ogg)
- Cek console browser untuk error

## 📱 Penggunaan di Mobile

### Tips Mobile

- Gunakan mode landscape untuk pengalaman yang lebih baik
- Scroll dengan jari untuk navigasi
- Tap pada elemen untuk interaksi
- Pastikan koneksi internet stabil untuk fitur chat room

### Fitur Mobile-Specific

- Bottom navigation khusus untuk mobile
- Hamburger menu untuk navigasi
- Touch-friendly buttons dan spacing

## 🔒 Privasi & Keamanan

- Chat Room menggunakan Google Authentication (aman)
- Data chat disimpan di Firebase (cloud)
- Tidak ada data pribadi yang dikumpulkan tanpa izin
- Form kontak perlu backend untuk mengirim email

## 📞 Bantuan

Jika mengalami masalah atau pertanyaan:

- **GitHub**: [LippyyDev](https://github.com/LippyyDev)
- **LinkedIn**: [Muhammad Alif Qadri](https://www.linkedin.com/in/muhalifqadri)
- **Email**: alifqadry@gmail.com

---

**Selamat menggunakan website portfolio! 🎉**
