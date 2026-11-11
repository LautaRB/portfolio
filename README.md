# 🍱 Portfolio — Bento Box UI

![Astro](https://img.shields.io/badge/Astro-4.0%2B-BC52EE?logo=astro&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwindcss&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?logo=typescript&logoColor=white)
![GitHub API](https://img.shields.io/badge/API-GitHub_REST-181717?logo=github&logoColor=white)

Portfolio personal de desarrollador diseñado desde cero bajo el concepto visual de una **Bento Box japonesa** minimalista e interactiva. Construido con **Astro**, **Tailwind CSS** y **TypeScript** para lograr una arquitectura modular, animaciones fluidas y máximo rendimiento estático.

> 🌐 **Demo en vivo:** [(https://lautarb-portfolio.netlify.app/)]

---

## 🔑 Funcionalidades Principales

- **Interfaz Bento Box Interactiva:** Diseño en grilla inspirado en cajas bento tradicionales, con compartimentos que cuentan con tapas interactivas animadas al hacer clic o *hover*.
- **Stack Tecnológico Modular ("Mamushka" UI):** Sección de habilidades técnicas organizada en sub-cajas anidadas por categoría (Frontend, Backend, Base de Datos, Herramientas e Infraestructura) para mantener una jerarquía visual limpia.
- **Sincronización Dinámica con GitHub:** Integración con la **GitHub REST API** para obtener y renderizar automáticamente los últimos 4 repositorios públicos actualizados sin necesidad de modificar el código manualmente.
- **Diseño Dark Mode & Responsive:** Estética oscura de alto contraste con acentos en rojo, completamente adaptada a dispositivos móviles, tablets y pantallas de escritorio.
- **Acceso Directo a CV y Contacto:** Integración de descarga directa de currículum en PDF y enlaces rápidos a redes profesionales.

---

## 📂 Estructura del Proyecto

Arquitectura basada en componentes modulares de Astro con tipado estricto en TypeScript:

```text
portfolio/
├── public/              # Archivos estáticos públicos (Favicon 'L', CV en PDF, assets)
├── src/
│   ├── pages/           # Ruta principal de la aplicación (index.astro)
│   └── styles/          # Configuración y directivas globales de Tailwind CSS
├── astro.config.mjs     # Configuración del framework Astro
├── tailwind.config.mjs  # Paleta de colores personalizada, grillas y animaciones
├── tsconfig.json        # Configuración de TypeScript
└── package.json         # Dependencias y scripts de ejecución
```
---

## ⚙️ Instalación y Ejecución Local

### Prerrequisitos
- **Node.js** (v18 o superior)
- **npm** o **pnpm**

### 1. Clonar el repositorio
```bash
git clone [https://github.com/LautaRB/tu-repo-portfolio.git](https://github.com/LautaRB/tu-repo-portfolio.git)
cd tu-repo-portfolio
```

### 2. Instalar dependencias
```bash
pnpm install
# o con npm:
npm install
```

### 3. Iniciar el servidor de desarrollo
```bash
pnpm run dev
# o con npm:
npm run dev
```

El sitio estará disponible localmente en `http://localhost:4321/`.

---

## 📦 Build de Producción

Para generar la versión estática optimizada lista para desplegar (Netlify / Render / Vercel):

```bash
pnpm run build
pnpm run preview
```

---

## 📜 Licencia
Distribuido bajo la licencia MIT.
