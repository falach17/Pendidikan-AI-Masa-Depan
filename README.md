# Pendidikan AI dimasa Depan 
Penjelajah Sekolah Berbasis AI: Eropa & Asia Tenggara

Aplikasi web satu halaman ini dirancang untuk menyediakan eksplorasi interaktif mengenai lanskap sekolah swasta berbasis Kecerdasan Buatan (AI) yang inovatif di Eropa dan Asia Tenggara. Terinspirasi oleh model disruptif Alpha School, aplikasi ini memungkinkan pengguna untuk memahami bagaimana AI membentuk kembali pendidikan, peran guru, dan kurikulum di berbagai wilayah.

---

## Deskripsi

Aplikasi ini berfungsi sebagai alat visual dan interaktif untuk menganalisis dan membandingkan model pendidikan berbasis AI. Aplikasi ini menyajikan data dan wawasan kualitatif dari laporan sumber dalam format yang mudah dicerna, dengan fokus pada pengalaman pengguna dan navigasi yang intuitif.

---

## Fitur Utama

* **Pengenalan Komprehensif:** Memberikan gambaran umum tentang tren pendidikan AI global.
* **Analisis Model Alpha School:** Menyoroti struktur unik Alpha School, termasuk "inti akademik 2 jam" dan peran "pemandu" guru.
* **Perbandingan Interaktif:** Memungkinkan pengguna untuk memfilter dan membandingkan sekolah-sekolah di Eropa dan Asia Tenggara berdasarkan wilayah, model pembelajaran, peran pendidik, dan kurikulum.
* **Visualisasi Tren Global:** Menyajikan bagan dinamis yang menggambarkan tren pasar pendidikan AI (misalnya, di Jerman) dan daftar inisiatif pemerintah di Asia Tenggara.
* **Desain Responsif:** Tata letak yang dioptimalkan untuk berbagai perangkat (desktop, tablet, seluler) menggunakan Tailwind CSS.
* **Visualisasi Data Jelas:** Menggunakan Chart.js untuk bagan yang mudah dipahami dengan label dan tooltip yang relevan.

---

## Struktur Aplikasi

Aplikasi ini diatur dalam beberapa bagian tematis untuk memfasilitasi eksplorasi:

* **Beranda:** Pengantar aplikasi dan topiknya.
* **Model Alpha:** Detail tentang model pendidikan Alpha School sebagai tolok ukur.
* **Perbandingan:** Bagian interaktif di mana pengguna dapat memfilter dan melihat studi kasus sekolah dari Eropa dan Asia Tenggara.
* **Tren Global:** Menyajikan data dan inisiatif tingkat makro terkait adopsi AI dalam pendidikan.

---

## Data yang Digunakan

Data mengenai sekolah, model pendidikan, dan inisiatif pemerintah disimulasikan dan disimpan dalam objek JavaScript internal aplikasi (`schoolData` dan `seaInitiativesData`) untuk tujuan demonstrasi dan interaktivitas.

---

## Teknologi yang Digunakan

* **HTML5:** Struktur dasar halaman web.
* **Tailwind CSS:** Kerangka kerja CSS untuk styling dan tata letak responsif.
* **Chart.js:** Pustaka JavaScript untuk membuat bagan interaktif (Doughnut Chart, Bar Chart).
* **Vanilla JavaScript:** Untuk semua logika interaktif, manipulasi DOM, pemfilteran data, dan inisialisasi bagan.

---

## Cara Menggunakan

1.  **Buka File:** Buka file `index.html` di peramban web Anda.
2.  **Navigasi:** Gunakan bilah navigasi di bagian atas untuk melompat ke bagian yang berbeda dari aplikasi.
3.  **Filter Sekolah:** Di bagian "Perbandingan Interaktif Model Sekolah AI", gunakan tombol filter ("Semua", "Eropa", "Asia Tenggara") untuk menampilkan studi kasus sekolah berdasarkan wilayah.
4.  **Jelajahi Bagan:** Arahkan kursor ke elemen bagan di bagian "Model Alpha School" dan "Tren dan Kebijakan Global" untuk melihat detail data.
5.  **Lihat Inisiatif:** Di bagian "Inisiatif Pemerintah di Asia Tenggara", arahkan kursor ke setiap item daftar untuk melihat detail inisiatif negara.
