# Furniture Management System

Backend-система для управления заказами мебельной компании.

## Требования

- Python 3.11.9

## Запуск

Создать виртуальное окружение:

    python -m venv .venv

Активировать окружение (Windows):

    .venv\Scripts\activate

Установить зависимости:

    pip install -r requirements.txt

Запустить приложение:

    uvicorn src.main:app --reload

После запуска API доступно по адресу:
http://127.0.0.1:8000

Swagger:
http://127.0.0.1:8000/docs

## Проверка работоспособности

После запуска выполнить:

    GET /health

Ожидаемый ответ:

    {"status": "ok"}

HTTP status: 200.

## Проверка запуска

- Дата: 19.10.2026
- ОС: Windows
- Python: 3.11.9
- Проверил: автор проекта
- Результат: приложение успешно запускается, GET /health возвращает HTTP 200.