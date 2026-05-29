# Julio Mora Organization — juliomora.org

Corporate portfolio website for **Julio Mora Organization**, a diversified holding company.

## Portfolio Companies

| Company | Domain | Sector |
|---------|--------|--------|
| Sailing Religion | [sailingreligion.com](https://www.sailingreligion.com) | Nautical Lifestyle & Education |
| Faro Docente | [farodocente.com](https://www.farodocente.com) | AI-Powered EdTech |
| RefriproFL LLC | [refriprofl.com](https://refriprofl.com) | HVAC & Climate Solutions |

## Features

- **Bilingual (EN/ES)** — Toggle in the navbar; preference saved in `localStorage`
- **Responsive** — Mobile-first grid layout using Tailwind CSS
- **Dark mode** — Native dark theme with subtle gradients and glow effects
- **Uniform card height** — CSS Grid `items-stretch` ensures all cards match
- **Accessible contrast** — `bg-slate-800/40` backgrounds with `border-slate-500/30` borders
- **Legible typography** — `text-base` (16px) minimum for descriptions

## Quick Start

1. **Download** the entire `juliomora_org/` folder.
2. **Open** `index.html` in any modern browser — no build step needed.
3. Optionally serve with any static server:
   ```bash
   # Python
   cd juliomora_org && python3 -m http.server 8080

   # Node (npx)
   npx serve juliomora_org
   ```

## File Structure

```
juliomora_org/
├── index.html          # Single-page website
├── assets/
│   └── logo.png        # Julio Mora Organization logo
└── README.md           # This file
```

## Deployment

Upload the contents of this folder to any static hosting provider:
- **GitHub Pages** — push to a `gh-pages` branch
- **Netlify / Vercel** — drag-and-drop the folder
- **Shared hosting** — upload via FTP to the `public_html` directory

## Tech Stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Inter](https://fonts.google.com/specimen/Inter) font via Google Fonts
- Vanilla JavaScript (bilingual toggle)

---

© 2026 Julio Mora Organization
