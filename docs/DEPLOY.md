# ПР 10. Публікація і захист

1. Створити GitHub repo; завантажити код. Розподілити роботу на ≥30 реальних комітів, гілки, PR, Issues, теги pr-01…pr-10. Не створювати фальшиву історію.
2. Netlify: base `client`, build `npm run build`, publish `client/dist` (налаштування залежить від base directory); змінна `VITE_API_URL=https://YOUR-SERVER`. Додати SPA redirect `/* /index.html 200`.
3. Render: root `server`, install `npm install`, start `npm start`; env `CLIENT_ORIGIN=https://YOUR-SITE`. Для постійних даних використати persistent disk/SQLite/Postgres; без цього JSON може обнулятися.
4. Відкрити frontend/API, протестувати CRUD, контактну форму, календар, статистику, PWA-інсталяцію.
5. Запустити Lighthouse/axe; зберегти скриншоти й реальні результати.
6. Додати URL у README, Figma URL, GitHub Release v1.0.0.
7. Заповнити щоденник та звіт реальними датами і результатами.
