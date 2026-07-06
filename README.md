# PROCSIM

Proyecto base (Vite + React) para correr el componente PROCSIM localmente.

## Cómo correrlo

1. Descomprime este .zip directamente en `C:\Users\User\Documents\ProcSim`
   (reemplazando lo que ya había, o en una carpeta nueva).
2. Abre una terminal en esa carpeta.
3. Instala dependencias:

   ```
   pnpm install
   ```

   (o `npm install` si no usas pnpm)

4. Corre el servidor de desarrollo:

   ```
   pnpm run dev
   ```

   (o `npm run dev`)

5. Abre la URL que aparezca en la terminal (normalmente `http://localhost:5173`).

## Estructura

```
ProcSim/
├── index.html
├── package.json
├── vite.config.js
└── src/
    ├── main.jsx     ← punto de entrada, monta <App />
    ├── index.css    ← estilos base
    └── App.jsx      ← tu componente PROCSIM (Ejemplos + Editor)
```

Para actualizar el componente más adelante, solo reemplaza `src/App.jsx`
por la versión nueva — no necesitas tocar nada más de esta estructura.
