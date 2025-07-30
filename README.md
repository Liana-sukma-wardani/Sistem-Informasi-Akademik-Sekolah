# Judul Project: Sistem-Informasi-Akademik-Sekolah

# Deskripsi Singkat
Sistem Informasi Akademik Sekolah merupakan project open source yang di kembangkan oleh Liana Sukma Wardani. Website ini khusus untuk para siswa dapat melihat jadwal pelajaran, dan nilai rapot dan para guru dapat menambahkan nilai siswa dengan muda melalui website.
Di dalam aplikasi ini terdapat beberapa fungsi dan fitur yang bisa digunakan oleh siswa dengan mudah, tak hanya itu fitur lain juga tersedia untuk guru seperti penginputan dll:
- Autentikasi Admin
- User & CRUD
- Jadwal & CRUD
- Kelas & CRUD
- Mata Pelajaran & CRUD
- Guru & CRUD
- Siswa & CRUD
- Rapot
- Dan lain-lain

# Cara Menjalankan Sistem

1. **Clone Repository**

```bash
git clone https://github.com/Liana-sukma-wardani/Sistem-Informasi-Akademik-Sekolah.git
cd Sistem-Informasi-Akademik-Sekolah-Laravel
composer install
cp .env.example .env
```

2. **Buka `.env` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

3. **Instalasi website**

```bash
php artisan key:generate
php artisan migrate --seed
```

4. **Jalankan website**

```bash
php artisan serve
```
# Akun Uji Coba Untuk Login

**Admin Default Account**

- email: admin@gmail.com
- Password: 12345678

# Dokumentasi API dengan software postman
<img width="1920" height="1080" alt="Screenshot 2025-07-30 102021" src="https://github.com/user-attachments/assets/123195cf-9ba7-4f89-b3ee-e0e5f1eae8b5" />
<img width="1920" height="1080" alt="Screenshot (393)" src="https://github.com/user-attachments/assets/4cab1e1e-248e-4f8d-acc3-d8af23ce74f1" />
<img width="1896" height="967" alt="Screenshot (395)" src="https://github.com/user-attachments/assets/cb177957-a9f4-4b43-ab6e-e0e874a8adf6" />

