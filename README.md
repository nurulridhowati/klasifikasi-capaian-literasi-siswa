# Klasifikasi Capaian Literasi Siswa

## Deskripsi
Proyek data mining yang bertujuan untuk menganalisis dan mengklasifikasikan capaian literasi siswa SMP berdasarkan kondisi sosial ekonomi, fasilitas belajar, dan lingkungan literasi rumah. Model klasifikasi yang digunakan adalah Decision Tree dan Random Forest untuk mengidentifikasi faktor-faktor yang berkontribusi terhadap tingkat literasi siswa.

## Tujuan
- Menganalisis hubungan antara faktor sosial ekonomi dan capaian literasi siswa.
- Mengidentifikasi pengaruh fasilitas belajar dan lingkungan literasi rumah terhadap kemampuan literasi.
- Membandingkan performa algoritma Decision Tree dan Random Forest dalam klasifikasi capaian literasi siswa.
- Menentukan variabel yang paling berpengaruh terhadap hasil klasifikasi.

## Dataset
Dataset yang digunakan berasal dari data pendidikan nasional dan memuat informasi mengenai:
- Pendidikan orang tua
- Pekerjaan orang tua
- Kepemilikan fasilitas belajar
- Kepemilikan buku dan sumber bacaan
- Lingkungan literasi rumah
- Skor literasi siswa

## Metode
Tahapan analisis meliputi:
1. Data preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature selection
4. Klasifikasi menggunakan Decision Tree
5. Klasifikasi menggunakan Random Forest
6. Evaluasi model dan perbandingan performa

## Hasil Utama
- Akurasi Decision Tree: 46,24%
- Akurasi Random Forest: 46,22%
- Random Forest menunjukkan performa cross-validation yang lebih stabil.
- Pekerjaan ibu, pekerjaan ayah, pendidikan ayah, serta ketersediaan sumber belajar di rumah menjadi faktor yang paling berpengaruh terhadap capaian literasi siswa.

## Tools
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Google Colab
