🌐 Читати: [English](README.md) | [Українською](README.uk.md)

## 👜 EcoTote — TailwindCSS Rewrite

## 📄 Опис
EcoTote — це персональний перепис завершеного командного проєкту GoIT із використанням Tailwind CSS та Vite.  
Проєкт реалізує лендинг про еко-сумки з адаптивними секціями, картками товарів, відгуками та формою зв’язку.

## 🔗 Live Demo
Посилання на live demo явно не вказано в цьому репозиторії.

## 🧩 Функціональність
- Односторінковий макет, зібраний з HTML partials (`header`, `menu`, `hero`, `about`, `advantages`, `assortment`, `gallery`, `feedbacks`, `support`, `footer`).
- Адаптивний дизайн для mobile, tablet і desktop із кастомними breakpoint у Tailwind (`768px`, `1440px`).
- Повноекранне мобільне меню з відкриттям/закриттям і блокуванням скролу сторінки.
- Плавна навігація по якірних посиланнях із мобільного меню до відповідних секцій.
- Обробка кліку по логотипу в header/menu/footer з переходом на `index.html`.
- Секція асортименту з 8 статичними картками товарів (зображення, назва, опис, ціна, кнопка).
- Адаптивна подача зображень через `<picture>` і `.webp` assets у варіантах `1x/2x`.
- Форма зв’язку з нативною валідацією (`required`, `minlength`, `maxlength`, email `pattern`) і CSS-станами valid/invalid.

## 🛠 Технології
- HTML5
- Tailwind CSS v4 (`tailwindcss`, `@tailwindcss/vite`)
- Vanilla JavaScript (ES modules)
- Vite 5
- Vite плагіни: `vite-plugin-html-inject`, `vite-plugin-full-reload`
- PostCSS інструменти: `postcss`, `postcss-sort-media-queries`
- `glob` для multi-entry HTML під час збірки

## 📁 Структура проєкту
```text
eco-tote/
├── .github/workflows/deploy.yml
├── src/
│   ├── css/styles.css
│   ├── img/
│   ├── partials/
│   ├── public/favicon.svg
│   ├── index.html
│   └── main.js
├── package.json
├── package-lock.json
└── vite.config.js
```

## 🚀 Локальний запуск
```bash
npm install
npm run dev
npm run build
npm run preview
```

## 🧠 Що реалізовано
- Tailwind-орієнтований адаптивний rewrite верстки та стилів сторінки.
- Модульна HTML-структура через partial injection у Vite.
- Інтерактивна логіка мобільної навігації та прокрутки між секціями в `main.js`.
- Кастомні theme-токени Tailwind (кольори, шрифти, breakpoints) і власні utility/component шари.
- Перемикання фонових зображень за breakpoint та retina-щільністю для ключових секцій.
- GitHub Actions workflow для автоматичної збірки та деплою в `gh-pages` при push у `main`.

## 👤 Author
**GoIT Student**  
GitHub: https://github.com/vitaliifedunyk
