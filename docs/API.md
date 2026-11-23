# ПР 8. REST API

Base URL: `http://localhost:4000/api`

| Метод | URL | Тіло | Успіх | Помилки |
|---|---|---|---|---|
| GET | /items | — | 200 | 500 |
| GET | /items/:id | — | 200 | 404 |
| POST | /items | name,category,frequency,icon | 201 | 400 |
| PUT | /items/:id | name,category,frequency | 200 | 400,404 |
| DELETE | /items/:id | — | 200 | 404 |
| POST | /items/:id/toggle | date: YYYY-MM-DD | 200 | 400,404 |
| POST | /contact | name,email,phone,topic,message,consent | 201 | 400 |
| GET | /health | — | 200 | — |

Примітка: збереження JSON локальне, без автентифікації; API є демонстраційним, не готовим до публічного багатокористувацького сервісу. Контактні звернення не надсилаються email і не зберігаються.
