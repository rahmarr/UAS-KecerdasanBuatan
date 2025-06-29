UAS KECERDASAN BUATAN
SITI RAHMAWATI (2306146)

❤️ Heart Disease Prediction using Machine Learning
Dataset sumber: Kaggle - Heart Disease Data

📄 Deskripsi
Proyek ini bertujuan memprediksi risiko penyakit jantung menggunakan algoritma Machine Learning (ML). Dataset yang digunakan merupakan subset dari UCI Heart Disease Dataset yang berisi data klinis pasien seperti usia, jenis kelamin, tekanan darah, kadar kolesterol, dan hasil pemeriksaan EKG.

Penyakit jantung merupakan salah satu penyebab kematian utama di dunia, dengan lebih dari 17,9 juta kematian setiap tahun menurut WHO. Dengan memanfaatkan ML, prediksi risiko penyakit jantung dapat dilakukan lebih cepat, murah, dan membantu diagnosis dini oleh tenaga medis.

📊 Dataset
Dataset terdiri dari 303 baris data (pasien) dengan 14 kolom (13 fitur dan 1 target).
Beberapa fitur penting:

No	Nama Fitur	Deskripsi	Tipe	Nilai
1	age	Usia pasien	Numerik	29–77
2	sex	Jenis kelamin (1=Laki-laki, 0=Perempuan)	Kategorikal	0,1
3	cp	Tipe nyeri dada	Kategorikal	0–3
4	trestbps	Tekanan darah istirahat (mmHg)	Numerik	94–200
5	chol	Kolesterol serum (mg/dl)	Numerik	126–564
6	fbs	Gula darah puasa >120 mg/dl (1=Ya, 0=Tidak)	Kategorikal	0,1
7	restecg	Hasil EKG istirahat	Kategorikal	0–2
8	thalach	Detak jantung maksimum	Numerik	71–202
9	exang	Angina akibat olahraga (1=Ya, 0=Tidak)	Kategorikal	0,1
10	oldpeak	Depresi ST akibat olahraga	Numerik	0–6.2
11	slope	Kemiringan segmen ST	Kategorikal	0–2
12	ca	Jumlah pembuluh darah utama yang diwarnai fluoroskopi	Numerik	0–4
13	thal	Status thalassemia (3=Normal, 6=Fixed defect, 7=Reversible defect)	Kategorikal	3,6,7
14	target	1=Memiliki penyakit jantung, 0=Tidak	Kategorikal	0,1

🧠 Metodologi
Proyek ini membandingkan performa beberapa algoritma Machine Learning:

Decision Tree

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Langkah-langkah:

Data Understanding & Exploratory Data Analysis (EDA)
Melihat distribusi data, outlier, dan korelasi antar fitur.

Data Preprocessing

Normalisasi data numerik

Encoding data kategorikal jika diperlukan

Modeling & Evaluation

Split data (contoh: 80% train, 20% test)

Latih model dan evaluasi menggunakan metrik: Accuracy, Precision, Recall, dan F1-score

Perbandingan Hasil
Menentukan algoritma terbaik.

📈 Hasil (contoh)
Algoritma	Akurasi
Decision Tree	~93%
SVM	~92%
KNN	~91%

Hasil ini adalah contoh dan dapat berbeda tergantung implementasi & parameter tuning.

⚙️ Tools & Teknologi
Python (Jupyter Notebook / Google Colab)

Scikit-Learn

Pandas, NumPy

Matplotlib, Seaborn

✅ Tujuan
Membantu deteksi dini risiko penyakit jantung.

Memberikan rekomendasi algoritma ML terbaik untuk prediksi.

Mendukung tenaga medis dalam pengambilan keputusan.

📚 Sumber & Referensi
Dataset: Kaggle - Heart Disease Data

Laporan UAS: Prediksi Penyakit Jantung Menggunakan Perbandingan Algoritma ML Decision Tree, SVM, dan KNN

UCI Machine Learning Repository
