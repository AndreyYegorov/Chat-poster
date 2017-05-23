# Poster

Небольшой чат, написанный на Express.js и Angular 2, включающий в себя авторизацию, загрузку фото, поиск сообщений, фильтр сообщений по хеш-тегам.

## Используемые технологии для сборки проекта

- `backend` - Node.js (Express.js + Pasport.js + Mongoose)
- `frontend` - Angular 2

## Функционал проекта

- Авторизация
- Возможность загрузки фотографий
- Фильтр ленты сообщений по хеш-тегам
- Фильтр ленты сообщений по поиску
- Использование http-клиента для отправки запросов на сервер

## Запуск проекта

``` sh
$ cd server
$ mongod --dbpath 'your-database-folder-path'
$ node server.js
```

## Разработка проекта

``` sh
$ cd server
$ mongod --dbpath 'your-database-folder-path'
$ node server.js
```

``` sh
$ cd 'app-folder-path'
$ npm start
```

``` sh
$ cd 'app-folder-path'
$ npm run build
```