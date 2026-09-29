ROMANTIC WEB - QUICK EDIT GUIDE
===============================

1. Buka index.html untuk mencoba web.

2. Masukkan aset ke folder assets/:
   - assets/cute.gif  -> GIF/foto di halaman terakhir
   - assets/music.mp3 -> musik background

3. Kalau ingin pakai JPG/PNG, edit di index.html:
   src="assets/cute.gif"
   menjadi misalnya:
   src="assets/photo.jpg"

4. Edit isi surat langsung di index.html pada bagian:
   <div class="letter-body"> ... </div>

5. Edit pertanyaan di bagian:
   Will you be my girlfriend?

6. Web dibuat mobile-first dan responsive untuk desktop/tablet.

7. Untuk publish gratis bisa pakai GitHub Pages, Netlify, atau Vercel.
   Pastikan seluruh isi folder ini ikut di-upload.

CATATAN:
- Jika cute.gif belum ada, otomatis tampil placeholder.
- Jika music.mp3 belum ada, web tetap bisa digunakan.
- Browser biasanya baru mengizinkan musik setelah user berinteraksi; web mencoba memutarnya setelah amplop diklik.
