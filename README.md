# RAPOR SMART PKBM — GitHub Pages & PWA

Paket ini sudah disiapkan agar logo tampil pada tab browser dan saat aplikasi dipasang di HP/laptop sebagai PWA.

## File yang harus diunggah

Unggah **semua file** di folder ini ke root repository GitHub (bukan ke dalam subfolder):

- `index.html` — aplikasi utama
- `manifest.webmanifest` — nama, warna, dan ikon aplikasi terpasang
- `sw.js` — service worker untuk instalasi dan cache/offline
- `logo.png` — logo master
- `icon-192.png` dan `icon-512.png` — ikon instalasi
- `favicon-64.png` — ikon tab browser

## Aktifkan GitHub Pages

1. Buka repository GitHub.
2. Pilih **Add file → Upload files**.
3. Unggah seluruh isi folder ini ke root repository dan pilih **Commit changes**.
4. Buka **Settings → Pages**.
5. Pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
6. Buka alamat GitHub Pages setelah publikasi selesai. Harus menggunakan HTTPS.

## Instal di HP atau laptop

- **Android (Chrome/Edge):** buka alamat GitHub Pages, pilih menu browser lalu **Install app** atau **Tambahkan ke layar utama**.
- **Windows/Linux (Chrome/Edge):** buka alamat aplikasi; pilih ikon instalasi di bilah alamat atau menu browser → **Install RAPOR SMART PKBM**.
- **iPhone/iPad:** buka melalui Safari → tombol Share → **Add to Home Screen**.

Ikon yang digunakan berasal dari `icon-192.png` dan `icon-512.png`. Favicon tab menggunakan `favicon-64.png`.

## Catatan pembaruan

Jika logo lama masih terlihat setelah update, tutup aplikasi, buka ulang alamat GitHub Pages, lalu lakukan hard refresh (`Ctrl + F5`) di laptop. Pada HP, hapus shortcut/aplikasi lama lalu pasang kembali jika ikon belum diperbarui. Service worker menggunakan cache versi `v1.3.0`.

Data rapor tetap disimpan lokal di browser/perangkat. PWA tidak otomatis menyinkronkan data ant perangkat. Lakukan backup berkala dari menu aplikasi. Jangan unggah backup berisi data pribadi peserta didik ke repository publik.
