# My Movie App

## Deskripsi
Aplikasi ini adalah platform untuk menampilkan film menggunakan API dari The Movie Database (TMDb). Pengguna dapat login untuk menyimpan film favorit mereka.

## Struktur Proyek
- **index.html/**: file statis.
- **src/**: Berisi semua kode sumber aplikasi.
  - **assets/**: Berisi file gambar, ikon, dan aset lainnya yang digunakan dalam aplikasi.
  - **components/**: Berisi komponen React untuk login user/guest, halaman utama, dan profil.
  - **api.ts**: Mengelola panggilan API untuk mendapatkan data film.
  - **app.tsx**: Komponen utama aplikasi yang mengatur rute dan logika.
  - **index.tsx**: Titik masuk aplikasi yang merender komponen utama ke DOM.
  
## Cara Menjalankan Proyek
1. Clone repository ini.
2. Ganti `YOUR_API_KEY` di `src/api.ts` dengan API Key Anda dari TMDb.
3. Jalankan `npm install` untuk menginstal dependensi.
4. Jalankan `npm start` untuk menjalankan aplikasi.

## Catatan
Pastikan Anda sudah mendaftar di [TMDb](https://developer.themoviedb.org/reference/intro/getting-started) untuk mendapatkan API Key.

## Kredensial Login
- **Username**: user  
- **Password**: 123
