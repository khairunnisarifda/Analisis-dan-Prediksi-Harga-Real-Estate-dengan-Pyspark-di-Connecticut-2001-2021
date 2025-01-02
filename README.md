# Analisis-dan-Prediksi-Harga-Real-Estate-dengan-Pyspark-di-Connecticut (2001-2021)
Proyek ini memprediksi nilai penjualan properti menggunakan PySpark dan Python. Data diolah, diproses dengan pipeline, dan dievaluasi menggunakan RMSE dan R². Visualisasi hasil mencakup perbandingan nilai aktual vs prediksi serta residual plot.

## Deskripsi Proyek
Proyek ini bertujuan untuk memprediksi nilai penjualan properti menggunakan PySpark dan Python. Data melalui proses pembersihan, penghapusan outlier, dan pra-pemrosesan dengan pipeline sebelum dilatih menggunakan model regresi linear. Evaluasi dilakukan menggunakan metrik RMSE dan koefisien determinasi (R²). Visualisasi hasil mencakup perbandingan nilai aktual vs prediksi serta residual plot.

## Langkah-Langkah
1. **Persiapan Data:** 
   - Membersihkan data dan menghapus kolom yang tidak relevan.
   - Menangani nilai NULL dan outlier.

2. **Pra-pemrosesan:**
   - Menggunakan StringIndexer, OneHotEncoder, dan VectorAssembler untuk transformasi fitur.
   - Menambahkan fitur interaksi untuk meningkatkan akurasi model.

3. **Modeling:**
   - Melatih model regresi linear menggunakan PySpark MLlib.
   - Membagi data menjadi set pelatihan dan pengujian.

4. **Evaluasi dan Visualisasi:**
   - Mengevaluasi performa model menggunakan RMSE dan R².
   - Membuat visualisasi nilai aktual vs prediksi dan residual plot.

## Teknologi yang Digunakan
- **PySpark:** Pemrosesan data skala besar.
- **Matplotlib & Scipy:** Analisis statistik dan visualisasi hasil.
- **Google Colab:** Kolaborasi dan pengelolaan lingkungan kerja.

## Cara Menjalankan
1. Install dependensi:
   ```bash
   pip install pyspark
   ```
2. Jalankan notebook Python di Google Colab dengan SparkSession yang telah disiapkan.
3. Masukkan dataset ke Google Drive dan sesuaikan path file pada kode.
4. Ikuti langkah-langkah dalam script untuk pembersihan data, pra-pemrosesan, modeling, dan evaluasi.

## Dataset
Dataset yang digunakan adalah data penjualan properti dari tahun 2001 hingga 2021. Dataset meliputi informasi seperti nilai taksiran, rasio penjualan, jenis properti, dan harga penjualan.
link: https://catalog.data.gov/dataset/real-estate-sales-2001-2018

## Hasil Proyek
- **RMSE:** Mengevaluasi seberapa baik model memprediksi nilai penjualan.
- **Koefisien Determinasi (R²):** Mengukur seberapa baik model menjelaskan variansi dalam data.

## Visualisasi
- Grafik perbandingan nilai aktual vs prediksi.
- Residual plot untuk memeriksa error model.

## Kontributor
Kelompok 7 - Tugas Besar ABD

---
