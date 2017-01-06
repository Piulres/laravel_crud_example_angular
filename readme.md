cd path/to/folder
composer create-project laravel/laravel laravelangular
php -S localhost:8080 -t public
-> create a database as 'laravelangular'
php artisan make:model Supplier
php artisan make:controller SupplierController --resource
php artisan make:migration create_supplier_table
php artisan migrate