# React Router Official Documentation & Website

The official documentation website, tutorial guides, and interactive API reference for React Router built with React Router v7, React 19, Vite, Express, Algolia DocSearch, and Shiki.

## Overview

`react-router-website` powers the official documentation platform for React Router v7. It features server-side rendering with `@react-router/express`, unified Markdown/MDX parsing (Unified, Remark, Rehype), syntax highlighting (Shiki), Algolia DocSearch integration, and Docker containerization.

## Tech Stack

- **Framework**: [React Router](https://reactrouter.com/) (v7 with `@react-router/express` server)
- **Frontend Core**: React 19, TypeScript
- **Documentation Pipeline**: Unified, Remark GFM, Rehype, Shiki syntax highlighter
- **Search**: Algolia DocSearch (`@docsearch/react`)
- **Styling**: Tailwind CSS (`@tailwindcss/postcss`, Tailwind v3)
- **Testing**: Vitest, Happy DOM
- **Deployment**: Docker, Fly.io (`fly.production.toml`)

## Prerequisites

- Node.js (v22 or higher recommended)
- Package manager (`npm`)

## Getting Started

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Configure Environment Variables**:
   Copy `.env.example` to `.env`:
   ```bash
   cp .env.example .env
   ```

3. **Run the Development Server**:
   ```bash
   npm run dev
   ```

4. **Access the Documentation**:
   Open `http://localhost:3000` in your web browser.

## Available Scripts

- `npm run dev` - Starts the development Express server with React Router HMR.
- `npm run build` - Compiles the production build via `react-router build`.
- `npm start` - Starts the production Express server.
- `npm test` - Runs unit test suite via Vitest.
- `npm run typecheck` - Runs React Router typegen and TypeScript validation.
- `npm run format` - Formats the codebase using Prettier.

## Author

Created by [Mehfooz-ur-Rehman](https://github.com/MehfoozurRehman).
