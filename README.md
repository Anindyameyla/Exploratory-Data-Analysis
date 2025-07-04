# Exploratory-Data-Analysis
## Background problem
Penerimaan mahasiswa merupakan proses penting dalam pendidikan tinggi. Namun, seringkali analisis terhadap data pelamar belum optimal sehingga tidak mampu memberikan gambaran menyeluruh tentang karakteristik pelamar yang diterima dan ditolak. Dataset admission yang besar dan kompleks membuat proses analisis dan visualisasi membutuhkan memori besar, sehingga hasil dashboard dan data disimpan di cloud. Tujuan dari proyek ini adalah untuk mengeksplorasi dan mengklasifikasikan data pelamar berdasarkan atribut akademik dan demografis, serta membangun model prediktif untuk menentukan status diterima atau ditolak. Saya menggunakan Dataset dari tautan berikut ini : https://www.kaggle.com/datasets/zeeshier/student-admission-records

## Version Libraries (opsional)
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## Insight
Beberapa insight yang diperoleh dari hasil eksplorasi dan modeling:
1. Kualitas Akademik Menentukan: Nilai SMA dan skor tes masuk memiliki pengaruh besar terhadap status penerimaan.
2. Distribusi Usia & Persentase SMA: Kedua fitur ini cenderung skewed, perlu distandarisasi.
3. Model Terbaik: Random Forest memberikan akurasi terbaik (67%) dibanding model lain seperti Logistic Regression, Decision Tree, dan SVM.
4. Korelasi Rendah: Korelasi antar variabel rendah (<0.3), sehingga fitur-fitur bersifat independen.

## Advice
Proyek ini dapat dikembangkan lebih lanjut, antara lain:
1. Optimasi Model ML: Lakukan hyperparameter tuning pada model Random Forest atau uji model lain seperti XGBoost.
2. Penambahan Variabel: Masukkan fitur tambahan seperti jurusan SMA, status ekonomi, atau aktivitas non-akademik.
3. Visualisasi Interaktif: Gunakan Streamlit untuk membuat dashboard interaktif yang bisa diakses publik.
   
#EDA #python #BI #machinelearning #admissiondata #classification #data-science #studentanalytics
Anda bisa terhubung dengan saya jika ingin mendiskusikan sesuatu melalui, meylacartika@gmail.com
