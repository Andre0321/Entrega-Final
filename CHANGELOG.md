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

- Se construyó la sección "Nuestros snacks" (catálogo) con tarjetas de producto (etiqueta, nombre, descripción, precio en COP y botón "Agregar"), usando Grid responsive (auto-fit)
- Se amplió el catálogo a 10 productos distribuidos en las 4 categorías
- Se agregó la variante de botón pequeño (.btn--small)
- Se construyó la sección "Ocasiones" con 4 tarjetas estilo overlay (cumpleaños, regalo, movie night, study box), cada una con ícono, título, descripción y CTA
- Se construyó la sección "¿Por qué SnackLab?" con 4 beneficios (personalizable, variedad, para cada ocasión, a tu medida) con íconos en círculo y fondo crema
- Se construyó la sección "Sobre nosotros" (Conoce SnackLab) con la historia de la marca, imagen placeholder y CTA
- Se construyó la sección "Contacto" con un formulario visual (nombre, email, whatsapp, ocasión, mensaje) con labels accesibles, validación básica (required, type=email, type=tel) y botón "Enviar solicitud"
- Se construyó el footer con logo, tagline, enlaces de navegación, redes sociales y copyright
- Se implementó el diseño responsive con media queries (breakpoints 992px, 768px y 480px): navbar simplificada en tablet/móvil, hero y "nosotros" en una columna, títulos y espaciados adaptados, botones a ancho completo y footer apilado, sin scroll horizontal
- Se reemplazaron los placeholders del catálogo por las 10 imágenes reales de producto y se reenfocó la marca hacia snacks saludables (productos, categorías, descripciones y textos del hero/catálogo actualizados)
- Se ajustó el tamaño de las imágenes de producto a un formato más compacto (140px, object-fit contain sobre fondo crema)
- Se agregaron las imágenes reales de fondo a las 4 tarjetas de ocasiones (cumpleaños, regalo, movie night, study box), manteniendo el overlay oscuro para legibilidad
- Se reemplazó el placeholder de la sección "Sobre nosotros" por la imagen real de marca (img/somos.png)
- Se aplicó un difuminado de bordes (mask-image) a la imagen de "Sobre nosotros" para fundirla con el fondo crema

### Cambiado
- Se rediseñaron las tarjetas de "Cómo funciona": la imagen ahora cubre el ancho superior de la tarjeta (tipo banner) con el texto debajo
- Se ajustó la presentación de los íconos de pasos para mostrar la ilustración completa (object-fit: contain) con imágenes de fondo transparente

### Corregido
- Se eliminó un archivo HTML ajeno guardado por error en la carpeta img/
