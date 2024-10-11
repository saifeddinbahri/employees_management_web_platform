

  

# Symfony 6.3 project setup

### IDE : PhpStorm

## Install dependencies
```
composer install
```
  
## Create database
```
php bin/console doctrine:database:create

symfony make:migration

symfony doctrine:migrations:migrate
```
  
## Run server
```
php -S localhost:8000 -t public/
```

# Vue 3 project setup

```
npm install
```
  
## Compiles and hot-reloads for development

```
npm run dev
```
  
