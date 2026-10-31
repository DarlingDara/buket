# Buket Moldavii — Astro Foundation v1

Основа: `Buket_Moldavii_v2.zip`. Дизайн и содержание существующей главной страницы сохранены.

## Запуск

Нужен Node.js 20.19+ или 22.12+.

```bash
npm install
npm run dev
npm run build
```

Откройте адрес, показанный командой `npm run dev` (обычно `http://localhost:4321`).

## Cloudflare Pages

- Framework preset: **Astro**
- Build command: **npm run build**
- Build output directory: **dist**
- Root directory: **/**

В GitHub загружайте **содержимое этой папки в корень ветки `astro-development`**, а не ZIP-файл и не вложенную папку.

## Структура

- `src/pages/index.astro` — главная страница, исходные секции.
- `src/components/Header.astro` — шапка/hero и меню.
- `src/components/Footer.astro` — подвал.
- `src/layouts/BaseLayout.astro` — общий HTML, метаданные, шрифты и скрипт.
- `src/styles/styles.css` — утверждённые стили.
- `src/scripts/main.js` — поведение мобильного меню.
- `public/assets/` — исходные изображения.

## Границы этапа

Это **только миграция основы**, не разработка каталога. Страницы товаров, языковые версии, маршруты и SEO-шаблоны будут проектироваться на следующем этапе после согласования карты сайта и модели данных. Ссылки-якоря главной страницы пока сохранены. Проверки сборки, мобильного меню и визуального соответствия обязательны до публикации.
