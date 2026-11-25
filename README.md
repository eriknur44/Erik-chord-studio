# Erik LyricChord Studio

Aplikasi web sederhana untuk menulis lirik dan chord, menampilkan chord tepat di atas lirik, transpose, dan auto-scroll.

## Isi folder
- `index.html` — struktur halaman aplikasi.
- `style.css` — desain responsif.
- `app.js` — editor, chord, transpose, auto-scroll, impor/ekspor, dan penyimpanan browser.

## Cara menjalankan di komputer
1. Ekstrak ZIP.
2. Buka `index.html` dengan Google Chrome.
3. Tidak membutuhkan instalasi atau server untuk penggunaan lokal.

## Publikasi gratis menggunakan GitHub Pages
1. Masuk atau buat akun di https://github.com
2. Klik **New repository**.
3. Beri nama repository: `erik-lyricchord-studio`.
4. Pilih **Public**, lalu klik **Create repository**.
5. Klik **Add file → Upload files**.
6. Unggah tiga file aplikasi: `index.html`, `style.css`, dan `app.js` (README boleh ikut diunggah).
   - Pastikan `index.html` berada di root repository, bukan di dalam subfolder.
7. Klik **Commit changes**.
8. Buka **Settings → Pages**.
9. Pada **Build and deployment**, pilih **Deploy from a branch**.
10. Pilih branch **main** dan folder **/(root)**, lalu klik **Save**.
11. Tunggu beberapa menit. GitHub akan menampilkan alamat website, biasanya:
   `https://NAMA-USERNAME.github.io/erik-lyricchord-studio/`
12. Buka alamat tersebut di Google Chrome Android atau komputer.

## Cara menggunakan
- Masukkan judul dan artis.
- Tulis chord dalam tanda kurung siku sebelum kata yang dimainkan, contoh:
  `[G]Aku [D]hadir dalam hidupmu`
- Baris bagian lagu dapat ditulis `[VERSE]`, `[CHORUS]`, atau `[BRIDGE]`.
- Klik **Terapkan** untuk memperbarui tampilan.
- Klik **Mulai scroll** untuk auto-scroll. Atur kecepatannya dengan slider.
- Gunakan tombol transpose untuk menaikkan/menurunkan chord per semitone.
- Klik **Simpan lagu** untuk menyimpan di browser perangkat yang sedang digunakan.
- Gunakan **Ekspor TXT** sebagai cadangan dan **Impor TXT** untuk membuka teks lagu.

## Catatan
- Penyimpanan lagu menggunakan `localStorage` browser. Data tidak otomatis tersinkron antarperangkat atau antarbrowser.
- Untuk mengedit aplikasi setelah dipublikasikan, unggah ulang file yang diubah ke repository GitHub.
- GitHub Pages menyediakan hosting statis gratis untuk repository publik.
