# Rujukan Tatatertib Siswa

Aplikasi carian untuk tiga dokumen BPT MARA (2023):

- Buku Peraturan Tatatertib Siswa KPM & KM
- Garis Panduan Pengendalian Kes Tatatertib Siswa KPM & KM
- Garis Panduan Pengurusan Asrama KM & KPM

Kandungan: carian teks penuh, Jadual Denda, Hukuman & Tempoh, Borang PTS, dan Istilah. Selepas dibuka sekali, aplikasi boleh digunakan tanpa internet.

## Fail dalam folder ini

| Fail | Kegunaan |
|---|---|
| `index.html` | Aplikasi (semua teks dokumen ada di dalam fail ini) |
| `apple-touch-icon.png` | Ikon skrin utama iPhone / iPad |
| `icon-192.png`, `icon-512.png` | Ikon Android dan pelayar |
| `favicon.svg` | Ikon tab pelayar |
| `manifest.webmanifest` | Maklumat aplikasi (nama, warna, ikon) |
| `sw.js` | Simpan salinan untuk kegunaan tanpa internet |

## Cara terbitkan di GitHub Pages

1. Log masuk ke github.com. Tekan **+** di penjuru kanan atas, pilih **New repository**.
2. Namakan repositori, contohnya `rujukan-tatatertib`. Pilih **Public**, kemudian tekan **Create repository**.
3. Tekan pautan **uploading an existing file**. Seret SEMUA fail dari folder ini (bukan folder itu sendiri) ke ruang muat naik. Tekan **Commit changes**.
4. Pergi ke **Settings**, kemudian **Pages** di menu kiri.
5. Di bawah **Build and deployment**, pilih Source: **Deploy from a branch**, Branch: **main**, folder: **/ (root)**. Tekan **Save**.
6. Tunggu 1 hingga 2 minit. Muat semula halaman Pages; alamat laman akan muncul, contohnya:
   `https://NAMA-ANDA.github.io/rujukan-tatatertib/`

## Pasang di skrin utama iPhone

1. Buka alamat tadi dalam **Safari**.
2. Tekan butang **Share**, kemudian **Add to Home Screen**.
3. Tekan **Add**. Ikon logo buku dan kanta emas akan muncul, dan aplikasi terbuka dalam skrin penuh tanpa bar Safari.

Pada Android (Chrome): buka alamat, tekan menu ⋮, pilih **Add to Home screen** atau **Install app**.

## Kemas kini kandungan

Gantikan `index.html` dengan versi baharu (Add file > Upload files di repositori). Jika ikon atau fail lain diubah, tukar `rujukan-tatatertib-v1` dalam `sw.js` kepada `v2` supaya telefon mengambil versi baharu.

## Perhatian

- Laman GitHub Pages boleh dibuka oleh **sesiapa sahaja** yang tahu alamatnya, walaupun repositori ditetapkan Private.
- Kedua-dua Garis Panduan menyatakan penggunaannya terhad kepada Unit HEP KPM, KM dan BPT, dan edaran di luar unit tersebut memerlukan kebenaran bertulis Pengarah BPT. Dapatkan kebenaran itu sebelum menerbitkan, atau terbitkan versi yang mengandungi Buku Peraturan sahaja.
- Fungsi **Tanya AI** hanya tersedia dalam versi claude.ai dan tidak dimasukkan dalam versi ini.

Hak cipta kandungan dokumen: Bahagian Pendidikan Tinggi MARA.
