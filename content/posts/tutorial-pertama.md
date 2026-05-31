---
title: "Cara Membuat Formula Excel untuk Rekonsiliasi Data"
date: 2026-05-31
draft: false
summary: "Catatan pribadi cara cepat mencocokan data laporan keuangan menggunakan VLOOKUP dan XLOOKUP agar tidak lupa."
---

Halo! Ini adalah catatan tutorial pertama saya di blog ini. Saya membuat ini agar rumus yang sering saya gunakan di kantor tidak hilang.

## 1. Rumus Dasar XLOOKUP
Dibandingkan VLOOKUP lama, XLOOKUP jauh lebih aman digunakan untuk admin manajemen.

Contoh penggunaannya:
`=XLOOKUP(A2, 'Data Master'!A:A, 'Data Master'!B:B, "Data Tidak Ditemukan")`

### Kelebihan XLOOKUP:
* Tidak urung eror kalau ada sisipan kolom baru.
* Bisa mencari data dari kanan ke kiri.

Berikut adalah gambaran alur kerjanya:
![Contoh Gambar Tempel](https://images.unsplash.com/photo-1551288049-bebda4e38f71?w=500)