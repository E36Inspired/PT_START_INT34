# Запуск проекта с использованием Docker Compose
Этот проект можно легко запустить с помощью Docker Compose. Вот пошаговая инструкция:

## Шаг 1: Запуск Docker Compose
Откройте терминал и перейдите в корневую директорию вашего проекта. Затем выполните следующую команду:

```docker-compose up --build```

Эта команда соберет и запустит все сервисы, определенные в вашем файле docker-compose.yml.

## Шаг 2: Проверка работы сервера
После запуска Docker Compose вы можете проверить работу сервера, отправив HTTP-запрос на путь /healthz. Вот как это сделать:

### Опция 1: Использование curl
Откройте новое окно терминала и выполните следующую команду:

```curl http://localhost:8000/healthz```

В ответ на эту команду вы должны увидеть текст 200 OK.

### Опция 2: Использование браузера
Откройте веб-браузер и перейдите по адресу ```http://localhost:8000/healthz```. Вы также должны увидеть текст 200 OK.

Если вы видите 200 OK, это означает, что ваш сервер работает правильно. Поздравляем, вы успешно запустили проект!