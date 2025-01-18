cd your-repo
composer install
cp .env.example .env
php artisan key:generate
php artisan key:generate
sail up -d 
sail artisan migrate

Документация API
Сервис предоставляет документацию для работы с API, которая доступна по адресу: http://localhost/docs.