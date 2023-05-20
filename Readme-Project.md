composer create-project laravel/laravel web-app
or
composer global require laravel/installer
laravel new web-app
//

php artisan serve
php artisan migrate


//Read through
Request Lifecycle
Configuration
Directory Structure
Frontend
Service Container
Facades
//

php artisan about
php artisan env:encrypt
///
Key ................................................... base64:wMf9Im9yOfDXuSflbeMdRj7vHBB6TJM80iHz7oV0jTQ=  
  Cipher ........................................................................................ AES-256-CBC  
  Encrypted file .......................................................... E:\Laravel\web-app\.env.encrypted  
  //

php artisan config:cache //in production
php artisan config:clear


//to enable maintenance mode, 
php artisan down
php artisan down --refresh=15
php artisan down --retry=60
php artisan down --secret="1630542a-246b-4b66-afa1-dd72a4c43515"
//https://example.com/1630542a-246b-4b66-afa1-dd72a4c43515
php artisan down --render="errors::503"
php artisan down --redirect=/
php artisan up


php artisan storage:link
php artisan test
php artisan list make
//
composer require laravel/breeze --dev
php artisan breeze:install --dark
php artisan breeze:install vue

//Auto done 
npm fund
php artisan inertia:middleware

//
