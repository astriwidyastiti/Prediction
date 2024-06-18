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
  
