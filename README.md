**API для блог-платформы Yatube.**
Данный проект представляет из себя API, построенное на основе Django REST Framework. 


Тут можно писать посты, объединять их в группы, комментировать их и подписываться на авторов.
Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

cd api_final_yatube
Cоздать и активировать виртуальное окружение:

python3 -m venv env
source env/bin/activate
Установить зависимости из файла requirements.txt:

python3 -m pip install --upgrade pip
pip install -r requirements.txt
Выполнить миграции:

python3 manage.py migrate
Запустить проект:

python3 manage.py runserver
