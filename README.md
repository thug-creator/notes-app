# Заметки (Notes) 📝

Простое веб-приложение на Django для создания, просмотра и удаления заметок.

## 🚀 Возможности
- Просмотр списка всех заметок (отсортированы по дате создания).
- Создание новой заметки (заголовок + текст).
- Просмотр отдельной заметки.
- Удаление заметки с подтверждением.

## 🛠 Технологии
- **Backend:** Python 3, Django 5.0
- **База данных:** SQLite (по умолчанию)
- **Frontend:** HTML, Bootstrap 5 (через CDN)

## 📦 Как запустить проект локально

1. **Клонируйте репозиторий:**
   git clone https://github.com/thug-creator/notes-app.git
   cd notes-app

2. **Создайте и активируйте виртуальное окружение:**
    python -m venv venv
    # Для Windows:
    venv\Scripts\activate
    # Для Mac/Linux:
    source venv/bin/activate

3. **Установите зависимости:**
    pip install -r requirements.txt

4. **Примените миграции (создастся база данных):**
    python manage.py migrate

5. **Запустите сервер:**
    python manage.py runserver

6. **Откройте в браузере:*
    Перейдите по адресу http://127.0.0.1:8000/