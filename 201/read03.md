Guía de CSS Layout
Box Model (Modelo de Caja)
El Box Model es la estructura fundamental que envuelve cada elemento HTML en una página web.
Componentes
Content (Contenido): Contenido real del elemento (texto, imágenes)
Padding (Relleno): Espacio entre contenido y borde
Border (Borde): Línea que rodea el padding
Margin (Margen): Espacio exterior entre elementos
Box-sizing
css


/* Dos tipos principales de cálculo de tamaño */
.elemento {
    /* Solo incluye el contenido */
    box-sizing: content-box;    

    /* Incluye contenido + padding + border */
    box-sizing: border-box;     
}
Flexbox
Contenedor Flex
css


.container {
    /* Activa flexbox */
    display: flex;

    /* Dirección de los elementos */
    flex-direction: row/column;

    /* Alineación horizontal */
    justify-content: center/space-between;

    /* Alineación vertical */
    align-items: center/stretch;
}
Elementos Flex
css


.item {
    /* Crecimiento proporcional */
    flex: 1;

    /* Control individual de crecimiento */
    flex-grow: 1;

    /* Control de reducción */
    flex-shrink: 1;
}
Colores en CSS
RGB/RGBA
css


.elemento {
    /* Rojo sólido */
    color: rgb(255, 0, 0);

    /* Rojo semi-transparente */
    background: rgba(255, 0, 0, 0.5);
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
    color: hsla(0, 100%, 50%, 0.5);
}
Preguntas Frecuentes
1. Box Model
Define la estructura de capas de elementos HTML
Incluye: contenido, padding, border y margin
Base fundamental para el diseño CSS
2. Box-sizing
content-box: Tamaño = solo contenido
border-box: Tamaño = contenido + padding + border
border-box es más intuitivo y usado comúnmente
3. Flexbox
Propiedades principales:
display: flex
flex-direction
justify-content
align-items
4. Propiedad flex
css


/* Sintaxis básica */
flex: [grow] [shrink] [basis];
5. Formatos de Color
RGB/RGBA: Control preciso y transparencia
Hexadecimal: Estándar web
HSL/HSLA: Ajuste intuitivo de colores
Consejos de Uso
Usar border-box para cálculos más intuitivos
Flexbox para layouts responsivos
RGBA/HSLA cuando necesites transparencia
Hexadecimal para compatibilidad web
