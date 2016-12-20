# LaravelAPIBoilerplateJWT

Example Laravel API Boilerplate JWT

## Install with Composer

```
    $ curl -s http://getcomposer.org/installer | php
    $ php composer.phar install
```
## Getting with Curl
```
    $ curl -H 'content-type: application/json' -v -X GET http://localhost:8000/api/book?token= :token
    $ curl -H 'content-type: application/json' -v -X GET http://localhost:8000/api/books/:id?token=:token
    $ curl -H 'content-type: application/json' -v -X POST -d '{"title":"Foo bar","author":"Foo author"}' http://localhost:8000/api/books?token=:token
    $ curl -H 'content-type: application/json' -v -X PUT -d '{"title":"Foo bar","author":"Foo author"}' http://localhost:8000/api/books/:id?token=:token
    $ curl -H 'content-type: application/json' -v -X DELETE http://localhost:8000/api/books/:id?token=:token
```
## User Registration with Curl
```	
	curl  -H 'content-type: application/json' -v -X POST -d '{"name":"tony","email":"tony_admin@lavarel.com","password":"admin"}' http://localhost:8000/api/auth/signup
```
## User Authentication with Curl
```
	curl  -H 'content-type: application/json' -v -X POST -d '{"email":"tony_admin@lavarel.com","password":"admin"}' http://localhost:8000/api/auth/login
```
