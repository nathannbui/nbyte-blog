# mac OS inspired blog page


A macOS Tahoe-themed blog page plate built with React, TypeScript, Vite, and Tailwind CSS. Features a fully interactive desktop environment with draggable windows, a dock, menu bar, Finder, Terminal, and Safari — all running in the browser.


![React](https://img.shields.io/badge/React-19-blue?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9-blue?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-blue?logo=tailwindcss)
![Vite](https://img.shields.io/badge/Vite-7-purple?logo=vite)
![License](https://img.shields.io/badge/License-MIT-green)


## Features


- **macOS Desktop UI** — Realistic desktop with wallpaper, menu bar, dock, and draggable windows
- **Finder Window** — Portfolio browser with sidebar categories, list/grid view toggle, and macOS-style column headers
- **Terminal Window** — Animated terminal with typing effect showing your bio, skills, and social links
- **Safari Window** — Blog article viewer with external link preview cards
- **Dock** — Animated dock with bounce effects, tooltips, and running indicators
- **Menu Bar** — Live clock, dark/light mode toggle, Wi-Fi, battery, and Control Center icons
- **Dark Mode** — Full dark/light mode support with one-click toggle
- **Config-Driven** — All content lives in a single `src/config.ts` file for easy customization
- **SEO Ready** — Open Graph, Twitter Cards, and JSON-LD structured data
- **Responsive** — Works on desktop and tablet screens
- **Deploy Anywhere** — Vercel, Netlify, GitHub Pages, or any static host




Open [http://localhost:5173](http://localhost:5173) to see portfolio.


## Customization


All customizable content is in **one file**: `src/config.ts`






## Project Structure


```
macos-tahoe-portfolio/
├── public/
│   ├── images/
│   │   ├── macos-icons/          # macOS dock icons (18 icons)
│   │   └── macos-tahoe-wallpaper.jpg
│   └── robots.txt
├── src/
│   ├── config.ts                 # <-- Edit this file to customize
│   ├── main.tsx
│   ├── App.tsx
│   ├── index.css
│   ├── components/
│   │   ├── SEO.tsx
│   │   ├── ScrollToTop.tsx
│   │   └── macos/
│   │       ├── Desktop.tsx       # Main desktop container
│   │       ├── DesktopContext.tsx # Window state management
│   │       ├── Dock.tsx          # Application dock
│   │       ├── FinderContent.tsx # Portfolio browser
│   │       ├── MenuBar.tsx       # Top menu bar
│   │       ├── SafariContent.tsx # Blog viewer
│   │       ├── TerminalContent.tsx # Terminal animation
│   │       └── Window.tsx        # Draggable window
│   └── pages/
│       ├── Home.tsx
│       └── NotFound.tsx
├── package.json
├── vite.config.ts
├── tsconfig.json
└── vercel.json
```


## Deployment


### Vercel (Recommended)


[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/nerdynikhil/macos-tahoe-portfolio)


### Netlify


```bash
npm run build
# Deploy the `dist` folder
```


### GitHub Pages


```bash
npm run build
# Deploy the `dist` folder to your GitHub Pages repo
```


## Tech Stack


| Technology | Purpose |
|---|---|
| [React 19](https://react.dev) | UI framework |
| [TypeScript 5.9](https://typescriptlang.org) | Type safety |
| [Vite 7](https://vite.dev) | Build tool |
| [Tailwind CSS 4](https://tailwindcss.com) | Styling |
| [React Router 7](https://reactrouter.com) | Client-side routing |
| [React Helmet Async](https://github.com/staylor/react-helmet-async) | SEO meta tags |


## License


MIT License. See [LICENSE](LICENSE) for details.


---


Made by [@nerdynikhil](https://github.com/nerdynikhil). If you use this template, a star on the repo would be appreciated!

