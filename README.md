### Tugas_Pertemuan_11_ANN

##### Nama : Rahmatul Idami

##### NPM : 2108107010071

<br>

#### Materi Pertemuan 11

- https://www.megabagus.id/deep-learning-artificial-neural-networks/ (halaman 1 - 7)
- ⁠⁠https://www.megabagus.id/deep-learning-artificial-neural-networks-aplikasi (halaman 1 - 4)

dari kedua artikel tersebut maka dikerjakan:

- Contoh pada artikel kedua menggunakan tensorflow pada python environment
- ⁠Tugas 2 sebelumnya menggunakan SVM, kerjakan dengan menggunakan ANN pada python environment yang sama


#### [Repository ini](https://github.com/rahmatulidami/2108107010071_Pertemuan_11_ANN) berisi:

- Dataset sebelum dipreprocessing (format csv) yang ada pada folder Dataset
- ⁠Kode python yang memuat process preprocessing, training, testing dan perhitungan akurasi
- ⁠File requirements.txt yang berisi library yang digunakan
- ⁠File README.md yang berisi penjelasan tentang kedua tugas yang dikerjakan beserta perbandingan akurasi SVM dan ANN

### DATASET

Dataset yang digunakan ada 2 yaitu :

- Dataset untuk SVM Klasifikasi (SVC)
  Dataset yang digunakan yaitu dataset yang diambil dari kaggle tentang Heart Attack Analysis & Prediction Dataset yang memiliki 13 fitur dan 1 label dengan banyak datanya adalah 303 data.

  link dataset nya: https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

  <br>

- Dataset untuk SVM Regresi (SVR)
  Dataset yang saya pakai adalah dataset tentang Data transaksi apartemen yang dihasilkan dari Agustus 2007 - Agustus 2017 di Daebong, kota Daegu, Korea Selatan. Dataset ini terdiri dari 30 fitur dan 5891 data.

  Dataset yang digunakan diambil dari kaggle, berikut link dataset nya: https://www.kaggle.com/datasets/gunhee/koreahousedata

### Langkah menjalankan repository ini
Install semua library yang ada dalam file requirements.txt. Dengan menjalankan di terminal: ```pip install -r requirements.txt```

### PERBANDINGAN AKURASI SVM DAN ANN
- Hasil akurasi untuk pengujian model  SVM klasifikasi adalah 0.70 sedangkan ANN Klasifikasi akurasinya adalah 0.85
  <br> Berikut hasilnya:
  ![SVM Klasifikasi](https://drive.google.com/uc?export=view&id=1TugA-upIZIyiUtHG-1LOIKI3VOsI0JxB)
  SVM Klasifikasi
  
  ![ANN Klasifikasi](https://drive.google.com/uc?export=view&id=1_RikpuASbAMRi7xCCyb8OgU3L66qJfrV)
ANN Klasifikasi
  

- Hasil MSE ntuk pengujian model SVM regresi adalah 11023728849.599525 sedangkan ANN regresi MSE yaitu 2760456905.482738
    <br> Berikut hasilnya:
  ![SVM Regresi](https://drive.google.com/uc?export=view&id=1nPbt9rCeCbz6CNvRMQYv_8qSLgaRAY5B)
SVM Regresi

  ![ANN Regresi](https://drive.google.com/uc?export=view&id=1EMAahHcZ5zl89e8m3969UgPP25fYn-Mh)
ANN Regresi

Untuk kode model SVM dapat di liat di [Repository ini](https://github.com/rahmatulidami/2108107010071-Pembelajaran-mesin)
