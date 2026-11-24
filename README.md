# Simulator Roket Air

Simulator roket air dua botol Coca-Cola (1,5 L atau 1 L): botol tekan berisi air dan nosecone dari ujung atas botol kedua dengan plastisin, sirip yang bisa diatur, mode auto target jarak, dan perbandingan dua ukuran botol.

Isi repo:

- `index.html`: aplikasi lengkap (satu file, tanpa build, tanpa server, tanpa database online). Tab Desain punya ekspor gambar PNG: ukuran sirip (dengan template cetak 1:1) dan desain roket lengkap.

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub, lalu upload `index.html` dan `.nojekyll` di root repo (bukan di dalam subfolder).
2. Settings, Pages, Source: Deploy from a branch, Branch: `main`, folder `/ (root)`, Save.
3. Tunggu satu menit. Alamatnya `https://<username>.github.io/<nama-repo>/`.

## Menyimpan desain (tab Simpan)

- **Save in device:** menyimpan desain ke file di komputer/HP Anda. Di Chrome/Edge desktop muncul jendela simpan file; di browser lain file diunduh.
- **Buka file:** membuka file .json hasil Save in device. Satu desain langsung dimuat, beberapa desain tampil sebagai daftar.
- **Save:** menyimpan di browser itu sendiri. Hanya pemilik browser yang bisa melihat dan menghapusnya.

Tidak ada data yang dikirim ke server mana pun.

## Catatan

- Hasil simulasi adalah perkiraan. Sesuaikan "Kalibrasi drag" (tab Lanjutan) dengan data uji lapangan.
- Tekanan 100 psi atau lebih berisiko memecahkan botol PET. Uji hidrostatik, pakai pelindung mata, dan luncurkan dari jauh.
