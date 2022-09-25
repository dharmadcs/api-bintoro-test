<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>


## Cara Penggunaan

- Downlod atau Clone Project
- Ubah .env.example menjadi .env dan set database menjadi api-bintoro
- Terminal  : composer install
- Terminal  : php artisan migrate
- Terminal  : php artisan serve
- Lalu test di postman/insomnia/frontend project
- Contoh ada di folder README


## API Route

User :
- register			-> POST	 ->http://127.0.0.1:8000/api/register
- login			    -> POST	 ->http://127.0.0.1:8000/api/login
- logout			-> POST	 ->http://127.0.0.1:8000/api/logout


Post :
- create data		-> POST	 ->http://127.0.0.1:8000/api/posts 		    ->Body
- get all data		-> GET	 ->http://127.0.0.1:8000/api/posts
- get data by id	-> GET	 ->http://127.0.0.1:8000/api/posts/1
- update data		-> PUT	 ->http://127.0.0.1:8000/api/posts/1		->Params
- delete data		-> DELETE ->http://127.0.0.1:8000/api/posts/1
