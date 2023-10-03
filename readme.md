# Проект "lyceum"

Бла-бла-бла, это мой проект на веб-фреймворке Django 4.2

## Запуск проекта в dev-режиме

1. Создайте и активируйте виртуальное окружение (cmd в папке проекта):  \
   python -m venv venv  \
   Далее:  \
   source venv/bin/activate  # для unix/linux  \
   venv\Scripts\activate  # для windows  \
   ...  # или сами через pycharm/другую ide

2. Установите зависимости:  \
   pip install -r requirements/prod.txt  # для прода \
   pip install -r requirements/test.txt  # для тестов \
   pip install -r requirements/dev.txt  # для разработки и линтинга

3. Выполните миграции базы данных (если они есть):  \
   python manage.py migrate

4. Запустите сервер разработки (cmd):  \
   py manage.py runserver

Приложение будет доступно по адресу `http://localhost:8000/`.

## .gitignore

В проекте есть файл `.gitignore`, который исключает из контроля версий некоторые файлы. Проверьте, что в нем учтены все
нужные вам файлы и папки.
 