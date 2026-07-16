# ❤️ Heart Disease Prediction Using Machine Learning

## UAS Kecerdasan Buatan

Proyek ini dibuat untuk memenuhi tugas Ujian Akhir Semester (UAS) Mata Kuliah **Kecerdasan Buatan** dengan menerapkan teknik Machine Learning untuk memprediksi kemungkinan seseorang mengalami penyakit jantung berdasarkan data kesehatan pasien.

---

# 👥 Anggota Kelompok

|      Nama        |  NIM    |
|------------------|---------|
| Nauval Al Ghafur | 2406035 |
| Sandi Febriansah | 2406001 |

---

# 📌 Deskripsi Proyek

Penyakit jantung merupakan salah satu penyebab kematian tertinggi di dunia. Banyak faktor yang dapat meningkatkan risiko penyakit jantung seperti usia, tekanan darah, kadar kolesterol, kondisi pembuluh darah, serta riwayat kesehatan lainnya.

Dengan memanfaatkan teknologi Artificial Intelligence dan Machine Learning, data kesehatan pasien dapat dianalisis untuk membantu proses identifikasi risiko penyakit jantung secara lebih cepat dan akurat.

Pada proyek ini dilakukan proses analisis data, visualisasi, preprocessing, pembangunan model klasifikasi, serta evaluasi performa model untuk menentukan algoritma terbaik dalam memprediksi penyakit jantung.

---

# 🎯 Tujuan Proyek

Tujuan dari proyek ini adalah:

- Memahami karakteristik data pasien penyakit jantung.
- Melakukan Exploratory Data Analysis (EDA).
- Melakukan preprocessing data sebelum proses pelatihan model.
- Membangun model klasifikasi menggunakan algoritma Machine Learning.
- Membandingkan performa beberapa algoritma klasifikasi.
- Menentukan model terbaik berdasarkan hasil evaluasi.

---

# 🏥 Latar Belakang

Menurut World Health Organization (WHO), penyakit kardiovaskular merupakan salah satu penyebab kematian terbesar secara global. Deteksi dini terhadap risiko penyakit jantung sangat penting untuk membantu tenaga medis dalam mengambil keputusan yang lebih cepat dan tepat.

Machine Learning dapat digunakan untuk mempelajari pola dari data kesehatan pasien dan menghasilkan prediksi yang dapat membantu proses diagnosis awal. Oleh karena itu, proyek ini berfokus pada penerapan algoritma klasifikasi untuk memprediksi keberadaan penyakit jantung berdasarkan data pasien.

---

# 📊 Dataset

Dataset yang digunakan adalah **Heart Disease Dataset** yang berisi informasi kesehatan pasien dan status penyakit jantung.

## Informasi Dataset

| Keterangan | Nilai |
|------------|--------|
| Jumlah Data | 1025 |
| Jumlah Kolom | 14 |
| Jumlah Fitur | 13 |
| Target | target |
| Jenis Masalah | Classification |

---

# 🎯 Distribusi Target

| Nilai Target | Keterangan | Jumlah Data |
|-------------|-------------|-------------|
| 0 | Tidak Memiliki Penyakit Jantung | 499 |
| 1 | Memiliki Penyakit Jantung | 526 |

Dataset memiliki distribusi kelas yang relatif seimbang sehingga cocok digunakan untuk membangun model klasifikasi tanpa memerlukan teknik penanganan data imbalance yang kompleks.

---

# 📋 Deskripsi Fitur Dataset

| Fitur | Deskripsi |
|---------|---------|
| age | Usia pasien |
| sex | Jenis kelamin pasien |
| cp | Tipe nyeri dada (chest pain) |
| trestbps | Tekanan darah saat istirahat |
| chol | Kadar kolesterol dalam darah |
| fbs | Gula darah puasa |
| restecg | Hasil elektrokardiogram saat istirahat |
| thalach | Detak jantung maksimum yang dicapai |
| exang | Angina akibat olahraga |
| oldpeak | Depresi ST akibat olahraga |
| slope | Kemiringan segmen ST |
| ca | Jumlah pembuluh darah utama |
| thal | Status thalassemia |
| target | Status penyakit jantung |

---

# 🔄 Metodologi Penelitian

Tahapan pengerjaan proyek mengikuti alur Data Science sebagai berikut:

