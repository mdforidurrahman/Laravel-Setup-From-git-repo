To install a Laravel project from a Git repository, follow these steps:

1. git clone https://github.com/username/repository.git
2. cd repository
3. composer install
4. cp .env.example .env
5. Configure the .env File
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE="demo" /  your_database_name
    DB_USERNAME=root /    your_database_user
    DB_PASSWORD=""   /    your_database_password
6. php artisan key:generate
7. php artisan migrate
8. php artisan migrate --seed / php artisan migrate:fresh --seed
9. npm install
10. npm run dev
11. php artisan serve


