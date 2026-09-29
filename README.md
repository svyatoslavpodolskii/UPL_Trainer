# Опора — GitHub Pages

Структура:
- index.html
- questions/test1.md ... questions/test40.md
- PROMPT.txt

GitHub Pages:
1. Загрузите содержимое папки в репозиторий.
2. Settings → Pages → Deploy from a branch.
3. Выберите main / root.
4. Сайт автоматически пытается загрузить test1.md…test40.md.
5. Отсутствующие файлы просто пропускаются.

Для 400 вопросов генерируйте по 10 вопросов в каждом testN.md.
Прогресс хранится в localStorage конкретного браузера.
