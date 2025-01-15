# Machine-Learning
## Definisi ML
Arthur Samuel memperkenalkan istilah machine learning pada tahun 1959. Dia mendefinisikan machine learning sebagai cabang ilmu yang memungkinkan komputer belajar dan berkembang tanpa diprogram secara eksplisit untuk setiap tugas. Jadi, alih-alih memerlukan serangkaian aturan dari manusia, mesin dapat mempelajari pola berdasarkan data. Mesin pun dapat membuat keputusan atau prediksi berdasarkan pembelajaran tersebut. Ini membuat proses pemrograman lebih fleksibel dan adaptif.

## Komponen utama ML
1. Data
2. Model
3. Algoritma
4. Feature Engineering
5. Training
6. Evaluation
7. Hyperparameter Tuning
8. Deployment

## Jenis-jenis ML
1. Supervised Learning
2. Unsupervised Learning
3. Semi-Supervised Learning
4. Reinforcement Learning

## merumuskan masalah dalam ML
1. identifikasi tujuan bisnis
2. pahami data yang tersedia
3. tentukan jenis masalah ML
4. definisikan variabel target dan fitur
5. membuat pernyataan masalah yang jelas

## tantangan utama dalam ML
1. kualitas data
2. keterbatasan data
3. pemilihan model dan algoritma
4. Etika dan privasi
5. pemeliharaan dan pembaruan

## ML Workflows
![Screenshot 2025-01-15 135209](https://github.com/user-attachments/assets/91543ced-d6df-4359-949c-1dc8be8ddd92)

# Supervised Learning - KLASIFIKASI
Klasifikasi adalah teknik dalam machine learning untuk mengelompokkan data ke dalam kategori atau kelas tertentu berdasarkan karakteristik atau fitur dari data tersebut. Klasifikasi termasuk dalam supervised learning, yaitu model dilatih menggunakan data yang sudah diberi label. Contoh aplikasi klasifikasi termasuk pengenalan wajah, filter spam pada email, deteksi penipuan, dan diagnosis penyakit.

### Proses Klasifikasi: Langkah Demi Langkah
1. pengumpulan data
2. pra-pemrosesan data
3. pembagian data
4. pemilihan algoritma klasifikasi
5. pelatihan model
6. evaluasi model
7. deployment

### Algoritma Klasifikasi
1. K-Nearest Neighbors (KNN)
2. Decision tree
3. Random Forest
4. Support Vector Machine (SVM)
5. Naive Baiyes

### Evaluasi Model Klasifikasi
1. Confusion Matrix
2. Metrik evaluasi (Akurasi, Precision, Recall, F1-Score)

# Supervised Learning - RREGRESI
Regresi adalah salah satu teknik dalam machine learning yang memiliki kesamaan dengan klasifikasi. Namun, perbedaan utama antara keduanya terletak pada hasil prediksinya. Pada klasifikasi, model machine learning bertugas untuk memprediksi sebuah kelas atau kategori. Misalnya, apakah suatu email adalah spam atau bukan. 

### Jenis-jenis regresi 
![Screenshot 2025-01-15 140039](https://github.com/user-attachments/assets/ce8444cd-7e3a-4631-80a8-7bc454ab9d79)

### Evaluasi Model regresi 
![Screenshot 2025-01-15 140147](https://github.com/user-attachments/assets/50c85a17-b1a6-4405-a54a-c9292fa27f82)

# Unsupervised Learning - CLUSTERING
Clustering adalah teknik unsupervised learning untuk mengelompokkan data ke dalam grup berdasarkan kesamaan fitur tanpa memerlukan label. Proses ini bermanfaat untuk menemukan pola atau struktur tersembunyi dalam data.

### Tahapan proses clustering
1. pengumpulan data
2. pemilihan fitur
3. pra-pemrosesan data
4. pemilihan motode pengukuran jarak
5. pemilihan algoritma clustering
6. penerapan algoritma clustering
7. evaluasi hasil
8. interpretasi dan tindakan

### Hierarchical Clustering (HC)
HC adalah teknik clustering yang membentuk struktur hierarki antara cluster. Ada dua pendekatan dalam HC:

*  Agglomerative (bottom-up): setiap objek dimulai sebagai cluster terpisah dan digabungkan hingga menjadi satu cluster besar.
*  Divisive (top-down): dimulai dengan satu cluster besar yang dibagi menjadi cluster lebih kecil.
Hierarchical clustering digambarkan dalam dendrogram untuk menunjukkan proses penggabungan atau pemecahan cluster.

### Non-hierarchical Clustering (NHC)
Non-hierarchical Clustering (NHC) adalah metode clustering yang membagi data menjadi cluster tanpa membentuk struktur hierarkis. Metode Non-hierarchical Clustering :
1. K-Means Clustering
2. K-Medoids Clustering
3. DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
4. Mean Shift Clustering

