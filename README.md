# Implementasi K-Means Clustering

## Informasi Mahasiswa
- **Nama:** Chornelius Delon
- **NIM:** 2343087

## Deskripsi Proyek
Proyek ini merupakan implementasi algoritma K-Means Clustering untuk mengelompokkan data mahasiswa berdasarkan nilai mata kuliah Logika Komputasi. Implementasi dilakukan menggunakan HTML, CSS, dan JavaScript.

## Fitur
- Visualisasi data awal dan data dengan koordinat
- Penjelasan rumus dan tahapan K-Means Clustering
- Perhitungan jarak Euclidean untuk setiap iterasi
- Visualisasi hasil akhir clustering
- Interpretasi dan rekomendasi berdasarkan hasil clustering
- Fitur download hasil dalam format Excel
- Fitur print laporan

## Cara Menjalankan
1. Buka file `index.html` di browser
2. Lihat visualisasi dan hasil clustering
3. Gunakan tombol "Download File Excel" untuk mengunduh data dalam format Excel
4. Gunakan tombol "Print Laporan" untuk mencetak laporan

## Algoritma K-Means Clustering
Algoritma K-Means Clustering yang diimplementasikan mengikuti tahapan berikut:
1. Menentukan k (nilainya bebas) sebagai jumlah cluster yang ingin dibentuk
2. Membangkitkan nilai random untuk pusat cluster awal (centroid) sebanyak k
3. Menghitung jarak setiap data input terhadap masing-masing centroid menggunakan rumus jarak Euclidean
4. Mengklasifikasikan setiap data berdasarkan kedekatannya dengan centroid (jarak terkecil)
5. Memperbaharui nilai centroid baru yang diperoleh dari rata-rata cluster yang bersangkutan
6. Mengulangi langkah 3-5 hingga konvergen

## Hasil
Hasil clustering menunjukkan pembagian mahasiswa menjadi 3 kelompok:
- **Cluster 1 (Tinggi):** Mahasiswa dengan nilai tinggi (3.5-4.0)
- **Cluster 2 (Sedang):** Mahasiswa dengan nilai sedang (2.5-3.25)
- **Cluster 3 (Rendah):** Mahasiswa dengan nilai rendah (0-2.25)