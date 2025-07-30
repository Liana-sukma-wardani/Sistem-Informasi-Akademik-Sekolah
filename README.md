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

