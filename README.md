# React TypeScript Tailwind Starter

A **modern frontend starter template** for building fast, scalable, and type-safe web applications using **React, TypeScript, and Tailwind CSS**, powered by **Vite as the build system**.

This setup is optimized for **developer experience and performance**, featuring instant hot module replacement (HMR), clean project structure, and production-ready tooling out of the box.

---

## Features

- **React 19**: Uses latest React version with improved performance and modern features.
- **TypeScript**: Strong typing for better maintainability and fewer runtime errors.
- **Tailwind CSS v4**: Utility-first CSS for rapid and consistent UI development.
- **Vite (Build System)**: Lightning-fast frontend tooling with instant dev server startup and optimized production builds.
- **ESLint**: Enforces code quality with React + TypeScript best practices.
- **Prettier**: Automatic code formatting for consistent style across the project.
- **React Compiler**: Optimized React compilation using Babel plugin.

---

## Tech Stack

- **Frontend Framework**: React 19
- **Language**: TypeScript
- **Styling**: Tailwind CSS v4
- **Build Tool**: Vite (modern frontend build system)
- **Linting**: ESLint v10 with React & TypeScript plugins
- **Formatting**: Prettier

---

## Prerequisites

- Node.js (v20 or higher — recommended: LTS versions like 22 or 24)
- Any package manager:
  - npm
  - yarn
  - pnpm
  - bun

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/chetan0121/react-ts-tailwind-template.git
cd react-ts-tailwind-template
```

### 2. Install dependencies

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

## VS Code Integration

Pre-configured task for smooth workflow:

- **Run Dev Server** → `Ctrl + Shift + B`

Default command:

```bash
bun run dev
```

You can change it in:

```
.vscode/tasks.json
```

Examples:

```bash
npm run dev
yarn dev
pnpm dev
```

---

## Available Scripts

```bash
npm run dev       # Start dev server (Vite)
npm run build     # Production build (Vite)
npm run preview   # Preview production build (runs /dist)
npm run lint      # Run ESLint
npm run format    # Format with Prettier
npm run ts-check  # Type checking
npm run release   # Format + lint + type-check + build
```

---

## Project Structure

```
src/
├── assets/          # Static files (images, icons, etc.)
├── components/      # Reusable UI components
├── pages/           # Page-level components
├── routes/          # Routing setup/config
├── App.tsx          # Root component
├── App.css          # Component-specific styles and animations
├── index.css        # Global styles (Tailwind)
└── main.tsx         # Entry point
```

---

## Why Vite?

- Instant server startup ⚡
- Fast HMR (no full reloads)
- Optimized production builds
- Native ES modules support

---

## License

MIT License — see [LICENSE](LICENSE)

---
