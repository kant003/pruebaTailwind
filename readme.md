# Creamos proyecto con empaquetador Vite

```
npm create vite@latest
```

# instalamos dependencias

```
npm install
```

# instalamos tailwind

npm install -D tailwindcss postcss autoprefixer

npx tailwindcss init -p

# Configuramos tailwind

```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

# Añadimos las clases de css al fichero style.css

@tailwind base;
@tailwind components;
@tailwind utilities;


# Instalar la extensión de vscode de tailwind
