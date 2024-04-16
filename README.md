# Klasifikasi dan Regresi dengan Support Vector Machine
### Nama : Siti Nurrahmasita
### NPM  : 2108107010015

# Tentang Datasets:
## 1. Klasifikasi: https://www.kaggle.com/datasets/aparnashankar/facebook-ads-dataset

Dataset ini dapat digunakan dalam menganalisis kinerja kampanye iklan Facebook dengan menggunakan algoritma SVM untuk klasifikasi pengguna yang mengklik iklan berdasarkan waktu yang dihabiskan di situs dan gaji mereka.
Keseluruhan atribuat yang ada di dalamnya:
  - Names: Nama pengguna (tidak digunakan dalam analisis)
  - Time Spent on Site: Waktu yang dihabiskan pengguna di situs (dalam satuan menit)
  - Salary: Gaji pengguna (dalam satuan dollar)
  - Clicked: Apakah pengguna mengklik iklan atau tidak (1=yes, 0=no)

## 2. Regresi: https://www.kaggle.com/datasets/yasserh/student-marks-dataset

Dataset ini terdiri dari tiga kolom: `number_courses`, `time_study`, dan `Marks`. Berikut adalah penjelasan singkat tentang setiap kolom:
  - number_courses: Kolom ini mewakili jumlah kursus atau mata pelajaran yang diambil oleh seorang siswa dalam suatu periode tertentu. Jumlah kursus dapat menjadi indikator beban akademik atau tingkat komitmen siswa terhadap pendidikannya.
  - time_study: Kolom ini mengacu pada waktu yang dihabiskan oleh seorang siswa untuk belajar dalam satuan jam. Variabel ini dapat mencerminkan tingkat upaya atau dedikasi siswa terhadap pembelajaran.
  - Marks: Kolom ini mencerminkan nilai atau prestasi akademik yang diperoleh oleh siswa dalam kursus atau mata pelajaran yang diambilnya. Nilai ini dapat diberikan dalam sakala presentasi.

Dataset ini dapat digunakan untuk menganalisis hubungan antara jumlah kursus, waktu belajar, dan prestasi akademik siswa. Misalnya, Anda dapat menjelajahi apakah ada hubungan antara jumlah kursus yang diambil dan prestasi akademik, atau apakah ada pola yang dapat ditemukan dalam waktu belajar dan prestasi akademik siswa. Analisis semacam itu dapat memberikan wawasan yang berharga bagi pendidik dan pengambil keputusan pendidikan untuk meningkatkan kualitas pembelajaran dan hasil akademik siswa.


## Cara Menjalankan Source Code
1. Download file .ipynb dan dataset atau clone repository
2. Install library dengan: python3 pip install -r requirement.txt
3. Input dataset ke dalam halaman .ipynb sesuai dengan kebutuhan, di mana dataset:
  - Facebook_Ads.csv untuk file SVC.ipynb
  - Salary Data.csv dan Salary untuk file SVR.ipynb
4. Run code Klasifikasi.ipynb dan Regresi.ipynb di server lokal Anda
