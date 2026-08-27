# Soli-Devs — Web Application

Frontend Web Application (SPA) integrada con el RESTful API interno.
Curso **1ASI0730 – Aplicaciones Web** — UPC, Ciclo 2026-20.

## Tech stack

- [Vue 3](https://vuejs.org/) (Composition API) + Vite
- [PrimeVue](https://primevue.org/) como biblioteca de componentes UI
- Lenguaje de diseño basado en **Material Design**
- HTML5 / CSS3 / JavaScript
- i18n: English (`en-US`, default) & Latin American Spanish (`es-419`)
- Accessibility: WAI-ARIA attributes, responsive web design

## Planned features

- Autenticación y gestión de sesiones
- Experiencia por segmento objetivo (call-to-actions del Landing → vistas de la app)
- Integración con el RESTful API interno (`Soli-Devs/web-services`)
- Integración con servicio externo de terceros

## Getting started

```bash
git clone https://github.com/Soli-Devs/web-application.git
cd web-application
npm install
npm run dev      # development server
npm run build    # production build
```

## Version control workflow

- **GitFlow**: `main` (releases) / `develop` (integración) / `feature/*` branches
- **Conventional Commits** + **Semantic Versioning**
