<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# INSTRUCCIONS PER ARRENCAR EL PROJECTE - CATALÀ

Aquest document proporciona instruccions detallades sobre com configurar i executar aquest projecte Laravel en un entorn local.

## Requisits previs

Abans de començar, assegura't de tenir instal·lat el següent programari al teu ordinador:

-   [PHP 8.1+](https://www.php.net/)
-   [Composer](https://getcomposer.org/)
-   [Node.js i npm](https://nodejs.org/)
-   [PostgreSQL](https://www.postgresql.org/)

## Instal·lació

Segueix aquests passos per configurar el projecte en el teu entorn local.

### 1. Clona el repositori

git clone https://github.com/el-teu-usuari/el-teu-repositori.git
cd el-teu-repositori

### 2. Instal·la les dependències de PHP

composer install

### 3. Configura l'arxiu .env

Copia el fitxer d'exemple .env.example i canvia-li el nom per .env. Després, actualitza les variables d'entorn amb la configuració de la teva base de dades local.

DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=el_teu_database
DB_USERNAME=el_teu_usuari
DB_PASSWORD=la_teva_contrasenya

### 4. Executa les migracions i seeders

php artisan migrate --seed

### 5. Instal·la les dependències de Node.js i compila

npm install
npm run dev

## Executar el servidor local

php artisan serve
El projecte estarà disponible a http://localhost:8000

## Middleware CORS

Assegura't que el middleware CORS estigui configurat correctament. Pots revisar el fitxer CorsMiddleware.php i la configuració en cors.php.

# INSTRUCTIONS TO START THE PROJECT - ENGLISH

This document provides detailed instructions on how to set up and run this Laravel project in a local environment.

## Prerequisites

Before starting, make sure you have the following software installed on your computer:

-   [PHP 8.1+](https://www.php.net/)
-   [Composer](https://getcomposer.org/)
-   [Node.js i npm](https://nodejs.org/)
-   [PostgreSQL](https://www.postgresql.org/)

## Installation

Follow these steps to set up the project in your local environment.

### 1. Clone the repository

git clone https://github.com/your-username/your-repository.git
cd your-repository

### 2. Install PHP dependencies

composer install

### 3. Configure the .env file

Copy the example file .env.example and rename it to .env. Then, update the environment variables with your local database configuration.

DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password

### 4. Run migrations and seeders

php artisan migrate --seed

### 5. Install Node.js dependencies and compile

npm install
npm run dev

## Run the local server

php artisan serve
The project will be available at http://localhost:8000

## CORS Middleware

Ensure that the CORS middleware is correctly configured. You can check the file CorsMiddleware.php and the configuration in cors.php.

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

-   [Simple, fast routing engine](https://laravel.com/docs/routing).
-   [Powerful dependency injection container](https://laravel.com/docs/container).
-   Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
-   Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
-   Database agnostic [schema migrations](https://laravel.com/docs/migrations).
-   [Robust background job processing](https://laravel.com/docs/queues).
-   [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

-   **[Vehikl](https://vehikl.com/)**
-   **[Tighten Co.](https://tighten.co)**
-   **[WebReinvent](https://webreinvent.com/)**
-   **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
-   **[64 Robots](https://64robots.com)**
-   **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
-   **[Cyber-Duck](https://cyber-duck.co.uk)**
-   **[DevSquad](https://devsquad.com/hire-laravel-developers)**
-   **[Jump24](https://jump24.co.uk)**
-   **[Redberry](https://redberry.international/laravel/)**
-   **[Active Logic](https://activelogic.com)**
-   **[byte5](https://byte5.de)**
-   **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
