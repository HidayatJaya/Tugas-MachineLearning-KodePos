# 📍 Machine Learning Kode Pos Jawa Barat

Proyek Machine Learning untuk memprediksi kode pos di wilayah Jawa Barat berdasarkan informasi wilayah administratif, seperti provinsi, kabupaten/kota, kecamatan, dan desa/kelurahan.

Proyek ini dibuat sebagai bagian dari pembelajaran dan praktikum Machine Learning, dengan tahapan mulai dari pengumpulan data, preprocessing, eksplorasi data, pembangunan model, hingga evaluasi.

---

## 📌 Daftar Isi

1. [Deskripsi Proyek](#-deskripsi-proyek)
2. [Tujuan](#-tujuan)
3. [Dataset](#-dataset)
4. [Tahapan Pengerjaan](#-tahapan-pengerjaan)
5. [Algoritma dan Metode](#-algoritma-dan-metode)
6. [Hasil Evaluasi](#-hasil-evaluasi)
7. [Teknologi yang Digunakan](#-teknologi-yang-digunakan)
8. [Struktur Folder](#-struktur-folder)
9. [Cara Menjalankan](#-cara-menjalankan)
10. [Pengembangan Selanjutnya](#-pengembangan-selanjutnya)

---

## 📖 Deskripsi Proyek

Proyek ini menggunakan dataset kode pos wilayah Jawa Barat untuk membangun model klasifikasi yang dapat memprediksi kode pos berdasarkan data wilayah administratif.

Model dilatih menggunakan algoritma **Random Forest Classifier** dengan memanfaatkan fitur nama provinsi, kabupaten/kota, kecamatan, dan desa/kelurahan.

## 🎯 Tujuan

- Memahami proses preprocessing dataset.
- Melakukan eksplorasi dan visualisasi data.
- Mengolah fitur kategorikal agar dapat digunakan oleh model Machine Learning.
- Membangun model klasifikasi untuk memprediksi kode pos.
- Mengukur performa model menggunakan metrik evaluasi yang sesuai.

## 📂 Dataset

Dataset yang digunakan adalah `KodePos.csv` yang berisi informasi kode pos wilayah Jawa Barat.

**Informasi dataset:**

| Keterangan | Jumlah |
|---|---:|
| Jumlah data | 5.957 baris |
| Jumlah kolom | 13 kolom |
| Nilai kosong | 0 |
| Data duplikat | 0 |
| Jumlah kelas kode pos | 914 |

**Fitur yang digunakan:**
- `nama_provinsi`
- `bps_nama_kabupaten_kota`
- `bps_nama_kecamatan`
- `bps_nama_desa_kelurahan`

**Target prediksi:**
- `kode_pos`

**Sumber dataset:** [Tambahkan tautan sumber dataset di sini]

## ⚙️ Tahapan Pengerjaan

Proyek ini dikerjakan melalui beberapa tahapan:

1. **Data Collecting**  
   Mengumpulkan dataset kode pos wilayah Jawa Barat.

2. **Data Preprocessing**  
   Memeriksa tipe data, nilai kosong, data duplikat, dan menyiapkan fitur yang akan digunakan.

3. **Exploratory Data Analysis (EDA)**  
   Melakukan eksplorasi data serta visualisasi untuk memahami karakteristik dataset.

4. **Encoding**  
   Mengubah fitur kategorikal menggunakan metode One-Hot Encoding.

5. **Data Splitting**  
   Membagi dataset menjadi data latih dan data uji dengan perbandingan 80:20.

6. **Modeling**  
   Membangun dan melatih model menggunakan algoritma Random Forest Classifier.

7. **Evaluation**  
   Mengukur performa model menggunakan Accuracy dan Weighted F1-Score.

8. **Model Saving**  
   Menyimpan model yang telah dilatih menggunakan Joblib agar dapat digunakan kembali.

## 🤖 Algoritma dan Metode

Algoritma yang digunakan dalam proyek ini adalah **Random Forest Classifier**.

Metode pendukung yang digunakan:

- One-Hot Encoding untuk pengolahan fitur kategorikal.
- Train-Test Split untuk membagi data latih dan data uji.
- Joblib untuk menyimpan dan memuat model.

## 📊 Hasil Evaluasi

Berdasarkan pengujian model, diperoleh hasil sebagai berikut:

| Metrik | Hasil |
|---|---:|
| Accuracy | 86,997% |
| Weighted F1-Score | 86,056% |

Hasil tersebut menunjukkan performa model dalam memprediksi kode pos berdasarkan fitur wilayah yang digunakan.

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

## 📁 Struktur Folder

```text
MachineLearning-KodePos-JawaBarat/
│
├── KodePos.csv
├── Kode Pos Jawa Barat.ipynb
├── model_kodepos.joblib
└── README.md
```

*Struktur folder dapat disesuaikan dengan isi repository yang sebenarnya.*

## ▶️ Cara Menjalankan

1. Clone repository ini:

   ```bash
   git clone [URL_REPOSITORY]
   ```

2. Masuk ke folder proyek:

   ```bash
   cd MachineLearning-KodePos-JawaBarat
   ```

3. Install library yang dibutuhkan:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn joblib jupyter
   ```

4. Buka file notebook:

   ```text
   Kode Pos Jawa Barat.ipynb
   ```

5. Jalankan setiap cell secara berurutan untuk melihat proses preprocessing, pelatihan, dan evaluasi model.

## 🚀 Pengembangan Selanjutnya

Beberapa pengembangan yang dapat dilakukan pada proyek ini:

- Meningkatkan performa model.
- Melakukan pengujian menggunakan data baru.
- Mengembangkan sistem prediksi kode pos yang lebih mudah digunakan.
- Menambahkan fitur atau visualisasi sesuai kebutuhan proyek.

---

## 👨‍💻 Informasi Pembuat

**Nama:** Muhammad Fauzan Hidayat  
**Proyek:** Machine Learning Kode Pos Jawa Barat  
**Mata Kuliah:** Machine Learning 


---

*Repository ini dibuat untuk keperluan pembelajaran dan pengembangan proyek Machine Learning.*
