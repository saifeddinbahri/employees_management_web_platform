

  

# Symfony 6.3 project setup

### IDE : PhpStorm

## Navigate to the front folder

```
cd backend
```

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

## Navigate to the front folder

```
cd front
```

## Install dependencies

```
npm install
```
  
## Run project

```
npm run dev
```
  
