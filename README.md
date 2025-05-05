## 1. Eksplorasi Data dengan Pandas

Langkah awal adalah memahami struktur data menggunakan pustaka `pandas`. Tahap ini melibatkan:

- Membaca dataset CSV
- Melihat preview data dengan `head()`
- Mengecek tipe data dan missing values
- Meninjau distribusi kelas target (serangan vs normal)

Eksplorasi ini penting untuk menentukan tindakan pembersihan atau transformasi data selanjutnya.

---

## 2. Visualisasi Data dengan Matplotlib & Seaborn

Visualisasi data membantu mengungkap pola dan hubungan antar fitur:

- Distribusi kelas target (apakah data imbalance?)
- Korelasi antar fitur numerik
- Visualisasi menggunakan histogram, heatmap, dan boxplot

---

## 3. Persiapan Data

Sebelum model dibangun, data diproses lebih lanjut:

- Encoding fitur kategorikal ke numerik (Label Encoding / One-Hot Encoding)
- Normalisasi data jika dibutuhkan
- Split data menjadi training dan testing set (biasanya 80:20 atau 70:30)

---

## 4. Klasifikasi dengan Naive Bayes

Naive Bayes bekerja dengan prinsip probabilistik dan mengasumsikan independensi antar fitur. Prosesnya meliputi:

- Melatih model pada data training
- Melakukan prediksi pada data testing
- Evaluasi menggunakan: Accuracy, Precision, Recall, F1-Score, dan Confusion Matrix

Naive Bayes sangat cepat namun kurang akurat jika asumsi independensi tidak terpenuhi.

---

## 5. Klasifikasi dengan Decision Tree

Decision Tree bekerja dengan membuat struktur pohon berdasarkan pembagian informasi fitur. Prosesnya mencakup:

- Melatih model Decision Tree
- Menampilkan struktur pohon menggunakan `plot_tree`
- Evaluasi hasil klasifikasi seperti pada Naive Bayes

Kelebihan Decision Tree adalah kemudahan interpretasi dan fleksibilitas dalam menangani data numerik/kategorikal.

---

## 6. Evaluasi Model

Evaluasi model dilakukan menggunakan:

- **Confusion Matrix** untuk melihat True Positive, False Positive, dll.
- **Classification Report** dari `sklearn` untuk metrik lengkap

Dalam script terbaru, visualisasi confusion matrix dan decision tree berhasil ditampilkan.

---
