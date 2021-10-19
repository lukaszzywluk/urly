# Urly - URL Shortener

Urly is a simple URL shortener built using PHP 8 and the Laravel 8 framework inspired by Bit.ly and TinyURL.
Urly is designed to generate the shortest link possible.
The app consist of headless API and a web client for the URL shortener.

## Manual Setup and Installation
Urly requires a webserver like apache or nginx. It can also be run locally using the PHP webserver.
The app can be installed manually by copying the .env.example file to .env environment file in the application's root directory.

`cp .env.example .env`

and filling out the .env environment configuration with database credentials.
For more infohttps://laravel.com/docs/8.x/configuration#environment-configuration

In the command shell run the following commands:

`composer install`

It will install the framework with all necessary packages.

`php artisan key:generate`

This command sets the APP_KEY value in your .env file to be used for all encryption needs by the app.

`php artisan migrate`

This will run database migrations and create database tables.
