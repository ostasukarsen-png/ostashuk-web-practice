# HabitFlow — трекер звичок (варіант 19)

Навчальна практика «WEB-технології та WEB-дизайн». React/Vite + Node.js/Express. Обов’язкова функція: календар виконання і статистика.

## Локальний запуск

Потрібен Node.js 20+. У корені проєкту: `npm install`, потім `npm install --prefix client`, `npm install --prefix server`. У двох терміналах: `npm run dev --prefix server` і `npm run dev --prefix client`. Відкрийте http://localhost:5173. API: http://localhost:4000/api/health. Альтернативно `npm run dev` після встановлення кореневих залежностей.

## Тести

`npm test` — клієнтські Vitest і серверні Node tests. `npm run build --prefix client` — production-збірка.

## Структура

- `client/src` — React, маршрути, компоненти, стилі, валідація, тести.
- `client/static` — статичні HTML/CSS/JS-артефакти ПР 4–6.
- `server` — REST API та JSON-сховище.
- `docs` — ТЗ, UX, дизайн, API, AI, аудит, щоденник, звітні матеріали.
- `postman` — колекція API-запитів.

## Деплой

Frontend: Netlify/Vercel, root `client`, build `npm run build`, output `dist`; встановити `VITE_API_URL` як повний URL сервера без `/api`. Backend: Render/Railway, root `server`, start `npm start`, `CLIENT_ORIGIN` — URL клієнта. Увага: JSON-файл на бездискових/ефемерних хостингах може втрачати зміни; для реального деплою потрібен постійний диск або БД.

**Репозиторій:** [додати URL після публікації]. **Деплой:** [додати URL]. **Figma:** [додати URL після створення макетів].

## Важливо

Git-історія, Pull Requests, 30 реальних комітів, Figma-файл, результати Lighthouse/axe, скриншоти та перевірка деплою не можуть бути підтверджені архівом і мають бути виконані окремо. Контактна форма демонстраційна: перевіряє і приймає запит, але не надсилає листа.
