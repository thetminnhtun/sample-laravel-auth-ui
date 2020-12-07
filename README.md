# Laravel Auth UI

Laravel Authentication and Authorization Using laravel UI

## Installation

Clone the repository:

```sh
git clone 
```

Install PHP dependencies:

```sh
composer install
```

Install NPM denpendencies:

```sh
npm install
```

Build assets:

```sh
npm run dev
```

Setup configuration:

```sh
cp .env.example .env
```

Generate application Key

```sh
php artisan key:generate
```

Setup database

```sh
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

Run database migration:

```sh
php artisan migrate
```

Run dev server

```sh
php artisan serve
```

The server will run on `localhost:8000`
