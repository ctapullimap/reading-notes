1. Box Model en CSS
El Box Model es la estructura fundamental de cada elemento HTML. Incluye:
css


.elemento {
    /* Contenido */
    width: 200px;
    height: 100px;
    
    /* Relleno interno */
    padding: 20px;
    
    /* Borde */
    border: 1px solid black;
    
    /* Margen exterior */
    margin: 10px;
}
Componentes:
Contenido: El área principal
Padding: Espacio interno
Border: Línea exterior
Margin: Espacio exterior
2. Box-sizing
css


/* Modelo tradicional */
.content-box {
    box-sizing: content-box;
    width: 100px; /* + padding + border = tamaño total */
}

/* Modelo moderno */
.border-box {
    box-sizing: border-box;
    width: 100px; /* tamaño total incluye padding y border */
}
3. Flexbox
Contenedor Principal
css


.container {
    /* Activar flexbox */
    display: flex;
    
    /* Dirección de los elementos */
    flex-direction: row;
    
    /* Alineación horizontal */
    justify-content: center;
    
    /* Alineación vertical */
    align-items: center;
}
Ejemplo Práctico
css


/* Centrar botones */
.button-container {
    display: flex;
    justify-content: center;
    gap: 10px;
}
4. Propiedad Flex
css


.elemento-flex {
    /* Sintaxis completa */
    flex-grow: 1;
    flex-shrink: 1;
    flex-basis: auto;
    
    /* Sintaxis abreviada */
    flex: 1 1 auto;
}

/* Ejemplo con tres cajas */
.caja-grande {
    flex: 2; /* Ocupa más espacio */
}
.caja-normal {
    flex: 1;
}
5. Formatos de Color
RGB/RGBA
css


.elemento {
    /* RGB básico */
    color: rgb(255, 0, 0);
    
    /* Con transparencia */
    background-color: rgba(255, 0, 0, 0.5);
}
Hexadecimal
css


.elemento {
    /* Formato largo */
    color: #FF0000;
    
    /* Formato corto */
    color: #F00;
}
HSL/HSLA
css


.elemento {
    /* HSL básico */
    color: hsl(0, 100%, 50%);
    
    /* Con transparencia */
    background-color: hsla(0, 100%, 50%, 0.5);
}
💡 Tips de Uso
css


/* Configuración recomendada */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

/* Contenedor flexible básico */
.flex-container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1rem;
}

/* Sistema de colores consistente */
:root {
    --color-primary: #007bff;
    --color-secondary: rgba(0, 123, 255, 0.5);
    --color-accent: hsl(211, 100%, 50%);
}
