# Docka - WordPress на Docker

Этот проект содержит готовую настройку для запуска **WordPress** с **MariaDB** и **Nginx** через **Docker Compose**. Также есть **phpMyAdmin** для удобного управления базой данных.

## Что входит в проект:

- **WordPress** — для создания и управления сайтом.
- **MariaDB** — база данных для WordPress.
- **Nginx** — веб-сервер для WordPress.
- **phpMyAdmin** — интерфейс для работы с базой данных.
- **GitHub Actions** — автоматически пушит изменения в репозиторий, если они есть.

## Как запустить:

### 1. Клонируйте репозиторий

```bash
git clone https://github.com/f1sher1762/docka.git
cd docka

# В файле docker-compose.yml можно настроить данные для базы данных (например, пароль).

Запустите контейнеры
bash
Копировать код
docker-compose up -d

Контейнеры будут запущены:

WordPress будет доступен по адресу: http://localhost:8080
phpMyAdmin — по адресу: http://localhost:8081
MariaDB работает в фоновом режиме.
