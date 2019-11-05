# Maquetando un diseño predefinido.

He utilizado para el desarrollo de la web HTML y Sass. Además el proyecto utiliza Gulp, para la automatización de las tareas.

## Guía de uso

1. Clonar el repositorio
2. Instala las dependencias locales con `npm install`
3. Arrancar con `npm start`

## Estructura del proyecto

Nuestro **gulpfile.js** usa un JSON de configuración con las rutas de los archivos a generar.

Sigue la siguiente estructura de carpetas:

```
/
`- _src
   |- assets
   |  |
   |  |- images
   |  |- js
   |  `- scss
   |     `- core
   |      `- layouts
   |
   `- templates
      `- partials

```

## HTML

Está formado por tres secciones (header, main, footer), a partir de estas grandes secciones hay varios html parciales.

## CSS

El proyecto lo he realizado mediante Sass, anidando y realizando parciales del css. Gracias a gulp, el fichero de css lo genera de manera automática.

## Objetivo del proyecto.

- Tener un código HTML y CSS bien indentado con sintaxis y semánticas correctas.
- Usar posiciones (absolutas, relativas..) flexbox y CSS grid para posicionar elementos.
- Usar media queries para que el proyecto sea responsive en diferentes dispositivos.
- Realizar animaciones y transiciones de algunos elementos para que la web sea más dinámica.
