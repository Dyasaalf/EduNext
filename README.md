# EduNext - Platform Kursus Online

EduNext adalah platform manajemen kursus online berbasis web yang dibangun menggunakan **CodeIgniter 4** dan dikelola di dalam lingkungan **Docker**. Proyek ini dirancang untuk memudahkan distribusi materi pembelajaran secara digital.

## 🚀 Fitur Utama
* **Autentikasi Ganda:** Login sistem dengan pengecekan password Hash (Bcrypt) maupun Plain Text (untuk kebutuhan development).
* **Manajemen Dashboard:** Antarmuka khusus untuk pengelolaan data materi.
* **Upload Materi:** Fitur unggah file dokumen/materi kursus.
* **Role-Based Access Control:** Pembedaan hak akses antara Admin dan User biasa.
* **Dockerized Environment:** Infrastruktur yang siap dideploy ke layanan cloud seperti AWS.

## 🛠️ Stack Teknologi
* **Framework:** [CodeIgniter 4.x](https://codeigniter.com/)
* **Server:** Apache (melalui Docker PHP-Apache image)
* **Database:** MySQL 8.0
* **Containerization:** Docker & Docker Compose

## 📦 Service Docker yang Digunakan
Proyek ini berjalan di atas 3 service utama:
1. **Web Server:** Menggunakan PHP 8.2 & Apache untuk menjalankan logika CodeIgniter 4.
2. **Database Server:** MySQL 8.0 sebagai pusat penyimpanan data persisten.
3. **Virtual Network:** Jaringan internal Docker untuk komunikasi aman antar-kontainer.
