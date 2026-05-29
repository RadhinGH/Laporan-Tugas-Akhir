========================================
README.txt
SISTEM MANAJEMEN NILAI MAHASISWA
========================================

Nama Program :
Sistem Manajemen Nilai Mahasiswa Berbasis Java

Bahasa Pemrograman :
Java

Deskripsi Program :
Program ini merupakan aplikasi berbasis console yang digunakan untuk mengelola data nilai mahasiswa. Sistem memiliki fitur CRUD (Create, Read, Update, Delete), searching, sorting, statistik, login multi role, restore data, validasi input, dan file handling menggunakan file txt.

========================================
FITUR PROGRAM
========================================

1. Login Admin dan User
   - Admin dapat mengakses seluruh fitur program.
   - User hanya dapat melihat data miliknya sendiri.

2. Tambah Data Mahasiswa
   - Menambahkan data mahasiswa baru.
   - Validasi ID agar tidak duplicate.
   - Validasi nilai hanya 1–100.
   - Validasi input harus angka.

3. Tampilkan Data
   - Menampilkan seluruh data mahasiswa aktif.
   - Menggunakan tabel ASCII agar lebih rapi.

4. Edit Data
   - Mengubah nama, prodi, dan nilai mahasiswa.

5. Hapus Data
   - Menghapus data dengan sistem nonaktif.

6. Restore Data
   - Mengembalikan data mahasiswa yang telah dihapus.

7. Searching Data
   - Cari Nama → Sequential Search
   - Cari ID → Binary Search
   - Cari Prodi → Sequential Search

8. Sorting Data
   - Sort ID → Quick Sort
   - Sort Nama → Quick Sort
   - Sort Nilai → Quick Sort

9. Statistik Mahasiswa
   - Total mahasiswa
   - Jumlah lulus dan tidak lulus
   - Rata-rata nilai
   - Persentase kelulusan
   - Distribusi grade

10. File Handling
    - Auto save data ke file data.txt
    - Auto load data saat program dijalankan

11. Interface Interaktif
    - ANSI Color
    - ASCII Table
    - Loading Animation
    - Progress Bar

========================================
ALGORITMA YANG DIGUNAKAN
========================================

1. Sequential Search
   Digunakan pada pencarian nama dan program studi.

2. Binary Search
   Digunakan pada pencarian ID mahasiswa.

3. Quick Sort
   Digunakan untuk pengurutan data mahasiswa.

4. File Handling
   Menggunakan File, Scanner, dan PrintWriter.

========================================
STRUKTUR DATA
========================================

Program menggunakan:
- Array of Object
- Class Mahasiswa
- Array Mahasiswa[200]

========================================
CARA MENJALANKAN PROGRAM
========================================

1. Pastikan Java JDK sudah terinstall.
2. Compile program:

   javac SistemManajemenPenilianMahasiswa.java

3. Jalankan program:

   java SistemManajemenPenilianMahasiswa

========================================
LOGIN DEFAULT
========================================

Admin:
Username : admin
Password : 123

User:
Username : gunakan ID mahasiswa
Password : 123

========================================
FILE YANG DIGUNAKAN
========================================

1. SistemManajemenPenilianMahasiswa.java
   File source code utama program.

2. data.txt
   File penyimpanan data mahasiswa.

========================================
KONSEP YANG DITERAPKAN
========================================

- Object Oriented Programming (OOP)
- Array
- Searching
- Sorting
- File Handling
- Percabangan
- Perulangan
- Validasi Input
- Statistik Sederhana

========================================
AUTHOR
========================================

Nama : Firman Hidayat
Project : Sistem Manajemen Nilai Mahasiswa
