## Introduction
A Laravel tutorial on how to login using Laravel Passport  We will create REST APIs with Laravel and add also Forgot and 
Reset Password functionality. Learn how to generate a JWT token with Laravel Passport and learn how to manage it. 
You will learn also how to add Migration and Seeders with Laravel. 


## Requirements
- PHP > 8.*
- Laravel > ^8.*
- MySQL > 5.x
- NPM > 8.*

## Below are the steps for Creating a fresh project (If you don't want to follow then you can just follow steps from # Setup Local Environment)

## Installation
For installing Laravel use below command
``composer create-project --prefer-dist laravel/laravel:^8 laravel-auth-api``

## Setup Local Environment
Run below command to install all vendors for Laravel 
``composer install``

Run below command for install Node related packages
``npm install``

## [Laravel Breeze](https://laravel.com/docs/8.x/starter-kits#laravel-breeze)
It's a minimal, simple implementation of all of Laravel's authentication features, including login, registration, password reset, email verification, and password confirmation.  
We will be using [Laravel Breeze API](https://laravel.com/docs/8.x/starter-kits#breeze-and-next) 
``php artisan breeze:install api``

## [Laravel Sanctum](https://laravel.com/docs/8.x/sanctum)
It provides a featherweight authentication system for SPAs (single page applications), mobile applications, and simple, token based APIs. Sanctum allows each user of your application to generate multiple API tokens for their account. These tokens may be granted abilities / scopes which specify which actions the tokens are allowed to perform.
We will be using [Laravel Sanctum SPA Authentication](https://laravel.com/docs/8.x/sanctum#spa-authentication)
``php artisan breeze:install api``

## ( Optional ) Using Sail for local development
Laravel Sail is a light-weight command-line interface for interacting with Laravel's default Docker development environment. Sail provides a great starting point for building a Laravel application using PHP, MySQL, and Redis without requiring prior Docker experience.

### Requirements
- Docker Desktop

### Installing Sail Into Existing Applications ( Optional as Laravel Sail comes with Laravel >=8.* )
``php artisan sail:install``

### For starting Sail use below command
``./vendor/bin/sail up -d``





