# Описание проекта:

API с полностью реализованным функционалом CRUD

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

git clone https://github.com/AMDisplay/api_final_yatube.git

cd api_final_yatube

## Cоздать и активировать виртуальное окружение:

python3 -m venv venv

source venv/bin/activate

## Установить зависимости из файла requirements.txt:

python3 -m pip install --upgrade pip

pip install -r requirements.txt
## Выполнить миграции:

python3 manage.py migrate

## Запустить проект:

python3 manage.py runserver


## Пример запроса:

http://127.0.0.1:8000/api/v1/posts/

## Ответ:

{
"count": 123,
"next": "http://api.example.org/accounts/?offset=400&limit=100",
"previous": "http://api.example.org/accounts/?offset=200&limit=100",
"results": [
{}
]
}

### Автор - Александр Мельников
