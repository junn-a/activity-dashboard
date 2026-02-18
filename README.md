# 🏍️ MotorLog & Activity Tracker
> **Modern GitHub-Style Activity Tracker for Your Daily Maintenance and Tasks.**

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Hosting](https://img.shields.io/badge/Hosting-GitHub_Pages-blue)
![License](https://img.shields.io/badge/License-MIT-orange)

Aplikasi web ringan berbasis **Single-File** untuk mencatat riwayat perawatan motor (ganti oli, cuci, servis) atau kegiatan harian lainnya dengan visualisasi heatmap ala kontribusi GitHub.

---

## ✨ Fitur Utama

- **📊 GitHub-Style Heatmap**: Visualisasi aktivitas selama 365 hari dalam setahun.
- **👥 Multi-User Ready**: Gunakan URL unik (e.g., `?user=budi`) untuk memisahkan data antar pengguna.
- **⚡ Quick Input**: Form input cepat di bagian atas yang otomatis mendeteksi tanggal hari ini (*anti-backdate*).
- **🎨 Smart Coloring**: Warna kotak berubah otomatis berdasarkan kata kunci (Cuci, Oli, Servis).
- **📱 Responsive Design**: Tampilan bersih dan nyaman diakses melalui smartphone maupun desktop.
- **🔒 Privacy Focused**: Data disimpan secara lokal di browser Anda menggunakan `LocalStorage`.
- **💎 Modern UI**: Menggunakan Tailwind CSS dengan custom modal yang elegan (bukan popup browser jadul).

---

## 🚀 Cara Instalasi & Hosting (Gratis)

Aplikasi ini sangat mudah untuk di-onlinekan:

1. **Fork atau Download** repository ini.
2. Pastikan file utama bernama `index.html`.
3. Upload ke **GitHub Repository** Anda.
4. Masuk ke **Settings > Pages**.
5. Pilih Branch `main`, lalu **Save**.
6. **Selesai!** Link aplikasi Anda akan segera aktif.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** & **JavaScript (Vanilla)** - Logika aplikasi.
- **Tailwind CSS** - Styling dan layouting modern.
- **LocalStorage API** - Penyimpanan data di sisi klien.
- **Lucide/Emoji Icons** - Visual yang intuitif.

---

## 📝 Cara Penggunaan

1. **Masuk ke Aplikasi**: Saat pertama kali dibuka, masukkan nama Anda.
2. **Input Aktivitas**: Ketik kegiatan Anda (misal: "Ganti Oli") di kolom input atas, lalu klik **Submit**.
3. **Lihat Kalender**: Kotak pada tanggal hari ini akan otomatis berubah warna.
4. **Edit/Hapus**: Ingin mengubah catatan lama? Cukup klik kotak pada kalender, perbarui teksnya, atau hapus.
5. **Ganti User**: Gunakan menu "Ganti User" di pojok kanan atas untuk berpindah akun.

---

## 💡 Tips
Agar data tetap aman, jangan sering menghapus *Cache/Clear Data* browser Anda, karena aplikasi ini menyimpan data di memori browser perangkat tersebut.

---

Dibuat dengan ❤️ untuk para pecinta motor dan produktivitas.  
**Bikin motormu kinclong, catat riwayatnya!** 🛵✨