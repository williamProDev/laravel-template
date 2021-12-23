<h1>Laravel template</h1>
### How to run the API

Make sure you have PHP and Composer installed globally on your computer.

Clone the repo and enter the project folder

```
git clone https://github.com/alexeymezenin/laravel-realworld-example-app.git
cd laravel-realworld-example-app
```

Install the app

```
composer install
cp .env.example .env
```

Run the web server

```
php artisan serve
```

That's it. Now you can use the api, i.e.

```
http://127.0.0.1:8000/api/articles
```
