﻿<h1 align="center">Laporan Praktikum Modul 5 </h1>
<p align="center">Hajratun Nisa - IF 11-03 - 2311102203 </p>


SOAL 1

Program ini menghitung dan menampilkan deret Fibonacci hingga suku ke-n berdasarkan input pengguna. Dengan fungsi rekursif fibonacci, program menghitung nilai setiap suku dengan memanggil dua suku sebelumnya hingga mencapai nilai dasar (0 atau 1). Di fungsi main, pengguna diminta memasukkan angka n, lalu program mencetak deret Fibonacci mulai dari 0 hingga n dengan memanggil fungsi `fibonacci` untuk setiap suku. Contohnya, jika pengguna memasukkan n = 5, hasilnya adalah 0 1 1 2 3 5.


SOAL 2

Program ini mencetak pola bintang bertingkat dari satu hingga n bintang per baris, berdasarkan input pengguna. Menggunakan fungsi rekursif printStars, program pertama-tama memanggil dirinya sendiri dengan nilai n-1 hingga mencapai satu bintang, lalu mencetak bintang bertambah satu per baris hingga mencapai n bintang. Jika pengguna memasukkan n = 4, hasilnya adalah pola bertingkat seperti: *, **, ***, dan ****.


SOAL 3

Program ini bertujuan untuk menemukan dan mencetak semua faktor dari sebuah bilangan yang diinput oleh pengguna. Fungsi rekursif findFactors menerima dua parameter, yaitu number (bilangan yang dicari faktornya) dan divisor (pembagi). Fungsi ini akan memeriksa setiap angka dari 1 hingga number untuk menentukan apakah angka tersebut adalah faktor dari number. Jika number dapat dibagi habis oleh divisor, maka divisor dicetak sebagai faktor. Proses ini berlanjut dengan menambah divisor secara rekursif hingga mencapai nilai number. Contohnya, jika pengguna memasukkan num = 6, outputnya akan berupa: Faktor dari 6 adalah: 1 2 3 6.


SOAL 4

Program ini mencetak barisan angka yang dimulai dari n hingga 1, lalu kembali naik ke n. Fungsi printSequence pertama mencetak angka n, lalu memanggil dirinya sendiri dengan n-1 hingga mencapai 1, kemudian mencetak angka n lagi saat kembali ke angka yang lebih besar. Jika pengguna memasukkan n = 4, hasilnya adalah: 4 3 2 1 2 3 4.


SOAL 5

Program ini mencetak deretan bilangan ganjil dari 1 hingga n, di mana n adalah input dari pengguna. Jika pengguna memasukkan bilangan genap, program menguranginya 1 untuk memastikan deret dimulai dari bilangan ganjil terdekat di bawahnya. Fungsi rekursif printOddNumbers akan mencetak setiap bilangan ganjil dari 1 hingga n dengan memanggil dirinya sendiri menggunakan n-2, sehingga menampilkan angka-angka ganjil secara bertahap. Contoh, jika num = 7, hasilnya adalah: 1 3 5 7.


SOAL 6

Program ini menghitung pangkat dari bilangan x yang dipangkatkan dengan y menggunakan rekursi. Jika y adalah 0, hasilnya 1. Jika y positif, program mengalikan x dengan dirinya sendiri sebanyak y kali. Jika y negatif, program menghitung kebalikan dari pangkat positif. Misalnya, jika x = 2 dan y = 3, hasilnya adalah 2 pangkat 3 adalah 8.