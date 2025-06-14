# SConnect

SConnect — это минималистичный клон SoundCloud на Django. Позволяет загружать треки, приглашать пользователей к совместным трекам (инвайты), лайкать и добавлять в избранное.

## Возможности
- Регистрация и авторизация
- Загрузка аудиотреков и обложек
- Просмотр профиля и треков
- Лайки и избранное
- Инвайты к совместным трекам

## Быстрый старт

### 1. Клонируйте репозиторий
```bash
git clone <repo_url>
cd SConnect
```

### 2. Установите зависимости
```bash
pip install -r requirements.txt
```

### 3. Примените миграции
```bash
python manage.py migrate
```

### 4. Создайте суперпользователя (админ)
```bash
python manage.py createsuperuser
```
Следуйте инструкциям (введите имя, email и пароль).

### 5. Запустите сервер
Вы можете запустить проект стандартно:
```bash
python manage.py runserver
```
или через скрипт:
```bash
bash run.sh
```

### 6. Откройте в браузере
```
http://127.0.0.1:8000/
```

### 7. Вход в админку
```
http://127.0.0.1:8000/admin/
```
Используйте данные суперпользователя для входа.
## Настройки
- Файлы загружаются в папку `media/`.
- В базе данных хранятся только пути к файлам.

## Пример .env (если потребуется)
```
DEBUG=True
SECRET_KEY=your_secret_key
```

## Для разработки
- Python 3.8+
- Django 5.x

---

**SConnect** — для быстрого старта музыкального проекта на Django!
