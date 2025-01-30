# Yahoo Clone

Este proyecto es un clon de la página principal de Yahoo, desarrollado utilizando HTML y CSS. El objetivo principal fue replicar la estructura y el diseño de la interfaz de Yahoo, con un enfoque en el uso de **Flexbox** para la disposición de los elementos en la página.

## Características

- **Header**: Contiene el logo de Yahoo y dos íconos de navegación (usuario y aplicaciones).
- **Main**:
  - **Saludo y noticia destacada**: Muestra un saludo personalizado y una noticia destacada con un enlace.
  - **Buscador**: Un campo de búsqueda con íconos de lupa y micrófono.
  - **Tendencias**: Una lista de temas que son tendencia en ese momento.
- **Footer**: Enlaces a diferentes secciones como Ayuda, Privacidad, Términos, entre otros, junto con un ícono de ajustes.

## Estructura del Proyecto

### HTML
El archivo HTML está estructurado en tres secciones principales:

1. **Header**: Contiene el logo de Yahoo y los íconos de usuario y aplicaciones.
2. **Main**: Incluye un saludo personalizado, un buscador y una sección de tendencias.
3. **Footer**: Muestra enlaces de navegación y un ícono de ajustes.

### CSS
El archivo CSS define los estilos para cada sección de la página, utilizando variables CSS para mantener consistencia en los colores y otros valores. Se destaca el uso de Flexbox en las siguientes áreas:

- **Header**: Los elementos del header están alineados horizontalmente con `display: flex` y `justify-content: space-between`.
- **Main**: El contenido principal está centrado en la página, y el buscador utiliza Flexbox para alinear el ícono de búsqueda, el campo de texto y el ícono de micrófono.
- **Footer**: Los enlaces del footer están distribuidos horizontalmente con Flexbox, y el ícono de ajustes está alineado con el texto.

## Tecnologías utilizadas

- **HTML5**: Para la estructura de la página.
- **CSS3**: Para los estilos y la disposición de los elementos, con un enfoque en Flexbox.

## Cómo Usar el Proyecto

1. Clona este repositorio o descarga los archivos.
2. Abre el archivo `index.html` en un navegador web.
3. Explora la interfaz y revisa los estilos aplicados.