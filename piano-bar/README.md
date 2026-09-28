# Proyecto Piano Bar - Primera Entrega

Este proyecto corresponde a la primera entrega del sitio web **"Piano Bar"**, enfocado en la arquitectura semántica HTML5, la jerarquía de contenidos y la identidad visual basada en la estética de cartelera y tablero de corcho colaborativo.

---

## 📁 Estructura de Archivos

```
piano-bar/
├── index.html        # Estructura principal semántica del sitio web
├── styles.css        # Hoja de estilos (paleta vintage, tablero de corcho y post-its)
├── README.md         # Documentación de la entrega y cumplimiento de consignas
└── images/           # Recursos visuales locales de alta resolución
    ├── logo.svg
    ├── hero.jpg
    ├── sobre-nosotros.jpg
    ├── lugar-1.jpg a lugar-4.jpg
    └── galeria-1.jpg a galeria-4.jpg
```

---

## 📋 Cumplimiento de Requisitos de la Consigna

| Requisito | Estado | Implementación |
| :--- | :---: | :--- |
| **Página principal llamada `index.html`** | Cumplido | Archivo [`index.html`](file:///c:/Users/juans/OneDrive/Documentos/piano-bar/index.html) con `<!DOCTYPE html>`, `lang="es"`, metadatos y enlaces tipográficos. |
| **Estructura semántica HTML5** | Cumplido | Uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<figcaption>`, `<aside>`, `<footer>`. |
| **Header con nombre o logo** | Cumplido | Logotipo SVG estilizado de Piano Bar con teclas y tipografía de imprenta. |
| **Título temático en Header** | Cumplido | Bajada: *"El punto de encuentro entre músicos independientes y espacios culturales"*. |
| **Menú de navegación con lista no ordenada** | Cumplido | `<nav>` con `<ul>` y enlaces ancla: Inicio, Lugares, Sobre Piano Bar, Galería, Datos Destacados, Enlaces, ¿Querés Tocar? |
| **Sección de Presentación (Main)** | Cumplido | Bloque Hero con `<h1>`, bajada introductoria, botones de llamado a la acción y foto destacada. |
| **Sección de Información sobre el tema (Main)** | Cumplido | Sección `Sobre Piano Bar`: análisis de la problemática de músicos independientes y bares, autogestión y lista ordenada `<ol>` de pilares. |
| **Sección con Imágenes (Main)** | Cumplido | Sección Galería con 4 fotos en `<figure>` y `<figcaption>`, además de 4 tarjetas de espacios en la cartelera. |
| **Sección de Datos destacados o curiosidades** | Cumplido | 4 métricas (+200 Espacios, +500 Músicos, +1000 Eventos, AMBA) y lista `<ul>` de curiosidades históricas del formato Piano Bar. |
| **Enlaces a páginas externas** | Cumplido | Enlaces a Wikipedia, YouTube, INAMU y redes con `target="_blank"` y `rel="noopener noreferrer"`. |
| **Footer con datos obligatorios** | Cumplido | Bloque con Nombre y Apellido del estudiante, Curso, Año (2026) y frase institucional requerida. |
| **Jerarquía de títulos ordenada** | Cumplido | Único `<h1>` principal, `<h2>` para cada sección temática, `<h3>` para tarjetas y subapartados, `<h4>` complementarios. |
| **Textos redactados por el estudiante** | Cumplido | Redacción original adaptada a la memoria de diseño del proyecto Piano Bar. |

---

## 🎨 Identidad Visual y Decisiones de Diseño

- **Paleta de Colores:** Acento vintage `#A78A7F`, combinada con fondos arena/crema (`#F5EFEB`), marrones cálidos nocturnos (`#2B231F`, `#362E29`) y tonos corcho (`#C5A992`).
- **Tipografías:**
  - **Títulos:** `Inria Serif` (Google Fonts) – evoca gráfica editorial y afiches tradicionales de bares nocturnos.
  - **Cuerpo:** `Crimson Text` (Google Fonts) – lectura cómoda, fluida y con carácter analógico.
- **Cartelera "Tablero de Corcho":** Las tarjetas de lugares simulan avisos o notas adhesivas fijadas con chinchetas, representando la autogestión y colaboración comunitaria.

---

## 🚀 Cómo visualizar el proyecto

1. Abrir la carpeta `piano-bar` en tu explorador de archivos.
2. Hacer doble clic sobre `index.html` para abrirlo en cualquier navegador (Chrome, Edge, Firefox, etc.).
3. O mediante un servidor local como Live Server en VS Code / Antigravity.
