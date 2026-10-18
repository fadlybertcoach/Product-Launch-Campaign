# Checklist Kempen Pelancaran (PWA)

Aplikasi Web Progresif (PWA) ringkas dan pantas yang direka khusus untuk menguruskan senarai semak (checklist) komprehensif bagi pelancaran produk. Alat digital ini memastikan setiap fasa kempen—daripada persediaan awal sehingga pelaporan akhir—dilaksanakan dengan teratur tanpa ada langkah yang tertinggal.

## Ciri-Ciri Utama
* **Fasa Berstruktur:** Membahagikan tugasan kepada fasa logik seperti Persediaan, Pangkalan Data, Medium, Tindakan/Pembelian, Perlaksanaan, dan Pelaporan.
* **Kotak Semak Interaktif:** Membolehkan pengguna menandakan tugasan yang telah selesai untuk memantau kemajuan kempen dengan mudah.
* **Penyimpanan Automatik:** Menyimpan status kemajuan secara automatik menggunakan fungsi `localStorage`, memastikan data anda kekal walaupun pelayar ditutup.
* **Mod Luar Talian & PWA:** Boleh dipasang terus pada skrin utama peranti pintar atau desktop dan diakses walaupun tanpa sambungan internet.
* **Antara Muka Bersih:** Reka bentuk minimalis yang memberikan tumpuan penuh kepada kecekapan penggunaan.

## Struktur Fail
Projek ini dibina menggunakan fail web asas tanpa memerlukan kerumitan pembangunan yang tinggi:
- `index.html` - Fail utama aplikasi yang mengandungi struktur HTML, gaya CSS, dan logik JavaScript.
- `manifest.json` - Fail konfigurasi PWA untuk membolehkan aplikasi dipasang pada peranti.
- `sw.js` - Service Worker untuk sokongan operasi luar talian (*offline caching*).
- `icon.png` - Ikon aplikasi berukuran 192x192 piksel.

## Cara Pemasangan & Penggunaan
1. Muat turun atau simpan semua fail (`index.html`, `manifest.json`, `sw.js`, dan `icon.png`) dalam satu folder yang sama.
2. Buka fail `index.html` menggunakan mana-mana pelayar web moden (Chrome, Safari, Edge, dll.).
3. Untuk peranti mudah alih, gunakan pilihan **"Add to Home Screen"** pada pelayar anda untuk memasangnya sebagai aplikasi asli.

---
Dibina untuk memudahkan pengurusan kempen pelancaran produk anda dengan lebih efisien dan bersistematik.
