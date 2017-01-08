# Simple CRUD Application with AngularJs
System Developed for tests and for fun. Made in Laravel 5.3 because client want.

----
### Author
* [Piulres]

----
### Version
1.0

----
### Requirement
You need the Apache, Mysql e PHP to run this application.

----
### Tech
Uses a number of open source projects to work properly:

* [jQuery]
* [Angular]
* [Bootstrap]
* [Composer]
* [Laravel]

----
### Installation
I hope you are familiar with [Xampp](https://www.apachefriends.org/pt_br/index.html) and the initial steps of the [Composer](https://scotch.io/tutorials/a-beginners-guide-to-composer) and [Laravel](http://www.darwinbiler.com/how-to-install-laravel-on-wamp-for-beginners/), but if not, follow the instructions to install on Windows:


```sh
cd path/to/folder
composer create-project laravel/laravel laravelangular
php -S localhost:8080 -t public
-> create a database as 'laravelangular'
php artisan make:model Supplier
php artisan make:controller SupplierController --resource
php artisan make:migration create_supplier_table
php artisan migrate
```

----
### Demo [Offline]
http://renan.zz.mu/laravel_crud_example_angular/


   [Piulres]: <https://github.com/Piulres/>
   [Composer]: <https://getcomposer.org/>
   [jQuery]: <http://jquery.com/>
   [Angular]: <https://angularjs.org/>
   [Laravel]: <https://laravel.com/>
   [Bootstrap]: <http://getbootstrap.com/>