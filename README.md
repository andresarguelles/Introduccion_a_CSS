# Tarea de Introducción a CSS

Este proyecto es una actividad para mi clase en el programa "Becalos Tech Challenge". En este proyecto, se ha trabajado con pseudoclases en CSS, así como con las propiedades `display: flex` y `display: grid` para lograr un diseño web responsivo y organizado.

## Descripción

El objetivo de este proyecto es demostrar el uso de pseudoclases en CSS y cómo se pueden aplicar para mejorar la experiencia del usuario. Además, se ha utilizado `display: flex` y `display: grid` para estructurar el contenido de la página de manera eficiente.

## Estructura del Proyecto

- **index.html**: Contiene la estructura HTML de la página.
- **style.css**: Contiene los estilos CSS aplicados a la página.

## Características

### Pseudoclases

Se ha utilizado la pseudoclase `:hover` para cambiar el aspecto del botón "Leer más" cuando el usuario pasa el mouse por encima del mismo.

```css
button:hover {
    background-color: #e1e1e1;
}
```

## Display Flex
Se ha utilizado display: flex en el encabezado (header) para alinear los elementos de navegación de manera horizontal y distribuir el espacio entre ellos.

```css
.header {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    column-gap: 2rem;
    align-items: baseline;
}

.header nav ul {
    display: flex;
    align-items: center;
    column-gap: 1rem;
}
```
## Display Grid
Se ha utilizado display: grid en el contenedor principal (body) para organizar el contenido en una estructura de tres filas: encabezado, contenido principal y pie de página.

```css
.grid-container {
    display: grid;
    grid-template-rows: auto 1fr auto;
    height: 100%;
}
```
## Conclusión
Este proyecto demuestra cómo se pueden utilizar pseudoclases y las propiedades display: flex y display: grid en CSS para crear una página web bien estructurada y con una mejor experiencia de usuario. Es una excelente práctica para entender cómo funcionan estas propiedades y cómo se pueden aplicar en proyectos reales.

## Créditos
Este proyecto fue realizado como parte del programa "Becalos Tech Challenge".

## ¿Cómo ver el proyecto?

- Observa el resultado en la siguiente liga:
[Introduccion a CSS](https://andresarguelles.github.io/Introduccion_a_CSS/)

- O si lo prefieres solo descarga el repositorio y abre el documento index.html con tu navegador de preferencia.