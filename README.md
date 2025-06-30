# UAS_KecerdasanBuatan

# Klasifikasi Penayakit Stroke Menggunakan Algoritma K-Nearest Neighbor(KNN)

# Deskripsi
Proyek ini bertujuan membangun sistem klasifikasi risiko stroke menggunakan Dataset yang digunakan berasal dari Kaggle dan telah melalui serangkaian tahapan preprocessing dan evaluasi. Algoritma yang digunakan adalah K-Nearet Neighbor (KNN) untuk memprediksi risiko stroke berdasarkan data medis pasien. 

# Anggota Kelompok
- Dhea Muhamad Faisal A. – 2306034
- Muhammad Faiz Alfarizi – 2306041
  
# Langkah Pengerjaan
# 1. Problem dan Data Understanding
   - Identifikasi masalah klasifikasi pasien berisiko stroke.
   - Referensi jurnal SINTA & internasional sebagai dasar pendekatan.
# 2. Data Understanding
   - Dataset: Healthcare Dataset Stroke Data dari Kaggle.
   - Fitur: umur, jenis kelamin, hipertensi, penyakit jantung, pekerjaan, tempat tinggal, status      merokok, BMI, kadar glukosa, dan label stroke.
# 3. Data Preparation
   - Mengisi missing value pada kolom bmi dengan median.
   - Label encoding untuk fitur kategorikal.
   - Deteksi dan penanganan outlier dengan metode IQR.
   - Normalisasi fitur numerik dengan MinMaxScaler.
   - Penanganan imbalance class menggunakan *SMOTE*.
# 4. Modeling
   - Algoritma: **K-Nearest Neighbor (K-NN)**
   - Parameter tuning dengan **GridSearchCV**.
   - Evaluasi awal dan akhir menggunakan **accuracy**, **precision**, **recall**, **f1-score**, dan **confusion matrix**.
# 5. Evaluation
   - Akurasi awal: ~62.43%
   - Akurasi setelah tuning: ~67.75%
   - FN berkurang dari 401 menjadi 297, menunjukkan peningkatan signifikan dalam mendeteksi           kasus stroke.
# 6. Interpretation
   - Fitur age, hypertension, dan avg_glucose_level memiliki korelasi positif terhadap                stroke.
   - Kombinasi parameter terbaik: n_neighbors=21, weights='uniform, metric='manhattan'.

# Tools dan Library
   - Python (pandas, numpy, matplotlib, seaborn)
   - Scikit-learn
   - imbalanced-learn (SMOTE)

# Link Google Colab
   [Klik untuk membuka notebook]
   (https://colab.research.google.com/drive/1jT9hp9UbmhPHND96qP65plnSvmqYwsXu?usp=sharing)  

# Referensi
   1. Yulianto, Riadi, dan Umar (2023) - Jurnal RABIT
   2. Avareddy et al. (2024) - IJARCCE
   3. Azhar et al. (2022) - SINTECH Journal

