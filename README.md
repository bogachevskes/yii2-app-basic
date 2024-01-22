<p align="center">
    <a href="https://github.com/yiisoft" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/993323" height="100px">
    </a>
    <h1 align="center">Базовый шаблон проекта обучения</h1>
    <br>
</p>

## Окружение

Требования к окружению:

* WSL / Linux
* docker 1.10.0+
* docker-compose 1.6.0+
* Make

### Переменные окружения

```dotenv
# Порт веб-сервера
APP_WEB_PORT=8077
```

## Установка

1. Скопировать **.env.dist** в **.env** и актуализировать все параметры
1. `make install` - установить проект

## Служебное

- `make install` - установка проекта
- `make up` - запуск контейнеров
- `make down` - остановка контейнеров
- `make restart` - перезапустить контейнеры
- `make logs` - логи контейнеров
- `make ps` - статус контейнеров
- `make logs` - просмотр логов контейнеров
- `make composer-install` - установка php-зависимостей