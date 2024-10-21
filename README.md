# Project base learning of Datamining : predict the mental and happiness data

## Deskripsi Proyek
Proyek ini bertujuan untuk memprediksi **Life Ladder** (tingkat kebahagiaan hidup) dari beberapa negara di Asia Tenggara. Setelah melakukan prediksi, data ini juga akan dianalisis lebih lanjut menggunakan metode clustering untuk mengelompokkan negara-negara tersebut berdasarkan faktor-faktor yang memengaruhi tingkat kesehatan mental dan kebahagiaan.

## Tujuan
- Memprediksi nilai Life Ladder (indeks kebahagiaan hidup) dari negara-negara Asia Tenggara menggunakan berbagai variabel seperti ekonomi, pendidikan, dan kesehatan mental.
- Melakukan clustering negara-negara berdasarkan hasil prediksi untuk melihat pola dan kesamaan di antara mereka.
- Menggunakan model data mining untuk mengidentifikasi faktor-faktor penting yang memengaruhi kesehatan mental dan kebahagiaan.

## Teknologi yang Digunakan
- Python
- Pandas dan NumPy untuk manipulasi data
- Scikit-learn untuk membangun model prediksi (SES , Moving Average, Linier Regression, ARIMA) dan clustering K-Means
- Matplotlib dan Seaborn untuk visualisasi data

## Dataset
Dataset yang digunakan dalam proyek ini mencakup informasi tentang tingkat kebahagiaan dan kesehatan mental dari negara-negara di Asia Tenggara. Data diperoleh dari survei global dan berbagai sumber resmi. Dataset ini berisi variabel seperti GDP, harapan hidup, dan dukungan sosial.

## Model yang Dibangun
1. **Preprocessing Data:** Melakukan pembersihan data, normalisasi, dan pengisian nilai yang hilang.
2. **Prediksi Life Ladder:** Menggunakan model SES , Moving Average, Linier Regression, ARIMA untuk memprediksi indeks kebahagiaan.
3. **Clustering:** Melakukan clustering menggunakan K-Means untuk mengelompokkan negara berdasarkan hasil prediksi dan variabel lainnya.
4. **Evaluasi Model:** Menggunakan metrik seperti MAE (Mean Absolute Error) dan silhouette score untuk mengevaluasi model prediksi dan clustering.

## Cara Menjalankan Proyek
1. Clone repositori ini:
   ```bash
   git clone https://github.com/Najmaakmalina/PBL_Datamining.git
