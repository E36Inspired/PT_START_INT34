# Мониторинг ptsecurity.com в Prometheus и Blackbox Exporter


# Инструкция по запуску:

## 1: Запуск Docker Compose
- Откройте терминал и перейдите в корневую директорию проекта. Затем выполните следующую команду:

```docker-compose up --build```

- Эта команда соберет и запустит все сервисы, определенные в docker-compose.yml.

# Просмотр таргетов

## 2: Проверка Prometheus:

- В браузере перейдите по адресу http://localhost:9090
-  Далее откройте Targets во вкладке Status http://localhost:9090/targets

##  3: Проверка Blackbox Exporter:
- В браузере перейдите по адресу http://localhost:9115/metrics
