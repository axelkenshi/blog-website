---
title: Learn C language
published: 2024-06-13
description: '[indonesian] Belajar bahasa pemrograman C dari dasar dasarnya'
image: 'https://images.unsplash.com/photo-1564865878688-9a244444042a?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTR8fHByb2dyYW1taW5nfGVufDB8fDB8fHww'
tags: ['c language']
category: 'Programming'
draft: false 
lang: 'id'
---

:::note
Jika anda pemula, ingin belajar pemerograman, maka materi bacaan ini bisa menjadi referensi untuk belajar bahasa pemrograman C. Maka dari itu, semangat yaa!
:::
:::tip
If you want to use English or another language, please use the translation feature in your browser.
:::

Click tombol ini jika sudah membaca pengenalan
[Lompat ke konseptual C](#konseptual-dasar-bahasa-pemerograman-c)
# Pengenalan: Apa itu Pemerograman Bahasa C?
Bahasa C adalah bahasa pemrograman yang dikembangkan pada tahun 1972 oleh Dennis Ritchie di Bell Labs. Bahasa ini dirancang untuk sistem operasi Unix dan menjadi salah satu bahasa pemrograman yang paling populer dan berpengaruh dalam sejarah pengembangan perangkat lunak. 

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
1. Menyiapkan lingkungan pengembangan, anggaplah kode editor di komputer
2. Memahami konsep dasar pemrograman
3. Menulis kode
4. Menjalankan kode
5. Mengulang langkah-langkah tersebut sampai mahir

## Apa saja yang harus dipelajari dalam bahasa C?
Untuk mempelajari bahasa C, berikut adalah beberapa konsep dasar yang perlu dipahami:
- **Sintaks Dasar**: Memahami cara penulisan kode, seperti penggunaan tanda kurung, titik koma, dan struktur kontrol.
- **Tipe Data**: Memahami tipe data dasar seperti integer, float, char, dan lainnya.
- **Variabel dan Konstanta**: Memahami cara mendeklarasikan variabel dan konstanta, serta cara menggunakannya dalam kode.
- **Operator**: Memahami operator-operator yang digunakan dalam pemrograman, seperti operator aritmatika, operator relasional, dan operator logika.
- **Perulangan**: Memahami cara menggunakan perulangan untuk menjalankan blok kode secara berulang.
- **Fungsi**: Memahami cara mendeklarasikan dan menggunakan fungsi untuk memecah kode menjadi bagian-bagian yang lebih kecil dan terorganisir.
- **Array**: Memahami cara menggunakan array untuk menyimpan kumpulan data dengan tipe yang sama.
- **Struktur Data**: Memahami struktur data seperti array, linked list, tree, dan graph.
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
# Konseptual dasar bahasa pemerograman C
Disini akan saya coba kenalkan beberapa konsep yang perlu kamu mengerti untuk membuat sebuah perintah di program C beserta penjelasannya.

## Struktur Program C
Lihat bagaimana penulisan awal struktur program..  
sebelum menulis perintah(disebut syntax)
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

:::warning
- Ketika kamu membuat program C, kamu harus menambahkan `#include <library>`  dan itu wajib beserta struktur programmya.  
- ketika kamu membuat sebuah perintah maka letakkan di dalam fungsi `main()`.  
kecuali jika membuat sebuah function, maka letakkan di luar fungsi `main()`.
- ketika kamu menjumpai error, coba analisis kode kamu tulis apakah ada typo atau kurang penggunaan
simbol wajib seperti `(){}[]:` dan `;`
:::

## Tipe Data dan Variabel
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

---

## Input output dan contoh penggunaannya
```c
// output
printf("Hello World!"); // output Hello World!

// input
char a;
scanf("%c", &a);
```
:::note
- `printf` adalah sebuah perintah yang mencetak nilai ke layar, biasanya ada di terminal.
- `scanf` adalah sebuah perintah yang menerima input dari user.
- `%c` adalah format spesifier untuk karakter, yang digunakan dalam `scanf` untuk membaca input karakter.
- `%d` adalah format spesifier untuk integer, yang digunakan dalam `scanf` untuk membaca input bilangan bulat.
- `%f` adalah format spesifier untuk float, yang digunakan dalam `scanf` untuk membaca input bilangan desimal.
- `%lf` adalah format spesifier untuk double, yang digunakan dalam `scanf` untuk membaca input bilangan desimal dengan presisi tinggi.
- `%s` adalah format spesifier untuk string, yang digunakan dalam `scanf` untuk membaca input string.
--
- `&` adalah operator yang digunakan untuk mengambil alamat dari variabel, sehingga `scanf` dapat menyimpan nilai input ke dalam variabel tersebut.
:::

---
Click tombol ini jika ingin 
[Kembali ke atas](#pengenalan-apa-itu-pemerograman-bahasa-c)