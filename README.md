# STOP SLOT Website

Versi website mobile-first untuk dibuka di browser Android.

## Fitur
- Penghitung durasi berhenti dalam tahun, bulan, dan hari.
- Estimasi uang yang dijaga berdasarkan nominal pengeluaran harian.
- Target tabungan dan target durasi.
- Check-in harian dan milestone sampai 5 tahun.
- Jurnal pemicu dan dorongan.
- Timer jeda 10 menit.
- Kontak pendukung tersimpan lokal.
- Ekspor/impor cadangan JSON.
- Mode PWA dasar (dapat dipasang dari browser setelah di-host HTTPS).

## Cara membuka
Ekstrak ZIP, lalu buka `index.html` di browser/file manager. Beberapa fitur PWA/offline hanya aktif saat website di-host melalui HTTPS. Untuk hasil terbaik, host sebagai static website.

## Cara online gratis lewat GitHub Pages
1. Buat repository GitHub baru.
2. Unggah `index.html`, `manifest.webmanifest`, dan `sw.js` ke root repository.
3. Buka Settings > Pages.
4. Pada Build and deployment, pilih Deploy from a branch.
5. Pilih branch `main` dan folder `/ (root)`, lalu Save.
6. Tunggu publikasi, kemudian buka URL Pages yang disediakan GitHub.
7. Di Chrome Android, buka menu ⋮ dan pilih “Tambahkan ke layar utama” atau “Install app” jika muncul.

GitHub Pages menghosting file statis dari repository. Website publik dapat diakses orang lain, tetapi catatan aplikasi ini disimpan pada browser perangkat masing-masing. Jangan masukkan informasi rahasia. Dokumentasi: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Catatan
- Data disimpan di localStorage browser, bukan server. Hapus data browser dapat menghapus data STOP SLOT; gunakan ekspor cadangan.
- Uang yang ditampilkan adalah estimasi, bukan saldo rekening atau bukti tabungan aktual.
- Timer berjalan saat halaman terbuka. Ini bukan notifikasi sistem.
- Website bukan layanan medis atau keuangan.
