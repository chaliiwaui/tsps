<p align="center">
  <img src="./public/logo192.png" alt="tsps" width="120" height="120">
</p>

<h1 align="center">⚛️ tsps</h1>

<p align="center">
  A fresh Create React App starter - React 18 with the default welcome screen and a passing test -<br>
  set up in October 2022 as the base for a future project.
</p>

<p align="center">
  <a href="#-whats-inside">✨ What's inside</a> •
  <a href="#-quick-start">🚀 Quick Start</a> •
  <a href="#-scripts">📦 Scripts</a> •
  <a href="#-structure">🏗️ Structure</a> •
  <a href="#-testing">🧪 Testing</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-18-61DAFB?logo=react" alt="React 18">
  <img src="https://img.shields.io/badge/Create_React_App-5-09D3AC?logo=createreactapp" alt="Create React App 5">
  <img src="https://img.shields.io/badge/Testing_Library-React_13-E33332?logo=testinglibrary" alt="Testing Library">
  <img src="https://img.shields.io/badge/Jest-via_CRA-C21325?logo=jest" alt="Jest">
</p>

---

## ✨ What's inside

The repo is the unmodified Create React App template:

- **React 18** entry point using `ReactDOM.createRoot` and `StrictMode`
- **Welcome screen** (`src/App.js`) with the spinning React logo
- **Testing Library** + Jest DOM matchers, with one smoke test for the welcome screen
- **Web Vitals** hook (`src/reportWebVitals.js`) ready to forward metrics to an analytics endpoint
- **PWA manifest**, `robots.txt` and favicon/logo assets in `public/`
- **ESLint** config `react-app` + `react-app/jest` (in `package.json`)

## 🚀 Quick Start

```bash
npm install
npm start
```

The dev server opens `http://localhost:3000` and reloads on every change.

## 📦 Scripts

| Script          | Description                                                   |
| --------------- | ------------------------------------------------------------- |
| `npm start`     | Development server with hot reload and lint output            |
| `npm test`      | Jest in interactive watch mode                                |
| `npm run build` | Production build into `build/` (minified, hashed filenames)   |
| `npm run eject` | Copy the CRA configuration into the project (one-way)         |

## 🏗️ Structure

```
public/            # index.html, manifest.json, robots.txt, icons
src/
├── App.js         # Welcome screen
├── App.css
├── App.test.js    # Renders and checks the "Learn React" link
├── index.js       # Entry point
├── index.css
├── logo.svg
├── reportWebVitals.js
└── setupTests.js  # jest-dom matchers
```

## 🧪 Testing

```bash
CI=true npm test -- --watchAll=false
```

## 🚀 Deployment

`npm run build` creates a static bundle in `build/` that can be hosted on any static host (Vercel, Netlify, GitHub Pages, S3, …). See the [CRA deployment guide](https://create-react-app.dev/docs/deployment/).

## 📚 Create React App reference

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). See the [CRA documentation](https://create-react-app.dev/) for code splitting, bundle analysis, PWA setup and advanced configuration.

## 📄 License

No license has been chosen yet.

## 👤 Author

**Chalii wa UX/UI** - [@chaliiwaui](https://github.com/chaliiwaui)

- 📧 Email: me@makindajackson.com
- 💼 LinkedIn: [Jackson Makinda](https://linkedin.com/in/makindajack)
- 🎨 Dribbble: [@makindajack](https://dribbble.com/makindajack)
- 🐦 Twitter: [@makindajack](https://twitter.com/makindajack)

---

Built with ❤️ in Dar es Salaam, Tanzania 🇹🇿
