# Klasifikasi dan Regresi dengan Support Vector Machine
#### Nama : Siti Nurrahmasita
#### NPM  : 2108107010015

## Tentang Datasets:
1. Klasifikasi: https://www.kaggle.com/datasets/aparnashankar/facebook-ads-dataset
Dataset ini dapat digunakan dalam menganalisis kinerja kampanye iklan Facebook dengan menggunakan algoritma SVM untuk klasifikasi pengguna yang mengklik iklan berdasarkan waktu yang dihabiskan di situs dan gaji mereka.
Keseluruhan atribuat yang ada di dalamnya:
  - Names: Nama pengguna (tidak digunakan dalam analisis)
  - Time Spent on Site: Waktu yang dihabiskan pengguna di situs (dalam satuan menit)
  - Salary: Gaji pengguna (dalam satuan dollar)
  - Clicked: Apakah pengguna mengklik iklan atau tidak (1=yes, 0=no)

2. Regresi:
##### Data Pertama: https://www.kaggle.com/datasets/rkiattisak/salaly-prediction-for-beginer 
Dataset ini berisi informasi mengenai gaji karyawan pada suatu perusahaan guna memprediksi gaji seseorang berdasarkan atribut lainnya. Setiap baris mewakili karyawan yang berbeda. Dalam visualisasinya hanya menggunakan satu fitur independent dengan korelasi tertinggi untuk meprediski label. 
Keseluruhan atribuat yang ada di dalamnya:
  - Age: Kolom ini mewakili usia setiap karyawan dalam satuan tahun. Nilai pada kolom ini bersifat numerik.
  - Gender: Jenis kelamin dari individu, yaitu "Male" atau "Female". Nilai pada kolom ini bersifat kategoris.
  - Education Level: Tingkat pendidikan dari individu, misalnya "High School", "Bachelor", "Master", dan "PhD"). Nilai pada kolom ini bersifat kategoris.
  - Job Title: Kolom ini berisi jabatan masing-masing karyawan. Judul pekerjaan dapat bervariasi tergantung pada perusahaan dan mungkin mencakup posisi seperti "Software Engineer", "Data Analyst", "Senior Manager", Sales Associate, "Director", dll. Nilai pada kolom ini bersifat kategoris.
  - Years of Experience: Jumlah tahun pengalaman kerja individu. Nilai pada kolom ini bersifat numerik.
  - Salary: Kolom ini mewakili gaji tahunan setiap karyawan dalam dolar AS. Kolom ini merupakan target/variabel dependent dengan nilai didalamnya bersifat numerik dan dapat bervariasi tergantung pada kolom lainnya.


##### Data Kedua: https://www.kaggle.com/datasets/rsadiq/salary 
Data ini terdiri dari gaji dan pengalaman kerja 35 orang pekerja. Dimana saya akan mencoba menunjukkan hubungan antara gaji dan pengalaman bertahun-tahun.
Keseluruhan atribuat yang ada di dalamnya:
  - YearsExperience (tahun)
  - Salary (dolar AS)

## Cara Menjalankan Source Code
1. Download file .ipynb dan dataset atau clone repository
2. Install library dengan: python3 pip install -r requirement.txt
3. Input dataset ke dalam halaman .ipynb sesuai dengan kebutuhan, di mana dataset:
  - Facebook_Ads.csv untuk file SVC.ipynb
  - Salary Data.csv dan Salary untuk file SVR.ipynb
4. Run code Klasifikasi.ipynb dan Regresi.ipynb di server lokal Anda
