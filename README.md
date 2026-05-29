# 🎓 Sistem Manajemen Nilai Mahasiswa

> Aplikasi console berbasis Java untuk mengelola data nilai mahasiswa secara lengkap, cepat, dan terstruktur.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Console-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

---

## 📖 Tentang Program

**Sistem Manajemen Nilai Mahasiswa** adalah aplikasi console yang memungkinkan pengelolaan data nilai mahasiswa secara menyeluruh. Dilengkapi dengan sistem login multi-role, operasi CRUD lengkap, algoritma pencarian dan pengurutan, serta fitur statistik kelulusan.

---

## ✨ Fitur Utama

### 🔐 Autentikasi Multi-Role
| Role  | Akses |
|-------|-------|
| Admin | Akses penuh ke seluruh fitur |
| User  | Hanya dapat melihat data miliknya sendiri |

### 📋 Manajemen Data
- **Tambah** — Menambahkan data mahasiswa baru dengan validasi ID unik dan nilai 1–100
- **Tampilkan** — Menampilkan seluruh data dalam format tabel ASCII yang rapi
- **Edit** — Mengubah nama, program studi, dan nilai mahasiswa
- **Hapus** — Penghapusan soft-delete (data bisa dipulihkan)
- **Restore** — Mengembalikan data mahasiswa yang telah dihapus

### 🔍 Pencarian
| Metode | Algoritma |
|--------|-----------|
| Cari berdasarkan Nama | Sequential Search |
| Cari berdasarkan ID | Binary Search |
| Cari berdasarkan Prodi | Sequential Search |

### 📊 Pengurutan
| Kolom | Algoritma |
|-------|-----------|
| ID | Quick Sort |
| Nama | Quick Sort |
| Nilai | Quick Sort |

### 📈 Statistik
- Total mahasiswa aktif
- Jumlah lulus dan tidak lulus
- Rata-rata nilai keseluruhan
- Persentase kelulusan
- Distribusi grade (A, B, C, D, E)

### 💾 File Handling
- Auto-save ke `data.txt` setiap ada perubahan
- Auto-load data saat program dijalankan

### 🖥️ Tampilan Interface
- Warna ANSI untuk tampilan yang lebih hidup
- Tabel ASCII untuk penyajian data yang rapi
- Loading animation
- Progress bar

---

## 🧠 Algoritma & Konsep yang Diterapkan

```
✔ Sequential Search     — Pencarian nama dan prodi
✔ Binary Search         — Pencarian ID mahasiswa
✔ Quick Sort            — Pengurutan data
✔ File Handling         — Penyimpanan dengan File, Scanner, PrintWriter
✔ Object Oriented (OOP) — Class Mahasiswa, enkapsulasi, modularisasi
✔ Validasi Input        — Pengecekan tipe data, range nilai, duplikasi ID
✔ Statistik Sederhana   — Rata-rata, persentase, distribusi grade
```

---

## 🗂️ Struktur Data

```java
class Mahasiswa {
    String id;
    String nama;
    String prodi;
    int nilai;
    boolean aktif;
}

Mahasiswa[] dataMahasiswa = new Mahasiswa[200];
```

---

## 🚀 Cara Menjalankan

### Prasyarat
- Java JDK 8 atau lebih baru sudah terinstall

### Langkah-langkah

**1. Clone atau download repository ini**

```bash
git clone https://github.com/username/sistem-manajemen-nilai-mahasiswa.git
cd sistem-manajemen-nilai-mahasiswa
```

**2. Compile program**

```bash
javac SistemManajemenPenilianMahasiswa.java
```

**3. Jalankan program**

```bash
java SistemManajemenPenilianMahasiswa
```

---

## 🔑 Akun Default

> ⚠️ **Catatan:** Segera ganti password setelah pertama kali login.

| Role  | Username         | Password |
|-------|------------------|----------|
| Admin | `admin`          | `123`    |
| User  | ID Mahasiswa     | `123`    |

---

## 📁 Struktur File

```
📦 sistem-manajemen-nilai-mahasiswa
 ┣ 📄 SistemManajemenPenilianMahasiswa.java   # Source code utama
 ┣ 📄 data.txt                                 # File penyimpanan data (auto-generated)
 ┗ 📄 README.md                                # Dokumentasi
```

---

## 👨‍💻 Author

**Firman Hidayat, Talitha Nailal Husna, Radhin Ramadhan Hendestian**

> Project ini dibuat sebagai implementasi konsep algoritma dan struktur data dalam pemrograman Java berbasis console.

---

