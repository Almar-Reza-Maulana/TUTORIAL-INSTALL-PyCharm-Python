# 📚 Tutorial Install Python & PyCharm Community Edition – Mulai Ngoding ala Pro!

Halo, sobat coder! Selamat datang di repo ini. Ini tutorial lengkap buat kamu yang baru mulai belajar bahasa Python pake PyCharm . Aku bikin ini biar kamu bisa setup environment ngoding dalam hitungan menit. Siapkan sedikit waktu untuk memulai perjalanan awal ini dan selamat mencoba 😎

---
## 🤔 Apa itu Python dan Pycharm ❓❓❓
![img](https://github.com/Almar-Reza-Maulana/TUTORIAL-INSTALL-PyCharm-Python/blob/main/Python_coding.jpg)
### </> Pengertian Python 

Python adalah bahasa pemrograman tingkat tinggi yang bersifat umum (general-purpose), mudah dibaca, dan fleksibel. Dikembangkan oleh Guido van Rossum pada tahun 1991, Python mendukung berbagai paradigma pemrograman, seperti pemrograman terstruktur, berorientasi objek, dan fungsional. Python banyak digunakan untuk pengembangan web, analisis data, kecerdasan buatan, otomatisasi, dan banyak lagi. 

### 🚀 Apa Saja Kegunaan Python?
Berikut adalah beberapa contoh utamanya:

1. Pengembangan Web : Python digunakan untuk menjalankan proses di belakang layar sebuah website atau aplikasi. Misalnya, ketika Anda login ke akun Instagram, Python bisa bertugas untuk memeriksa apakah nama pengguna dan kata sandi Anda benar, lalu mengambil data foto dan profil Anda dari database untuk ditampilkan. Google dan Spotify juga menggunakan Python secara ekstensif.
   
2. Analisis Data dan Kecerdasan Buatan (AI): Ini adalah salah satu kegunaan Python yang paling populer. Python memiliki alat bantu yang sangat kuat untuk mengolah, membersihkan, dan menganalisis data dalam jumlah sangat besar. Dengan Python, para analis bisa menemukan pola, membuat visualisasi data (grafik), dan membangun model kecerdasan buatan, seperti sistem yang merekomendasikan film di Netflix.
   
3. Otomatisasi Tugas: Python bisa digunakan untuk membuat program kecil (script) yang secara otomatis melakukan tugas-tugas berulang di komputer. Contohnya, Anda bisa membuat program Python untuk:
- Mengubah nama ratusan file sekaligus sesuai pola tertentu.
- Menyalin informasi dari ribuan baris file Excel ke dokumen Word.
- Mengunduh data dari sebuah situs web setiap jam.

4. Pengembangan Perangkat Lunak: Berbagai aplikasi dan alat bantu dibuat menggunakan Python, mulai dari program untuk penelitian ilmiah, aplikasi desktop, hingga bagian-bagian dalam pembuatan video game.

---
### 💻 Pengertian Pycharm

Secara teknis, PyCharm adalah sebuah IDE (Integrated Development Environment). Sederhananya, IDE adalah satu aplikasi yang menggabungkan berbagai alat yang dibutuhkan seorang programmer ke dalam satu tempat yang terpadu.PyCharm ini dikembangkan oleh perusahaan Ceko JetBrains.

#### 🔗 Kaitan PyCharm dengan Bahasa Python

Hubungannya sangat langsung dan tidak terpisahkan: Python adalah bahasanya, sedangkan PyCharm adalah program untuk menulis dan mengelola bahasa tersebut.

- Python adalah Inti ⚙️:
  
  Python adalah bahasa pemrograman itu sendiri. Anda harus memasang (install) Python di komputer Anda agar komputer bisa mengerti dan mengeksekusi instruksi yang kamu berikan. Tanpa Python, tidak ada kode yang bisa dijalankan.

- PyCharm adalah Alat Bantu 🌱:
  
  PyCharm adalah aplikasi terpisah yang dirancang khusus untuk membuat proses menulis kode Python menjadi jauh lebih mudah, cepat, dan efisien. PyCharm membutuhkan Python untuk berfungsi; ia tidak bisa menjalankan kode tanpa "mesin" Python terpasang di komputer.

Kita sebenarnya bisa menulis kode Python hanya dengan Notepad biasa, lalu menjalankannya secara manual. Namun, cara itu sangat tidak praktis, terutama untuk proyek yang besar. PyCharm menyediakan semua fasilitas yang dibutuhkan agar kamu bisa fokus pada penulisan logika program tanpa repot dengan hal-hal teknis lainnya.

---
## 📤 Panduan Lengkap Instalasi Python dan PyCharm 
Tutorial ini akan memandumu langkah demi langkah untuk menginstal Python versi 3.9.13 dan PyCharm Community Edition, serta cara memeriksa konfigurasi lingkungan.

---

## Tahap 1: Instalasi Python 

### 1.1 Unduh Python

1.  Kunjungi situs resmi Python: [https://www.python.org/downloads/release/python-3913/](https://www.python.org/downloads/release/python-3913/).
2.  Gulir ke bawah ke bagian **Files**. Pilih installer yang sesuai dengan sistem operasi (OS) kamu:
   ![img](https://github.com/Almar-Reza-Maulana/TUTORIAL-INSTALL-PyCharm-Python/blob/main/Screenshot_install%20web%20python.png)
    * **Untuk Windows:** Cari `Windows installer (64-bit)` jika OS kamu 64-bit.
    * **Untuk macOS:** Cari `macOS 64-bit Intel installer`.

### 1.2 Proses Instalasi

1.  Jalankan file installer yang sudah diunduh.
2.  **PENTING:** Pada jendela instalasi pertama, **centang kotak "Add Python 3.9 to PATH"** di bagian bawah. Ini sangat krusial agar Python bisa dikenali oleh sistem operasi dari mana saja.
   
     ![img](https://github.com/Almar-Reza-Maulana/TUTORIAL-INSTALL-PyCharm-Python/blob/main/Screenshot%202025-09-19%20022620.png)
3.  Pilih **"Install Now"**.
4.  Ikuti langkah-langkah instalasi sampai selesai.

---

## Tahap 2: Verifikasi Instalasi dan Environment

### 2.1 Buka Command Prompt/Terminal

1.  **Untuk Windows:** Buka `Command Prompt` (atau `CMD`) dengan mengetik `cmd` di menu Start.
2.  **Untuk macOS/Linux:** Buka `Terminal` dari Launchpad atau aplikasi.

### 2.2 Periksa Versi Python dan PIP

Ketikkan perintah berikut dan tekan Enter:

```bash
python --version
```
Outputnya harus menunjukkan versi Python 3.9.13.

Selanjutnya, periksa PIP (Python's Package Installer), alat untuk menginstal library Python:
```bash
pip --version
```
Outputnya harus menunjukkan versi PIP yang terpasang.

![img](https://github.com/Almar-Reza-Maulana/TUTORIAL-INSTALL-PyCharm-Python/blob/main/Screenshot%202025-09-19%20023800.png)

### 2.3 Periksa Environment Variable (Opsional)
Jika perintah di atas tidak berhasil, mungkin environment variable belum teratur.

Untuk Windows:

1. Cari "Edit the system environment variables" di menu Start.
   ![img](https://github.com/Almar-Reza-Maulana/TUTORIAL-INSTALL-PyCharm-Python/blob/main/Screenshot%202025-09-19%20024246.png)
   
2. Klik Environment Variables....

3. Di bagian "System variables", cari dan klik Path, lalu klik Edit....

Pastikan ada entri yang mengarah ke lokasi instalasi Python, seperti:

C:\Users\NamaUser\AppData\Local\Programs\Python\Python39

C:\Users\NamaUser\AppData\Local\Programs\Python\Python39\Scripts
  ![img](https://github.com/Almar-Reza-Maulana/TUTORIAL-INSTALL-PyCharm-Python/blob/main/Screenshot%202025-09-19%20024738-fotor-2025091924919.png)
  
Jika tidak ada, tambahkan secara manual.

---
## Tahap 3: Instalasi PyCharm

### 3.1 Unduh PyCharm

1. Kunjungi situs resmi JetBrains: [https://www.jetbrains.com/pycharm/download/other.html](https://www.jetbrains.com/pycharm/download/other.html).

2. Pastikan kamu memilih tab Community edition di bagian kanan.
   ![img](https://github.com/Almar-Reza-Maulana/TUTORIAL-INSTALL-PyCharm-Python/blob/main/Screenshot%202025-09-19%20030714-fotor-202509193850.png)
   
3. Pilih sistem operasi kamu dan klik tombol Download. Pastikan kamu mengunduh versi Community, bukan Professional.

### 3.2 Proses Instalasi PyCharm

1. Jalankan file installer yang sudah diunduh.

2. Ikuti petunjuk instalasi. Kamu bisa membiarkan opsi default.

3. Centang Semua dan centang "Create Desktop Shortcut" (opsional) jika kamu ingin ikon pintasan di desktop.
    ![img](https://github.com/Almar-Reza-Maulana/TUTORIAL-INSTALL-PyCharm-Python/blob/main/Screenshot%202025-09-19%20095430.png)
   
4.  Setelah instalasi selesai, pilih *i want to manually reboot later* dan jalankan PyCharm.
    ![img](https://github.com/Almar-Reza-Maulana/TUTORIAL-INSTALL-PyCharm-Python/blob/main/Screenshot%202025-09-19%20100300.png)
    
5. PyCharm akan meminta kamu untuk mengimpor pengaturan atau membuat proyek baru. Pilih "Do not import settings" jika ini instalasi pertamamu.

---
✅ Selesai!

Udah kelar nih, bro/sis! 🥳. Gimana? gampang kannn. Nahh instalasi beres, *environment* aman, PyCharm siap digarap. Saatnya bikin karya, jangan cuma jadi wacana. Selamat berkarya dan happy coding! 😉
