# UAS_KecerdasanBuatan

Klasifikasi Risiko Stroke Menggunakan Algoritma K-Nearest Neighbor(KNN)

Deskripsi
Proyek ini bertujuan membangun sistem klasifikasi risiko stroke menggunakan data pasien yang diambil dari Kaggle. Algoritma yang digunakan adalah K-Nearet Neighbor (KNN) dengan pendekatan balancing data menggunakan SMOTE untuk mengatasi ketidakseimbangan kelas.

Langkah Pengerjaan
1. Problem dan Data Understanding
   - Dataset: Stroke Prediction Dataset dari Kaggle
   - Target: Kolom stroke
   - Total data: 5110 baris, 11 fitur
2. Data Preparation
   - Hapus kolom id
   - Imputasi nilai kosong pada bmi
   - Label encoding untuk fitur kategorikal
   - Penanganan data tidak seimbang menggunakan SMOTE
   - Split data: 80% train, 20% test
3. Modeling
   - Algoritma: K-Nearest Neighbor (KNN)
   - Hyperparameter tuning dengan GridSearchCV
   - Evaluasi menggunakan confusion matrix dan classification report (Accuracy, Precision, Recall,      F1-score)
4. Evaluation
   - Visualisasi hasil evaluasi menggunakan seaborn dan matplotlib
   - Akurasi dan metrik lainnya dianalisis secara mendalam
5. Tools
   - Python (Jupyter Notebook)
   - Library: pandas, scikit-learn, matplotlib, seaborn, imbalanced-learn
