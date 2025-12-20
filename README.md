📡 Arduino Serial Monitor Web

Created by Al Zakaria

Aplikasi web ini memungkinkan Anda membaca data dari Arduino secara langsung melalui browser menggunakan Web Serial API, menampilkannya dalam bentuk log teks dan grafik real-time menggunakan Chart.js. File dapat disimpan sebagai .txt secara otomatis.

Telah terkalibrasi untuk konduktivitas tanah dengan satuan (μS/cm) menggunakan persamaan kalibrator
Formula Konduktivitas dari lab menggunakan sampel tanah
---
\[
y = 0.3186x + 332.49
\]
\[
σ =3,1387𝐴𝐷𝐶 −1043
\]
---
<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/4d5aff5d-0b8b-4ba6-b536-493f13645598" />


🚀 Fitur Utama

Koneksi langsung ke Arduino melalui Web Serial API

Menampilkan log data serial secara real-time

Grafik data dinamis menggunakan Chart.js (update setiap ±2 detik)

Simpan data ke file .txt

Hapus log dan grafik

🛠️ Teknologi yang Digunakan

HTML5, CSS3, JavaScript

Web Serial API

Chart.js (CDN)

📋 Cara Menggunakan

Buka file HTML melalui:

HTTPS, atau

localhost (disarankan)

Klik “Connect Arduino”

Pilih port Arduino Anda (COM/USB)

Data akan tampil otomatis pada:

Panel Log Data

Grafik Chart.js (update setiap 2 detik)

Klik Save Data untuk mengunduh data ke .txt

Klik Clear Data untuk reset tampilan

⚠️ Catatan Penting

Web Serial API hanya bekerja pada Chrome, Edge, atau Opera versi terbaru.

Tidak berfungsi di Firefox atau Safari.

Pastikan Arduino mengirim data dalam format angka jika ingin muncul di grafik.

📄 Lisensi

Proyek ini dibuat untuk penggunaan pribadi dan edukasi.
Silakan dimodifikasi sesuai kebutuhan Anda.
