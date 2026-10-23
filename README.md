# SiantarKerja — Desain Aplikasi Android

Aplikasi lowongan kerja untuk **Pematangsiantar**, dengan desain biru gelap dan mint. Dokumen ini memperlihatkan rancangan tampilan untuk peninjauan tugas.

> Gambar berikut adalah mockup desain, bukan tangkapan layar aplikasi yang sudah diuji. Semua perusahaan, lowongan, dan gaji adalah contoh fiktif. Login menggunakan akun demo lokal; tidak ada lamaran yang dikirim.

## 1. Halaman Login

Form email, kata sandi, pilihan tampilkan kata sandi, dan tombol masuk. Pada prototipe, pengguna masuk menggunakan akun demo.

![Desain halaman login](desain/01-login.svg)

## 2. Dashboard

Menampilkan lokasi Pematangsiantar, pengantar pencarian kerja, jumlah lowongan contoh dan simpanan, rekomendasi lowongan, serta navigasi bawah.

![Desain dashboard](desain/02-dashboard.svg)

## 3. Detail Lowongan dan Gaji

Menampilkan posisi, perusahaan, lokasi, jenis pekerjaan, kisaran penghasilan, deskripsi, kualifikasi, tombol simpan, dan simulasi lamaran.

![Desain detail lowongan](desain/03-detail-lowongan.svg)

## Alur penggunaan

Login → Dashboard → Daftar lowongan → Detail lowongan → Simpan atau coba simulasi lamaran.

Dari navigasi bawah, pengguna juga dapat membuka lowongan tersimpan dan halaman akun untuk mengedit profil. Gambar khusus halaman daftar, simpanan, dan akun belum disertakan dalam paket desain ini.

## Warna utama

| Penggunaan | Warna |
| --- | --- |
| Judul dan kartu utama | `#122B40` |
| Aksen mint | `#A8EBCB` |
| Tombol utama dan nominal gaji | `#087F70` |
| Latar belakang | `#F5F7FA` |

## Status aplikasi

Prototipe Android native dengan Java dan Android Views. Data contoh dapat digunakan offline tanpa hosting. Pemeriksaan kompilasi Java pernah berhasil, tetapi build APK dan pengujian login pada perangkat belum terverifikasi.

## Pratinjau HTML

Unduh lalu buka `Pratinjau-SiantarKerja.html` di browser untuk melihat desain gabungan. GitHub menampilkan gambar SVG pada README ini; file HTML tidak memerlukan GitHub Pages atau hosting untuk dibuka secara lokal.

## Cara unggah ke GitHub

1. Ekstrak paket ZIP ini.
2. Unggah `README.md`, folder `desain`, dan file HTML ke repositori dengan susunan folder yang sama.
3. Buka halaman utama repositori. Gambar desain tampil pada README.

Jika repositori sudah memiliki README, gabungkan bagian desain ke README tersebut atau letakkan paket ini dalam folder `docs/desain` agar README lama tetap tersimpan.
