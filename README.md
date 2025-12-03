# project-kelompok-4




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
