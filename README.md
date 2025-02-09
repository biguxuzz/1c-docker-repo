# 1С: Хранилище конфигураций в Docker с Apache2

![Docker](https://img.shields.io/badge/docker-enabled-blue) ![License](https://img.shields.io/badge/license-GPL--3.0-green)

## О проекте
Данный проект представляет собой сборку Docker-контейнера для хранилища конфигураций 1С:Предприятие с публикацией через Apache2. 

## Функционал
- Разворачивание сервера хранилища конфигураций 1С в Docker
- Проксирование через Apache2
- Поддержка переменных среды для настройки

## Установка и запуск

### 1. Клонируйте репозиторий
```sh
git clone https://github.com/biguxuzz/1c-docker-repo.git
cd 1c-docker-repo
```

### 2. Создайте `.env` файл на основе `.env.dist` и настройте параметры
```sh
cp .env.dist .env
nano .env
```

### 3. Соберите и запустите контейнер
```sh
docker-compose up -d --build
```

### 4. Проверка логов
```sh
docker-compose logs -f
```

### 5. Остановка контейнера
```sh
docker-compose down
```

## Контакты
- 📧 Email: gorp@1cgst.ru
- 🐙 GitHub: [biguxuzz](https://github.com/biguxuzz)
- 📱 Telegram: [biguxuzz](https://t.me/biguxuzz)

## Лицензия
Проект распространяется под лицензией [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html).

---

# 1C: Configuration Storage in Docker with Apache2

## About the Project
This project provides a Docker container for 1C:Enterprise configuration storage with Apache2 proxying.

## Features
- Deploys 1C configuration storage in a Docker container
- Proxying via Apache2
- Supports environment variables for configuration

## Installation and Running

### 1. Clone the repository
```sh
git clone https://github.com/biguxuzz/1c-docker-repo.git
cd 1c-docker-repo
```

### 2. Create an `.env` file from `.env.dist` and configure parameters
```sh
cp .env.dist .env
nano .env
```

### 3. Build and start the container
```sh
docker-compose up -d --build
```

### 4. Check logs
```sh
docker-compose logs -f
```

### 5. Stop the container
```sh
docker-compose down
```

## Contacts
- 📧 Email: gorp@1cgst.ru
- 🐙 GitHub: [biguxuzz](https://github.com/biguxuzz)
- 📱 Telegram: [biguxuzz](https://t.me/biguxuzz)

## License
The project is licensed under [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html).


