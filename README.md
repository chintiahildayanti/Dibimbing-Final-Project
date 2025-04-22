# Final Project - Analisis Pendapatan Masyarakat AS

**Author**: Chintia Hildayanti  
**Cohort**: DS26  

## 📄 Deskripsi Proyek

Proyek ini menggunakan **Adult Census Income Dataset** dari [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/2/adult).

### 🎯 Objective

Sebagai pegawai pemerintah, proyek ini bertujuan untuk menganalisis karakteristik masyarakat Amerika Serikat yang memiliki penghasilan kurang dari \$50.000 per tahun. Hasil analisis ini digunakan untuk membantu pengambilan keputusan dalam:

- Mengecualikan individu dari pengenaan pajak penghasilan.
- Menentukan siapa yang layak menerima bantuan sosial dari pemerintah.
- Menentukan siapa yang dapat memperoleh fasilitas pelatihan keterampilan.

## 📊 Dataset

Dataset berisi informasi demografis dan pekerjaan dari individu di Amerika Serikat.

### Fitur utama:
- `age`: Usia
- `workclass`: Kelas pekerjaan
- `education`: Tingkat pendidikan
- `marital-status`: Status pernikahan
- `occupation`: Jenis pekerjaan
- `relationship`: Hubungan dalam keluarga
- `race`: Ras
- `sex`: Jenis kelamin
- `capital-gain`: Keuntungan modal
- `capital-loss`: Kerugian modal
- `hours-per-week`: Jam kerja per minggu
- `native-country`: Negara asal
- `income`: Label target (<=50K atau >50K)

## 🛠️ Tools & Library
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## ⚙️ Proses Analisis
1. Import library
2. Load dan eksplorasi data
3. Pembersihan data
4. Feature Engineering
5. Visualisasi
6. Pemodelan klasifikasi (ML)
7. Evaluasi model

## 🧠 Hasil
Model dikembangkan untuk memprediksi apakah seseorang memiliki pendapatan >\$50K atau <=\$50K berdasarkan fitur-fitur demografis.

## 🚀 How to Run

Clone repository ini, jalankan digoogle colab/Jupyter notebook.
