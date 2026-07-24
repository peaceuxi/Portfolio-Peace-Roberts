# Portfolio

## Getting started in VS Code

1. Unzip this folder and open it in VS Code.
2. Install dependencies:
   ```
   npm install
   ```
3. Run the dev server:
   ```
   npm run dev
   ```
4. Open the local URL it prints (usually http://localhost:5173).

## Structure

- `src/App.jsx` — the whole portfolio page (all sections/components).
- `src/main.jsx` — React entry point.
- `src/index.css` — Tailwind imports.
- `public/assets/` — project cover images (referenced as `/assets/...` in `App.jsx`).

## Build for production

```
npm run build
```

Output goes to `dist/`, ready to deploy (Vercel, Netlify, etc.).
