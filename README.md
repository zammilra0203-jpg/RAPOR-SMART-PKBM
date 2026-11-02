# RAPOR SMART PKBM

Aplikasi administrasi dan pengolahan rapor PKBM untuk Program Kesetaraan Paket A, Paket B, dan Paket C.

## Isi paket

- `index.html` — aplikasi utama. Seluruh HTML, CSS, JavaScript, Garuda, dan logo bawaan sudah berada dalam satu file.
- `.nojekyll` — membantu GitHub Pages menyajikan file statis tanpa pemrosesan Jekyll.

## Cara mengunggah ke GitHub

1. Buka repository GitHub yang akan digunakan.
2. Pilih **Add file → Upload files**.
3. Unggah `index.html` dan `.nojekyll` dari folder ini (atau unggah semua isi ZIP setelah diekstrak).
4. Klik **Commit changes**.
5. Buka **Settings → Pages**.
6. Pada **Build and deployment**, pilih **Deploy from a branch**.
7. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
8. Tunggu proses publikasi selesai. Alamat aplikasi biasanya berbentuk:
   `https://NAMA-USERNAME.github.io/NAMA-REPOSITORY/`

## Catatan penting

- Aplikasi ini merupakan situs statis; tidak memerlukan server, database, API key, atau proses build.
- Data aplikasi disimpan di `localStorage` pada browser/perangkat yang digunakan. Data tidak otomatis tersinkron ke perangkat lain atau ke GitHub.
- Gunakan menu **Backup & Pemulihan** secara berkala untuk mengunduh cadangan JSON.
- Untuk memindahkan data ke perangkat/browser lain, gunakan file backup JSON melalui menu pemulihan.
- Saat mencetak, pilih ukuran kertas A4 dan periksa pratinjau cetak browser. Menu dan petunjuk aplikasi disembunyikan dari hasil cetak.
- Jangan mengunggah file backup yang berisi data pribadi peserta didik ke repository publik.

## Pembaruan aplikasi

Untuk memperbarui aplikasi, unggah file `index.html` versi terbaru ke root repository dan pilih **Commit changes**. Jika halaman masih menampilkan versi lama, lakukan hard refresh browser (`Ctrl + F5`) atau bersihkan cache situs.
