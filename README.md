# app

Getting started

1. Склонировать репозиторий ```git clone git@github.com:silent-admin/app.git```
2. Установить docker-compose https://docs.docker.com/compose/install/
3. В корне проекта выполнить docker-compose up
Ожидается запущенный фронтенд на localhost:8080, и бекенды с localhost:3000 до localhost:3002 

Дизайн базы данных можно посмотреть на тут: ```https://ondras.zarovi.cz/sql/demo/?keyword=default```, скопировав содержимое файла ```database_design.yml```, лежащий в корне проекта

Инициализировать новый проект:
```
rails new APPNAME --skip-test --api --skip-actioncable --skip-turbolinks --skip-webpack-install --skip-javascript --skip-git
```
