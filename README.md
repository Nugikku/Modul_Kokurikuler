# 📚 ModulKu - Sistem Penyusun Modul Kokurikuler Digital

Sebuah aplikasi web *client-side* yang dirancang untuk membantu tenaga pendidik dalam menyusun, mengelola, dan mengekspor dokumen Modul Kokurikuler secara digital, terstruktur, dan profesional.

## ✨ Fitur Utama

- **Formulir Cerdas & Dinamis:** Antarmuka pengisian data yang dilengkapi logika kondisional (menyesuaikan jenjang Sekolah/Madrasah) dan mendukung berbagai instrumen pedagogik seperti Tema Lintas Mapel, 7 Kebiasaan Anak, dan Target Dimensi Profil Lulusan.
- **Ekspor PDF Anti-Blank:** Menggunakan teknik *element cloning* tingkat lanjut bersama `html2pdf.js` untuk menjamin hasil unduhan PDF yang rapi, presisi, dan mengatasi *bug* halaman kosong akibat koordinat *scroll*.
- **Penyimpanan Riwayat Offline:** Dilengkapi fitur "Riwayat Modul" yang menyimpan data secara persisten di dalam browser menggunakan `localStorage`. Tidak memerlukan konfigurasi *database* backend.
- **Desain Modern & Responsif:** Antarmuka bergaya *SaaS (Software as a Service)* yang dibangun dengan Tailwind CSS. Mendukung navigasi *Off-Canvas* sehingga tetap rapi saat diakses melalui *smartphone* maupun Desktop.

## 🛠️ Teknologi yang Digunakan

- **HTML5 & Vanilla JavaScript** (Struktur, Logika DOM, dan *Local Storage*)
- **Tailwind CSS** (via CDN untuk *styling* dan *layouting* responsif)
- **html2pdf.js** (Mesin konversi HTML ke dokumen PDF beresolusi tinggi)

## 🚀 Cara Menjalankan Aplikasi

Aplikasi ini berjalan murni di sisi klien (*Client-Side Rendering*) tanpa perlu repot melakukan instalasi server lokal (seperti XAMPP/Node.js) atau konfigurasi MySQL.

1. *Clone* repositori ini ke komputer Anda:
   ```bash
   git clone [https://github.com/Nugikku/nama-repo-anda.git](https://github.com/Nugikku/nama-repo-anda.git)
