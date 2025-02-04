# Trainings - 00 Básicos: Trabajo Práctico N1 - Andrés Dalla Rizza

## Puntos (escrito):

### 1. Con tus palabras explicar qué es HTML y qué es CSS.

HTML (Hypertext Markup Language) es un lenguaje utilizado para definir la estructura y el significado de una página web. Está compuesto por elementos que le indican al navegador cómo disponer el contenido. El navegador lo que hace ecencialmente es interpretar el lenguaje HTML. Los elementos de HTML se distinguen por etiquetas, que son nombres entre corchetes ("<" y >"), y permiten clasificar el contenido en párrafos, encabezados, imágenes, etc. 

- Referencias:
  - https://www.w3schools.com/html/html_intro.asp
  - https://developer.mozilla.org/es/docs/Web/HTML

CSS (Cascading Style Sheets) es un lenguaje utilizado para describir cómo se deben mostrar los elementos HTML en el navegador. Mediante un archivo CSS, se puede definir el diseño de varias páginas al mismo tiempo. Permite separar la estructura del contenido (HTML) de la presentación visual, facilitando el mantenimiento y la consistencia del diseño de la web.Ofrece distintas formas para personalizar la apariencia de los elementos HTML, como colores, tipografías, márgenes, alineaciones,etc.

- Referencias:
  - https://www.w3schools.com/css/css_intro.asp
  - https://developer.mozilla.org/en-US/docs/Web/CSS

---

### 2. ¿Qué es una clase CSS? ¿Qué es traer un elemento por el id en CSS?

- Clase CSS:  

Las clases en CSS son selectores que permiten aplicar un estilo a uno o más elementos HTML. Se definen en un archivo CSS o dentro de la etiqueta "< style >" en el documento HTML. Se aplican a los elementos HTML mediante el atributo "class". El valor asignado al atributo "class" debe coincidir con el nombre de la clase definida en el archivo CSS.

Ejemplo:

Archivo CSS:
```css
.nombreDeLaClase {
    color: red;
}
```

Archivo HTML:
```html
<h1 class= "nombreDeLaClase">Contenido del header</h1>
<h2>Contenido del segundo header</h2>
<p class= "nombreDeLaClase">Contenido del párrafo</p>

```

En este caso, el estilo se aplica a los elementos `h1` y `p`.

- Traer un elemento por el id en CSS:  

El atributo `id` es único para cada elemento HTML. Se utiliza para seleccionar un elemento específico en el documento HTML. A diferencia de las clases, no debe haber dos elementos con el mismo `id`.

---

### 3. ¿Qué propiedad de CSS me permite dar un margen derecho a un div?

La propiedad que permite dar un margen derecho a un `div` es `margin-right`. Las unidades que se pueden usar son:

- px: Píxeles.
- %: Porcentaje relativo al tamaño del contenedor.
- em: Tamaño relativo al tamaño de la fuente del elemento.
- rem: Tamaño relativo a la fuente del elemento raíz.
- auto: Tamaño automático.

En la siguiente pregunta se van a dar ejemplo de cada uno de las unidades
Referencias: https://developer.mozilla.org/es/docs/Web/CSS/margin

---

### 4. ¿Qué propiedad de CSS me permite dar un margen izquierdo a un div?

La propiedad que permite dar un margen izquierdo a un "div" es "margin-left". Las unidades son las mismas que para "margin-right".

Ejemplo:
```css
.nombreDeLaClase {
    margin-left: 15px;
}
```

Referencia: https://developer.mozilla.org/es/docs/Web/CSS/margin

---

### 5. ¿Qué propiedades de CSS me permiten dar un alto y ancho a un div? ¿Y cambiarle el color?

- **Alto**: La propiedad es "height".
- **Ancho**: La propiedad es "width".

Unidades aceptadas:
- px: Píxeles.
- %: Porcentaje relativo al tamaño del contenedor.
- vh: Altura relativa al tamaño de la ventana del navegador.
- vw: Ancho relativo al tamaño de la ventana del navegador.
- em y rem: Relativo al tamaño de la fuente.

**Para cambiar el color**:
- Color de fondo: background-color.
- Color del texto: color.
- Color del borde: border.

Valores de color:
- RGB - rgb(255, 0, 0) (rojo).  
- Hexadecimal -  #00FF00 (verde)
- HSL - hsl(240, 100%, 50%) (azul).
- RGBA - rgba(255, 165, 0, 0.5) (naranja con 50% de opacidad).
- HSLA - hsla(83, 85.50%, 48.60%, 0.95) (verde con 95% de opacidad).

Referencia: https://www.w3schools.com/css/css_colors.asp

---

### 6. Nombra y explica 14 etiquetas de HTML (incluye table, ul, li, div)

1. < head > :  Da información general sobre el documento: 
    - Metadatos: Palabras clave, conjunto de caracteres (generalmente UTF-8) y la descripcion de la página. 
    - El título del documento
    - Enlaces a hojas de estilo, scripts.
    - Iconos.

2. < title > :  Define el título del documento. Este se muestra en un browser, la barra de título o la pestaña de una página.
 
3. < body > : Se usa para representar el contenido de un documento HTML. Tiene que ser único en el documento.

4. < address > : Hace referencia a una sección de la página que consiste en la información de contacto del autor o propietario de un documento o artículo. Ejemplos del contenido de esta etiqueta son: país, mail de contacto, y  direcciones de correo electrónico del autor de la información de la página.

5. < header >: Esta etiqueta representa un grupo de ayudas introductorias o un conjunto de enlaces de navegación. Puede contener algunos elementos de encabezado (< h1 >, …, < h6 >), logo , un formulario de búsqueda, un nombre de autor y otros componentes.

6. < h1 > (incluye también < h2 >, < h3 >, < h4 >, < h5 >, < h6 >) : Se usan para definir encabezados. La importancia del mismo, se define mediante el número, siendo el < h1 > más importante y el < h6 > el menos importante. La finalidad del encabezado es describir brevemente el tema de la sección que le precede.

7. < main > : La etiqueta main contiene el contenido principal del  < body > de un documento HTML. El contenido debe ser único en el documento excluyendo  
8. < footer >: Representa un pie de página para su ancestro mas cercano.
9. < section >: Sirve para determinar qué contenido corresponde a qué parte de un determinado esquema. La principal funcionalidad es estructurar semánticamente el documento.
10. < nav > : Define un conjunto de enlaces de navegación
11. < div > : sirve para definir una seccion en un documento HTML. Se usa a modo de contenedor que puede contener otros elementos
12. < ul > : Se usa para crear una lista no ordenada  en un documento HTML.
13. < li > : Usado para crear una lista no ordenada  en un documento HTML.
14. < table > : Por medio de esta etiqueta se puede crear una tabla compuesta por filas y columnas


Referencias:
- https://www.w3schools.com/Tags/tag_nav.asp
- https://developer.mozilla.org/es/docs/Web/HTML/Element
- https://www.w3schools.com/tags/tag_address.asp
https://www.w3schools.com/tags/tag_hn.asp
- https://www.w3schools.com/tags/tag_ul.asp
- https://www.w3schools.com/tags/tag_div.asp


### 7. ¿Que se carga en el < head > del HTML, y en el < body >? ¿Cual es la diferencia entre head y div?

Como se explicó en el punto anterior, en la etiqueta < header > se cargan los datos generales sobre el documento, mientras que el < body >, contiene el contenido principal del documento. En este contenido se pueden encontrar párrafos, imagenes, encabezados, formularios, entre otras coasas.

Tiene dos principales diferencias: La primera es que el propósito de la etiqueta < head > es contener los metadatos y los enlaces a los recursos externos (contenido no visible en la página web), mientras que el < div > es usado como contenedor para otros elementos del html (contenido visible en la web). Por otra parte, la etiqueta < div >, se puede usar múltiples veces en el documento HTML, mientras que el < head > solo se puede usar una única vez.
