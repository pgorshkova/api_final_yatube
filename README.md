## Проект «API для Yatube»

API для Yatube позволяет пользователям публиковать свои посты и управлять подписками через программный интерфейс взаимодействия.


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

`git clone https://github.com/apolwow/api_final_yatube.git`

`cd api_final_yatube`


Создать и активировать виртуальное окружение:

+ `python3 -m venv env`
+ `source venv/Scripts/activate`
+ `python -m pip install --upgrade pip`

Установить зависимости из файла requirements.txt:
`pip install -r requirements.txt`

Выполнить миграции:
`python manage.py migrate`


Запустить проект:
`python manage.py runserver`
#### После запуска проекта, документация будет доступна по адресу:
`http://localhost:port/redoc/`

