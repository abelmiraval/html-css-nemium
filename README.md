## Profesiones en el mundo de la programacion

###  Frontend
HTML, CSS, JavaScript se encarga de programar las interfaces.

### Backend
Python, PHP, Node, Java, Bases de datos.

### Devops
Docker, AWS, GPC, Linux.

### Full Stack
Frontend + Backend + Devops.

### Tech Lead
Experiencia y liderazgo tecnico.

### Product Manager
UX, Scrum Master, Soft Skills.

### Enginner Manager
Soft Skills: carrer path, contratacion, negociacion.

### CTO
Responsable del area tecnica. Decisiones y negociaciones directas con los demas C level.

### Herramientas
1. Google Chrome
2. Visual Code
2. Figma
4. Github

---

### HTML
Hyper Text Markup Language o Lenguaje de marcas Hipertext. Es el componente mas basico de la web.
Define el significado y la estructura del contenido.

### DOM
El Document Object Model es una estructura de arbol que representara todos nuestros proyectos web.

![dom](/images/dom.png)

### Etiquetas
Las etiquetas HTML van a ayudarnos a brindar una estructura y semantica al contenido de nuestros webiste y cada una tiene caracteristicas y usos diferentes aunque visualmente den un resultado similar.

![label](/images/label.png)

### Atributos
Los atributos dan caracteristicas extras a las etiquetas.

### Semantica
La semantica le brinda sentido a cada elemento existente en un sitio web.

[Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

[Web Skills](https://andreasbm.github.io/web-skills/)

[HTML Reference](https://htmlreference.io/)

### Enlaces y rutas
- http://www.mozilla.org/logo.png, ruta absoluta
- /images/rutas.png, ruta absoluta busca desde el direcctorio root
- images/rutas.png, ruta relativa busca desde el directorio actual
- ./images/rutas.png, ruta relativa busca desde el directorio actual
- .../images/rutas.png, ruta relativa navegacion entre carpetas

### Insertar codigo
[Escapa codigo](https://www.freeformatter.com/html-escape.html)

### CSS
CSS Cascaing Style Sheets es el lenguaje de estilos utilizado para describir la presentacion de documentos HTML

### 3 formas de agregar CSS
- A través de la etiqueta  *** link ***
- A través de la etiqueta *** <style> </style> ***

- A traves del atributo *** style ***

La etiqueta *** <style> </style> *** se utiliza para hacer aplicar estilos a una plantilla de correo.

### Reglas de CSS
![Reglas de css](/images/rules-css.png)

### Selectores
Los selectores definen sobre que elemento se aplicara un conjutno de reglas CSS

[practice selectors](https://flukeout.github.io/)

#### Global
Afecta a TODOS los elementos.
![Selector global](/images/selector-global.png)

#### Etiqueta
Hacen referencia a todos los elementos HTML que coincidan
![Selector etiqueta](/images/selector-etiqueta.png)

#### Clase
Las clases se puedan repetir y un elemento puede tener mas de una clase.
![Selector clase](/images/selector-clase.png)

#### Id
Solo un elemento puede tener el mismo id en una pagina.
![Selector id](/images/selector-id.png)

#### [atributo]
Todos los elementos que contengan el atributo o valor de atributo en cuestion.
![Selector atributo](/images/selector-atributo.png)

#### Grupo
N selectores se pueden configurar con las mismas propiedas.
![Selector grupo](/images/selector-grupo.png)

#### Descendente
Mas especificos.
![Selector descendente](/images/selector-descendente.png)

#### > Hijo directo
Los hijos directos del selector previo a >.
![Selector hijo directo](/images/selector-hijo-directo.png)

#### ~ Hermano
Los elementos en el mismo nivel.
![Selector hermano](/images/selector-hermano.png)

#### + Adyacente
Como el hermano pero solo el mas cercano.
![Selector adyacente](/images/selector-adyacente.png)

### Pseudo Selectores

#### :PseudoClase
Representan estados de un elemento
![pseudoclase](/images/pseudoclase-hover.png)

#### :PseudoElemento
Crean elementos especiales
![pseudoelemento](/images/pseudoelemento.png)

### User Agent Style
Las etiquetas reciben estilos particulares predefinidos por el navegador.

Para quitar esos estilos usar [Reset CSS](https://meyerweb.com/eric/tools/css/reset/) y que el estilo en varios navegadores sea homogeo con nuestras CSS.

![user agent style](/images/user-agent-style-1.png)

![user agent style](/images/user-agent-style-2.png)

### Cascada, Especificidad y Herencia

#### Cascada
Cascada de arriba hacia abajo, una hoja de estilos css se lee de arriba hacia abajo, lo que venga va sobrescribir a lo otro.

#### Especificidad
- Cuando hay coincidencia de elementos se aplica la cascada y tambien se aplica la relevancia que tiene ese elemento. La relevancia de clase es mayor a la relevancia del tag.

- La clase es superior a la etiqueta, el id es superior a la clase.

#### Herencia
La herencia va en todos los niveles, la herencias mas usados, son tamaño, font-weight, fuente, color.

![propiedades herencia](/images/propiedades-herencia.png)


### Content Component Layout
#### Contenido
Lo mas desglosado posible

![content](/images/content.png)

#### Componentes
Son conjunto un de contenidos

![component](/images/component.png)

#### Layout
Con los componentes componenmos un layout
![layout](/images/layout.png)

### display / flow / inline-block

#### display
Nos referimos a la propiedad que dice si un elemento o tag de HTML se comporta como block o inline

#### display:block
Toma el ancho de su línea y empuja al contenido siguiente.

#### display:inline
Toma todo el ancho de su contenido.

#### Flow
Es el flujo y la manera en como se va renderizando el contenido.

#### Flow Layout
Obecede la configuración writing-mode y direction.

#### writing-mode: horizontal-tb
Leemos de forma horizontal y de arriba hacia abajo.
#### direction: ltr
Leemos de izquierda a derecha. Esto se puede modificar en CSS para poder ajustar nuestro website a otro idiomas como el Árabe por ejemplo.

### Colors
Un color puede ser descrito como palabra clave, hexadecimal, rgb(a) y hls(a) [color_value](https://developer.mozilla.org/es/docs/Web/CSS/color_value)

### Values and Units
Existen [unidades de medida](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units) a absolutas y relativas, en esta clase aprende a usar px, em, rem y vw

#### px
Es una medida absoluta

#### em
Es una medida relativa, siempre toma el valor del font-size del elemento padre mas cercano y va en relativo en cadena

#### rem
Es una medida relativa, no va en herencia sobre herencia como lo hace los em, sino que siempre va tomar el valor de tamano de fuente que tenga mas acercado al root de nuestro elemento ejem: html(el elemento mas padre)

#### vw
Area visible del navegador, sin contar con el scroll

### Pseudo-clase
Una [pseudo-clase](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes ) CSS es una palabra clave que se añade a los selectores y que especifica un estado especial del elemento seleccionado.

#### :root
Tiene un peso superior cuando lo usamos como pseudo-clase.


### Custom properties
Los [custom properties](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes ) o variables en CSS nos ayudarán a almacenar datos para ser reutilizados por referencia en múltiples partes de nuestras hojas de estilo, son modificables según su contexto y también manipulables desde JavaScript. Se puede almacenar cualquier cosa, antes se usaba sass para poder lograr esta caracteristica.

### Custom fonts
Con las regla [@font-face](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes ) puedes añadir fuentes personalizadas

### Google fonts
[google fonts](https://fonts.google.com/)

### Background
Con Background puedes poner un color, una imagen o hasta un degradado de fondo sobre un mismo elemento.

El background  hace que se multiplique en el eje x y en el eje y, es una opcion por defecto.

background es una propiedad resumida, donde aparte del color puedes añadir su position, repeat, etc. background-color es exclusiva para el color en color clase, hexadecimal, rgba o hsla.

### Pseudo Elements
Hay elementos seleccionables y creados a partir de otros elementos como after y before o el placeholder de los inputs de formulario.

### Counters
Podemos crear [listas personalizadas](https://www.w3.org/TR/CSS2/generate.html#counter-styles) con otros elementos semánticos que no sean ul ol li, en este ejercicio vamos a enumerar cada subtítulo dentro de cada sección de nuestra página.


### Box Model
Todos nuestros elementos forman un espacio potencialmente compuesto por contenido, relleno, bordes y márgenes.

![box model](/images/box-model.png)

#### Margin
![box model](/images/margin.png)

#### Border
![box model](/images/margin.png)

#### Padding
![box model](/images/padding.png)

#### Width height
![box model](/images/width-height.png)

### Logical and physical properties and values
Introducción al  [nuevo modelo de propiedades y valores](https://drafts.csswg.org/css-logical/)  nuevo modelo de propiedades y valores para una web más semántica

Los valores logicos son de donde empiezo y donde termino.
En  vertical seria el bloque, en horizontal seria la linea

[Explicacion model logico y fisico](https://medium.com/@SusCasasola/el-futuro-de-css-modos-de-escritura-propiedades-y-valores-l%C3%B3gicos-a9c4bcaae5a1)

#### Default Config
1. direction: ltr;
2. writing-mode: horizontal-tb;
3. text-orientation: mixed;

---

### Layout with properties and physical values

#### Margins
Espacio que hay alrededor de un elemento HTML por fuera de sus bordes

#### Margin Collapsing
Efecto que sufren los márgenes colindantes en bloques que en vez de sumarse “colapsan” y solo queda el de mayor tamaño
Este efecto solo funciona de manera vertical cuando el contexto es un elemento en bloque

[margin collapsing](https://dev.to/lupitacode/entendiendo-el-colapso-de-margenes-margin-collapsing-4oj6)

#### Padding
Margen interno o “relleno” de un elemento HTML.

El espaciado con respecto a otros elementos para separarlos es el margin, el espaciado que tiene el contenido con su caja contenedora es el padding.

#### Border
Las fronteras visibles con las que podrás diferenciar entre margen y relleno

#### Box sizing
<pre>box-sizing: border-box</pre> sirve para poder controlar el ancho, los padding y borde no se sumarian a la caja, lo que haria es adaptarse al width.
En proyectos que requiren mucha escabilidad no es recomendable la propiedad border box. Al no tener la propiedad <pre>border box</pre> cuando se expande se ajustara mas flexible.
<pre>
* {
  box-sizing: border-box;
}
</pre>

Es una mala practica decir que todos los elementos sean border-box

Donde es recomendable usar <pre>border box</pre> es en los formularios para poder dividir en dos columnas, ejemplo la columna nombre y apellidos.

#### Debug styles
Cuando nuestros estilos y elementos se van expandiendo a veces es difícil saber dónde está un elemento y si realmente nuestros selectores lo están afectando o si sus dimensiones son correctas con respecto al modelo de caja.

#### Wrapping techniques
Consiste en tener un componente, un encapsulador del contenido y el contenido.x

 ```html
  <section class="services">
    <div class="wrapper">
      <div class="services-content">
      </div>
    </div>
  </section>
```

services => podria pintar el color de fondo
wrapper => deliminar las fronteras del contenido, tambien para centrarlo
services-content => para todo el contenido

#### Positions
Existen 5 tipo de position:
- relative
- absolute
- static
- fixed
- sticky

Cuando usamos position se activan 5 propiedades para poder usar top, left, right, bottom, z-index.

a) El position relative conserva su lugar fisico

b) El position absolute se ubica en donde se encuentra fisicamente, no conserva su lugar fisico

Podemos crear ventanas de modal con el position absolute de la siguiente manera:
<pre>
  .modal{
    position: absolute
    top:0;
    right:0;
    bottom:0;
    left:0;
    margin: 50px
  }
</pre>

Esta tecnica se asemeja a dos imanes que esta jalando al elemento y entre comillas le va dar el 100% de su contenedor.

- Cuando usamos position absolute toma como padre al primer elemento con <code>position:relative</code>, si no lo hubiera toma al viewport

---

### Layout with properties and logical values

#### Margins

<code>margin-inline: 100px;</code>, esta es de derecha a izquierda

<code>margin-block: 100px;</code>, es es de arriba hacia abajo

Esto se aplica en ese caso, siempre y cuando no se haya modificado el flex-direction

#### Sizes / Wrapper
Aplicación de la técnica del wrapper usando max-inline-size

#### Padding
Aprenderemos sobre padding-block y padding-inline

#### Borders
Aprenderemos sobre border-block y border-inline

#### Positions
Aprenderemos sobre insets para reemplazar top right bottom left

Creacion de un modal
```css
.header {
  background: red;
  position: fixed;
  inset: 0;
}
```

### Slider with just CSS
Sin JavaScript podemos lograr un gran slider, mucho performance y de fácil implementación. Lo mejor de 2 mundos.

### Forms
Los formularios son fundamentales para el ingreso de datos y conocer más a nuestros usuarios.

[Formularios](https://developer.mozilla.org/es/docs/Learn/Forms/Your_first_form)

### Media Queries y Responsive Design
Vamos a adaptar nuestro sitio para que se vea excelente en pantallas pequeñas

```pre
@media print, afecte a impresion
@media all, afecte a todos los dispositivos
@screen, afecte solo a la pantalla
```


- Móviles en horizontal o tablets en vertical
```html
@media creen and (min-width: 768px) { }
```

- Tablets en horizonal y escritorios normales
```html
@media creen and (min-width: 1024px) { } /
```

- Escritorios muy anchos
```html
@media creen and (min-width: 1350px) {
}
```

###  Open Graph
Los metadatos ayudarán a los motores de búsqueda y crawlers a dar más información sobre lo que vamos a presentar en nuestra página, de hecho es el tip más valioso para generar un preview de la página en Facebook, Twitter, o cualquier red social donde compartamos un enlace.

[https://developers.facebook.com/tools/debug/](https://developers.facebook.com/tools/debug/)
[ogp.me](https://ogp.me/)

### Favicon
El logo de nuestro proyecto se verá en el tab del navegador con esta clase


[https://www.favicon-generator.org/](https://www.favicon-generator.org/)
