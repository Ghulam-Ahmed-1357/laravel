# laravel
-- create database command
  mysql -u root -e'create database database_name'
then go to .env file and change the 'DB_DATABASE' name
php artisan migrate
migrataion is used to Runs all pending migrations and creates the tables in the database.
Migrations = Database structure as code.
They help in creating, updating, and rolling back tables easily.

create project command
composer create-project laravel/laravel project_name

for setting up sanctum
composer require laravel/sanctum
publish command:  php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"
php artisan migrate

php artisan install:api










  
