# Customer Segmentation dengan RFM dan K-Means Clustering (2021–2024)
### 📄 Ringkasan Proyek

Proyek ini melakukan segmentasi pelanggan pada data transaksi koperasi menggunakan pendekatan RFM (Recency, Frequency, Monetary) dan algoritma K-Means Clustering.

Dataset mencakup:

48.538 baris data transaksi detail
11.679 transaksi unik
247 pelanggan
Periode transaksi: 2021 – 2024

Tujuan utama segmentasi ini adalah untuk memahami perilaku pelanggan dan membantu bisnis dalam menyusun strategi seperti loyalty program, retensi pelanggan, hingga rekomendasi promosi berbasis data.

### 📄 Persiapan Data
Langkah-langkah yang dilakukan:
1. Menghapus data duplikat.
2. Menangani missing values.
3. Mengubah tipe data tanggal ke datetime.
4. Menyesuaikan data agar hanya memuat transaksi pelanggan.

### 📄 Feature Engineering
Variabel RFM dan tambahan dihitung sebagai berikut:

1. Recency: Jumlah hari sejak transaksi terakhir.
2. Frequency: Total jumlah transaksi dalam periode data.
3. Monetary: Total nilai belanja pelanggan.
4. Jumlah_Barang: Total kuantitas barang dibeli.
5. Total_Profit: Total profit yang dihasilkan pelanggan.

### Pengolahan Data
1. Dilakukan pengecekan dan penanganan skewness untuk mengatasi outlier
Berikut grafik hasil

2. Data yang sudah ditransformasi log dinormalisasi dengan min-max
3. pada fitur recency data di balik dengan mengurangi nilai dengan 1

### Pemodelan K-Means
Menentukan Jumlah Cluster
Hasil Elbow dan Silhoutte

K terbaik = 4

Hasil Clustering 



### Ringkasan karakteristik tiap cluster:


### Visualisasi 









