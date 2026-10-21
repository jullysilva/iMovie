# iMovie

[🇧🇷 Português](README.md) | 🇺🇸 English

Movie catalog web app built with **React**, **TypeScript** and **Vite**, using accessible **React Aria** components and the **Untitled UI** visual foundation.

> 🚧 **Work in progress:** for now the repository only contains the environment setup (theme, routing, providers and utilities). The catalog screens are yet to be built.

## Stack

- React 19 + TypeScript
- Vite
- Tailwind CSS (`@tailwindcss/vite` plugin) + `tailwindcss-animate`
- React Aria Components + Untitled UI Icons
- React Router
- TanStack Query (data fetching and caching)
- ESLint

## Structure

```
src/
├── hooks/       # use-breakpoint, use-clipboard
├── providers/   # RouteProvider (React Router + React Aria) and ThemeProvider
├── styles/      # theme and global styles
├── utils/       # helpers such as cx (class merging)
├── App.tsx
└── main.tsx
```

## Getting started

Requirement: **Node.js 18+**.

```bash
npm install
npm run dev
```

The app runs at `http://localhost:5173`.

| Script | Description |
|---|---|
| `npm run dev` | Dev server with HMR |
| `npm run build` | Production build |
| `npm run preview` | Preview the build |
| `npm run lint` | Run ESLint |
