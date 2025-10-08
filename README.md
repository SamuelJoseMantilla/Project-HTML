# LuxTime — Maqueta HTML/CSS (sin JS)

Proyecto académico para el sitio corporativo **LuxTime**, desarrollado con **HTML + CSS nativo** (sin librerías, sin JS, sin backend). Enfoque en **wireframes**, **componentes interactivos simulados** (carruseles/hover/scroll-snap) y **layout responsive** (Flexbox + CSS Grid).

## Estructura
/css
main.css # tokens, reset, tipografías, base
layout.css # header, nav, footer, helpers (flex+grid), media queries
components.css # hero, cards, timeline, gallery, forms, product page
/assets
/img # banners, productos, historia
home.html
catalogo.html
producto.html
historia.html
contacto.html
README.md

markdown
Copiar código

## Páginas
- **Home (index.html)**: Hero con rotación (CSS animation), 6 destacados (cards), resumen de historia.
- **Catálogo (catalogo.html)**: 20 productos en grid (4/2/1 columnas).
- **Producto (producto.html)**: Galería con zoom (hover), thumbs (scroll-snap), specs, personalización simulada y relacionados (rail).
- **Historia (historia.html)**: Línea de tiempo desde 1970, galería mosaico por décadas, valores y futuro.
- **Contacto (contacto.html)**: Formulario con validación CSS pura, datos y redes.

## Responsive
- Breakpoints: `≤480px` (móvil), `481–768px` (tablet), `≥769px` (desktop).
- Uso de **Flexbox** y **Grid** en todo el proyecto.

## Requisitos del enunciado — checklist
- [x] HTML/CSS 
- [x] Wireframes.
- [x] Responsive (3 breakpoints).
- [x] Componentes simulados (rotación CSS, carrusel visual, validación CSS).
- [x] Footer con info requerida.

## Cómo ver el proyecto
Abrir `index.html` en el navegador.  
(Opcional: VS Code con Live Server).

## Autoría
- **Desarrollado por:** Samuel Pallares  
- **Contacto:** contacto@luxtime.co

## Link de la web
link: https://luxtimesamp.netlify.app/