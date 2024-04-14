## HOW TO USE

----------

1. Clone repository ini, dan tempatkan ke `PATH public_html` kalian, jika menggunakan xampp maka ini ada di `htdocs`
2. Lakukan command `composer install`
3. Copy `.env.example` menjadi `.env`
4. Ubah `.env` sesuai dengan pengaturan database anda
5. Lakukan command `php artisan key:generate`
6. Lakukan command `php artisan migrate --seed`
7. Lakukan command `php artisan storage:link`
7. Lakukan command `php artisan serve`

## FITUR

1. Admin
    - Login
    - Logout
    - Register
    - Forgot Password
2. Setting
    - Logo
    - Basic Info
3. Blog
    - Category
    - posts
4. Users
    - Users Data
    - Role & Permisnivi
5. Website
    - Logo
    - Login
    - Filter By Category
    - Recent Post
    - Pagination

