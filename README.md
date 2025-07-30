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
'''bash 
1. Clone Repository 
git clone https://github.com/adhiariyadi/Sistem-Informasi-Akademik-Sekolah-Laravel.git
cd Sistem-Informasi-Akademik-Sekolah-Laravel
composer install
cp .env.example .env
'''

3. Buka .env lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=

4. Instalasi website
php artisan key:generate
php artisan migrate --seed

5. Jalankan website
php artisan serve
