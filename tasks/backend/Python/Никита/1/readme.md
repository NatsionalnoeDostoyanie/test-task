# 1 задание

API для магазина с пивасом и шавермой.
Добавляется пиво через админку. API служит только для отображения продуктов.

#### Для запуска:

Установить зависимости:
```
pip install -r requirements.txt
```

Запустить миграции:
```
python manage.py migrate
```

Запустить дев-сервер:
```
python manage.py runserver
```

Основные URL's:
```
[http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin) - админка для добавления продуктов
[http://127.0.0.1:8000/api/docs](http://127.0.0.1:8000/api/docs) - документация в виде swagger
```

