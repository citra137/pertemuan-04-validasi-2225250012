# Pertemuan 04 Seleksi Multi-Kondisi dan Validasi Input

Nama: Aulia Citra Aljazeera Jan's
NIM: 2225250012
Kelas: 3F


## Tujuan

Membangun program validasi dan klasifikasi menggunakan struktur seleksi multi-kondisi if-elif-else.


## Cara Menjalankan

Jalankan program menggunakan perintah:

py praktik/validasi_klasifikasi_nilai.py


## Tabel Keputusan

| Predikat | Syarat |
|---|---|
| A | Nilai akhir >= 85 |
| B | Nilai akhir >= 70 |
| C | Nilai akhir >= 60 |
| D | Nilai akhir >= 50 |
| E | Nilai akhir < 50 |


## Hasil Pengujian

| No | Input | Output | Status |
|---|---|---|---|
|1|90, 80, 90|Nilai akhir 86.00, Predikat A, Lulus|Sesuai|
|2|75, 70, 85|Nilai akhir 73.00, Predikat B, Lulus|Sesuai|
|3|90, 90, 70|Tidak memenuhi syarat kehadiran|Sesuai|
|4|a, b, c|Masukan ditolak: seluruh data harus berupa angka|Sesuai|


## Refleksi

Masukan tidak valid yang sebelumnya dapat menyebabkan error adalah input berupa teks.

Solusi yang digunakan adalah menggunakan try-except ValueError untuk menangani kesalahan konversi tipe data.
## Repository

Tugas pertemuan 04 selesai dibuat menggunakan Python dan GitHub.