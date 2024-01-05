# Logistic Regression

_Logistic Regression_ atau regresi logistik adalah algoritma _supervised mechine learning_ yang digunakan untuk klasifikasi dan bertujuan untuk memprediksi kemungkinan sesuatu termasuk ke dalam kelas tertentu atau tidak. _Logistic Regression_ digunakan terutama untuk klasifikasi biner dimana kita menggunakan fungsi logistik, atau biasa dikenal dengan fungsi sigmoid yang mengambil input sebagai variabel independen dan menghasilkan nilai probabilitas antara 0 dan 1. Misalnya, kita memiliki dua kelas. 0 dan Kelas 1 jika nilai fungsi logistik suatu input lebih besar dari 0,5 (nilai ambang batas) maka termasuk Kelas 1 termasuk Kelas 0. 

Disebut regresi karena merupakan perpanjangan dari regresi linier tetapi pada dasarnya digunakan untuk masalah klasifikasi. Perbedaan antara regresi linier dan regresi logistik adalah bahwa keluaran regresi linier adalah nilai kontinu yang dapat berupa apa saja, sedangkan regresi logistik memprediksi kemungkinan suatu instance termasuk dalam kelas tertentu atau tidak.

## Perbedaan _Logistic Regression_ dan _Linear Regression_
|No|Linear Regression|Logistic Regression|
|:---:|:-------------:|:-----------------:|
|1|Regresi linier digunakan untuk memprediksi variabel terikat kontinu dengan menggunakan sekumpulan variabel bebas tertentu.|Regresi logistik digunakan untuk memprediksi variabel dependen kategoris dengan menggunakan sekumpulan variabel independen tertentu.|
|2|Regresi linier digunakan untuk menyelesaikan masalah Regresi.|Ini digunakan untuk memecahkan masalah klasifikasi.|
|3|Memprediksi nilai variabel kontinu|Memprediksi nilai variabel kategori|
|4|Menemukan garis yang paling cocok.|Menemukan Kurva-S.|
|5|Metode estimasi kuadrat terkecil digunakan untuk memperkirakan akurasi.|Metode estimasi kemungkinan maksimum (_Maximum Likelihood_) digunakan untuk Estimasi akurasi.|
|6|Outputnya harus berupa nilai berkelanjutan, seperti harga, usia, dll.|Outputnya harus berupa nilai kategorikal seperti 0 atau 1, Ya atau tidak, dll|
|7|Untuk itu diperlukan hubungan linier antara variabel terikat dan bebas.|Tidak diperlukan hubungan linier.|
|8|Mungkin ada kolinearitas antara variabel independen.|Tidak boleh ada kolinearitas antar variabel independen.|