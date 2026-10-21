# iMovie

🇧🇷 Português | [🇺🇸 English](README.en.md)

Aplicação web de catálogo de filmes construída com **React**, **TypeScript** e **Vite**, usando componentes acessíveis do **React Aria** e a base visual do **Untitled UI**.

> 🚧 **Em desenvolvimento:** por enquanto o repositório tem apenas a configuração do ambiente (tema, rotas, providers e utilitários). As telas do catálogo ainda serão implementadas.

## Stack

- React 19 + TypeScript
- Vite
- Tailwind CSS (plugin `@tailwindcss/vite`) + `tailwindcss-animate`
- React Aria Components + Untitled UI Icons
- React Router
- TanStack Query (busca e cache de dados)
- ESLint

## Estrutura

```
src/
├── hooks/       # use-breakpoint, use-clipboard
├── providers/   # RouteProvider (React Router + React Aria) e ThemeProvider
├── styles/      # tema e estilos globais
├── utils/       # helpers como cx (merge de classes)
├── App.tsx
└── main.tsx
```

## Como rodar

Pré-requisito: **Node.js 18+**.

```bash
npm install
npm run dev
```

A aplicação sobe em `http://localhost:5173`.

| Script | Descrição |
|---|---|
| `npm run dev` | Servidor de desenvolvimento com HMR |
| `npm run build` | Build de produção |
| `npm run preview` | Pré-visualiza o build |
| `npm run lint` | Executa o ESLint |
