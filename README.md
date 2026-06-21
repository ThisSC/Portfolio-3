# Samuel Castro — Portfolio

Portafolio personal construido con **Astro 4**.

## 🚀 Inicio rápido

```bash
# 1. Instalar dependencias
npm install

# 2. Dev server (http://localhost:4321)
npm run dev

# 3. Build para producción
npm run build

# 4. Preview del build
npm run preview
```

## 📁 Estructura

```
src/
├── components/
│   ├── Nav.astro          # Navbar sticky + menú mobile
│   ├── Hero.astro         # Sección hero con profile card
│   └── ProjectCard.astro  # Card de proyecto con preview
├── layouts/
│   └── Layout.astro       # Layout base (head, fuentes, scroll-reveal)
├── pages/
│   └── index.astro        # Página principal (todas las secciones)
└── styles/
    └── global.css         # Variables CSS, utilidades, animaciones
```

## 🖼️ Agregar screenshots reales a los proyectos

1. Pon la imagen en `public/images/` (ej. `public/images/frameandwave.png`)
2. En `src/pages/index.astro`, descomenta la línea `screenshot:` del proyecto correspondiente:

```js
{
  title: 'Frame & Wave',
  screenshot: '/images/frameandwave.png',  // ← descomenta esto
  ...
}
```

## 🎨 Personalización rápida

- **Colores** → `src/styles/global.css` (variables `:root`)
- **Proyectos** → array `projects` en `src/pages/index.astro`
- **Habilidades** → array `skills` en `src/pages/index.astro`
- **Links sociales** → `src/components/Hero.astro` y sección contacto

## 🌐 Deploy

Funciona directo con **Vercel** o **Netlify** sin configuración extra.
Solo conecta el repo y despliega.
