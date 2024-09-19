# Rosón de Rosas Amarillas

Este proyecto es una simple página web que muestra una animación de un rosón hecho de cinco pétalos de rosas amarillas girando continuamente. Utiliza SVG para crear las formas y animaciones en el navegador.

## Características

- **SVG**: El diseño está hecho completamente con SVG, lo que permite crear gráficos escalables sin pérdida de calidad.
- **Animación**: La animación de rotación se implementa usando CSS (`@keyframes` y `transform`), lo que hace que el rosón gire indefinidamente.
- **Flexbox**: Se utiliza Flexbox para centrar el contenido en la página, tanto vertical como horizontalmente.

## Estructura

- **HTML**: Define la estructura básica de la página, incluyendo el `div` que contiene el SVG con la animación.
- **CSS**: Aplica el estilo a la página y define la animación de giro con la propiedad `@keyframes`.

## Uso

1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` en cualquier navegador web.
3. La página mostrará un rosón giratorio compuesto por cinco pétalos amarillos y un círculo en el centro.

## Código SVG

El SVG crea cinco pétalos en forma de "C", posicionados en un círculo usando la propiedad `transform: rotate()`. El color de los pétalos es amarillo (#FFD700), simulando rosas amarillas.

```html
<svg viewBox="0 0 100 100">
    <g class="rosa">
        <path d="M50 10 C60 30 70 30 50 50 C30 30 40 30 50 10" fill="#FFD700" />
        <path d="M50 10 C60 30 70 30 50 50 C30 30 40 30 50 10" fill="#FFD700" transform="rotate(72 50 50)" />
        <path d="M50 10 C60 30 70 30 50 50 C30 30 40 30 50 10" fill="#FFD700" transform="rotate(144 50 50)" />
        <path d="M50 10 C60 30 70 30 50 50 C30 30 40 30 50 10" fill="#FFD700" transform="rotate(216 50 50)" />
        <path d="M50 10 C60 30 70 30 50 50 C30 30 40 30 50 10" fill="#FFD700" transform="rotate(288 50 50)" />
    </g>
    <circle cx="50" cy="50" r="5" fill="#FFD700" />
</svg>
