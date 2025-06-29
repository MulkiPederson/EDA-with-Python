# EDA-with-Python
EDA - Data Pasien Liver

## Dataset
Dataset yang digunakan merupakan dataset yang diunduh dari https://www.kaggle.com/datasets/uciml/indian-liver-patient-records. Dataset ini berisikan data - data pasien di India yang dinyatakan terkena sakit liver dan tidak sakit liver (sehat).

## Background Problem
Penyakit liver adalah masalah kesehatan serius dengan angka kematian tinggi. Dataset Indian Liver Patient berisi data pasien liver dan sehat dari India dengan berbagai fitur medis. Data ini memiliki nilai hilang dan terduplikat serta distribusi data tidak normal, sehingga perlu dilakukakan EDA (Exploratory Data Analysis) terlebih dahulu. Proyek ini fokus pada EDA dan persiapan awal dataset pasien liver untuk mendukung tindakan selanjutnya.

## Libraries
- `Pandas` untuk membaca dan memanipulasi data tabular.
- `matplotlib.pyplot` untuk menampilkan visualisasi distirbusi data dengan histogram.

## Insight
- Dataset memiliki data kosong (missing value) yang dapat ditangani, diisi dengan nilai rata-rata karena merupakan kolom numerik.
- Distribusi data tidak sepenuhnya normal (banyak yang skewed).
- Kolom target `Dataset` menunjukkan ketidakseimbangan data.
- Data yang duplikat dihapus, data menjadi bersih dan siapkan di analisis lebih lanjut
- Perlu preprocessing lebih lanjut sebelum modeling

## Advice
Lakukan transformasi log/sqrt pada fitur skewed
