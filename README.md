## Laravel specs:
- Laravel 10
- php 8.1
- Vue **Inertia**
- MySQL (of evt SQLlite)

## Dev Setup:
- npm install
- composer install
- php artisan serve (Laravel server port 8000)
- npm run dev (Vite watch)
- .env.example to .env

#### Requirements: 
- php 8.1
- league/mime-type-detection:^1.11.0 (stond verkeerd in default laravel 10)
- composer
- nodejs 18 of 16 (LTS)

#### PHP ini extensions:
- extension=curl
- extension=fileinfo
- extension=mbstring
- extension=openssl
- extension=pdo_mysql
- extension=soap
- extension=sodium

### Initial setup process & resources:
- https://laravel.com/docs/10.x/installation#your-first-laravel-project
- https://laravel.com/docs/10.x/starter-kits#laravel-breeze-installation
- For DB: https://laravel.com/docs/10.x/database
- In case of Docker, laravel/sail https://laravel.com/docs/10.x/sail

(indien auth nodig, ff reinstall met bovenstaande instructies of php artisan breeze:install vue)
