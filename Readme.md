# Klasifikasi Kesehatan Mental dari Teks Media Sosial (NLP)

## Deskripsi Project

Project ini bertujuan untuk mengklasifikasikan kondisi kesehatan mental pengguna media sosial berdasarkan teks postingan menggunakan pendekatan Natural Language Processing (NLP). Studi kasus ini termasuk dalam kategori Supervised Learning dengan tipe permasalahan klasifikasi.

## Dataset

Dataset yang digunakan berasal dari Kaggle:
**Mental Health Social Media Dataset**

https://www.kaggle.com/datasets/sonalshinde123/social-media-mental-health-indicators-dataset

Dataset berisi teks postingan media sosial beserta label kondisi kesehatan mental.

## Metodologi

Tahapan yang dilakukan pada project ini meliputi:

1. Exploratory Data Analysis (EDA)
2. Pre-processing data teks
3. Feature Engineering menggunakan TF-IDF dan Bag of Words
4. Training model klasifikasi
5. Evaluasi dan analisis performa model

## Model yang Digunakan

* Logistic Regression (TF-IDF)
* Naive Bayes (Bag of Words)
* Support Vector Machine / SVM (TF-IDF)

## Evaluasi

Evaluasi model dilakukan menggunakan metrik:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Hasil evaluasi menunjukkan bahwa model Logistic Regression dan SVM dengan representasi TF-IDF memberikan performa terbaik.

## Kesimpulan

Pendekatan NLP dengan TF-IDF efektif dalam mengklasifikasikan kondisi kesehatan mental dari teks media sosial. Model Logistic Regression dan SVM direkomendasikan karena menghasilkan performa yang stabil dan seimbang.

## How to Run This Project

### 1. Persiapan Environment

Pastikan Python sudah terinstall (disarankan Python 3.8 atau lebih baru).

Install seluruh dependency yang dibutuhkan dengan perintah:

```
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

### 2. Struktur Folder

Pastikan struktur folder project sebagai berikut:

```
UASAI/
├── dataset.csv
├── uas-praktek.ipynb
└── README.md
```

### 3. Menjalankan Project

1. Buka folder project menggunakan terminal atau VS Code
2. Jalankan Jupyter Notebook dengan perintah:

```
jupyter notebook
```

3. Buka file `uas-praktek.ipynb`
4. Jalankan seluruh cell secara berurutan dari atas ke bawah

> Catatan: Pada saat pertama dijalankan, notebook akan mengunduh resource NLTK (stopwords dan wordnet).

### 4. Output

* Hasil EDA berupa visualisasi distribusi data
* Hasil evaluasi model berupa nilai accuracy, precision, recall, f1-score
* Confusion matrix untuk analisis performa model

## Author

#### Muhamad Faisal Ilham
( NIM: 312210322 )