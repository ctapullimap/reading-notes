### Guía de CSS Layout para GitHub
📦 Box Model
El Box Model es como una caja que envuelve cada elemento HTML. Cada elemento tiene:
Content: Contenido real (texto, imagen, etc.)
Padding: Espacio entre contenido y borde
Border: Línea que rodea el padding
Margin: Espacio exterior entre elementos
📏 Box-sizing
css


/* Dos tipos de cálculo de tamaño */
.elemento {
    /* Solo incluye el contenido */
    box-sizing: content-box;    

    /* Incluye todo (más intuitivo) */
    box-sizing: border-box;     
}
🔄 Flexbox
Contenedor Principal
css


.container {
    /* Activar flexbox */
    display: flex;
    
    /* Dirección de elementos */
    flex-direction: row/column;
    
    /* Alineación horizontal */
    justify-content: center/space-between;
    
    /* Alineación vertical */
    align-items: center/stretch;
}
Elementos Hijos
css


.item {
    /* Crecimiento igual */
    flex: 1;
    
    /* Control de crecimiento */
    flex-grow: 1;
    
    /* Control de reducción */
    flex-shrink: 1;
}
🎨 Colores en CSS
RGB/RGBA
css


.elemento {
    /* Color sólido */
    color: rgb(255, 0, 0);
    
    /* Con transparencia */
    color: rgba(255, 0, 0, 0.5);
}
Hexadecimal
css


.elemento {
    color: #FF0000;  /* Rojo */
}
HSL/HSLA
css


.elemento {
    /* Color base */
    color: hsl(0, 100%, 50%);
    
    /* Con transparencia */
    color: hsla(0, 100%, 50%, 0.5);
}
❓ Preguntas Frecuentes
1. Box Model
Estructura básica de elementos HTML
Componentes: content, padding, border, margin
Base del diseño web
2. Box-sizing
content-box: Tamaño = solo contenido
border-box: Tamaño = contenido + padding + border
3. Propiedades Flexbox
display: flex
flex-direction
justify-content
align-items
4. Propiedad flex
css


/* Sintaxis */
flex: [grow] [shrink] [basis];
5. Formatos de Color
Formato	Uso Recomendado
RGB/RGBA	Transparencia
Hexadecimal	Diseño web estándar
HSL	Ajustes intuitivos
💡 Tips
Usa border-box para cálculos más simples
Flexbox para layouts responsivos
RGBA cuando necesites transparencia
Hexadecimal para compatibilidad web general
🚀 Recursos Adicionales
MDN Web Docs - Box Model
CSS-Tricks - Flexbox Guide
Color formats in CSS
