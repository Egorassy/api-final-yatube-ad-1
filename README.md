# API Final Yatube

## Описание

Проект API для социальной сети Yatube. Позволяет публиковать посты, оставлять комментарии и подписываться на других пользователей.

## Установка

1. Клонировать репозиторий:
git clone <repo_url>

2. Создать виртуальное окружение:

python -m venv venv

3. Активировать:

venv\Scripts\activate

4. Установить зависимости:

pip install -r requirements.txt

5. Выполнить миграции:

python manage.py migrate

6. Запустить сервер:

python manage.py runserver