# ***Genetic Alghoritm*** (Algoritma Genetika)
## **Algoritma Genetika**

Algoritma Genetika adalah salah satu algoritma evolutionary yang paling populer karena dapat digunakan untuk menyelesaikan banyak permasalahan yang berbeda.

Algoritma Genetika adalah algoritma berbasis populasi yang menggunakan **Seleksi**, ***Crossover*** (persilangan), dan **Mutasi** untuk membentuk populasi baru yang lebih baik.

Istilah lain yang digunakan dalam algoritma genetika: **Gen**, **Kromosom**, **Populasi**, **Fungsi Fitness**

## **Langkah-langkah Algoritma Genetika**
Langkah-langkah dari Algoritma Genetika adalah sebagai berikut:
1.  Membentuk **Kromosom** yang mempresentasikan solusi dari permaslahan yang dibahas.
2.  Mendefinisikan **Fungsi Fitness** yang digunakan untuk menentukan baik atau buruknya suatu kromosom.
3.  Membentuk **Populasi Awal** yang terdiri dari *n* kromosom.
4.  Menentukan peluang *crossover* (*Pc*), peluang mutasi (*Pm*), dan maksimum generasi (*N*).
5.  Melakukan **Seleksi** untuk memilih 2 kromosom dari populasi.
6.  Membentuk kromosom baru dengan melakukan ***Crossover*** pada kromosom yang terpilih dari seleksi.
7.  Lakukan **Mutasi** pada kromosom baru
8.  Ulangi langkah **5** - **7** sebanyak *n* kali (sesuai jumlah kromosom)
9.  Gabungkan semua kromosom (populasi awal, hasil *crossover*, dan hasil mutasi) yang ada dan pilih *n* kromosom terbaik (berdasarkan fitness) sebgai **Populasi Baru**
10. Ulangi langkah **5** - **9** sebanyak *N* kali (maksimum generasi)

## **Pseudocode Algoritma Genetika**
![Pseudocode](https://user-images.githubusercontent.com/49557695/121672831-76381400-cada-11eb-9641-a451b9c77559.png)

## **Contoh**
Untuk Traveling Salesman Problem :<br>
1 : [Click Here!](https://github.com/sandhiwr/Genetic-Alghoritm/blob/main/GeneticAlgorithmTSP1_Sandhi%20Wijaya%20Rosga_06111840000031.ipynb)<br>
2 : [Click Here!](https://github.com/sandhiwr/Genetic-Alghoritm/blob/main/GeneticAlgorithmTSP2_Sandhi%20Wijaya%20Rosga_06111840000031.ipynb)

Untuk Clustering :<br>
[Click Here!](https://github.com/sandhiwr/Genetic-Alghoritm/blob/main/Clustering.ipynb)

**Sekian dan Terimakasih** :+1:
