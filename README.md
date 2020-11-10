# Laravel 7 create word document with PHPOffice/PHPWord
This is using phpoffice package

# Installation
1. Clone this repo
```
https://github.com/Mohammedbilal15/htmltoword
```

2. Install composer packages
```
cd laravel-7-word-document
 composer install
```

3. Create and setup .env file
```
make a copy of .env.example and rename to .env
$ php artisan key:generate
put database credentials in .env file
```

4. Migrate and insert records
```
$ php artisan migrate
$ php artisan tinker
$ factory(App\User::class, 50)->create()
```
