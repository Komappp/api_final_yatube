API для моего проекта YaTube https://github.com/Komappp/Yatube
=====

Описание проекта
----------
Разработан API для проекта социальной сети. Реализована возможность добавления, 
удаления и изменения постов и комментариев. Настроена пагинация, пермишены.

# Как запустить проект:
### Клонировать репозиторий и перейти в него в командной строке:
`git clone git@github.com:Komappp/api_final_yatube.git`\
`cd api_final_yatube`

### Cоздать и активировать виртуальное окружение:
`python -m venv venv`\
`source venv/bin/activate`

### Установить зависимости из файла requirements.txt:
`python -m pip install --upgrade pip`\
`pip install -r requirements.txt`

### Выполнить миграции:
`python manage.py migrate`

### Запустить проект:
`python manage.py runserver`
