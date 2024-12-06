# Dry-Cleaner Web

## Установка и настройка проекта

### Шаг 1: Создание виртуального окружения

```bash
python3 -m venv venv
```

### Шаг 2: Активация виртуального окружения

- На Windows:
  ```bash
  .\venv\Scripts\activate
  ```
- На macOS и Linux:
  ```bash
  source venv/bin/activate
  ```

### Шаг 3: Установка зависимостей

Убедитесь, что файл `requirements.txt` находится в корне проекта, затем выполните команду:

```bash
pip install -r requirements.txt
```

### Шаг 4: Применение миграций

Для настройки базы данных выполните команду:

```bash
python manage.py migrate
```

### Шаг 5: Создание тестового суперпользователя

Для создания суперпользователя выполните команду и следуйте инструкциям на экране:

```bash
python manage.py createsuperuser
```

### Шаг 6: Запуск сервера

Для запуска сервера разработки выполните команду:

```bash
python manage.py runserver
```

Теперь ваш проект должен быть запущен и доступен по адресу `http://127.0.0.1:8000/`.

### Зависимости

Список зависимостей, указанных в `requirements.txt`:

- asgiref==3.8.1
- Django==5.1.4
- sqlparse==0.5.2
- tzdata==2024.2

### Данные для входа в админ-панель

- **Логин**: root
- **Пароль**: 12345

Ссылка для входа в админ-панель: [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

