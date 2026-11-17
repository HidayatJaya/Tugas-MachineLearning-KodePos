# 🤖 Machine Learning Projects

Repository ini berisi kumpulan proyek dan praktikum Machine Learning yang berfokus pada tiga jenis klasifikasi, yaitu **Binary Classification, Multiclass Classification, dan Multilabel Classification**.

Selain klasifikasi, repository ini juga berisi latihan Machine Learning menggunakan metode Support Vector Classification (SVC) dan Support Vector Regression (SVR).

Proyek ini dibuat sebagai bagian dari pembelajaran dan praktikum Machine Learning untuk memahami proses pengumpulan data, preprocessing, eksplorasi data, pembangunan model, hingga evaluasi performa model.

---

## 📌 Daftar Isi

1. [Deskripsi Proyek](#-deskripsi-proyek)
2. [Tujuan](#-tujuan)
3. [Jenis Klasifikasi](#-jenis-klasifikasi)
4. [Dataset](#-dataset)
5. [Notebook dan Praktikum](#-notebook-dan-praktikum)
6. [Tahapan Pengerjaan](#-tahapan-pengerjaan)
7. [Algoritma dan Metode](#-algoritma-dan-metode)
8. [Evaluasi Model](#-evaluasi-model)
9. [Teknologi yang Digunakan](#-teknologi-yang-digunakan)
10. [Struktur Repository](#-struktur-repository)
11. [Cara Menjalankan](#-cara-menjalankan)
12. [Informasi Pembuat](#-informasi-pembuat)

---

## 📖 Deskripsi Proyek

Repository ini merupakan kumpulan implementasi Machine Learning menggunakan beberapa pendekatan untuk menyelesaikan permasalahan berdasarkan karakteristik dataset yang berbeda.

Terdapat tiga jenis klasifikasi yang dipelajari:

- **Binary Classification:** Mengklasifikasikan data ke dalam dua kelas.
- **Multiclass Classification:** Mengklasifikasikan data ke dalam lebih dari dua kelas.
- **Multilabel Classification:** Mengklasifikasikan data yang dapat memiliki beberapa label sekaligus.

Selain itu, terdapat latihan penerapan algoritma SVC dan SVR sebagai bagian dari pembelajaran Machine Learning.

## 🎯 Tujuan

- Memahami konsep dasar Machine Learning.
- Mempelajari perbedaan Binary, Multiclass, dan Multilabel Classification.
- Melakukan pengumpulan dan pemuatan dataset.
- Melakukan preprocessing dan eksplorasi data.
- Membangun model Machine Learning.
- Melakukan pengujian dan evaluasi performa model.
- Memahami penggunaan algoritma klasifikasi dan regresi.

## 📚 Jenis Klasifikasi

### 1. Binary Classification

Binary Classification merupakan metode klasifikasi yang digunakan untuk memprediksi data ke dalam dua kelas atau kategori.

**Dataset yang digunakan:**
- DataKlinisKuda_Biner.csv
- Keseimbangan_Biner.csv
- Obesitas_Biner.csv
- diabetes.csv

### 2. Multiclass Classification

Multiclass Classification merupakan metode klasifikasi yang digunakan untuk memprediksi data ke dalam lebih dari dua kelas, tetapi setiap data hanya memiliki satu kelas target.

**Dataset yang digunakan:**
- BijiKopi_MultiKelas.csv
- Candy_MultiKelas.csv
- Kebun_MultiKelas.csv
- KodePos.csv

### 3. Multilabel Classification

Multilabel Classification merupakan metode klasifikasi yang memungkinkan satu data memiliki lebih dari satu label secara bersamaan.

**Dataset yang digunakan:**
- KebunBinatang_MultiLabel.csv
- Kosmetik_MultiLabel.csv
- Narkoba_MultiLabel.csv

## 📂 Dataset

Repository ini menggunakan beberapa dataset dengan karakteristik dan permasalahan yang berbeda.

| Jenis Klasifikasi | Jumlah Dataset |
|---|---:|
| Binary Classification | 4 |
| Multiclass Classification | 4 |
| Multilabel Classification | 3 |
| **Total** | **11** |

Dataset disimpan dalam format CSV dan digunakan sebagai sumber data untuk proses pembelajaran serta pemodelan Machine Learning.

## 📓 Notebook dan Praktikum

Berikut merupakan file Jupyter Notebook yang tersedia dalam repository:

| Notebook | Keterangan |
|---|---|
| ClassificationBinary.ipynb | Praktikum klasifikasi biner |
| ClassificationMultiClass.ipynb | Praktikum klasifikasi multikelas |
| ClassificationMultiLabel.ipynb | Praktikum klasifikasi multilabel |
| Kode Pos Jawa Barat.ipynb | Proyek prediksi kode pos Jawa Barat |
| Latihan_Diabetes_SVC.ipynb | Latihan Support Vector Classification |
| Latihan_SalaryData_SVR.ipynb | Latihan Support Vector Regression |

## ⚙️ Tahapan Pengerjaan

Tahapan pengerjaan Machine Learning meliputi:

1. **Data Collecting**  
   Mengumpulkan dataset dari sumber yang relevan.

2. **Data Loading**  
   Memuat dataset menggunakan Pandas.

3. **Data Preprocessing**  
   Memeriksa dan mempersiapkan data sebelum digunakan dalam pemodelan.

4. **Exploratory Data Analysis (EDA)**  
   Melakukan eksplorasi dan visualisasi untuk memahami karakteristik dataset.

5. **Encoding**  
   Mengubah data kategorikal menjadi bentuk numerik jika diperlukan.

6. **Data Splitting**  
   Membagi dataset menjadi data latih dan data uji jika diperlukan.

7. **Modeling**  
   Membangun dan melatih model Machine Learning.

8. **Evaluation**  
   Mengukur performa model menggunakan metrik evaluasi yang sesuai.

9. **Model Saving**  
   Menyimpan model yang telah dilatih jika diperlukan.

10. **Testing dan Monitoring**  
    Menguji model dan memantau performanya.

## 🤖 Algoritma dan Metode

Beberapa algoritma dan metode yang dipelajari dalam repository ini meliputi:

- Support Vector Machine (SVM)
- Support Vector Classification (SVC)
- Support Vector Regression (SVR)
- Algoritma klasifikasi lainnya sesuai implementasi pada masing-masing notebook.

**Metode pendukung:**

- Label Encoding
- One-Hot Encoding
- Train-Test Split
- Accuracy
- Precision
- Recall
- F1-Score
- Hamming Loss

## 📊 Evaluasi Model

Evaluasi dilakukan untuk mengetahui kemampuan model dalam melakukan prediksi berdasarkan jenis permasalahan yang dikerjakan.

| Jenis Model | Metrik Evaluasi |
|---|---|
| Binary Classification | Accuracy, Precision, Recall, F1-Score |
| Multiclass Classification | Accuracy, Precision, Recall, Weighted F1-Score |
| Multilabel Classification | Hamming Loss, Precision, Recall, F1-Score |
| Regression | MAE, MSE, RMSE, R² (sesuai implementasi) |

Hasil evaluasi dapat dilihat pada masing-masing notebook.

## 🛠️ Teknologi yang Digunakan

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook
- Visual Studio Code
- GitHub

## 📁 Struktur Repository

Berikut merupakan struktur file sesuai dengan repository GitHub:

```text
Tugas-MachineLearning-KodePos/
│
├── ClassificationBinary.ipynb
├── ClassificationMultiClass.ipynb
├── ClassificationMultiLabel.ipynb
│
├── Kode Pos Jawa Barat.ipynb
├── Latihan_Diabetes_SVC.ipynb
├── Latihan_SalaryData_SVR.ipynb
│
├── DataKlinisKuda_Biner.csv
├── Keseimbangan_Biner.csv
├── Obesitas_Biner.csv
├── diabetes.csv
│
├── BijiKopi_MultiKelas.csv
├── Candy_MultiKelas.csv
├── Kebun_MultiKelas.csv
├── KodePos.csv
│
├── KebunBinatang_MultiLabel.csv
├── Kosmetik_MultiLabel.csv
├── Narkoba_MultiLabel.csv
│
├── Salary_Data.csv
├── Laporan Praktek Machine Learning.docx
│
└── README.md
```

## ▶️ Cara Menjalankan

1. Clone repository:

```bash
git clone https://github.com/HidayatJaya/Tugas-MachineLearning-KodePos.git
```

2. Masuk ke folder repository:

```bash
cd Tugas-MachineLearning-KodePos
```

3. Install library yang dibutuhkan:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib jupyter
```

4. Buka folder repository menggunakan Visual Studio Code.

5. Pilih file Jupyter Notebook yang ingin dijalankan.

6. Jalankan setiap cell secara berurutan.

## 🚀 Pengembangan Selanjutnya

- Menambahkan dataset dengan permasalahan yang berbeda.
- Mencoba berbagai algoritma Machine Learning.
- Meningkatkan performa model.
- Membandingkan hasil evaluasi antaralgoritma.
- Mengembangkan model menjadi aplikasi prediksi.

---

## 👨‍💻 Informasi Pembuat

**Nama:** Muhammad Fauzan Hidayat

**Proyek:** Machine Learning Projects

**Mata Kuliah:** Machine Learning

**GitHub:** [HidayatJaya](https://github.com/HidayatJaya)

---

*Repository ini dibuat untuk keperluan pembelajaran, praktikum, dan pengembangan proyek Machine Learning.*
