## api_final
"Yatube — социальная сеть с возможностью публикации постов. Представленный API расширяет функционал платформы, позволяя пользователям создавать публикации и управлять подписками через программный интерфейс."
### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Didamoko/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```
#### После запуска проекта, документация будет доступна по адресу: 
`http://localhost:port/redoc/`
