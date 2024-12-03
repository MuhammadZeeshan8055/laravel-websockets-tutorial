1. composer create-project laravel/laravel laravel-websockets-tutorial "10.*"
2. composer require beyondcode/laravel-websockets --with-all-dependencies
3. php artisan vendor:publish --provider="BeyondCode\LaravelWebSockets\WebSocketsServiceProvider" --tag="migrations"
4. php artisan migrate
5. composer require pusher/pusher-php-server "^7.0"
6. php artisan optimize
7. php artisan config:clear
8. php artisan websockets:serve
9. php artisan serve
10. http://127.0.0.1:8000/laravel-websockets
11. npm install vite@^6.0.0
12. npm install --save-dev laravel-echo pusher-js
13. npm run dev
14. php artisan make:event NewTrade

event (new \App\Events\NewTrade('100'))

php artisan websockets:serve => separate cmd
php artisan serve => separate cmd
php artisan tinker => separate cmd
npm run dev => separate cmd


