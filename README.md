# Mario Ochoa— Portfolio

Personal portfolio website for Mario Abraham Ochoa Tovar, Senior Mobile & Fullstack Developer.

## Stack

Pure HTML + CSS. No frameworks, no build step, no dependencies.

- **Typography:** Manrope (headlines) + Inter (body) via Google Fonts
- **Icons:** Material Symbols Outlined
- **Deploy:** GitHub Pages via GitHub Actions

## Features

- Glassmorphism navigation with scroll-spy
- Fluid typography with `clamp()`
- CSS custom properties design system (full Material You token palette)
- Responsive bento grid for skills
- Grayscale-to-color hover on project cards
- Zero JavaScript except for the IntersectionObserver scroll-spy

## Deploy

Pushes to `main` automatically deploy to GitHub Pages via `.github/workflows/deploy.yml`.

---

## Built with

| Tool                                           | Role                                  |
| ---------------------------------------------- | ------------------------------------- |
| [Google Stitch](https://stitch.withgoogle.com) | UI design & screen generation         |
| [Antigravity](https://antigravity.dev)         | Skill management & agent tooling      |
| [Claude Code](https://claude.ai/code)          | Code generation & workflow automation |

> Design system extracted directly from the Stitch project via MCP, then translated to semantic CSS custom properties by Claude Code.
