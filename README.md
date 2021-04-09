# api_yatube
## API для проекта Yatube

## Установка:

1. Клонируйте репозиторий на локальную машину.

`git clone https://github.com/ps-iria/api_yatube`

2. Установите виртуальное окружение.

`python3 -m venv venv`

3. Активируйте виртуальное окружение.

`source venv/bin/activate`

4. Установите зависимости.

`pip install -r requirements.txt`

5. Выполните миграции.

`python manage.py migrate`

6. Запустите локальный сервер.

`python manage.py runserver`

## Работа с api
Документация по всем командам описана в redoc

http://0.0.0.0/redoc/

## Основные использованные технологии
+ python 3.7
+ django
+ DRF
