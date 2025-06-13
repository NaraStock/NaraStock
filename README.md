# naraDev-React Web App
Naradev adalah Platform Analisis Pasar saham untuk investor pemula dengan design web modern yang dikembangkan menggunakan **React**, **Vite**, dan **Tailwind CSS**. Proyek ini menggunakan arsitektur **MVP (Model-View-Presenter)** dan memiliki berbagai fitur seperti artikel, prediksi, bookmark, autentikasi user & admin, dan lain-lain.

---

## Project Structure
```
├── public/ # File public
├── src/ # Kode sumber utama
│ ├── assets/ # seluruh asset image website
│ ├── components/ # Komponen aplikasi yang pada umumnya digunakan
│ │ ├── article/ # Daftar article
│ │ ├── auth/ # Login user & admin
│ │ ├── bookmark/ # Halaman bookmark
│ │ ├── common/ # Header & Footer
│ │ ├── contact/ # Halaman kontak
│ │ ├── fitur/ # Fitur aplikasi
│ │ ├── home/ # Beranda
│ │ ├── prediksi/ # Halaman prediksi
│ │ ├── showArticle/ # Tampilkan isi artikel
│ │ └── tentang/ # Halaman tentang kami
│ ├── services/ # Model atau koneksi API
│ ├── App.jsx # Komponen utama aplikasi
│ ├── main.jsx # Entry point aplikasi
│ └── index.css # Styling global
├── dist/ # Hasil build produksi
├── vite.config.js # Konfigurasi Vite
├── tailwind.config.js # Konfigurasi Tailwind
├── postcss.config.js # Konfigurasi PostCSS
├── eslint.config.js # Aturan ESLint
├── package.json # Dependency dan script npm
└── README.md # Dokumentasi proyek
```


## Fitur Utama
- Tampilan responsif dan modern
- Menggunakan arsitektur MVP (Model - View - Presenter)
- Autentikasi Admin & User
- Artikel dan fitur bookmark
- Fitur prediksi
- Halaman kontak & tentang kami
- Struktur folder modular & terorganisir
- Styling dengan Tailwind CSS
- Konfigurasi menggunakan Vite (build cepat)

---

## Cara Menjalankan Proyek
1. git clone https://github.com/NaraStock/NaraStock.git
   cd NaraStock

2. Install Dependency
   npm install

3. Jalankan Aplikasi Secara Lokal
   npm run dev
   Lalu buka http://localhost:5173 di browser.

Script NPM yang Tersedia
Perintah	Fungsi:
1. npm run dev	Menjalankan server pengembangan (development) menggunakan Vite
2. npm run build	Membuat versi produksi dari aplikasi
3. npm run preview	Menjalankan preview lokal dari hasil build produksi
4. npm run deploy Melakukan Deploy gh-pages


Teknologi yang Digunakan
```
React — Library UI modern
Vite — Build tool cepat untuk React
Tailwind CSS — Styling berbasis utility
ESLint — Alat untuk menjaga konsistensi kode
PostCSS — Alat transformasi CSS
MVP Architecture — Pola arsitektur terstruktur dan modular
```

Catatan Pengembangan
```
Setiap fitur dipisah ke dalam folder masing-masing.
Folder presenter menangani logika, sedangkan page menangani tampilan.
Anda bisa mengembangkan lebih jauh dengan menambahkan koneksi API melalui services/Model.js.
```

🙋‍♀Kontributor
Dibuat oleh: Priscilia Leza
GitHub: @AmandaPriscilia






