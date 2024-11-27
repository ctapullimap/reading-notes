# CSS Layout: Reflexión y Resumen

## Introducción
El diseño en CSS es una de las habilidades más importantes para cualquier desarrollador web. Este tema es esencial porque nos permite organizar y dar estilo a las páginas web, haciendo que sean visualmente atractivas y funcionales. En este módulo, aprendemos conceptos clave como el **Box Model**, **Flexbox** y los diferentes formatos de color, que son herramientas fundamentales para estructurar y diseñar cualquier sitio web.

---

## Respuestas a las Preguntas

### 1. ¿Qué es el Box Model en CSS y cuáles son sus componentes principales?
El **Box Model** es la forma en que CSS organiza y representa cada elemento en una página web. Piensa en cada elemento como una caja con varias capas que definen su tamaño y espacio.

- **Contenido:** Lo que está dentro de la caja, como texto o imágenes.
- **Padding (Relleno):** Espacio entre el contenido y el borde de la caja.
- **Border (Borde):** La línea que rodea la caja.
- **Margin (Margen):** Espacio exterior que separa la caja de otros elementos.

```css
/* Ejemplo de Box Model */
.elemento {
    width: 200px; /* Contenido */
    padding: 20px; /* Relleno */
    border: 2px solid black; /* Borde */
    margin: 10px; /* Margen */
}
