# PA_KB
<div align="center">
    <h1>PROYEK AKHIR<br><b>CLASSIFICATION OF CATS AND RABBITS</b><br><b>KECERDASAN BUATAN</b></h1><br>
    <div>
        <a>
            <img src="Image/unmul.png" height="150">
        </a>
        <div align="center">
            <p style="font-size: 18px;">
                Program Studi Informatika<br>
                Fakultas Teknik<br>
                Universitas Mulawarman
            </p>
        </div>
    </div>
</div>

<div align="center">
    <div>
        <p><h4>Disusun Oleh : </h4></p>
        <p><h4>Kelompok 8 Kelas A1 2021</h4></p>
        <div>
            <p><h3>
                Al Fiana Nur Priyanti 2109106022 (Ketua)<br>
                Shafira Octafia 2109106023
            </h3></p>
        </div>
    </div>
</div>
<br>

#### - Al Fiana Nur Priyanti / 2109106022
- Sebagai Ketua Kelompok dan mengatur Data Analisis & Visualization, Modeling, Evaluasi
#### - Shafira Octafia / 2109106023
- Bagian mengatur Data Collecting, Preprocessing, dan Prediksi

## 1. Penjelasan DataSet
Link Sumber Dataset Cat vs Rabbit berasal dari [kaggle](https://www.kaggle.com/datasets/muniryadi/cat-vs-rabbit)<br> 
Dataset yang telah displit terdapat pada folder "Cat vs Rabbit" <br>

Kumpulan data citra yang berisikan gambar kucing dan kelinci. Karena pada dataset aslinya sudah terbagi data train, data test, dan data validation. Kami menggabungkan data yang sudah terbagi tersebut menjadi satu sesuai dengan kelasnya. Lalu di split lagi dengan perbandingan 7:1:2.

## 2. Penjelasan Project
Pada projek akhir ini membahas mengenai model kecerdasan buatan dalam menentukan apakah benar hewan yang diprediksi itu termasuk kedalam klasifikasi hewan kucing atau kelinci.

## 3. Table of Content
•	IMPORT LIBRARY Yang Digunakan <br>

•	DATA COLLECTING <br>
-	Train <br>
-	Validation <br>
-	Test <br>
<br>

•	DATA PREPROCESSING <br>
-	Split Data <br>
-	Augmentasi Data <br>
<br>

•	DATA ANALISIS DAN VISUALISASI <br>
-	Shape Gambar <br>
-	Shape label <br>
-	Kelas Dalam Dataset <br>
-	Preview Image <br>
-	Visualisasi Jumlah Data Pada Setiap Kelas <br>
<br>

•	DATA MODELLING <br>
-	Arsitektur Model <br>
-	Callback <br>
-	Optimasi Model <br>
-	Fitting Training Model <br>
<br>

•	EVALUASI <br>
-	Evaluasi Loss dan Akurasi <br>
-	Visualisasi hasil train dan validation <br>
-	Prediksi <br>
<br>

•	SAVE MODEL <br>
