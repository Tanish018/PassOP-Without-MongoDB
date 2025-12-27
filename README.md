# PassOP

 A lightweight client-side password manager built with React and Vite — stores data locally (no MongoDB).

 ## Features

 - Add, view, and manage saved credentials
 - Password copying to clipboard
 - Persisted in browser `localStorage` (no server required)
 - Simple, responsive UI using React components

 ## Tech Stack

 - React (JSX)
 - Vite
 - Plain CSS

 ## Prerequisites

 - Node.js v16+ and npm

 ## Quick Start

 1. Install dependencies

 ```bash
 npm install
 ```

 2. Run development server

 ```bash
 npm run dev
 ```

 3. Build for production

 ```bash
 npm run build
 ```

 4. Preview production build

 ```bash
 npm run preview
 ```

 ## Project Structure (key files)

 - `index.html` — app entry HTML
 - `vite.config.js` — Vite config
 - `src/main.jsx` — React entry
 - `src/App.jsx` — main App component
 - `src/components/Manager.jsx` — password manager UI and logic
 - `src/components/Navbar.jsx` — top navigation
 - `src/components/Footer.jsx` — footer

 If you need to inspect or modify storage logic, check `src/components/Manager.jsx`.

 ## Environment

 No external API or database is required. All data is stored locally in the browser.

 ## Contributing

 1. Fork the repo
 2. Create a feature branch (`git checkout -b feature/my-change`)
 3. Commit your changes (`git commit -m "feat: ..."`)
 4. Push and open a PR

 ## License

 MIT

 ---

 If you'd like a more detailed README (screenshots, security notes, encryption instructions, or CI/CD), tell me what to include and I'll update it.
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
