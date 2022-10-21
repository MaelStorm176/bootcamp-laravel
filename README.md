
## Installation

Let's install this project with composer and npm

```bash
composer install && npm install
```

Copy .env.example
```bash
cp .env.example .env
```

Configure database in .env
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
````

Generate a key for your application
```bash
php artisan key:generate
```

## Start application

Start php server
```bash
php artisan serve
```

Start ViteJS server
```bash
npm run dev
```

Enjoy ! App Started !
