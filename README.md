# project-kelompok-4

Pendahuluan

Kami membuat sebuah program kalkulator sederhana menggunakan bahasa pemrograman Python. Program ini dirancang untuk menerima dua input angka dari pengguna, kemudian memilih jenis operasi aritmatika yang diinginkan. Selanjutnya, program akan memproses perhitungan sesuai pilihan dan menampilkan hasilnya secara langsung. Pembuatan program ini bertujuan untuk memahami dasar-dasar logika pemrograman, penggunaan input-output, percabangan kondisi, serta pengolahan data dalam Python.

Melalui pembuatan program ini, diharapkan pengguna dapat memperoleh gambaran mengenai cara kerja kalkulator digital serta memahami bagaimana struktur kode dapat digunakan untuk menyelesaikan masalah matematis secara efisien. Selain itu, pembuatan proyek sederhana ini menjadi langkah awal untuk mengembangkan program yang lebih kompleks dan fungsional di masa mendatang.

Fitur Utama
1. Input Dua Angka
Program menyediakan mekanisme untuk menerima dua angka dari pengguna. Angka ini akan dijadikan nilai yang akan diolah dalam proses perhitungan. Pengguna bebas memasukkan angka berapa pun sesuai kebutuhan

2. Pemilihan Jenis Operasi
Program menawarkan empat jenis operasi aritmatika dasar, yaitu:
-Penjumlahan
-Pengurangan
-Perkalian
-Pembagian
Setiap pilihan diwaliki dengan angka 1 sampai 4 sehingga pengguna dapat memilih operasi yang diinginkan dengan mudah.

3. Proses Perhitungan Otomatis
Setelah pengguna memasukkan pilihan, program akan menjalankan perhitungan sesuai operasi yang dipilih. Proses ini dilakukan menggunakan struktur percabangan sehingga setiap operasi dieksekusi sesuai kondisi.

4. Penanganan Input Pilihan yang Salah
Jika pengguna memasukkan angka di luar pilihan 1 sampai 4, program akan memberikan pesan peringatan bahwa pilihan tersebut tidak valid. Hal ini membantu menghindari kesalahan eksekusi program.

5. Menampilkan Hasil Perhitungan
Setelah operasi dilakukan, program menampilkan hasil akhir kepada pengguna dalam format yang mudah dibaca. Output yang ditampilkan berbeda tergantung operasi yang dipilih.

6. Pesan Penutup
Program memberikan pesan bahwa proses perhitungan telah selesai. Hal ini berfungsi sebagai penanda bahwa seluruh alur kerja program sudah dijalankan.


Dokumentasi teknis (flowchart)

flowchart TD
  A([Start]) --> B[Inisialisasi: int a, int b]
  B --> C[Input program (1-4)]
  C --> D{program == 1?}
  D -->|Ya| E[hasil_akhir = a + b]
  D -->|Tidak| F{program == 2?}
  F -->|Ya| G[hasil_akhir = a - b]
  F -->|Tidak| H{program == 3?}
  H -->|Ya| I[hasil_akhir = a * b]
  H -->|Tidak| J{program == 4?}
  J -->|Ya| K[hasil_akhir = a / b]
  J -->|Tidak| L[Error: program tidak valid]
  E --> M[Output hasil_akhir]
  G --> M
  I --> M
  K --> M
  L --> N([END])
  M --> N


Panduan Instalasi git
pertama tama pengguna diharapkan install git di link ini https://git-scm.com dan klik download for windows, situs web akan mendeteksi versi windows secara otomatis. Setelah selesai, buka file exe git dan mulai instalasi.
saat installer terbuka, ikuti beberapa langkah dibawah ini:
dibagian . Select Components  
   Biarkan default saja, pastikan opsi berikut dicentang:
   - Git Bash
   - Git GUI
   - Windows Explorer integration (Git Bash Here)

selanjutnya bagian  Choosing the default editor  
   Pilih editor teks favoritmu. Kalau bingung, biarkan default: Vim atau pilih Notepad.

 Adjusting your PATH environment  
   Pilih opsi “Git from the command line and also from 3rd-party software”. Ini penting agar kamu bisa pakai Git dari terminal manapun.

Choosing HTTPS transport backend  
   Pilih “Use the OpenSSL library” (default).

Configuring the line ending conversions  
   Pilih “Checkout Windows-style, commit Unix-style line endings” (default).

Klik Next terus hingga tombol Install muncul. Klik Install dan tunggu proses selesai.

Setelah instalasi selesai:
 Klik Start Menu → cari dan buka terminal atau command prompt
 Di halaman command prompt, tuliskan
 git --version
Jika muncul versi Git (misalnya git version 2.43.0), berarti Git berhasil diinstal.
