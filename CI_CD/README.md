# Сборка HTTP сервера на Python в Docker
## Инструкция по запуску:

## 1: Запуск Docker Compose
- Откройте терминал и перейдите в корневую директорию проекта. Затем выполните следующую команду:

```docker-compose up --build```

- Эта команда соберет и запустит все сервисы, определенные в файле docker-compose.yml.

## 2: Проверка работы сервера
После запуска Docker Compose вы можете проверить работу сервера, отправив HTTP-запрос на путь /healthz. Вот как это сделать:

- Использование curl

Откройте новое окно терминала и выполните следующую команду:

```curl http://localhost:8000/healthz```

В ответ на эту команду вы должны увидеть текст 200 OK.

- Использование браузера

Откройте веб-браузер и перейдите по адресу ```http://localhost:8000/healthz```. Вы также должны увидеть текст 200 OK.


