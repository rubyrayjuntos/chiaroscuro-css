# 🌒 ChiaroscuroCSS

> **Light, shadow, and balance, redefined for the web.**  
> A lightweight CSS micro-library for accessible neumorphism with personality-driven theming, responsive design, and WCAG compliance.

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![WCAG AA](https://img.shields.io/badge/accessibility-WCAG%202.1%20AA-brightgreen)](https://www.w3.org/WAI/WCAG21/quickref/)
[![npm](https://img.shields.io/npm/v/chiaroscuro-css.svg)](https://www.npmjs.com/package/chiaroscuro-css)
[![Demo](https://img.shields.io/badge/demo-online-green)](https://your-live-demo-link.com)

---

## ✨ Features

✅ Accessible neumorphic design  
✅ Personality-driven theme system (`serene`, `playful`, `mystical`, `professional`)  
✅ Fully responsive & mobile-first  
✅ WCAG 2.1 AA compliance & prefers-reduced-motion support  
✅ Declarative CSS variables for easy customization  
✅ Tiny footprint, framework-agnostic

---

## 🚀 Quick Start

### Install via npm
```bash
npm install chiaroscuro-css
```

### Or use via CDN
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/chiaroscuro-css@latest/neumorphic.css">
```

---

## 🌈 Themes

ChiaroscuroCSS ships with four personality-driven themes:  
- `serene` – calming greens  
- `playful` – warm yellows & oranges  
- `mystical` – deep purples  
- `professional` – cool greys  

To apply, simply set the `data-theme` attribute on `<body>` or a container:
```html
<body data-theme="mystical">
```

---

## 🎨 Usage Examples

### Raised
```html
<div class="neumorphic-raised">Raised</div>
```

### Inset
```html
<div class="neumorphic-inset">Inset</div>
```

### Beveled
```html
<div class="neumorphic-beveled">Beveled</div>
```

### Buttons
```html
<button class="btn btn-circular">+</button>
<button class="btn btn-pill">Pill</button>
```

See the [demo](https://your-live-demo-link.com) for more.

---

## 📐 Customization

ChiaroscuroCSS is built on CSS custom properties.  
You can override variables at runtime:
```css
:root {
  --accent-primary: #ff5722;
  --shadow-dark: rgba(0, 0, 0, 0.8);
}
```

---

## 🧑‍🦽 Accessibility

✅ WCAG 2.1 AA compliant colors  
✅ Keyboard navigation  
✅ Screen reader friendly  
✅ Respects `prefers-reduced-motion`  
✅ High contrast mode support

---

## 📦 Project Structure

```
/src/neumorphic.css   → Main stylesheet
/docs/                → Demo site
LICENSE
README.md
package.json
```

---

## 🤝 Contributing

ChiaroscuroCSS is an open-source project, maintained as part of [Ray Swan](https://ray.codes)’s creative portfolio. Contributions, feedback, and suggestions are warmly welcomed.

If you’d like to contribute:  
✅ Fork the repository  
✅ Create a feature branch (`git checkout -b feature/your-feature`)  
✅ Make your changes and test thoroughly  
✅ Submit a Pull Request with a clear description of your change

For feature requests, bug reports, or ideas, feel free to open an issue on GitHub.

---

## 👥 Governance

ChiaroscuroCSS is currently maintained as a personal project by [Ray Swan](https://ray.codes). Decisions about roadmap, merging, and releases remain at the discretion of the maintainer.

If the project attracts sustained community interest, governance may transition to a more formal structure (e.g., GitHub organization + maintainers).

All contributors are expected to adhere to a standard of respectful, inclusive collaboration.

---

## 📜 License

MIT License — see [LICENSE](LICENSE).

---

## 🌌 Author

Created by [Ray Swan](https://ray.codes) with love for accessible, creative design.  
Follow on [GitHub](https://github.com/rubyrayjuntos) and [LinkedIn](https://linkedin.com/in/raycswan).
