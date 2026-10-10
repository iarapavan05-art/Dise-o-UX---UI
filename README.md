# Coffea — Landing Page

Proyecto académico de Diseño UX-UI realizado con HTML5 y CSS3.

## Descripción
Landing page de una cafetería llamada **Coffea**, con navegación, sección principal, categorías, cafés, postres, promoción, testimonios, suscripción y pie de página.

## Tecnologías
- HTML5 semántico
- CSS3
- Variables CSS
- Flexbox y CSS Grid
- Diseño responsive
- scroll-snap
- Validación nativa de formularios
- Accesibilidad básica
- Sin JavaScript

## Estructura
```text
coffea-landing/
├── index.html
├── 404.html
├── netlify.toml
├── README.md
├── css/
└── assets/
```

## Ejecución
Abrir `index.html` con un navegador web. No requiere instalación ni compilación.

## Nota
Se incluyen imágenes SVG locales de reemplazo para que el proyecto funcione sin depender de enlaces externos. Pueden sustituirse por los recursos originales de Figma.


## Imágenes de café y postres

Se incorporaron fotografías externas para que los productos de café y postres se vean como productos reales en la landing. La fotografía de café proviene de PxHere y está indicada como CC0; la fotografía de postres se utiliza como recurso visual de referencia para el proyecto académico.

## Fotos individuales de cada producto

La sección de productos utiliza una foto diferente para cada café y cada postre, para que la imagen corresponda con el nombre mostrado en la tarjeta:

- Café lungo — PxHere, CC0.
- Capuchino — PxHere, CC0.
- Espresso — Wikimedia Commons, CC BY-SA 4.0.
- Latte — PxHere, CC0.
- Tiramisú — Wikimedia Commons.
- Brownie — PxHere, CC0.
- Cheesecake — PxHere, CC0.
- Cookie — Wikimedia Commons.

Las imágenes se cargan desde Internet mediante sus URLs. Si la página se abre sin conexión, las fotos remotas pueden no mostrarse.


## Cómo agregar las 8 fotos de productos

Colocá tus 8 imágenes dentro de `assets/img/productos/` usando exactamente estos nombres:

- `cafe-lungo.jpg`
- `capuchino.jpg`
- `espresso.jpg`
- `latte.jpg`
- `tiramisu.jpg`
- `brownie.jpg`
- `cheesecake.jpg`
- `cookie.jpg`

No hace falta modificar `index.html`: las tarjetas ya apuntan a esos archivos. Si tus fotos tienen otra extensión, por ejemplo `.png` o `.webp`, cambiá la extensión en `index.html` o renombrá las imágenes a `.jpg`.

## Imágenes tomadas del Word "Cafés.docx"

Las 8 fotos de productos de la carpeta `assets/img/productos/` fueron extraídas del documento proporcionado para el trabajo:
- Café con leche
- Café capuchino
- Café espresso
- Café latte
- Tiramisú
- Brownie
- Cheesecake
- Cookie

Para cambiar alguna foto, reemplazá el archivo manteniendo exactamente el mismo nombre.


### Hero actualizado
El encabezado principal se adaptó a la referencia visual: fondo marrón, marca “coffea”, navegación en español, texto y botones a la izquierda, y foto circular del café a la derecha. La foto está guardada localmente en `assets/img/hero-coffee.png`.


### Fotos de granos de café
La sección “Descubrí nuestros mejores granos de café” incluye dos fotografías locales en `assets/img/hero-coffee-beans.jpg` y `assets/img/hero-beans.jpg`. No necesitan conexión a Internet.
