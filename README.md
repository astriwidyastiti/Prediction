# Proyek Akhir: Menyelesaikan Permasalahan Institusi Pendidikan

## Business Understanding
Jaya Jaya Institut merupakan salah satu institusi pendidikan perguruan yang telah berdiri sejak tahun 2000.

## Permasalahan Bisnis
Hingga saat ini Jaya Jaya Institute telah mencetak banyak lulusan dengan reputasi yang sangat baik. Akan tetapi, terdapat banyak juga siswa yang tidak menyelesaikan pendidikannya alias dropout. Jumlah dropout yang tinggi ini tentunya menjadi salah satu masalah yang besar untuk sebuah institusi pendidikan. Oleh karena itu, Jaya Jaya Institut ingin mendeteksi secepat mungkin siswa yang mungkin akan melakukan dropout sehingga dapat diberi bimbingan khusus.

### Cakupan Proyek
Cakupan proyek yang dilakukan adalah sebagai berikut :
1. Persiapan
   - Menyiapkan library yang akan digunakan pada proses analisis
   - Menyiapkan daya yang akan digunakan
2. Data Understanding
   - Melakukan pengecheckan data yang kosong (missing value)
   - Melakukan pengecheckan tipe data
   - Eksplorasi Data
3. Data Preprocessing
   - Train test split : membagi data latih dan data uji yang akan digunakan degnan rasio 90% data train dan 10% data test
   - Undersampling sample : menangani imbalance data dengan mengurangi jumlah data pada kelas mayoritas secara acak
   - Split X dan Y : menentukan feature yang akan digunakan untuk train data sebagai X dan Y sebagai target (status)
   - Standarizing & Label Encoder : melakukan encoding pada data categorical dan scaling pada data numerik
   - PCA : reduksi pada feature yang tidak berkolerasi linear
4. Modeling & Evaluation
   - Modeling : algoritma yang digunakan pada tahap modeling adalah Decision Tree dan Random Forest
   - Evaluation : akurasi pada model Decision Tree adalah sebesar 69% dan Random Forest sebesar 85% dengan menggunakan evaluasi confussion matrix.

### Persiapan

Sumber Data : https://raw.githubusercontent.com/dicodingacademy/dicoding_dataset/main/students_performance/data.csv

Setup Environment :
#### Library Installation
1. Pastikan python sudah terinstall dengan mengetik kode berikut pada Command Prompt
   ```
   python --version
   ```
2. Passtikan pip sudah terinstall dengan mengetik kode berikut pada Command Prompt
   ```
   pip --version
   ```
3. Install library yang digunakan pada proyek ini dengan mengetik kode berikut
   ```
   pip install requirements.txt
   ```
#### Running Streamlit
Untuk menjalankan prototype applikasi dapat mengetikkan kode berikut pada terminal
```
streamlit run prediction_app.py
```
## Business Dashboard
<div align="center">
   
![image](https://github.com/astriwidyastiti/Prediction/assets/112534966/bd587e9a-8dac-4886-af7a-0c02e561ce89)

</div>

Untuk mengakses dashboard di atas dapat melalui link berikut :
https://lookerstudio.google.com/reporting/8915d4aa-44f5-42b6-b052-e859dcdea030

Terdapat beberapa insight yang didapatkan berdasarkan dashboard yang dibuat, antara lain :
1. Jumlah siswa yang dinyatakan dropout sebanyak 1.421 orang
2. Nilai rata-rata siswa yang dinyatakan dropout adalah sebesar 124,96
3. Sebanyak 50,7% siswa yang dinyatakan dropout adalah perempuan
4. Nilai rata-rata GDP siswa yang dinyatakan dropout adalah -0.2, hal ini dapat menjadi asumsi jika siswa yang dinyatakan dropout memiliki nilai GDP yang kecil.
5. Siswa yang dinyatakan dropout paling banyak pada usia 18-19 tahun
6. Siswa yang melakukan metode aplikasi dengan kategori diatas 23 tahun paling banyak dinyatakan dropout
7. Terdapat korelasi antara addmision grade dan previous qualification grade dengan jumlah kurikulum yang diambil oleh siswa pada semester 1 dan 2

## Menjalankan Sistem Machine Learning





  