```text
Business Understanding
        ↓
Data Understanding
        ↓
Exploratory Data Analysis
        ↓
Data Preparation
        ↓
Modeling
        ↓
Evaluation
        ↓
Conclusion
```

---

# 🔍 Exploratory Data Analysis (EDA)

Pada tahap ini dilakukan analisis awal terhadap dataset untuk memahami pola data dan hubungan antar fitur.

Analisis yang dilakukan:

- Pemeriksaan ukuran dataset
- Pemeriksaan tipe data
- Analisis distribusi target
- Visualisasi histogram setiap fitur
- Analisis korelasi antar variabel menggunakan heatmap
- Pemeriksaan keseimbangan kelas
- Analisis pola awal yang berhubungan dengan penyakit jantung

Visualisasi yang digunakan:

- Histogram
- Countplot
- Boxplot
- Correlation Heatmap

---

# ⚙️ Data Preparation

Tahap preprocessing dilakukan untuk memastikan data siap digunakan oleh algoritma Machine Learning.

Langkah-langkah yang dilakukan:

- Pemeriksaan missing value
- Pemeriksaan data duplikat
- Pemisahan fitur dan target
- Split data training dan testing
- Normalisasi/standardisasi data numerik menggunakan StandardScaler

---

# 🤖 Algoritma Machine Learning

Dalam proyek ini digunakan minimal dua algoritma klasifikasi untuk membandingkan performa model.

## 1. Decision Tree

Decision Tree merupakan algoritma berbasis pohon keputusan yang mudah dipahami dan dapat divisualisasikan.

Kelebihan:

- Interpretasi mudah
- Cepat dalam proses training
- Cocok untuk klasifikasi

---

## 2. Random Forest

Random Forest merupakan metode ensemble learning yang menggabungkan banyak Decision Tree untuk menghasilkan prediksi yang lebih stabil.

Kelebihan:

- Akurasi lebih tinggi
- Mengurangi overfitting
- Performa stabil pada berbagai jenis data

---

# 📈 Evaluasi Model

Evaluasi model dilakukan menggunakan beberapa metrik berikut:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Tabel hasil evaluasi akan ditampilkan setelah proses pelatihan model selesai dilakukan.

| Model | Accuracy | Precision | Recall | F1-Score |
|---------|---------|---------|---------|---------|
| Decision Tree | 0.985366 | 1.000000 | 0.971429 | 0.985507 |
| Random Forest | 1.000000 | 1.000000 | 1.000000 | 1.000000 |

---

# 🏆 Hasil Penelitian

Berdasarkan hasil pelatihan dan evaluasi model, algoritma dengan performa terbaik akan dipilih berdasarkan nilai Accuracy, Precision, Recall, dan F1-Score tertinggi.

Hasil akhir evaluasi akan ditampilkan pada notebook dan laporan proyek.

---

# 🛠️ Tools dan Library

## Software

- Visual Studio Code
- Jupyter Notebook
- GitHub

## Library Python

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

# 📁 Struktur Repository

```text
UAS-KecerdasanBuatan-HeartDiseasePrediction/
│
├── README.md
├── Laporan_uas.md
├── uas_model.ipynb
│
├── Data/
│   └── heart.csv
│
├── Jurnal/
│   └── Referensi Jurnal
│
└── images/
    └── Hasil Visualisasi dan Evaluasi
```

---

# ▶️ Cara Menjalankan Proyek

### Clone Repository

```bash
git clone https://github.com/Nauval35/UAS-KecerdasanBuatan-HeartDiseasePrediction.git
```

### Install Library

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Jalankan Notebook

```bash
jupyter notebook uas_model.ipynb
```

---

# 📚 Referensi

Referensi ilmiah yang digunakan dalam proyek ini disimpan pada folder:

```text
Jurnal/
```

Minimal 5 jurnal ilmiah digunakan sebagai dasar teori dan pendukung penelitian.

---

# 📄 Lisensi

Repository ini dibuat untuk keperluan akademik sebagai pemenuhan tugas Ujian Akhir Semester (UAS) Mata Kuliah Kecerdasan Buatan.

---

## ⭐ Heart Disease Prediction Project

Implementasi Machine Learning untuk membantu prediksi penyakit jantung berdasarkan data kesehatan pasien menggunakan algoritma klasifikasi dan evaluasi performa model.