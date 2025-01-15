# Feature Engineering
Feature engineering adalah proses yang sangat penting dalam machine learning, di mana data mentah atau kotor diubah menjadi fitur-fitur yang dapat digunakan oleh model untuk melakukan prediksi. Proses ini melibatkan pemilihan, transformasi, dan penciptaan fitur-fitur yang relevan serta bermakna dari data yang tersedia. Tujuan utamanya adalah untuk memaksimalkan performa model dengan menyediakan input yang paling representatif dan informatif.
Secara sederhana metode binning ini berfokus pada penyederhanaan data numerik, sementara encoding  menangani variabel kategorikal.

## Teknik Pemilihan Fitur (Feature Selection)
Teknik Pemilihan Fitur (Feature Selection) adalah proses pemilihan subset fitur yang paling relevan atau penting untuk digunakan dalam model machine learning. Tujuannya adalah untuk meningkatkan performa model dengan menghilangkan fitur yang tidak relevan, redundan, atau kotor (biasa disebut noise). Dengan demikian, kita bisa mengurangi kompleksitas model, meningkatkan akurasi, dan mempercepat proses pelatihan.
![Screenshot 2025-01-15 170545](https://github.com/user-attachments/assets/0eedc47b-09b5-4a4d-a491-bfad26f6395f)

## Encoding Variabel ke Numerik
Encoding dalam machine learning adalah proses mengonversi data non-numerik (kategorikal atau teks) menjadi bentuk numerik. 
![Screenshot 2025-01-15 161745](https://github.com/user-attachments/assets/0aa929ac-13c2-48d2-a0b1-a8ae5522ffe6)

## Binning Numerik ke Kategorikal
Binning digunakan untuk mengubah data numerik kontinu menjadi kategori atau interval diskrit. Tujuannya adalah untuk menyederhanakan data numerik dengan memisahkannya menjadi beberapa kelompok atau bin berdasarkan rentang atau distribusi nilai tertentu. 

## Scaling Fitur
Scaling feature pada machine learning adalah proses menyesuaikan rentang atau skala nilai-nilai fitur agar berada dalam rentang tertentu yang lebih seragam. Proses ini memiliki peran yang cukup penting karena banyak algoritma machine learning sensitif terhadap perbedaan skala antara fitur. 

## Penanganan Outlier
Dalam statistik, outlier adalah sebuah nilai yang jauh berbeda dari kumpulan nilai lainnya dan dapat mengacaukan hasil dari sebuah analisis statistik. Outlier dapat disebabkan oleh kesalahan dalam pengumpulan data atau nilai tersebut benar ada dan memang unik dari kumpulan nilai lainnya.

## Oversampling dan Undersampling
Imbalanced Dataset adalah situasi ketika jumlah data pada satu kelas jauh lebih sedikit atau lebih banyak dibandingkan dengan kelas lainnya. Ini sering terjadi dalam masalah klasifikasi, khususnya dalam binary classification (klasifikasi dua kelas) ketika satu kelas (sering disebut minoritas) memiliki jauh lebih sedikit sampel dibandingkan kelas lainnya (disebut mayoritas).beberapa teknik untuk mengatasi permasalahan imbalance dataset seperti oversampling atau undersampling.
1. Oversampling
2. Undersampling

## SMOTE (Synthetic Minority Over-Sampling Technique)
Synthetic Minority Over-sampling Technique (SMOTE) adalah teknik oversampling yang dirancang untuk menangani masalah imbalanced dataset pada machine learning. Berbeda dengan random oversampling yang hanya menduplikasi sampel dari kelas minoritas, SMOTE menghasilkan sampel sintetis (baru) berdasarkan data yang sudah ada di kelas minoritas. Dari hal itu terciptalah variasi baru di dalam dataset dan mengurangi risiko overfitting yang mungkin terjadi jika kita hanya menduplikasi data secara acak.
