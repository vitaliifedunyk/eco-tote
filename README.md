🌐 Read this in: [English](README.md) | [Українською](README.uk.md)

## 👜 EcoTote — TailwindCSS Rewrite

## 📄 Description
EcoTote is a personal rewrite of a completed GoIT group project, rebuilt with Tailwind CSS and Vite.  
It presents an eco-bag landing page with responsive sections, product cards, feedback, and a contact form.

## 🔗 Live Demo
Live demo link is not explicitly provided in this repository.

## 🧩 Features
- Single-page layout assembled from HTML partials (`header`, `menu`, `hero`, `about`, `advantages`, `assortment`, `gallery`, `feedbacks`, `support`, `footer`).
- Responsive design for mobile, tablet, and desktop with custom Tailwind breakpoints (`768px`, `1440px`).
- Mobile full-screen menu with open/close controls and body scroll lock.
- Smooth in-page anchor navigation from the mobile menu to target sections.
- Header, menu, and footer logo click handling that redirects to `index.html`.
- Assortment section with 8 static product cards (image, name, description, price, button).
- Responsive image delivery using `<picture>` + `1x/2x` `.webp` assets.
- Support form with native validation (`required`, `minlength`, `maxlength`, email `pattern`) and CSS invalid/valid states.

## 🛠 Tech Stack
- HTML5
- Tailwind CSS v4 (`tailwindcss`, `@tailwindcss/vite`)
- Vanilla JavaScript (ES modules)
- Vite 5
- Vite plugins: `vite-plugin-html-inject`, `vite-plugin-full-reload`
- PostCSS tooling: `postcss`, `postcss-sort-media-queries`
- `glob` for multi-entry HTML build input

## 📁 Project Structure
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

## 🚀 How to Run Locally
```bash
npm install
npm run dev
npm run build
npm run preview
```

## 🧠 What Was Implemented
- Tailwind-based responsive rewrite of the page layout and component styling.
- Modular HTML composition through partial injection in Vite.
- Interactive mobile navigation behavior and section scrolling logic in `main.js`.
- Custom Tailwind theme tokens (colors, fonts, breakpoints) and reusable utility/component layers.
- Background image switching by breakpoint and retina density for key sections.
- GitHub Actions workflow for automatic build and deploy to `gh-pages` on pushes to `main`.

## 👤 Author
**GoIT Student**  
GitHub: https://github.com/vitaliifedunyk
