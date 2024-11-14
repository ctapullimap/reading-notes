# Introducción al DOM y su relación con JavaScript

## ¿Qué es el DOM?
El **DOM** o **Modelo de Objetos del Documento** es una representación estructurada de una página web. Imagínalo como un árbol donde cada elemento de la página (como párrafos, imágenes, botones, etc.) es una "rama" o "nodo" que se puede acceder y modificar. Gracias al DOM, los desarrolladores pueden manipular dinámicamente el contenido y la estructura de una página web.

## Relación entre el DOM y JavaScript
JavaScript y el DOM trabajan juntos para hacer que las páginas web sean interactivas. JavaScript usa el DOM para "hablar" con la página web, accediendo y modificando sus elementos. Por ejemplo, con JavaScript puedes cambiar el texto de un párrafo, ocultar una imagen, o actualizar el contenido sin necesidad de recargar toda la página. En resumen, el DOM es la estructura y JavaScript es la herramienta que permite interactuar con ella.

## ¿Cómo seleccionar un elemento del DOM por su ID?
Para seleccionar un elemento específico en el DOM por su ID, se usa el método `getElementById`. Este método permite acceder directamente a un elemento que tenga un `id` específico.

### Ejemplo:

``javascript
let elemento = document.getElementById("miElementoID");


## ¿Cómo cambiar el color de fondo de un elemento en el DOM?

Para cambiar el color de fondo de un elemento en el DOM, podemos usar la propiedad `style.backgroundColor`. Una vez que hemos seleccionado el elemento, podemos ajustar su color de fondo de la siguiente manera:

### Ejemplo:

``javascript
let elemento = document.getElementById("miElementoID");
elemento.style.backgroundColor = "blue";
