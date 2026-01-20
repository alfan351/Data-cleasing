🧹 Data Cleansing Project – Klinik & Sales Performance
📌 Deskripsi Proyek

Proyek ini bertujuan untuk melakukan data cleansing dan standarisasi pada data pelanggan klinik yang diperoleh dari sumber operasional (Google Sheets). Data awal memiliki berbagai isu kualitas seperti:

Inkonsistensi penulisan bulan (Indonesia & Inggris)

Typo pada nilai bulan

Perbedaan format huruf

Duplikasi data

Validasi tipe data numerik

Hasil akhir dari proyek ini adalah dataset yang bersih, konsisten, dan siap digunakan untuk analisis bisnis, dashboard, maupun pengembangan machine learning.

📂 Struktur Data Awal

Dataset terdiri dari kolom berikut:

Kolom	Deskripsi
ID Pelanggan	Kode unik pelanggan
Nama Klinik	Nama klinik dan/atau cabang
Nama Sales	Sales yang menangani
Bulan Join	Bulan pertama bergabung
Jumlah Klinik	Jumlah unit/cabang klinik
🎯 Tujuan Data Cleansing

Menyeragamkan format nama kolom

Membersihkan teks (spasi & kapitalisasi)

Menormalisasi bulan join menjadi format numerik (1–12)

Memperbaiki typo bulan

Mendeteksi dan menangani duplikasi

Memastikan tipe data numerik valid

Menyiapkan dataset final untuk analisis lanjutan

🛠️ Tools & Teknologi

Python 3

Google Colab

Pandas

NumPy

Google Sheets (CSV source)
