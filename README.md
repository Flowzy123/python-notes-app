Система заметок (Django)

Простое приложение на Django с API на DRF. Пользователи могут регистрироваться, создавать, редактировать и удалять свои заметки.



Технологии

- Python 3.10+
- Django 4+
- Django REST Framework
- SQLite
- django-taggit

 Установка и запуск

1. Клонируем репозиторий и переходим в проект

bash

git clone <URL_репозитория>
cd python25



2. Создаем виртуальное окружение и активируем его


python -m venv venv
# Windows PowerShell
.\venv\Scripts\Activate.ps1
# Windows CMD
venv\Scripts\activate.bat
# Linux/macOS
source venv/bin/activate



3. Устанавливаем зависимости


pip install -r requirements.txt



4. Применяем миграции

python manage.py migrate



5. Создаём суперпользователя

python manage.py createsuperuser



6. Запускаем сервер

python manage.py runserver

