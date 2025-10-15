# Sistem Absensi Mahasiswa
**Pengaplikasian looping dan tipe data boolean ke dalam sistem absensi mahasiswa**

## Anggota Kelompok
- **Kevin Stevino Arnovan** (G1A025121)
- **Cantika Vania Azzahra** (G1A025065)  
- **AAnnisa Rohimah Sufriyani** (G1A025013)

---



---

## Daftar Isi
1. [Overview Sistem](#overview-sistem)
2. [Landasan Teori](#Landasan-Teori)
3. [Soal Dan Pembahasan](#Soal-Dan-Pembahasan)
4. [Teknik Preprocessing Data](#teknik-preprocessing-data)
5. [Strategi Evaluasi Model](#strategi-evaluasi-model)
6. [Struktur Project](#struktur-project)
7. [Instalasi dan Setup](#instalasi-dan-setup)
8. [Penggunaan Sistem](#penggunaan-sistem)
9. [Pengembangan Sistem Lanjutan](#pengembangan-sistem-lanjutan)

---

## Overview Sistem

### Cerita Sistem
Prodi Informatika ingin membuat sistem absensi digital untuk mencatat kehadiran mahasiswa pada setiap pertemuan. Sistem ini akan menyimpan data mahasiswa, mencatat hadir/tidak hadir, dan menampilkan rekap kehadiran. 

Maka dibuatlah Sistem absensi mahasiswa ini dengan bahasa pemograman Java. Menggunakan Looping,dan beberapa tipe data(String,Int,Boolean) Di buat dengan struktur program class Kelas,Class Mahasiswa,Dan Class Main Yang nantinya projek ini bisa untuk menginput jumlah pertemuan dan mahasiswa serta menentukan apakah mahasiswa lulus berdasarkan kehadiran ≥ 75%

**Penjelasan Teknis:**
Program ini merupakan sistem absensi digital sederhana berbasis Java Console Application.
Tujuannya adalah untuk mencatat kehadiran mahasiswa setiap pertemuan, menghitung persentase kehadiran, dan menampilkan rekap hasil akhir berupa status LULUS atau TIDAK LULUS berdasarkan tingkat kehadiran minimal 75%.

---

## Landasan Teori
Perkembangan  dalam  bidang teknologi  diera  modern  saat  ini  sudah  semakin pesat, banyak aspek kehidupan manusia yang berubah akibat berkembangnya teknologi saat   ini.   Penggunaan   alat-alat   berbasis   komputer   saat   ini   sudah   jauh   berbeda dibandingkan  tahun-tahun  sebelumnya,  alat  seperti  smartphone,  komputer,  laptop,  dll sekarang telah menjadi barang wajib yang dipakai untuk memanfaatkan teknologi yang ada saat ini. Dalam era saat ini pengumpulan data, pengolahan data dan juga untuk distribusi data mejadi peran kunci yang sangat dibutuhkan. 
	Pemrograman merupakan proses menulis, menguji, memperbaiki, serta memelihara kode yang membangun suatu program komputer. Program komputer adalah serangkain instruksi yang ditulis untuk melakukan suatu fungsi spesifik pada komputer. Pemrograman komputer adalah proses dari penyuntingan kode sehingga membentuk sebuah program. Penyuntingan kode meliputi proses pengetesan, analisis, pembetulan kesalahan, pengoptimasian algoritma, dan juga normalisasi kode. Java adalah salah satu Pemgrograman Berorientasi Obyek yang layak untuk dipelajari, karena Java mempunyai kemampuan dapat berjalan diberbagai platform dan memiliki fitur yang sesuai dengan kebutuhan para pengembang perangkat lunak serta bersifat open source. Java merupakan teknologi dimana teknologi tersebut mencakup Java sebagai Bahasa pemrograman yang memiliki sintaks dan aturan pemrograman tersendiri.  Oleh karena itu Java banyak dipakai untuk kepentingan pembelajaran khususnya dibidang informatika.
	Bahasa Java dikembangkan oleh Sun Microsystems yang saat ini telah diakuisisi oleh Oracle Corporation. Diciptakan oleh James Gosling dan timnya,  Java  awalnya dibuat  untuk  perangkat embedded, namun  segera  menjadi bahasa  yang  digunakan  di  banyak jenis  aplikasi.  Java dirancang agar mudah dipelajari, diimplementasikan, dan dirawat. Penggunaannya meluas karena Java memiliki kemampuan untuk dijalankan di berbagai perangkat dan platform tanpa harus diubah.  Java digunakan untuk membangun berbagai jenis aplikasi mulai dari aplikasi desktop, mobile, hingga enterprise. Namun, Java juga memiliki beberapa kelemahan seperti penggunaan memori yang tinggi dan GUI yang kurang menarik. Java adalah salah satu bahasa pemrograman yang sangat popular di dunia TI karena sifatnya yang platform-independen, aman, dan kuat dalam mendukung pengembangan aplikasi berbasis objek. 
	Tipe data array dalam Java adalah tipe data yang digunakan untuk menyimpan beberapa nilai dalam satu variabel, alih-alih mendeklarasikan variabel terpisah untuk setiap nilai. Array juga dapat diakses secara acak (random-access structure) karena semua elemen array dapat diacu secara acak dengan aturan tertentu, yaitu dengan mengetahui  nomor urutnya yang disebut degan indeks. Array merupakan salah bentuk struktur data. Array adalah sebuah variabel yang bisa menyimpan banyak data dalam satu variabel. Bentuk array yang paling sederhana adalah array satu dimensi yang didefinisikan sebagai himpunan terurut dari elemen homogen yang jumlahnya berbatas. Berbatas berarti bahwa jumlah elemen dalam suatu array sudah ditentukan. Terurut berarti bahwa elemen dalam suatu array disusun dengan cara tertentu sehingga ada elemen ke-0, ke-1, ke-2, dan seterusnya. Homogen berarti bahwa elemen dari suatu array harus memiliki tipe yang sama.
	Pada bahasa Java, String adalah tipe data dalam bahasa pemrograman yang digunakan untuk menyimpan dan memanipulasi teks, yang terdiri dari deretan karakter seperti huruf, angka, dan simbotipe data string dibuat menggunakan keyword String. Selain itu teks string ini harus berada di dalam tanda kutip dua ( " ). Tipe data integer adalah tipe data yang dipakai untuk menampung angka bulat positif maupun negatif, seperti: 4, 30, dan -1234. Bilangan ini juga mengenal nilai positif dan negatif (signed number). Tipe data boolean merupakan suatu tipe data yang dapat menyimpan true and false. Contohnya dapat menggunakan operator perbandingan , seperti operator lebih besar dari ( >), untuk mengetahui apakah suatu ekspresi (atau variabel) benar atau salah.
	Percabangan merupakan sebuah cara yang digunakan dalam program untuk mengambil suatu keputusan. Didalam pemrograman kita harus dapat menentukan aksi apa yang harus dikerjakan oleh pemroses (processor) ketika sebuah kondisi terpenuhi, dengan menggunakan operasi logic. Percabangan adalah suatu pilihan atau opsi dengan kondisi tertentu. Jika kondisi yang menjadi syarat terpenuhi, maka opsi atau pilihan akan dijalankan, jika tidak maka sebaliknya. Percabangan if digunakan jika kita hanya memiliki satu pernyataan yang akan dijalankan dengan syarat tertentu. Percabangan if-else digunakan saat kita memiliki dua pernyataan dengan syarat tertentu. Percangan else-if digunakan saat kita memiliki kondisi lebeih dari 2 dan pernyataan lebbih dari 2.
	For dalam Java adalah jenis perulangan yang jumlahnya sudah ditentukan sebelumnya. Perulangan dengan teknik ini dikontrol oleh tiga bagian yang ada dalam tanda kurung dan masing-masing bagaian ini dipisahkan dengan tanda titik koma. Perulangan (looping) pada Bahasa pemrograman Java adalah proses eksekusi perintah yang ada di dalam blok perulangan tersebut secara berulang-ulang sesuai dengan nilai yang ditentukan atau sampai mencapai suatu batas tertentu dari sebuah perulangan tersebut. Pernyataan while loop adalah pernyataan atau blok pernyataan yang diulang-ulang sampai mencapai kondisi yang cocok. Perulangan while adalah suatu bentuk perulangan yang memodifikasi teknik percabangan secara kasar. Pada perulangan do-while minimal melakukan satu kali pekerjaan yang ada di dalam blok while.

## Soal Dan Pembahasan



