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
4. [Kesimpulan](#Kesimpulan)
5. [Daftar Pustaka](#Daftar-Pustaka)
6. [Lampiran](#Lampiran)


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
- **STUDI KASUS 9: SISTEM ABSENSI MAHASISWA**

#### **Class Mahasiswa**
Atribut:
- nama (String), npm (String), absent (boolean)])
Method:
- Absensint pertemuan, boolean hadir)
Mengisi kehadiran berdasarkan pertemuan hitungKehadiran()
Menghitung jumlah pertemuan yang dihadiri get Persentase Kehadiran()
Menghitung persentase kehadiran (%)

![alt text](https://github.com/hakaishaaa28/UTS-PEMOGRAMAN-SISTEM-ABSENSI-UTS-19/blob/main/Class%20Mahasiswa.png?raw=true)
![alt text](https://github.com/hakaishaaa28/UTS-PEMOGRAMAN-SISTEM-ABSENSI-UTS-19/blob/main/Class%20Mahasiswa2.png?raw=true)

##### Source code:
    package uts;
    public class Mahasiswa {
    String nama;
    String npm;
    boolean[] absensi;
    public Mahasiswa(String nama, String npm, int jumlahPertemuan) {
        this.nama = nama;
        this.npm = npm;
        this.absensi = new boolean[jumlahPertemuan];
    }
    // isi absensi tiap pertemuan
    public void isiAbsensi(int pertemuan, boolean hadir) {
        absensi[pertemuan] = hadir;
    }
    //  total hadir
    public int hitungKehadiran() {
        int total = 0;
        for (boolean hadir : absensi) {
            if (hadir) total++;
        }
        return total;
    }

    // persentase kehadiran
    public double getPersentaseKehadiran() {
        return (double) hitungKehadiran() / absensi.length * 100;
     }
    }
##### **Penjelasan Source Code:**
Dari source code di atas dapat diketahui bahwa tipe classnya adalah public berarti bisa di akses dari file lain juga yang mana variable dalam class terdapat nama yang di simpan dalam bentuk string untuk menyimpan nama mahasiswa, npm yang disimpan dalam bentuk string untuk menyimpan nomor pokok mahasiswa dan absensi yang di simpan dalam bentuk array boolean, yang jika hadir akan jadi true dan jika tidak hadir akan jadi false.
Selanjutnya ada yang namanya konstruktor untuk menjalankan otomatis saat objeknya dibuat. this.nama = nama; untuk menyimpan nilai yang dimasukkan ke atribut nama, begitupun this.npm = npm; untuk menyimpan npm yang dimasukkan ke atribut npm. Untuk new boolean[jumlah pertemuan]; untuk membuat array absensi sesuai jumlah pertemuan. Pada method isi Absensi() digunakan untuk mengisi data hadir/tidak hadir berdasarkan pertemuan keberapa. Method hitung kehadiran digunakan untuk menghitung berapa kali mahasiswa hadir.
Looping akan memeriksa setiap nilai di absensi[ ], menambah total jika true. Method getPersentaseKehadiran() untuk menghitung persentase kehadiran dalam % dimana jumlah hadir dibagi jumlah kehadiran dan di kali 100.



##### **Class Kelas**
Atribut:
- namakelas (String), List<Mahasiswa daftar Mahasiswa
- Method:
- tambah Mahasiswa Mahasiswa m) Menambahkan mahasiswa ke dalam kelas.
tampilkan Rekap() Menampilkan daftar mahasiswa beserta kehadirannya dalam persentase.
![alt text](https://github.com/hakaishaaa28/SISTEM-ABSENSI-UTS/blob/main/Class%20Kelas.png?raw=true)
#### Source Code: 
    package uts;
    import java.util.ArrayList;
    import java.util.List;
    public class Kelas {
    String namaKelas;
    List<Mahasiswa> daftarMahasiswa;
    public Kelas(String namaKelas) {
        this.namaKelas = namaKelas;
        this.daftarMahasiswa = new ArrayList<>();
    }
    public void tambahMahasiswa(Mahasiswa m) {
        daftarMahasiswa.add(m);
    }

    // rekap seluruh mahasiswa
    public void tampilkanRekap() {
        System.out.println("\n===== REKAP ABSENSI KELAS " + namaKelas + " =====");
        System.out.printf("%-20s %-15s %-15s %-10s\n", "Nama", "NPM", "Persentase", "Status");
        System.out.println("-----------------------------------------------------------");

        for (Mahasiswa m : daftarMahasiswa) {
            double persen = m.getPersentaseKehadiran();
            String status = (persen >= 75) ? "Lulus" : "Tidak Lulus";

            System.out.printf("%-20s %-15s %-13.2f%% %-10s\n",
                    m.nama, m.npm, persen, status);
        }
     }
    }
##### **Penjelasan Source Code:**
Dari source code di atas dapat dilihat bahwa perlu import java untuk membuat list, dimana import. java. until. Arraylist; untuk menyimban banyak data mahasiswa dan import. java. until. list; untuk struktur data daftar. Di dalam public class Kelas namaKelas digunakan untuk menyimpan nama kelas dan daftarMahasiswa digunakan untuk menyimpan kumpulan objek Mahasiswa dalam bentuk list.
Pada kontruktor this.namaKelas = kelas; digunakan untuk menyimpan nama kelas ke atribut namaKelas. this.daftarMahasiswa = new ArrayList<> ( ): digunakan untukmembuat list kosong daftarMahasiswa agar siap menampung data mahasiswa baru. Pada Method tambahMahasiswa() berfungsi untuk menambahkan mahasiswa ke dalam daftar kelas. 
Method tampilkanRekap() untuk menampilkan rekap absen dalam bentuk tabel. Dimana System.out.println("\n===== REKAP ABSENSI KELAS " + namaKelas + " ====="); digunakan untuk menampilkan data dalam bentuk tabel rapi yang rapi. System.out.printf("%-20s %-15s %-15s %-10s\n", "Nama", "NPM", "Persentase", "Status"); printf digunakan untuk mencetak teks dengan format tertentu, seperti mengatur jarak, lebar kolom, atau jumlah angka di belakang koma agar tampilan output lebih rapi dan teratur. Format "%-20s %-15s %-15s %-10s" artinya tiap kolom punya lebar tetap dan teks rata kiri dan /n untuk menambah baris baru. for (Mahasiswa m : daftarMahasiswa) looping untuk menampilkan semua mahasiswa yang ada di kelas.
getPersentaseKehadiran() digunakan untuk memanggil method dari class Mahasiswa untuk menghitung persentase kehadiran. (persen >= 75) ? "Lulus" : "Tidak Lulus"; menunjukkan bentuk operator ternary yang artinya jika persentase ≥ 75 berarti lulus dan jika jika < 75 berarti tidak lulus

	

### **Class Main**
Input beberapa mahasiswa dan jumlah pertemuan
Gunakan looping untuk input kehadiran
Gunakan if-else untuk menentukan apakah mahasuwa lulus berdasarkan kehadiran 2 75%.
![alt text](https://github.com/hakaishaaa28/SISTEM-ABSENSI-UTS/blob/main/Assets/Class%20Main.png?raw=true)
![alt text](https://github.com/hakaishaaa28/UTS-PEMOGRAMAN-SISTEM-ABSENSI-UTS-19/blob/main/Class%20Main2.png?raw=true)
#### Source code:
    package uts;
    import java.util.Scanner;

    public class MAIN{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        // Input data kelas
        System.out.print("Masukkan nama kelas: ");
        String namaKelas = sc.nextLine();
        Kelas kelas = new Kelas(namaKelas);

        // Input jumlah pertemuan
        System.out.print("Masukkan jumlah pertemuan: ");
        int jumlahPertemuan = sc.nextInt();

        // Input jumlah mahasiswa
        System.out.print("Masukkan jumlah mahasiswa: ");
        int jumlahMahasiswa = sc.nextInt();
        sc.nextLine(); // bersihkan buffer

        // Looping untuk input mahasiswa dan absensinya
        for (int i = 0; i < jumlahMahasiswa; i++) {
            System.out.println("\nData Mahasiswa ke-" + (i + 1));
            System.out.print("Nama: ");
            String nama = sc.nextLine();

            System.out.print("NPM: ");
            String npm = sc.nextLine();

            Mahasiswa m = new Mahasiswa(nama, npm, jumlahPertemuan);

            // Input absensi per pertemuan
            for (int j = 0; j < jumlahPertemuan; j++) {
                System.out.print("Pertemuan ke-" + (j + 1) + " (hadir? true/false): ");
                boolean hadir = sc.nextBoolean();
                m.isiAbsensi(j, hadir);
            }
            sc.nextLine(); // clear buffer setelah input boolean

            // Tambah mahasiswa ke kelas
            kelas.tambahMahasiswa(m);
        }

        // Tampilkan rekap hasil akhir
        kelas.tampilkanRekap();
        sc.close();
     }
    }

##### **Penjelasan Source Code:**
Melalui source code diatas dapat diketahui bahwa tipe classnya public yang dimana dapat di akses dari file yang lain. Source code ini juga menggunakan Scanner sebagai kelas yang digunakan untuk mengurai tipe primitif. Pada code ini juga menggunakan String untuk menyimpan nama kelas. Tipe data String sendiri merupakan kumpulan karakter yang digunakan untuk membentuk urutan tertentu. Di dalam source code tersebut juga menginput jumlah pertemuan dengan menggunaka tipe data Int. Int sendiri adalah tipe data primitif yang sering digunakan saat melakukan perhitungan numerik dalam program,dan dengan menggunakan tipe data int memungkinkan pemrosesan yang efisien dalam hal memori dan kecepatan. Untuk menjalankan sebuah code ini, juga menggunakan Looping sebagai salah satu konsep fundamental dalam pemrograman yang digunakan untuk menjalankan serangkaian perintah atau kode secara berulang hingga kondisi tertentu terpenuh. Dengan adanya Looping, kita dapat menentukan Nama, NPM, dan juga jumlah pertemuan mahasiswa.
	Tipe data boolean dalam source code ini, digunakan untuk menentukan sebuah true or false dari inputan absen mahasiswa. Jika true, dia akan memberikan sebuah output hadir didalam nama mahasiswa tersebut. Dalam Scanner, jika kita menggunakan tipe data String maka kita akan menggunakan nextLine(); dan jika tipe datanya Int ataupun angka maka kita akan menggunakan nextInt();. Jika ingin menutup Scanner yang membaca dari System.in, kita harus menggunakan sc.close();.

	

#### **Output**
![alt text](https://github.com/hakaishaaa28/SISTEM-ABSENSI-UTS/blob/main/Assets/Output.png?raw=true)

##### Penjelasan Output:
Dari semua souce code dari ketiga file yang sudah dibuat mulai dari file class mahasiswa, class kelas, dan class MAIN maka akan didapatkan output seperti poda gambar 1.5 di atas, dimana awalnya akan di cetak nama kelas, jumlah pertemuan, dan jumlah mahasiswa yang semuanya diketik atau dimasukkan oleh pengguna saat menjalankan program, barulah memasukkan semua data mahasiswa yang jumlahnya akan ada 3 orang karena dari data awal yang dimasukkan jumalah mahasiswanya ada 3 orang. Setelah itu masukkan nama, NPM, dan kehadiran setiap mahasiswa dalam 5 kali pertemuan seperti yang sudah dicantumkan sebelumnya. Barulah di akhir akan muncul tabel yang berisi rekap absensi dari semua mahasiswa dari source code yang sebelumnnya dimasukkan.

## Kesimpulan
Kesimpulan dari proyek pembuatan **sistem absensi digital** ini adalah bahwa program yang dirancang mampu membantu Prodi Informatika dalam mengelola data kehadiran mahasiswa secara efisien dan terstruktur. Dengan memanfaatkan konsep **pemrograman berorientasi objek (OOP)**, sistem ini membagi fungsi ke dalam beberapa kelas, yaitu *Mahasiswa*, *Kelas*, dan *Main*, sehingga kode menjadi lebih mudah dipahami dan dikembangkan. Kelas *Mahasiswa* bertanggung jawab menyimpan identitas dan status kehadiran setiap mahasiswa, sedangkan kelas *Kelas* berfungsi untuk mengelola daftar mahasiswa dan menampilkan rekapitulasi kehadiran secara keseluruhan. Melalui kelas *Main*, pengguna dapat melakukan input data, mencatat kehadiran tiap pertemuan, serta menentukan kelulusan mahasiswa berdasarkan persentase kehadiran minimal 75%. Dengan demikian, sistem ini tidak hanya mempermudah proses pencatatan kehadiran tetapi juga meningkatkan akurasi dan efisiensi dalam evaluasi kehadiran mahasiswa secara digital.

## Daftar Pustaka
Hannan. (2013). *Pengertian pemrograman.*

Muhammad, M., & Muhammad, R. (2021). *Makalah perulangan Java.*

Sekreningsih, N. (2021). *Job sheet pemrograman berorientasi objek with "Java"*.

Suryana, T. (2019). *Percabangan dalam JavaScript.*



## Lampiran
![alt text](https://github.com/hakaishaaa28/SISTEM-ABSENSI-UTS/blob/main/Lampiran2.png?raw=true)
![alt text](https://github.com/hakaishaaa28/SISTEM-ABSENSI-UTS/blob/main/Lampiran3.png?raw=true)
![alt text](https://github.com/hakaishaaa28/SISTEM-ABSENSI-UTS/blob/main/lampiran1.png?raw=true)









