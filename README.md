# LaravelAPIBoilerplateJWT

[![Build Status](https://travis-ci.org/Tony133/LaravelAPIBoilerplateJWT.svg?branch=master)](https://travis-ci.org/Tony133/LaravelAPIBoilerplateJWT)

Simple example of a API Boilerplate JWT with Laravel 6 LTS

## Install with Composer

```
    $ curl -s http://getcomposer.org/installer | php
    $ php composer.phar install or composer install
```

## Set Environment

```
    $ cp .env.example .env
```

## Set the application key

```
   $ php artisan key:generate
```

## User Registration with Curl
```	
	$ curl  -H 'content-type: application/json' -v -X POST -d '{"name":"tony","email":"tony_admin@lavarel.com","password":"admin"}' http://127.0.0.1:8000/api/auth/signup
```
## User Authentication with Curl
```
	$ curl  -H 'content-type: application/json' -v -X POST -d '{"email":"tony_admin@lavarel.com","password":"admin"}' http://127.0.0.1:8000/api/auth/login
```