## Установка
Склонируйте репозиторий с помощью git:
    git clone https://github.com/da-maltsev/Netology-Py.git

1. При первом запуске выполните команду из директории проекта:

 `docker-compose up -d --build`

 2. Далее запускаем миграции внутри контейнера:

  `docker-compose run app python manage.py migrate`

 3. В последующие разы достаточно использовать: 

 `docker-compose up -d`

**Стучать вот сюда:**
http://127.0.0.1:8000/