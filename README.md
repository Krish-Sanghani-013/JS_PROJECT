# JS Project Vault

Welcome to the JS Project Vault — a curated collection of front-end experiments and micro-applications built with **extreme craftsmanship** in vanilla HTML, CSS, and JavaScript. Each project is designed to sharpen core web fundamentals while remaining modular, scalable, and ready for rapid iteration.

## 🚀 Current Lineup

| Project | Snapshot | Highlights |
| --- | --- | --- |
| `calculator/` | Minimalist calculator UI | Clean layout hierarchy, keyboard-first UX, resilient arithmetic engine |
| `Modern Login Page Design/` | Futuristic authentication shell | Fluid micro-interactions, layered glassmorphism, accessibility-first form handling |
| `weather forecasting/` | Weather insights dashboard | Async data flows, animated state transitions, responsive layout grid |

> Planning more builds? Mirror the structure above to keep the vault cohesive.

## 🔧 Stack and Tooling

- Pure HTML5, modern CSS3 (Flexbox/Grid), and modular ES6 JavaScript — no frameworks hiding the fundamentals.
- Utility-first CSS snippets for rapid prototyping while keeping selectors semantic.
- JavaScript organized by feature, relying on strict mode and descriptive naming to avoid silent failures.
- Git-driven workflow following feature branches merged into `main` after review.

## 🗂️ Repository Structure

```
.
├── calculator/
│   ├── calculator.html
│   └── calculator.css
├── Modern Login Page Design/
│   ├── login.html
│   ├── login.css
│   └── login.js
├── weather forecasting/
│   ├── weather.html
│   ├── weather.css
│   ├── weather.js
│   └── assets/
└── README.md
```

Add new projects as sibling directories following the same convention: concise folder name, entry HTML file, dedicated CSS/JS modules, and optional `assets/` for static media.

## ⚡ Quick Start

1. Clone the repo or pull the latest from `main`.
2. Open any project folder in your browser by dragging the HTML file into the window or serving via your favorite static server.
3. Iterate aggressively: tweak styles, wire up JS modules, and validate behavior across viewports.
4. Commit with meaningful messages (`feat: add temperature trend animation`) and push.

## 🧪 Quality Checklist

Before declaring victory on a project:

- ✅ Layout holds up from 320px to 1440px+.
- ✅ Interactions remain smooth at 60fps.
- ✅ Keyboard navigation and screen-reader labels are verified.
- ✅ CSS and JS are linted (use `npx stylelint **/*.css` and `npx eslint **/*.js` if configs are present).
- ✅ README entry updated with a one-liner and highlight bullet.

## 🛠️ Scaling the Vault

- Modularize shared patterns (buttons, cards, loaders) into `components/` if reuse emerges.
- Automate builds with a lightweight bundler (Vite, Parcel) when bundle size or SASS/PostCSS becomes essential.
- Add testing with Playwright or Cypress for interactive flows once projects go beyond static prototypes.

## 🤝 Contributing (Future-Proofed)

1. Fork or branch from `main`.
2. Implement features with isolated commits and human-readable messages.
3. Open a PR with screenshots/GIFs and outline the tech decisions.

## 📈 Vision

The JS Project Vault is a perpetual playground: every project should teach a nuance—be it async patterns, accessibility wins, or micro-animation timing. Keep builds lean, performant, and visually sharp. Extreme coding isn’t about complexity for its own sake; it’s about deliberate craftsmanship at every layer.
