# Vite + Tailwind CSS Starter

A minimal, clean starter template combining React 18, Vite, and Tailwind CSS for rapid modern frontend development.

---

## Overview

This repository provides an instant setup for building React applications styled with Tailwind CSS, powered by Vite's fast hot module replacement (HMR). It eliminates manual configuration so you can start coding your UI components immediately.

---

## Features

- **React 18**: Component-based UI with modern hooks and JSX.
- **Vite 4**: Fast build tool with near-instant dev server startup and hot reload.
- **Tailwind CSS v3**: Pre-configured utility-first styling with PostCSS and Autoprefixer.
- **Clean Structure**: Minimal project layout ready for your custom pages and components.

---

## Tech Stack

- **Framework**: React 18
- **Bundler**: Vite 4
- **Styling**: Tailwind CSS v3, PostCSS, Autoprefixer
- **Package Manager**: Yarn (or npm / pnpm)

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/iamjunaidjutt/vite-tailwindcss-app.git
cd vite-tailwindcss-app
```

### 2. Install dependencies

```bash
yarn install
# or
npm install
```

### 3. Run the development server

```bash
yarn dev
# or
npm run dev
```

Open your browser and navigate to `http://localhost:5173` to see the application running.

---

## Available Scripts

- `yarn dev` — Starts the local Vite development server with HMR.
- `yarn build` — Compiles and minifies production-ready assets into the `dist/` directory.
- `yarn preview` — Locally previews the built production assets.

---

## Project Structure

```
vite-tailwindcss-app/
├── public/                # Static public assets
├── src/
│   ├── App.jsx            # Root application component
│   ├── main.jsx           # React DOM entry point
│   └── index.css          # Tailwind CSS directives
├── index.html             # HTML template
├── package.json           # Dependencies and scripts
├── postcss.config.cjs     # PostCSS configuration
├── tailwind.config.cjs    # Tailwind CSS theme configuration
└── vite.config.js         # Vite bundler configuration
```

---

## License

This project is open-source and available under the [MIT License](LICENSE).
