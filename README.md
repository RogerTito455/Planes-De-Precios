# Planes de Precios - Proyecto de CSS y HTML

Este proyecto es una página web simple que muestra diferentes planes de precios utilizando HTML y CSS. El objetivo del proyecto es crear una interfaz de usuario atractiva y responsive que pueda ser utilizada en cualquier sitio web que ofrezca servicios o productos con distintos niveles de precios.

## Estructura del Proyecto

El proyecto consiste en un archivo HTML (`index.html`) y un archivo CSS (`styles.css`). A continuación, se describe la estructura básica:

### HTML (`index.html`)

- **Doctype y Metadatos:** 
  - El documento HTML utiliza `<!DOCTYPE html>` para indicar que se trata de HTML5.
  - Los metadatos incluyen la codificación de caracteres UTF-8 y la configuración de la vista para dispositivos móviles.
  
- **Cuerpo Principal:**
  - Contiene un `main` que envuelve un `div` principal con la clase `container`.
  - Dentro de `container`, hay tres `div` con la clase `subcontainer`, cada uno representando un plan de precios: `Starter`, `Intermediate`, y `Advanced`.
  - Cada plan incluye un título (`h1`), un precio (`h2`), una lista de características (`ul`), y un botón de compra (`a`).

### CSS (`styles.css`)

- **Estilos Globales:**
  - El `body` utiliza Flexbox para centrar el contenido vertical y horizontalmente.
  - Se utiliza `background-color: bisque;` para un fondo suave y acogedor.

- **Estilos del Contenedor:**
  - La clase `.container` se encarga de la disposición de los `subcontainers` usando Flexbox con alineación al final y un espaciado de 16px.

- **Estilos del Subcontenedor:**
  - Cada `subcontainer` tiene un fondo blanco, bordes redondeados, y una sombra para darle un efecto de tarjeta.
  - Se aplica un borde superior de color verde para resaltar cada plan.
  - Se incluye una animación de transformación para elevar la tarjeta al pasar el mouse por encima.

- **Estilos del Botón:**
  - Los botones de compra están diseñados con bordes redondeados, color de fondo negro, y cambian a verde con una sombra más intensa al pasar el mouse.

## Cómo Usar

1. Clona este repositorio o descarga los archivos.
2. Abre el archivo `index.html` en tu navegador preferido.
3. Experimenta con los estilos en `styles.css` para ver cómo afectan al diseño.

## Personalización

Este proyecto es fácilmente personalizable. Puedes modificar:

- Los textos en los `h1`, `h2`, y `ul` en `index.html`.
- Los colores, tamaños de fuente, y efectos de hover en `styles.css`.
- Añadir o quitar características dentro de cada plan.

## Previsualización

![Preview](preview.png)

> *Incluye una captura de pantalla del proyecto si lo deseas.*

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Puedes usarlo libremente para proyectos personales y comerciales.
