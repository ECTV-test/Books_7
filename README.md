# Book Reader Prototype

- Frontend: GitHub Pages (`index.html`, папка `books/`).
- Backend: Cloudflare Worker (переклад/озвучення через OpenAI, ключ у Worker secrets).

## Каталог книг: два варіанти

1) Ручний: редагуєш `books/index.json` руками.
2) Авто: локальний Python‑скрипт (папка `tools/`) генерує `books/index.json` за всіма `books/<id>/book.json`.
   Скрипт не запускається сам — ти запускаєш його вручну перед комітом.
