# 📷 QR Code Web Tool (Scanner & Generator)

Sebuah aplikasi berbasis web sederhana dan interaktif yang berfungsi untuk **membuat (Generate)** QR Code dari teks/URL dan **memindai (Scan)** QR Code menggunakan kamera perangkat secara langsung. Proyek ini dibangun menggunakan teknologi web dasar: **HTML5, CSS3, dan Vanilla JavaScript**.

---

## 🚀 Fitur Utama

* **QR Code Generator:**
  * Mengubah teks, nomor telepon, atau URL menjadi QR Code secara instan.
  * Fitur untuk mengunduh (*download*) hasil QR Code dalam format gambar (PNG).
* **QR Code Scanner:**
  * Memindai QR Code langsung menggunakan kamera HP atau *webcam* laptop secara *real-time*.
  * Fitur alternatif untuk memindai dengan cara mengunggah (*upload*) file gambar QR Code dari galeri.
  * Deteksi otomatis URL (jika hasil scan berupa link, pengguna bisa langsung mengkliknya).
* **Desain Modern & Responsif:** Tampilan antarmuka yang bersih, intuitif, dan nyaman digunakan baik di layar komputer maupun *smartphone*.

---

## 🛠️ Teknologi & Library yang Digunakan

Proyek ini dibuat menggunakan kombinasi teknologi web murni tanpa *framework* berat, serta memanfaatkan library open-source yang ringan:

1. **HTML5** – Untuk menyusun struktur elemen halaman (input, tombol, dan area pratinjau kamera).
2. **CSS3** – Untuk tata letak (Layouting) yang rapi, efek transisi, dan desain responsif.
3. **Vanilla JavaScript (ES6+)** – Untuk logika aplikasi, manipulasi DOM, dan integrasi library.
4. **Library Pendukung (Menggunakan CDN):**
   * **[qrcode.js](https://cdnjs.com/cards/qrcodejs)** (atau `davidshimjs/qrcodejs`) – Digunakan untuk menghasilkan/generate gambar QR Code.
   * **[html5-qrcode](https://github.com/mebjas/html5-qrcode)** – Library yang efisien untuk mengakses kamera dan memproses pemindaian/scan QR Code.

---

## 📸 Tampilan Proyek

*(Tips: Ambil screenshot dari aplikasimu lalu masukkan ke sini agar tampilan repository GitHub terlihat lebih profesional)*