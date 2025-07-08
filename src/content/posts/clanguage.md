---
title: Learn C language
published: 2024-06-13
description: '[indonesian] Belajar bahasa pemrograman C dari dasar dasarnya'
image: 'https://wallpapercave.com/wp/wp2825120.jpg'
tags: ['C language']
category: 'Programming'
draft: false
lang: 'en'
---

:::note
Jika anda pemula, ingin belajar pemerograman, maka materi bacaan ini bisa menjadi referensi untuk belajar bahasa pemrograman C. Maka dari itu, semangat yaa!
:::
:::tip
If you want to use English or another language, please use the translation feature in your browser.
:::

---

Click tombol dibawah ini jika sudah membaca pengenalan.  
**Lihat apa yang konten ini sajikan** [Daftar isi](#apa-saja-yang-harus-dipelajari-dalam-bahasa-c).  

# A letter from author
![gif](https://media.tenor.com/1Ygfg3W4V2cAAAAM/akane-kurokawa-kurokawa-akane.gif)
Halo semuanya, saya Axel-- penulis dari blog ini. Saya disini berniat menuangkan kembali ilmu yang saya telah pelajari dari bahasa pemerograman C, murni dari pengalaman saya. Alasan kenapa saya menuliskan blog ini secara khusus adalah untuk membantu kamu yang baru mau terjun di dunia pemrograman... karena saya tau betapa sulitnya belajar otodidak dari sumber yang gak jelas, penjelasan yang bertele-tele, dan tidak ada contoh yang nyata.  
Maka dari itu saya bakal jelaskan dengan cara yang gampang dipahami anak smp sekalipun.  

Sebelum kamu belajar pemerograman, kamu harus tau alasan kenapa tertarik pada pemerograman -- coba baca [Manfaat coding](https://luminarysirx.my.id/posts/whylearncoding/).  
Serta harus tau masing masing kegunaan tombol-tombol dalam [keyboard](https://luminarysirx.my.id/posts/keyboard/).  

Disekolah selama ini mungkin hanya di ajarkan mata pelajaran formal saja, tidak ada tempat yang mengajarkan keahlian bagaimana cara membangun teknologi, bagaimana cara mengetahui cara kerja dari beberapa teknologi yang kita gunakan selama ini.
Dan baru pertama kalinya mungkin kamu merasa bingung sekaligus aneh lihat konsep baru yang kedengaran rumit sebagai orang yang masih awam~ padahal gampang banget.  
> "Semua yang anda kira sulit, sebenarnya akan mudah jika tau caranya" -- Dr. Norman Ramsey.  

Okelah saya cukupkan sampai disini aja, selamat belajar -- santai aja bacanya.  
semoga anda bisa fasih pemerograman C dalam waktu 1-2 bulan saja.
![gif](https://media.tenor.com/L3ZGtEmZvncAAAAm/kokomi-dizzy.webp)

## Pengenalan: Apa itu Pemerograman Bahasa C?
Pemerograman adalah suatu cara bagaimana manusia bisa memerintah mesin komputasi (komputer bukan cuma laptop dan pc loh yaa!) melakukan tugas tertentu untuk mempermudah kebutuhan sehari-hari yang berkaitan erat dengan teknologi yang kita gunakan seperti misalnya Handphone, laptop, mesin manufaktur, robot, dan lainnya. -- dalam bentuk kode program yang menjadi rangkaian alur sistematis tentang apa yang harus dikerjakan komputer.  
Intinya ilmu pemerograman itu untuk membuat sebuah software atau yang kita kenal aplikasi, -- ingat itu.

Bahasa C adalah bahasa pemrograman yang dikembangkan pada tahun 1972 oleh Dennis Ritchie di Bell Labs. Bahasa ini dirancang untuk sistem operasi Unix(OS perangkat komputer zaman dulu) dan menjadi salah satu bahasa pemrograman yang paling populer dan berpengaruh dalam sejarah pengembangan perangkat lunak. 

## Apa yang bisa dipelajari dari bahasa C?
Bahasa C memiliki banyak kelebihan, seperti: 
- **Portabilitas**: Kode yang ditulis dalam bahasa C dapat dijalankan di berbagai platform tanpa perlu banyak perubahan.
- **Efisiensi**: Bahasa C menghasilkan kode yang sangat efisien dan cepat, sehingga cocok untuk pengembangan sistem operasi, perangkat keras, dan aplikasi yang membutuhkan performa tinggi.
- **Kontrol yang Tinggi**: Bahasa C memberikan kontrol yang tinggi terhadap memori dan sumber daya sistem, memungkinkan pengembang untuk mengoptimalkan kinerja aplikasi.
- **Struktur yang Jelas**: Bahasa C memiliki struktur yang jelas dan mudah dipahami, sehingga cocok untuk pemula yang ingin belajar pemrograman.
- **Komunitas yang Besar**: Bahasa C memiliki komunitas yang besar dan aktif, sehingga banyak sumber daya, tutorial, dan forum yang tersedia untuk membantu pemula belajar.
- **Aplikasi yang Banyak**: Bahasa C digunakan dalam pengembangan aplikasi-aplikasi tingkat tinggi, seperti sistem operasi, perangkat lunak, dan game.

---
![coding icon](https://images.unsplash.com/photo-1610360655260-decd32e267aa?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1yZWxhdGVkfDg0fHx8ZW58MHx8fHx8)
## Kenapa disarankan belajar bahasa C?
Jika niatmu memang mau terjun di dunia pemerograman, maka ini adalah langkah awal yang tepat. Bahasa C adalah bahasa pemrograman yang paling dasar dan banyak digunakan dalam dunia pemrograman. Bahasa ini sangat penting untuk memahami konsep-konsep pemrograman lainnya, seperti bahasa pemrograman lain seperti C++, Java, dan Python.

## Bagaimana cara belajar bahasa pemrograman C?
Untuk belajar bahasa pemrograman C, kamu bisa mengikuti langkah-langkah berikut:
1. Menyiapkan lingkungan pengembangan, anggaplah kode editor yang ada di komputer
2. Memahami konsep dasar pemrograman
3. Menulis kode
4. Menjalankan kode
5. Mengulang langkah-langkah tersebut sampai mahir serta terbiasa.

### Sebelum memulai menulis kode, ada yang perlu disiapkan... 
Hal pertama yang perlu kamu siapkan pada device komputer atau gadget lainnya; adalah code editor / text editor.  
Gunanya untuk mengotak atik baris kode yang akan dituliskan nantinya.  
Untuk belajar bahasa C, disarankan menggunakan code editor yang sederhana. Ada banyak code editor yang bisa kamu gunakan, namun disini saya sarankan untuk menggunakan Dev C++. Atau pun juga ada Visual Studio Code adalah code editor yang banyak digunakan oleh para developer -- silahkan pilih sesuka hati pakai yang mana.  
**A. Link download software kode editor** [dev C](https://sourceforge.net/projects/dev-cpp/files/Binaries/Dev-C%2B%2B%204.9.9.2/devcpp-4.9.9.2_setup.exe/download).  
Nah sekalian setelah download, coba tonton tutorial pemakaian aplikasinya.  
<iframe width="560" height="315" src="https://www.youtube.com/embed/ut-M21Unhuo?si=kkjl6BWvY47ryoST" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**B. Link download software Visual Studio Code** [VSCode](https://code.visualstudio.com/download).  
Nah sekalian setelah download, coba tonton tutorial pemakaian aplikasinya.  
<iframe width="560" height="315" src="https://www.youtube.com/embed/9563Y0kxxzM?si=pS5_A98YhjbDc3-w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Apa saja yang harus dipelajari dalam bahasa C?
Oh iya.. ini juga sebagai daftar isi dari apa yang bakal kita bahas.  
Untuk mempelajari bahasa C, berikut adalah beberapa konsep dasar yang perlu dipahami:
- [**Sintaks Dasar**](#konseptual-dasar-bahasa-pemerograman-c): Memahami cara penulisan kode, seperti penggunaan tanda kurung, titik koma, dan struktur program.
- [**Tipe Data dan Variabel**](#tipe-data-dan-variabel): Memahami tipe data dasar seperti integer, float, char, dan lainnya.
- [**Input output dan contoh penggunaannya**](#input-output-dan-contoh-penggunaannya): Memahami cara membuat perintah input dan output.
- [**Konstanta**](#konstanta): Memahami cara mendeklarasikan variabel dan konstanta, serta cara menggunakannya dalam kode.
- [**Operator**](#operator): Memahami operator-operator yang digunakan dalam pemrograman, seperti operator aritmatika, operator relasional, dan operator logika.
- [**Struktur Kontrol**](#struktur-kontrol): Memahami cara menggunakan struktur kontrol yang akan mengatur alur sistem bekerja.
    - [**Percabangan**](#percabangan): Memahami cara membuat keputusan program berdasarkan kondisi tertentu. (if-else, switch case).
    - [**Perulangan**](#perulangan): Memahami cara menggunakan perulangan untuk menjalankan blok kode secara berulang. (for, while, do-while).
- **Fungsi**: Memahami cara mendeklarasikan dan menggunakan fungsi untuk memecah kode menjadi bagian-bagian yang lebih kecil dan terorganisir.
- **Struktur Data**: Memahami struktur data seperti array, linked list, tree, dan graph.
    - **Array**: Memahami cara menggunakan array untuk menyimpan kumpulan data dengan tipe yang sama.
    - **Linked List**: Memahami cara kerja linked list dan bagaimana menggunakan pointer untuk mengakses dan mengelola data.
    - **Tree**: Memahami konsep tree dan bagaimana menggunakan struktur tree dalam pemrograman.
    - **Graph**: Memahami konsep graph dan bagaimana menggunakan struktur graph dalam pemrograman.
- **Pemrosesan File**: Memahami cara membaca dan menulis file.
- **Pointer**: Memahami konsep pointer dan bagaimana menggunakannya untuk mengakses memori secara langsung.
- **Alokasi Memori**: Memahami alokasi memori dinamis menggunakan `malloc` dan `free`.
- **Penggunaan Library**: Memahami cara menggunakan library yang sudah ada untuk mempermudah pengembangan.

## Apa saja yang harus dipersiapkan untuk belajar bahasa C?
Untuk belajar bahasa C, berikut adalah beberapa hal yang perlu dipersiapkan:
- **Lingkungan Pengembangan**: Siapkan lingkungan pengembangan seperti IDE (Integrated Development Environment) atau teks editor yang mendukung bahasa C, seperti Code::Blocks, Visual Studio Code, atau Dev-C++.
- **Kompiler**: Pastikan kamu memiliki kompiler C yang terpasang di komputermu, seperti GCC (GNU Compiler Collection) atau Clang.
- **Buku atau Sumber Belajar**: Cari buku atau sumber belajar online yang membahas bahasa C secara mendalam, seperti tutorial, video, atau kursus online.
- **Proyek Praktis**: Siapkan proyek praktis yang bisa kamu kerjakan untuk menerapkan konsep-konsep yang telah dipelajari, seperti membuat program sederhana, kalkulator, atau permainan kecil.
- **Komunitas dan Dukungan**: Bergabunglah dengan komunitas online yang aktif di bidang pemrograman C, seperti Stack Overflow, Reddit, atau Discord, untuk mendapatkan bantuan dan dukungan dari pengembang lain.

oke! saya cukupkan pendahuluannya sekian saja..  
Next kita bahas konsep dasar bahasa C.

---

![coding icon](https://images.unsplash.com/photo-1607705703571-c5a8695f18f6?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NjJ8fHByb2dyYW1tZXJ8ZW58MHx8MHx8fDA%3D)
# Konseptual dasar bahasa pemerograman C
Disini akan saya coba kenalkan beberapa konsep yang perlu kamu mengerti untuk membuat sebuah perintah di program C beserta penjelasannya.  

Mulai sekarang dan selanjutnya selama belajar pemerograman C, kita akan sering berinteraksi dengan media CLI (Command line interface) atau disebut juga sebagai Terminal (semacam media input output program sederhana dengan antarmuka/tampilan 2d dalam bentuk teks saja) biasanya dia akan terbuka jika kode program di eksekusi. -- contohnya kayak gini:
![img](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/52881909218_15f72bb07c_o.jpg)
Kalau dari sudut pandang code editor, kira-kira bakal seperti ini bagian ngoding-nya:  
![gif](https://code.visualstudio.com/assets/updates/1_97/nes-arrow-directions.gif)
Oke cukup begitu saja gambaran awal sebelum mulai belajar..  

---

# Fondasi awal dari segalanya...
## Struktur Program C
Struktur kode itu seperti serangkaian aturan yang harus dipatuhi agar program yang kamu buat bisa dijalankan.  
Struktur kode itu tidak bisa diubah-ubah secara ngawur.. Ibaratnya seperti aturan saat membuat puisi atau pantun tergantung jenisnya sih.. Gunanya supaya menjaga keindahan dan kerapihan dari kode itu sendiri.

Lihat bagaimana penulisan awal struktur program..  
sebelum menulis perintah~  
(Perintah dianggap juga sebagai Syntax-- Aturan-aturan yang mengatur bagaimana kode harus ditulis agar dapat dipahami oleh komputer... Dengan kata lain Syntax merupakan aturan tata bahasa yang digunakan untuk menulis perintah tersebut agar dapat dipahami oleh komputer).
```c
#include <stdio.h>
int main() {
    //your code...
    return 0;
}
```
penjelasan:
1. `#include <stdio.h>`: adalah bagian kepala atau yang disebut header yang gunanya untuk memasukkan library `stdio.h`, yang berisi fungsi-fungsi sebuah formula untuk input output.
2. `int main()`: adalah fungsi utama dari program C, di mana kode program akan dijalankan.
3. `//your code...`: adalah komentar, tidak akan di eksekusi mesin, jadi hanya sebagai pesan saja yang mendeskripsikan tentang kode ini untuk apa pada programmer.  
di dalam `{}` inilah kamu bisa menuliskan perintah yang di inginkan.
4. `return 0;`: untuk menghentikan program ketika selesai eksekusi dan mengembalikan nilai 0.  
opsional tapi lebih baik ditulis saja yaa.

:::warning[PERINGATAN TERKAIT SELURUH MATERI UNTUK KEDEPANNYA JUGA]
- Khusus untuk kamu sebagai pemula, selalu ingat ini... Dalam setiap hendak membuat program C, Pastikan pembuatan file nya benar seperti `pertama-belajar.c` Pastikan ekstensi di akhirnya adalah `.c`, bukan `.txt .cpp .js etc.`. Ada beberapa rules yang harus di ingat:
    - Nama file harus sama dengan kegunaannya begitupula dengan variabel, jangan gaje -- contoh baik:`kalkulator.c`.
    - Perhatikan huruf besar dan kecilnya baik dari file ataupun kode program yang kamu buat nantinya.
    - Dalam penamaan **file** dan **variabel** tidak boleh pakai `spasi` dan karakter aneh `@#%$ !*&.c`.
    sebagai gantinya kalau diperlukan pemisah sebagai jarak penamaan, gunakan `_` (underscore) contoh: `pertama_belajar.c` atau `-` (Dash/strip) contoh: `first-time.c`
- Ketika kamu membuat program C, kamu harus menambahkan `#include <library>`  dan itu wajib beserta struktur programmya.  
- ketika kamu menjumpai error, coba analisis kode kamu tulis apakah ada typo atau kurang penggunaan
simbol wajib seperti `(){}[]:` dan `;`
- setiap kode yang kamu ciptakan, Wajib diberi tanda `;` sebagai bagian akhirnya. (misal: `printf("hallo!");`)
- disarankan ngasih komentar sebagai dokumentasi ringkas dari kutipan sebuah kode.. yaa seperti yang saya lakukan supaya pembaca tidak bingung ini kode apaan🤔..  beberapa bentuk komentar seperti `//blablabla..` dan `/*blablabla..*/`.  
juga sebuah komentar gak akan di eksekusi mesin, jadi aman aja untuk dituliskan.
- ketika kamu membuat sebuah perintah maka letakkan di dalam fungsi `main()`.  
kecuali jika membuat sebuah function, maka boleh saja letakkan di luar fungsi `main()` *nanti dibahas.
:::

## Tipe Data dan Variabel
Biar saya jelaskan sedikit, Setiap komputer itu butuh tipe data... Lalu apa itu tipe data? menurut saya itu adalah semacam Aneka dari jenis informasi yang bisa komputer olah. Contohnya aplikasi kalkulator standar deh, itu butuh data numerik.. bukan abjad untuk di proses perhitungannya, yaa mungkin beda lagi kalau ada kalkulator sains.  
Setiap informasi itu pasti punya jenis yang berbeda: ada yang angka, huruf, simbol, dan lainnya.  
contoh lagi kalau kamu punya akun sosial media.. pasti harus input username dan password, itu umumnya pakai tipe data karakter(username) dan angka(password) untuk diproses sistem, bahkan macam-macam tipe data bisa digabung penggunaannya untuk keunikan. jadii...

***Tipe data*** adalah jenis data yang bisa digunakan dalam program.  
Tipe data ini akan mempengaruhi bagaimana data akan disimpan dan diolah oleh komputer.  


***Variabel*** adalah tempat penyimpanan nilai yang dapat berubah-ubah.  
ibaratnya seperti ember yang bisa diisi dengan air, di mana air itu adalah nilai yang akan disimpan.
```c
// tipe data primitif

int a; // tipe data integer ~ menyimpan bilangan bulat 12345...
float b; // tipe data float ~ menyimpan bilangan desimal 3.14...
double c; // tipe data double ~ menyimpan bilangan desimal dengan banyak digit 123.456789...
char d; // tipe data karakter ~ menyimpan karakter 'a', 'b', 'c', '1', '2', '3', ...
        // serta menyimpan macam-macam simbol seperti '@$#!^&%*()<>?/|\'

/*cara pengisian nilai*/

int a = 10; // diberi nilai
int b; // nilai kosong
```
:::tip
cara serupa diatas juga diterapkan pada tipe data lainnya.
:::
:::note
tipe data primitif adalah tipe data yang paling umum digunakan.
- `int` adalah tipe data integer yang menyimpan bilangan bulat.
- `float` adalah tipe data yang menyimpan bilangan desimal dengan presisi sedang.
- `double` adalah tipe data yang menyimpan bilangan desimal dengan presisi tinggi.
- `char` adalah tipe data yang menyimpan karakter tunggal.
:::
untuk mendeklarasikan tipe data beserta variabel ingat cara berikut:  
`<ruas kiri> <tengah> = <nilai(opsional)>;`  
ruas kiri adalah tipe data, ruas tengah adalah nama variabel, dan `=` adalah operator untuk mengisi nilainya.
Note: penamaan variabel bebas kok ngasihnya contoh `int skibidi`.

### Konstanta 
Kalau tadi variabel itu bisa dimanipulasi nilainya.. kalau konstanta tidak bisa.  
Mirip seperti konsep di matematika yang menggunakan konstanta sebagai nilai tetap.  
contohnya adalah `pi = 3.14`.

```c title="how to use constanta"
const float phi = 10;
// phi tidak bisa diubah nilainya
// biasanya diletakkan dalam fungsi main
------------------------------------
// alternative
#define n = 10;
//biasanya diletakkan diluar fungsi main
/*
Perhatikan bahwa konstanta yang didefinisikan dengan #define tidak memiliki tipe data, dan penggantian nilai dilakukan secara harfiah.
*/
```
:::note
- `const` adalah keyword yang digunakan untuk mendeklarasikan konstanta.
- `#define` adalah preprocessor directive yang digunakan untuk mendefinisikan konstanta.
- Konstanta biasanya digunakan untuk nilai-nilai yang tidak akan berubah selama program berjalan, seperti nilai pi, euler, atau nilai tetap lainnya.
- Konstanta tidak bisa di deklarasikan di dalam function.
- Konstanta biasanya diletakkan di luar fungsi `main()` untuk memudahkan akses dan penggunaan di seluruh program.
:::
:::warning[SUPER WARNING]
- *Setiap pen-deklarasian _varibel_, _konstanta_ ataupun sebuah _fungsi_ Ada yang namanya ***Case Sensitive***, yaitu dimana huruf besar dan kecil akan dianggap berbeda.  Contohnya: `int Angka` dan `int angka` kedua variabel tersebut adalah entitas berbeda meskipun beda satu huruf saja.  
hal ini pun berlaku pada pembuatan sintaks lain, seperti kata kunci `int`, `char`, `float`, `if`, `else`, `printf`, dll --pun juga harus dituliskan dalam huruf **kecil**. Bahkan kamu memberikan nama pada file pun tidak boleh sama persis, harus unik setidaknya; seperti `contoh.txt` dan `Contoh.txt`.
- const memungkinkan deklarasi konstanta dengan tipe data tertentu, sedangkan #define tidak.
- Konstanta yang didefinisikan dengan const akan muncul dalam informasi debugging, sedangkan konstanta #define tidak.
- const dapat memiliki scope lokal (dalam blok fungsi atau kode), sedangkan #define biasanya bersifat global.
:::

---

## Input output dan contoh penggunaannya
Secara harfiah, input artinya nilai masukkan (maksudnya nilai yang kamu berikan)  
sedangkan output adalah nilai yang dikeluarkan setelah diproses oleh program.
```c
// output
printf("Hello World!"); // output Hello World!

// input
char a;
scanf("%c", &a);

// output program
printf("Your input successful to process! \n");
printf("This is the output: %c", a); // this is the output : blabla...from input
```
:::note
- `printf` adalah sebuah perintah yang mencetak nilai ke layar, biasanya ada di terminal.
- `scanf` adalah sebuah perintah yang menerima input dari user.
- `%c` adalah format spesifier untuk karakter, yang digunakan dalam `scanf` untuk membaca input karakter.
- `%d` adalah format spesifier untuk integer, yang digunakan dalam `scanf` untuk membaca input bilangan bulat.
- `%f` adalah format spesifier untuk float, yang digunakan dalam `scanf` untuk membaca input bilangan desimal.
- `%lf` adalah format spesifier untuk double, yang digunakan dalam `scanf` untuk membaca input bilangan desimal dengan presisi tinggi.
- `%s` adalah format spesifier untuk string, yang digunakan dalam `scanf` untuk membaca input string.
- `&` adalah operator yang digunakan untuk mengambil alamat dari variabel, sehingga `scanf` dapat menyimpan nilai input ke dalam variabel tersebut.
:::
:::tip
Beberapa typografi supaya penulisan output lebih rapih dan indah:
- `\n` adalah karakter typografi yang digunakan untuk membuat baris baru.
- `\t` adalah karakter typografi yang digunakan untuk membuat tab.
- `\\` adalah karakter typografi yang digunakan untuk membuat backslash.
- `\"` adalah karakter typografi yang digunakan untuk membuat tanda kutip.
- `\'` adalah karakter typografi yang digunakan untuk membuat tanda kutip tunggal.
:::

:::important
Sampai sini dulu...  
Silahkan experiment dengan menggunakan `printf` dan `scanf` serta penggunaan berbagai variabel untuk memahami cara kerjanya. ini penting untuk anda ketahui.
silahkan coba di text editor sendiri atau online compiler di bawah ini 👇  
[built-in online compiler](#online-compiler)
  kemudian lihat eksekusi programmnya apakah jalan atau error.  
  Note: Jika program yang error.. itu terkadang dari kesalahan anda sendiri seperti penulisan sintaks yang salah, makanya coba intropeksi apa yang salah dari hasil tulisan anda lalu coba perbaiki.
:::

---

## Operator
Operator adalah operasi yang dilakukan pada nilai-nilai dalam program.  
ada 3 jenis operator yang akan kita bahas :  
utama :
- Operator [Aritmatika](#operator-aritmatika)
- Operator [Relasional](#operator-relasional)
- operator [Logika](#operator-logika)

tambahan :
- Operator Bitwise
- Operator Penugasan
- Operator Unary
- Operator Ternary

### Operator Aritmatika
Penggunaannya sama seperti operasi matematika dasar yang kamu pelajari di sekolah.  
mari implementasikan ke dalam kode program
```c
int a = 10;
int b = 5;

// operator use case
int c = a + b; // c = 15
int d = a - b; // d = 5
int e = a * b; // e = 50
int f = a / b; // f = 2
int g = a % b; // g = 0
```

### operator Relasional
:::important
disini kamu akan mengenal tentang konsep biner, yaitu 1 dan 0.    
1 = true,  
0 = false.  

Dengan kata lain, operator relasional akan menghasilkan nilai boolean, yaitu true atau false.
- True adalah logika yang di anggap **benar**.
- False adalah logika yang di anggap **salah**.
:::
Operator relasional digunakan untuk membandingkan dua nilai dan menghasilkan nilai boolean (true atau false).
```c
int a = 10;
int b = 5;

// operator use case
int c = a > b; // c = true
int d = a < b; // d = false
int e = a == b; // e = false
int f = a != b; // f = true
int g = a >= b; // g = true
int h = a <= b; // h = false
```
:::important
nilai true dan false di C adalah nilai boolean yang merepresentasikan logika benar dan salah.  
biasanya diwakili oleh angka `1 = true` dan `0 = false` oleh komputer.  
yah secara sederhana seperti komputer mengembalikan benar atau salah berdasarkan pengecekan kondisi.
ibaratnya seperti manusia yang membedakan ini benar atau salah berdasarkan kondisi yang dilihatnya.
:::
:::tip
- `>` adalah operator yang digunakan untuk membandingkan apakah nilai a lebih besar dari nilai b.
- `<` adalah operator yang digunakan untuk membandingkan apakah nilai a lebih kecil dari nilai b.
- `==` adalah operator yang digunakan untuk membandingkan apakah nilai a sama dengan nilai b. penulisan operatornya `= =`
- `!=` adalah operator yang digunakan untuk membandingkan apakah nilai a tidak sama dengan nilai b. penulisan operatornya `! =`
- `>=` adalah operator yang digunakan untuk membandingkan apakah nilai a lebih besar dari sama dengan nilai b. penulisan operatornya `> =`
- `<=` adalah operator yang digunakan untuk membandingkan apakah nilai a lebih kecil dari sama dengan nilai b. penulisan operatornya `< =`
:::

### Operator Logika
Operator logika digunakan untuk menggabungkan beberapa kondisi atau ekspresi logika.
```c
int a = 10;
int b = 5;
// operator use case && || ! !=
int c = (a > b) && (a < 20); // c = true
int d = (a < b) || (a > 20); // d = false
int e = !(a == b); // e = true
-----------------------------
/*Contoh lainnya:*/
int f = (a > b) || (a < 20) && (a != b); // f = true
int g = (a < b) && (a > 20) || (a == b); // g = false
int h = !(a > b) && !(a < 20); // h = true
int i = !(a < b) || !(a > 20); // i = false
-----------------------------
int j = (a > b) && (a < 20) || (a != b); // j = true
int k = (a < b) && (a > 20) || (a == b); // k = true
int l = !(a > b) && !(a < 20) || (a != b); // l = false
int m = !(a < b) || !(a > 20) && (a == b); // m = true
```
:::tip
- `&&` adalah operator logika `AND` yang digunakan untuk menggabungkan dua ekspresi logika, dimana kedua ekspresi dalam () harus bernilai true agar hasilnya true.
- `||` adalah operator logika `OR` yang digunakan untuk menggabungkan dua ekspresi logika, dimana minimal salah satu ekspresi harus bernilai true agar hasilnya true.
- `!` adalah operator logika `NOT` yang digunakan untuk menegasikan nilai boolean, yaitu jika nilai true maka akan menjadi false, dan sebaliknya.
:::
***Silahkan coba satu persatu contoh di atas untuk tau cara kerjanya***  
terserah mau experiment di text editor sendiri atau online compiler di bawah ini 👇  
[online compiler](#online-compiler)  
![gif](https://media.tenor.com/VmwF50n-d5sAAAAM/narenare-confusing.gif)
mampus mulai pusing tuh 😹

## Struktur Kontrol
Struktur kontrol itu ibaratnya kayak aturan bermain dalam program kita. Mereka membantu program untuk mengambil keputusan dan melakukan tindakan yang **berbeda** tergantung pada **kondisi** tertentu. Tanpa struktur kontrol, program kita hanya akan berjalan lurus dari atas ke bawah tanpa bisa "berpikir" atau "memilih".  
Ada dua jenis utama struktur kontrol yang akan kita bahas:  

1. **Percabangan** (Conditional Statements): Ini seperti saat kita di persimpangan jalan dan harus memilih belok kanan, kiri, atau lurus. Program akan mengecek suatu kondisi, dan jika kondisi itu benar, ia akan melakukan satu hal; jika salah, ia akan melakukan hal lain.  

2. **Perulangan** (Looping Statements): Ini seperti saat kita harus melakukan hal yang sama berkali-kali, misalnya suatu kondisi dimana harus mengocok kartu sebanyak 52 kali. Program akan mengulang blok kode tertentu selama kondisi tertentu masih terpenuhi. (Kita fokus pada percabangan dulu ya!)  

## Percabangan
### A. `if-else`: Si Penentu Pilihan "Ya atau Tidak"
`if-else` adalah percabangan yang paling sederhana. Ia memeriksa apakah suatu kondisi benar atau tidak. Jika benar, ia akan menjalankan perintah di dalamnya. Jika tidak, ia akan melompati perintah tersebut dan melanjutkan ke perintah setelahnya dalam `if-else`.  
Contohnya berikut:
```c
#include <stdio.h>

int main() {
    int usia;

    printf("Masukkan usia Anda: ");
    scanf("%d", &usia); // Membaca input usia dari pengguna

    if (usia >= 18) { // Kondisi: apakah usia lebih dari atau sama dengan 18?
        printf("Anda boleh menonton film dewasa. Selamat menikmati! \n");
    } else if (usia >= 12) {
        printf("Anda boleh menonton film anak-anak. Selamat menikmati! \n");
    }
    else {
        printf("Maaf, Anda belum cukup umur untuk menonton film dewasa. \n");
    }

    return 0; // Menandakan program berakhir dengan sukses
}
```
:::tip
- Didalam blok if ataupun else memerlukan statement kondisi `( //kondisi )` dan blok kode jika kondisi terpenuhi dalam `{ //kode }`.
- `if` artinya jika kondisi ini blablabla...
- `else if` artinya jika selain itu kondisi ini blablabla...
- `else` artinya kalau seluruh kondisi di atas tidak terpenuhi maka ia akan aktif (kode pengecualian).
:::

### B. `Switch Case`: Si Pemilih Banyak Opsi
switch-case itu seperti menu di restoran atau tombol pilihan di mesin minuman otomatis. Anda punya banyak pilihan bisa memilihnya sendiri berdasarkan keinginan, dan Anda memilih salah satunya. Daripada harus bertanya pada pengkondisian "Apakah ini A? Kalau tidak, apakah ini B? Kalau tidak, apakah ini C?" berulang-ulang (yang bisa jadi panjang dengan `if-else if-else if`), `switch-case` Bisa membuat kode lebih rapi dan mudah dibaca ketika Anda memiliki banyak opsi untuk satu variabel.  
Contohnya berikut:
```c
#include <stdio.h>

int main() {
    int hari;

    printf("Masukkan angka hari (1-7): ");
    scanf("%d", &hari);

    switch (hari) { // Kita akan cek nilai variabel 'hari'
        case 1:
            printf("Hari ini adalah Minggu. \n");
            break;
        case 2:
            printf("Hari ini adalah Senin. \n");
            break;
        case 3:
            printf("Hari ini adalah Selasa. \n");
            break;
        case 4:
            printf("Hari ini adalah Rabu. \n");
            break;
        case 5:
            printf("Hari ini adalah Kamis. \n");
            break;
        case 6:
            printf("Hari ini adalah Jumat. \n");
            break;
        case 7:
            printf("Hari ini adalah Sabtu. \n");
            break;
        default: // Jika angka yang dimasukkan tidak 1-7
            printf("Angka yang Anda masukkan tidak valid untuk hari. \n");
            break;
    }

    return 0;
}
```
:::note[PENJELASAN]
- Pada contoh diatas, `switch (hari)` akan memeriksa nilai dari variabel `hari`. Setiap `case` akan memeriksa apakah nilai `hari` sama dengan angka yang di dalamnya. Jika ya, ia akan menjalankan perintah di dalamnya. Jika tidak, ia akan melompati perintah tersebut dan melanjutkan ke perintah setelahnya.
- `default` adalah perintah yang akan dijalankan jika tidak ada `case` yang sesuai dengan nilai `hari` (mirip kayak blok else di `if-else`).

---

- `switch(//variabel)` akan memeriksa apakah nilai `//variabel` sama dengan nilai `case` yang di dalam `{// case-nya}`.
- `break` adalah perintah yang akan menghentikan perulangan atau percabangan. Jika tidak ada `break`, ia akan menjalankan perintah di bawahnya, meskipun kondisi tidak terpenuhi -- Akan sangat berbahaya kalau anda lupa memberi break ~ jadi wajib diberi untuk setiap case yaa!.
- **KESIMPULAN**: Switch berbeda dengan if-else karena switch membutuhkan input untuk pengecekan nilainya, sedangan if else tidak membutuhkan input setidaknya mampu melakukan pengecekan nilai langsung di dalam sistem yang sudah diberikan dalam program.
:::

:::tip
Kapan Menggunakan if-else dan Kapan switch-case?  
**Gunakan if-else ketika:**
- Anda punya dua kemungkinan (benar/salah, ya/tidak).
- Anda perlu memeriksa rentang nilai (misalnya, `usia >= 18 atau nilai > 70 && nilai <= 100`).
- Anda punya kondisi yang kompleks dengan operator logika (`&& (AND), || (OR), ! (NOT)`).

**Gunakan switch-case ketika:**
- Anda ingin kode lebih rapi dan mudah dibaca dibandingkan banyak if-else if-else.
- Anda punya satu variabel yang bisa memiliki banyak nilai diskrit (nilai yang jelas dan terpisah, bukan rentang), dan Anda ingin melakukan tindakan berbeda untuk setiap nilai. 

(sedikit info: Nilai diskrit adalah nilai-nilai yang terpisah dan dapat dihitung, biasanya dalam bentuk bilangan bulat, yang tidak dapat dipecah menjadi nilai yang lebih kecil atau desimal. Contohnya adalah jumlah siswa dalam satu kelas atau jumlah mobil di tempat parkir. Sebaliknya, nilai kontinu adalah nilai yang dapat diukur dan dapat memiliki nilai di antara titik-titik yang terukur, seperti tinggi badan atau suhu. yah anda bisa cari tau sendiri di pelajaran matematika).
:::

---

![gif](https://media.tenor.com/92wsxnhSzBEAAAAM/dance-anime.gif)
## Perulangan
Bayangkan Anda memiliki tugas yang harus diulang berkali-kali. Misalnya, menulis suatu kalimat sebanyak 100 kali..  Melakukannya secara manual pasti sangat melelahkan, bukan?  

Nah, dalam dunia pemrograman, kita punya perulangan (atau dalam bahasa Inggris disebut loop) yang bertugas persis seperti itu: membuat komputer melakukan suatu pekerjaan berulang kali secara otomatis.  

### Analogi sederhana-nya
Anggap saja perulangan itu seperti mesin fotokopi otomatis. Anda cukup memberikan satu dokumen (program yang ingin diulang) dan memberitahu berapa banyak salinan yang Anda inginkan (berapa kali perulangan harus berjalan). Mesin fotokopi akan melakukannya tanpa Anda perlu menekan tombol satu per satu.  

### Jenis-jenis Perulangan di Bahasa C
Dalam bahasa C, ada beberapa "mesin fotokopi" yang bisa kita gunakan, yaitu:

- **A. for loop** (Perulangan "Untuk"):
Ini seperti Anda sudah tahu pasti berapa banyak salinan yang Anda inginkan.  
Contoh: "Untuk 10 kali, cetak tulisan 'Halo!'"  
Sangat cocok jika Anda sudah tahu dari awal berapa kali tugas harus diulang.  

- **B. while loop** (Perulangan "Selama"):
Ini seperti Anda terus menyalin dokumen selama masih ada kertas di baki. Anda tidak tahu pasti berapa banyak salinan yang akan dibuat, tapi Anda tahu bahwa perulangan akan berhenti jika syaratnya tidak terpenuhi.  
Contoh: "Selama persediaan barang masih ada, masukkan ke dalam keranjang."  
Sangat cocok jika perulangan bergantung pada suatu kondisi yang bisa berubah.  

- **C. do-while loop** (Perulangan "Lakukan Selama"):
Ini mirip dengan while loop, tapi ada satu perbedaan penting: tugas pasti akan dilakukan minimal satu kali, baru kemudian dicek kondisinya.  
Contoh: "Lakukan proses belanja, lalu cek apakah Anda ingin belanja lagi. Jika ya, ulangi."  
Cocok jika Anda ingin memastikan bahwa kode di dalam perulangan dijalankan setidaknya sekali.  

## Contoh dari masing masing tiga perulangan diatas
### A. For loop (Perulangan "Untuk")
Ini cocok ketika kita sudah tahu pasti berapa kali kita ingin mengulang sesuatu.  

**Skenario:** Kita ingin mencetak angka dari 1 sampai 3.  

**Logika:** "Untuk angka i yang dimulai dari 1, selama i masih kurang dari atau sama dengan 3, dan i bertambah 1 setiap putaran, cetak nilai i."  
```c
#include <stdio.h> // Untuk fungsi printf

int main() {
    printf("--- Demonstrasi 'for' Loop ---\n");
    // 'i' adalah penghitung kita
    // Dimulai dari 1; berhenti saat i > 3; i bertambah 1 setiap putaran
    for (int i = 1; i <= 3; i++) {
        printf("Angka: %d\n", i); // Cetak nilai 'i' saat ini
    }
    printf("Selesai 'for' Loop!\n");
    return 0;
}
```
```txt title="Output Program"
--- Demonstrasi 'for' Loop ---
Angka: 1
Angka: 2
Angka: 3
Selesai 'for' Loop!
```

### B. while Loop (Perulangan "Selama")
Ini cocok ketika kita ingin mengulang sesuatu selama suatu kondisi masih benar. Kita mungkin tidak tahu berapa kali tepatnya akan berulang.  

**Skenario:** Kita ingin mencetak angka mulai dari 1, tapi hanya selama angka itu masih kurang dari atau sama dengan 3.  

**Logika:** "Selama angka a (yang dimulai dari 1) masih kurang dari atau sama dengan 3, cetak angka a, lalu tambahkan a."  
```c
#include <stdio.h> // Untuk fungsi printf

int main() {
    printf("\n--- Demonstrasi 'while' Loop ---\n");
    int a = 1; // Inisialisasi penghitung 'a'
    
    // Perulangan akan berjalan selama 'a' kurang dari atau sama dengan 3
    while (a <= 3) {
        printf("Angka: %d\n", a); // Cetak nilai 'a'
        a++; // Penting: Jangan lupa ubah nilai 'a' agar kondisi suatu saat salah (biar tidak looping terus tanpa henti)
    }
    printf("Selesai 'while' Loop!\n");
    return 0;
}
```
```txt title="Output Program"
--- Demonstrasi 'while' Loop ---
Angka: 1
Angka: 2
Angka: 3
Selesai 'while' Loop!
```

### C. do-while Loop (Perulangan "Lakukan... Selama")
Ini mirip while loop, tapi aksi di dalamnya PASTI akan dijalankan setidaknya SATU KALI, baru kemudian kondisinya dicek.  

**Skenario:** Kita ingin mencetak angka, dan kita menjamin setidaknya satu angka akan tercetak, meskipun kondisi awalnya mungkin sudah salah.  

**Logika:** "Lakukan (cetak angka b), lalu tambahkan b. Ulangi proses ini selama b masih kurang dari atau sama dengan 3."  
```c
#include <stdio.h> // Untuk fungsi printf

int main() {
    printf("\n--- Demonstrasi 'do-while' Loop ---\n");
    int b = 1; // Inisialisasi penghitung 'b'
    
    do {
        printf("Angka: %d\n", b); // Cetak nilai 'b'
        b++; // Tambahkan 'b'
    } while (b <= 3); // Cek kondisi SETELAH melakukan aksi
    
    printf("Selesai 'do-while' Loop!\n");

    // Contoh menarik do-while:
    // Bagaimana jika kondisi awalnya sudah salah?
    printf("\n--- Contoh 'do-while' jika kondisi awal salah ---\n");
    int c = 5; // Nilai 'c' sudah lebih dari 3
    do {
        printf("Ini PASTI tercetak setidaknya sekali: %d\n", c);
        c++;
    } while (c <= 3); // Kondisi 'c <= 3' (5 <= 3) adalah false, tapi tetap dijalankan sekali!
    printf("Selesai 'do-while' Loop (kondisi salah)!\n");

    return 0;
}
```
```txt title="Output Program"
--- Demonstrasi 'do-while' Loop ---
Angka: 1
Angka: 2
Angka: 3
Selesai 'do-while' Loop!

--- Contoh 'do-while' jika kondisi awal salah ---
Ini PASTI tercetak setidaknya sekali: 5
Selesai 'do-while' Loop (kondisi salah)!
```
Anda bisa lihat bahwa meskipun dengan int c = 5; di contoh do-while kedua (kondisi c <= 3 sudah salah dari awal), baris printf tetap dieksekusi sekali. Itulah perbedaan utamanya!  
Perbedaan utama antara while dan do-while:
- while: Perulangan dieksekusi selama kondisi benar.
- do-while: Perulangan dieksekusi setidaknya sekali, lalu dicek kondisi.

### contoh implementasi gabungan dari materi diatas
![restauran-foods](https://images.unsplash.com/photo-1600891964599-f61ba0e24092?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8cmVzdGF1cmFudCUyMGZvb2R8ZW58MHx8MHx8fDA%3D)
```c title="restaurant menu" collapse={7-109}
#include <stdio.h> // Diperlukan untuk fungsi input/output seperti printf dan scanf
#include <string.h> // Diperlukan untuk fungsi string seperti strcmp

// Konstanta untuk harga menu
#define HARGA_NASI_GORENG 15000
#define HARGA_MIE_AYAM 12000
#define HARGA_ES_TEH 5000
#define PAJAK_PERSEN 10 // Pajak 10%

int main() {
    // Deklarasi variabel
    int pilihanMenu;
    int kuantitasNasiGoreng = 0;
    int kuantitasMieAyam = 0;
    int kuantitasEsTeh = 0;
    int totalHargaMakanan = 0;
    int totalHargaMinuman = 0;
    int totalHargaKeseluruhan = 0;
    float pajakAmount = 0.0;
    float hargaBersih = 0.0;

    char lanjutPesan; // Untuk konfirmasi melanjutkan pemesanan

    printf("=======================================\n");
    printf("   Selamat Datang di Restoran Kami!\n");
    printf("=======================================\n");

    do {
        // Menampilkan menu
        printf("\n--- Menu Hari Ini ---\n");
        printf("1. Nasi Goreng  (Rp %d)\n", HARGA_NASI_GORENG);
        printf("2. Mie Ayam     (Rp %d)\n", HARGA_MIE_AYAM);
        printf("3. Es Teh       (Rp %d)\n", HARGA_ES_TEH);
        printf("4. Selesai Memesan\n");
        printf("-----------------------\n");

        printf("Masukkan pilihan Anda: ");
        scanf("%d", &pilihanMenu); // Menggunakan operator aritmatika dan input

        // Menggunakan operator relasional dan logika untuk validasi pilihan
        if (pilihanMenu >= 1 && pilihanMenu <= 3) {
            int kuantitas;
            printf("Masukkan kuantitas: ");
            scanf("%d", &kuantitas);

            if (kuantitas > 0) { // Operator relasional
                switch (pilihanMenu) {
                    case 1:
                        kuantitasNasiGoreng += kuantitas; // Operator aritmatika
                        totalHargaMakanan += kuantitas * HARGA_NASI_GORENG;
                        printf("%d Nasi Goreng ditambahkan.\n", kuantitas);
                        break;
                    case 2:
                        kuantitasMieAyam += kuantitas;
                        totalHargaMakanan += kuantitas * HARGA_MIE_AYAM;
                        printf("%d Mie Ayam ditambahkan.\n", kuantitas);
                        break;
                    case 3:
                        kuantitasEsTeh += kuantitas;
                        totalHargaMinuman += kuantitas * HARGA_ES_TEH;
                        printf("%d Es Teh ditambahkan.\n", kuantitas);
                        break;
                }
            } else {
                printf("Kuantitas harus lebih dari 0.\n");
            }
        } else if (pilihanMenu == 4) {
            printf("Pesanan Anda akan diproses.\n");
            break; // Keluar dari loop do-while
        } else {
            printf("Pilihan tidak valid. Silakan coba lagi.\n");
        }

        // Konfirmasi untuk melanjutkan pemesanan
        printf("\nApakah Anda ingin memesan lagi? (y/n): ");
        scanf(" %c", &lanjutPesan); // Perhatikan spasi sebelum %c untuk membersihkan buffer

    } while (lanjutPesan == 'y' || lanjutPesan == 'Y'); // Operator logika

    // Menghitung total dan pajak
    totalHargaKeseluruhan = totalHargaMakanan + totalHargaMinuman; // Operator aritmatika
    pajakAmount = (float)totalHargaKeseluruhan * PAJAK_PERSEN / 100; // Type casting dan operator aritmatika
    hargaBersih = totalHargaKeseluruhan + pajakAmount;

    // Menampilkan struk pembayaran
    printf("\n\n=============== Struk Pembayaran ===============\n");
    printf("Item                  Kuantitas      Harga\n");
    printf("-----------------------------------------------\n");
    if (kuantitasNasiGoreng > 0) { // Operator relasional
        printf("Nasi Goreng             %d           Rp %d\n", kuantitasNasiGoreng, kuantitasNasiGoreng * HARGA_NASI_GORENG);
    }
    if (kuantitasMieAyam > 0) {
        printf("Mie Ayam                %d           Rp %d\n", kuantitasMieAyam, kuantitasMieAyam * HARGA_MIE_AYAM);
    }
    if (kuantitasEsTeh > 0) {
        printf("Es Teh                  %d           Rp %d\n", kuantitasEsTeh, kuantitasEsTeh * HARGA_ES_TEH);
    }
    printf("-----------------------------------------------\n");
    printf("Total Harga Makanan     : Rp %d\n", totalHargaMakanan);
    printf("Total Harga Minuman     : Rp %d\n", totalHargaMinuman);
    printf("Total Keseluruhan       : Rp %d\n", totalHargaKeseluruhan);
    printf("Pajak (%d%%)             : Rp %.0f\n", PAJAK_PERSEN, pajakAmount);
    printf("Total Bayar             : Rp %.0f\n", hargaBersih);
    printf("===============================================\n");
    printf("          Terima Kasih Atas Kunjungan Anda!\n");
    printf("===============================================\n");

    return 0; // Menandakan program berakhir dengan sukses
}
```

**in English context but similary code like above ☝️👇**
```c title="laptop Store" collapse={7-109}
#include <stdio.h> // Required for input/output functions like printf and scanf
#include <string.h> // Not strictly necessary for this revised version but often useful for string manipulation

// Constants for product prices
#define PRICE_LAPTOP 1200
#define PRICE_SMARTPHONE 800
#define PRICE_HEADPHONES 150
#define SALES_TAX_PERCENT 8 // 8% sales tax

int main() {
    // Variable declarations
    int productChoice;
    int laptopQuantity = 0;
    int smartphoneQuantity = 0;
    int headphonesQuantity = 0;
    int totalGadgetCost = 0;
    int totalAccessoryCost = 0;
    int grandTotalBeforeTax = 0;
    float salesTaxAmount = 0.0;
    float finalAmountDue = 0.0;

    char continueShopping; // For confirming whether to continue adding items

    printf("==========================================\n");
    printf("     Welcome to ElectroMart Online!\n");
    printf("==========================================\n");

    do {
        // Displaying the product catalog
        printf("\n--- Product Catalog ---\n");
        printf("1. Laptop        ($ %d)\n", PRICE_LAPTOP);
        printf("2. Smartphone    ($ %d)\n", PRICE_SMARTPHONE);
        printf("3. Headphones    ($ %d)\n", PRICE_HEADPHONES);
        printf("4. Proceed to Checkout\n");
        printf("-------------------------\n");

        printf("Enter your choice: ");
        scanf("%d", &productChoice); // Uses arithmetic operators and input

        // Using relational and logical operators for choice validation
        if (productChoice >= 1 && productChoice <= 3) {
            int quantity;
            printf("Enter quantity: ");
            scanf("%d", &quantity);

            if (quantity > 0) { // Relational operator
                switch (productChoice) {
                    case 1:
                        laptopQuantity += quantity; // Arithmetic operator
                        totalGadgetCost += quantity * PRICE_LAPTOP;
                        printf("%d Laptop(s) added to cart.\n", quantity);
                        break;
                    case 2:
                        smartphoneQuantity += quantity;
                        totalGadgetCost += quantity * PRICE_SMARTPHONE;
                        printf("%d Smartphone(s) added to cart.\n", quantity);
                        break;
                    case 3:
                        headphonesQuantity += quantity;
                        totalAccessoryCost += quantity * PRICE_HEADPHONES;
                        printf("%d Headphone(s) added to cart.\n", quantity);
                        break;
                }
            } else {
                printf("Quantity must be greater than 0.\n");
            }
        } else if (productChoice == 4) {
            printf("Processing your order...\n");
            break; // Exit the do-while loop
        } else {
            printf("Invalid choice. Please try again.\n");
        }

        // Confirmation to continue shopping
        printf("\nDo you want to add more items? (y/n): ");
        scanf(" %c", &continueShopping); // Note the space before %c to clear the buffer

    } while (continueShopping == 'y' || continueShopping == 'Y'); // Logical operator

    // Calculating total and sales tax
    grandTotalBeforeTax = totalGadgetCost + totalAccessoryCost; // Arithmetic operator
    salesTaxAmount = (float)grandTotalBeforeTax * SALES_TAX_PERCENT / 100; // Type casting and arithmetic operators
    finalAmountDue = grandTotalBeforeTax + salesTaxAmount;

    // Displaying the checkout summary
    printf("\n\n=============== Checkout Summary ===============\n");
    printf("Item                   Quantity      Price\n");
    printf("-----------------------------------------------\n");
    if (laptopQuantity > 0) { // Relational operator
        printf("Laptop                     %d            $ %d\n", laptopQuantity, laptopQuantity * PRICE_LAPTOP);
    }
    if (smartphoneQuantity > 0) {
        printf("Smartphone                 %d            $ %d\n", smartphoneQuantity, smartphoneQuantity * PRICE_SMARTPHONE);
    }
    if (headphonesQuantity > 0) {
        printf("Headphones                 %d            $ %d\n", headphonesQuantity, headphonesQuantity * PRICE_HEADPHONES);
    }
    printf("-----------------------------------------------\n");
    printf("Total Gadget Cost        : $ %d\n", totalGadgetCost);
    printf("Total Accessory Cost     : $ %d\n", totalAccessoryCost);
    printf("Subtotal                 : $ %d\n", grandTotalBeforeTax);
    printf("Sales Tax (%d%%)         : $ %.2f\n", SALES_TAX_PERCENT, salesTaxAmount);
    printf("Final Amount Due         : $ %.2f\n", finalAmountDue);
    printf("===============================================\n");
    printf("          Thank You for Shopping with Us!\n");
    printf("===============================================\n");

    return 0; // Indicates successful program termination
}
```

---
# online compiler
Kalau kamu penasaran ingin coba materi yang kamu pelajari tadi, silahkan coba di online compiler di bawah ini 👇
<iframe width="100%" height="468" src="https://onecompiler.com/c/" title="C compiler" frameborder="0" allowfullscreen></iframe>

---
Click tombol ini jika ingin --  
[Kembali ke atas](#pengenalan-apa-itu-pemerograman-bahasa-c).  
[Lihat daftar isi untuk lanjut materi](#apa-saja-yang-harus-dipelajari-dalam-bahasa-c).  

Sekian saya cukupkan dari ribuan kata yang telah saya tuliskan. Terima kasih banyak sudah membaca.  
Capek njir 😊 Funfact: Pengerjaan artikel ini membutuhkan waktu 4 hari 1 malam... thats insane.
![gif](https://media.tenor.com/ZBtJFtWJeFYAAAAM/ga-logis-ambatukam.gif) ![gif](https://media.tenor.com/i6pfhZCP1QcAAAAm/%E5%AD%A4%E7%8D%A8%E6%90%96%E6%BB%BE-%E5%B0%8F%E5%AD%A4%E7%8D%A8.webp)