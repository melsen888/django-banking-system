# Proyek Bank Digital Sederhana (Django)

Ini adalah proyek aplikasi web bank digital sederhana yang dibangun menggunakan Python dan framework Django. Aplikasi ini mencakup fungsionalitas inti perbankan seperti manajemen akun, transfer dana, riwayat transaksi, dan sistem pinjaman.



## Fitur Utama
-   **Otentikasi Pengguna:** Registrasi, Login, dan Logout yang aman.
-   **Dasbor Nasabah:** Tampilan saldo rekening dan 10 riwayat transaksi terakhir.
-   **Transfer Dana:** Pengguna dapat mentransfer dana ke rekening lain dengan berita transaksi.
-   **Fitur Admin:**
    -   Dasbor admin modern menggunakan tema **django-jazzmin**.
    -   Kemampuan khusus untuk melakukan deposit ke rekening nasabah.
    -   Sistem persetujuan pinjaman melalui *admin actions*.
-   **Sistem Pinjaman:** Fondasi untuk pengajuan dan persetujuan pinjaman.
-   **Tugas Backend Otomatis:**
    -   Membebankan biaya administrasi bulanan.
    -   Menghitung dan menambahkan bunga tabungan bulanan.

## Teknologi yang Digunakan
* **Backend:** Python, Django
* **Frontend:** HTML, CSS, Bootstrap 5
* **Database:** SQLite3 (default untuk pengembangan)
* **Admin Theme:** `django-jazzmin`



---
## Instalasi dan Setup Lokal

Untuk menjalankan proyek ini di komputer lokal Anda, ikuti langkah-langkah berikut.

### 1. Prasyarat
-   Python 3.8+
-   Pip (Package Installer for Python)
-   Git

### 2. Buat `requirements.txt`
Buat file baru bernama `requirements.txt` di direktori utama proyek dan isi dengan teks berikut:
