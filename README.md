# bottec_project

# e-commerce бот с админ-панелью

## Используемые технологии:

- Python 3.11
- Django 5.1
- Aiogram 3.14

## Для загрузки модулей

1. Перейти в папку проекта

```bash
cd bottec_project
```

2. Модуль бота

```bash
cd bot && git clone git@github.com:SowaSova/bottec_bot.git .
```

3. Модуль админ-панели

```bash
cd ../adminpanel && git clone git@github.com:SowaSova/bottec_admin.git .
```

## Запуск через Docker:

1. Переименовать файлы .env, убрав "\_example"
2. Добавить данные для переменных BOT_TOKEN и YOOKASSA_TOKEN
3. Запустить контейнер

```bash
docker compose up -d --build
```

4. Для доступа к админ-панели ([ссылка](http://localhost:8000))
