# Simulator Roket Air

Simulator roket air botol Coca-Cola 1,5 L (tabung tekan + nosecone berplastisin + sirip), dengan mode auto target jarak dan library desain.

Isi repo:

- `index.html`: aplikasi lengkap (satu file, tanpa build, tanpa server).
- `library/designs.js`: file library yang menjadi database desain bersama.

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub, lalu upload semua isi folder ini (di root repo).
2. Settings, Pages, Source: Deploy from a branch, Branch: `main`, folder `/ (root)`, Save.
3. Tunggu satu menit. Alamatnya `https://<username>.github.io/<nama-repo>/`.

Tidak ada layanan lain yang perlu disiapkan.

## Cara kerja database

- **Library (file):** `library/designs.js` berisi array `window.RA_LIBRARY`. Semua pengunjung membaca file ini di tab Library. Pengunjung tidak bisa mengubahnya.
- **Desain saya:** desain yang disimpan pengunjung ada di browser mereka sendiri, sehingga hanya bisa dilihat, dimuat, dan dihapus oleh pemiliknya. Bisa dipindah antar perangkat lewat Ekspor/Impor `.json`.

## Menambah desain ke library

1. Di tab Library, simpan desain, lalu klik **Ekspor sebagai library (designs.js)**.
2. Ganti `library/designs.js` di repo dengan file hasil ekspor, lalu commit.
3. Setelah Pages memperbarui halaman, desain muncul untuk semua pengunjung.

Atau sunting `library/designs.js` langsung: tiap desain adalah satu objek di dalam array.

## Catatan

- Karena GitHub Pages hanya hosting statis, penambahan ke library bersama dilakukan lewat commit oleh pemilik repo, bukan langsung dari halaman.
- Hasil simulasi adalah perkiraan. Sesuaikan "Kalibrasi drag" (tab Lanjutan) dengan data uji lapangan.
- Tekanan 100 psi atau lebih berisiko memecahkan botol PET. Uji hidrostatik, pakai pelindung mata, dan luncurkan dari jauh.
