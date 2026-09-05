# Changelog

Todos los cambios notables de este proyecto se documentan en este archivo.

El formato está basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/)
y este proyecto adhiere a [Versionamiento Semántico](https://semver.org/lang/es/).

## [No publicado]

### Agregado
- Se creó la estructura inicial del proyecto SnackLab (index.html semántico, css/styles.css con reset base, img/, README.md, .gitignore)
- Se creó la barra de navegación con logo, menú de anclas internas y CTA "Crear mi SnackBox"
- Se definieron las variables CSS de la paleta de marca (:root)
- Se agregó la fuente decorativa "Shadows Into Light" (local vía @font-face) aplicada al logo y a los títulos (h1, h2)
- Se construyó la sección hero con título, subtítulo, texto de valor, botones (principal y secundario) e imagen placeholder
- Se crearon estilos reutilizables de botones (.btn, .btn--primary, .btn--secondary)
- Se construyó la sección "¿Cómo funciona?" con 4 pasos usando CSS Grid
- Se crearon estilos reutilizables de sección (.section, .section__title, .section__subtitle)

- Se rediseñó la interfaz visual (paleta cálida, fuentes Baloo 2 y Nunito vía Google Fonts, logo de dos colores con tagline, hero con título de dos líneas y formas decorativas, sección "Cómo funciona" con círculos, íconos y líneas punteadas)

- Se reemplazó el placeholder del hero por la imagen principal real (img/ppal.png) con texto alternativo
- Se reemplazaron los emojis de la sección "Cómo funciona" por 4 imágenes reales (paso1-4.png) con texto alternativo

### Cambiado
- Se rediseñaron las tarjetas de "Cómo funciona": la imagen ahora cubre el ancho superior de la tarjeta (tipo banner) con el texto debajo
- Se ajustó la presentación de los íconos de pasos para mostrar la ilustración completa (object-fit: contain) con imágenes de fondo transparente

### Corregido
- Se eliminó un archivo HTML ajeno guardado por error en la carpeta img/
