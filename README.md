# 📚 Aplikasi Buku Tamu Digital - Universitas Siber Asia

Aplikasi Buku Tamu Digital berbasis web ini dibuat untuk memenuhi tugas **Ujian Tengah Semester (UTS)** pada mata kuliah **Pemrograman Web II (IF 405)**, Program Studi PJJ Informatika, Universitas Siber Asia. 

Aplikasi ini berfungsi untuk mencatat data pengunjung yang datang ke lingkungan kampus secara digital, terstruktur, dan real-time menggunakan kombinasi PHP natif, database MySQL, serta framework CSS Bootstrap.

---

## Identitas Mahasiswa
* **Nama:** Kafka Syahrial Fauzan
* **NIM:** 240401010045
* **Kelas:** IF 405
* **Mata Kuliah:** Pemrograman Web II

---

## Fitur Utama Aplikasi
1. **Halaman Formulir Tamu (`index.php`):**
   * Desain responsif bertema resmi UNSIA (Biru & Kuning Emas) menggunakan Bootstrap.
   * Input data minimal: Nama Lengkap, Instansi/Lembaga Asal, dan Tujuan Kedatangan.
   * Validasi client-side bawaan Bootstrap.
   * Pencatatan tanggal dan waktu kunjungan secara otomatis oleh server saat data disimpan.
2. **Halaman Daftar & Riwayat Tamu (`riwayat.php`):**
   * Menampilkan riwayat seluruh tamu dalam bentuk tabel interaktif dengan efek *striped* dan *hover*.
   * **Fitur Pencarian:** Mempermudah pencarian data tamu secara cepat berdasarkan Nama Lengkap atau Instansi.
   * Penghitung total otomatis jumlah tamu yang telah terdaftar.
3. **Arsitektur Terpisah:**
   * Konfigurasi database dipisahkan secara modular di dalam file `koneksi.php` menggunakan ekstensi `mysqli`.

---

## Spesifikasi & Teknologi
* **Bahasa Pemrograman:** PHP 8.x
* **Database:** MySQL / MariaDB
* **Framework CSS:** Bootstrap 5.3 (via CDN)
* **Icon Pack:** Bootstrap Icons v1.10.5 (via CDN)

---

## ⚙️ Petunjuk Instalasi & Penggunaan (Lokal)

### 1. Persiapan Database
1. Pastikan modul **Apache** dan **MySQL** pada aplikasi XAMPP Anda sudah aktif.
2. Buka browser dan akses `http://localhost/phpmyadmin/`.
3. Buat database baru bernama `db_bukutamu`[cite: 1].
4. Import file database **`buku_tamu.sql`** yang tersedia di dalam repositori ini ke database tersebut[cite: 1].

### 2. Pemasangan Aplikasi
1. Unduh repositori ini atau ekstrak file `kafguestbook.zip` ke dalam direktori lokal server Anda[cite: 1]:
   * Di Windows: `C:\xampp\htdocs\kafguestbook\`
2. Pastikan file konfigurasi database di `koneksi.php` sudah sesuai dengan pengaturan server lokal Anda (User default: `root`, Password: `""`).

### 3. Menjalankan Aplikasi
Buka browser kesayangan Anda lalu akses URL berikut:
* **Halaman Formulir Tamu:** `http://localhost/kafguestbook/index.php`
<img width="1284" height="667" alt="image" src="https://github.com/user-attachments/assets/8f7d918d-cff9-4cab-94fd-9fb46ce6d942" />

* **Halaman Riwayat & Pencarian:** `http://localhost/kafguestbook/riwayat.php`
<img width="1286" height="668" alt="image" src="https://github.com/user-attachments/assets/17f88495-ceb2-4a7c-be5b-28ec0482f12c" />


---
*Terima Kasih!*
