# @netoum/corex-tailwind

[Corex](https://www.npmjs.com/package/@netoum/corex) default Tailwind package providing global design tokens and component-level utility styles for scalable UI development.

---

## 📦 About

This package provides precompiled CSS styles for the [Corex](https://netoum.com/corex) UI system. It includes:

- 🎨 Global design tokens (colors, spacing, typography, etc.)
- 🧩 Component-level utility styles
- 🔧 Built from design tokens compatible with Tokens Studio files 
- 🌗 Multiple themes (Neo, Revo, Uno) with light/dark modes
- 🚀 Ready-to-use CSS for scalable design systems and modern UIs
---

## 📦 Installation

```bash
npm install @netoum/corex-tailwind
```

## 💡 Usage

### Import a full theme stylesheet:

```css
@import "@netoum/corex-tailwind/neo.css";   /* or revo.css, uno.css */
/* or */
@import "@netoum/corex-tailwind/neo/light.css";   /* or dark.css*/
/* or */
@import "@netoum/corex-tailwind/revo/light.css";   /* or dark.css*/
/* or */
@import "@netoum/corex-tailwind/uno/light.css";   /* or dark.css*/

```

### Import component-level styles:

```css
@import "@netoum/corex-tailwind/components/button.css";
```

### Import token-based styles directly:

```css
@import "@netoum/corex-tailwind/tokens/global/color.css";
@import "@netoum/corex-tailwind/tokens/neo/light/semantic/color.css";
```

💡 You can explore all available paths in the exports section of package.json.

## 🛠️ Development

### 🔧 Full Build (from design tokens)

Build all themes and modes (light/dark) using token configurations:

```bash
npm run build
```

### ⚡ CSS Build Only (skip design tokens)

Skip token processing and rebuild only the final output CSS:

```bash
npm run build:from:css
```

### 🔍 Lint

```bash
npm run lint
```

## 📜 License

MIT © Netoum

## 🤝 Built by Netoum

Corex is built by Netoum — a web agency specializing in modern applications using HTML, Vanilla JS, TypeScript, Elixir/Phoenix, and accessibility-first development.

Creating exceptional web experiences for clients worldwide.

**Get in touch:** info@netoum.com