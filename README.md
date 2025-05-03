# ML-KNN-Code
# K-Nearest Neighbors (KNN) Classifier on Iris Dataset

## Deskripsi Proyek
Repositori ini berisi implementasi algoritma **K-Nearest Neighbors (KNN)** menggunakan bahasa Python dan pustaka `scikit-learn`, dengan dataset klasik **Iris**. Kode ini merupakan bagian dari eksperimen sederhana untuk studi kecerdasan buatan dan machine learning.

---

## Versi Awal (Kode Belum Dimodifikasi)

Kode awal dari repositori GitHub [Saswat956/Machine-Learning-Codes](https://github.com/Saswat956/Machine-Learning-Codes) hanya memuat fungsi dasar dari algoritma KNN, seperti:

- Pemrosesan dataset menggunakan `load_iris()`
- Pembagian data latih dan uji
- Inisialisasi model KNN
- Evaluasi akurasi model menggunakan data uji

Namun, belum terdapat visualisasi distribusi data maupun confusion matrix.

---

## Versi Dimodifikasi

Kode yang telah dimodifikasi menambahkan sejumlah fitur penting untuk memperjelas proses eksperimen dan evaluasi model:

### Perubahan yang Dilakukan:
1. **Konversi ke Pandas DataFrame**  
   Dataset `iris` dikonversi ke dalam DataFrame untuk eksplorasi awal.

2. **Visualisasi Distribusi Kelas**  
   Ditambahkan `countplot()` dari `seaborn` untuk menunjukkan distribusi kelas target pada dataset.

3. **Standarisasi Fitur**  
   Menggunakan `StandardScaler` untuk menormalkan fitur karena KNN sensitif terhadap skala.

4. **Confusion Matrix**  
   Ditambahkan visualisasi confusion matrix menggunakan `seaborn.heatmap()` untuk melihat detail prediksi model terhadap kelas aktual.

5. **Evaluasi Akurasi**  
   Akurasi model dicetak secara eksplisit dengan format yang lebih informatif.

---

## Output Eksperimen

- Akurasi Model: `1.00` (100%)
- Confusion Matrix menunjukkan klasifikasi sempurna pada semua kelas (*setosa*, *versicolor*, *virginica*).
- Distribusi kelas seimbang dan visualisasi membantu memahami model secara intuitif.

---

## Topik Kecerdasan Buatan Terkait

Eksperimen ini termasuk dalam **Machine Learning**, khususnya pada **algoritma supervised learning** berbasis kedekatan jarak (*instance-based learning*), yaitu **K-Nearest Neighbors (KNN)**.

---

## Referensi

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [UCI Machine Learning Repository - Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
- [Saswat956/Machine-Learning-Codes GitHub](https://github.com/Saswat956/Machine-Learning-Codes)

---

