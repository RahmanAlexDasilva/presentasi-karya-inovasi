# Panduan Menambahkan Foto Dokumentasi

Foto ditampilkan pada **slide "Penerapan Modul 4 & Dokumentasi" → tab "Dokumentasi"**.
Tersedia 4 judul, masing-masing 3 slot foto.

## 1. Letak folder

Buat/simpan foto pada folder berikut (sudah dibuatkan, satu folder per judul):

| No | Judul di website | Folder penyimpanan | Nama file |
|----|------------------|--------------------|-----------|
| 1 | Pengenalan | `dokumentasi/1-pengenalan/` | `foto-1.jpg`, `foto-2.jpg`, `foto-3.jpg` |
| 2 | Penggunaan Modul | `dokumentasi/2-penggunaan-modul/` | `foto-1.jpg`, `foto-2.jpg`, `foto-3.jpg` |
| 3 | Siswa Antusias Menggunakan Website Python Step-Up Berbasis Gamifikasi | `dokumentasi/3-gamifikasi-python-step-up/` | `foto-1.jpg`, `foto-2.jpg`, `foto-3.jpg` |
| 4 | Siswa Mengisi Form Refleksi | `dokumentasi/4-form-refleksi/` | `foto-1.jpg`, `foto-2.jpg`, `foto-3.jpg` |

Struktur akhirnya:

```
Python Step-Up_ Seminar Karya Inovasi PPG.html
PANDUAN-FOTO.md
dokumentasi/
├── 1-pengenalan/            foto-1.jpg  foto-2.jpg  foto-3.jpg
├── 2-penggunaan-modul/      foto-1.jpg  foto-2.jpg  foto-3.jpg
├── 3-gamifikasi-python-step-up/  foto-1.jpg  foto-2.jpg  foto-3.jpg
└── 4-form-refleksi/         foto-1.jpg  foto-2.jpg  foto-3.jpg
```

## 2. Aturan penamaan file (penting)

- Nama **harus** `foto-1`, `foto-2`, `foto-3` (huruf kecil, tanda hubung, tanpa spasi).
- Ekstensi yang didukung: `.jpg`, `.jpeg`, `.png` (huruf besar/kecil sama-sama terbaca).
- Jangan menambahkan spasi, kurung, atau akhiran seperti `foto-1 (1).jpg` — file tidak akan terdeteksi.
- Cukup timpa/ganti file, tidak perlu mengubah kode HTML sama sekali.

## 3. Tips agar hasil rapi

- Gunakan orientasi **landscape** dan ukuran sekitar **1200–1600 px** sisi terpanjang (ukuran file ±150–400 KB) supaya ringan saat dibuka.
- Foto otomatis dipotong **4:3** dari tengah (objek utama sebaiknya di tengah frame).
- Nama judul, jumlah foto, dan urutan grup diatur di dalam file HTML pada bagian `var DOCS=[ ... ]` di dekat akhir file (bagian `<script>`). Ubah teks `t:` bila perlu mengubah judul.

## 4. Cara mengecek berhasil atau belum

1. Buka file `Python Step-Up_ Seminar Karya Inovasi PPG.html` di browser.
2. Masuk ke **Bagian 03 · Karya Inovasi → slide "Penerapan Modul 4 & Dokumentasi"**.
3. Klik tab **Dokumentasi**.
4. Foto yang belum ada akan tampil sebagai kotak abu-abu berisi ikon kamera dan **path file** yang dicari — itu penanda nama/letak file belum sesuai. Cocokkan path tersebut dengan file Anda.
5. Jika foto sudah muncul: selesai. Tidak ada langkah build atau upload.
