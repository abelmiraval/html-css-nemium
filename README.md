### Profesiones en el mundo de la programacion

####  Frontend
HTML, CSS, JavaScript se encarga de programar las interfaces

#### Backend
Python, PHP, Node, Java, Bases de datos

#### Devops
Docker, AWS, GPC, Linux

#### FulLStack
Frontend + Backend + Devops

#### Tech Lead
Experiencia y liderazgo tecnico

#### Product Manager
UX, Scrum Master, Soft Skills

#### Enginner Manager
Soft Skills: carrer path, contratacion, negociacion

#### CTO
Responsable del area tecnica. Decisiones y negociaciones directas con los demas C level

### Herramientas
1. Google Chrome
2. Visual Code
2. Figma
4. Github

---

#### HTML

Hyper Text Markup Language o Lenguaje de marcas Hipertext. Es el componente mas basico de la web.
Define el significado y la estructura del contenido.

#### DOM

El Document Object Model es una estructura de arbol que representara todos nuestros proyectos web.

![dom](/images/dom.png)

#### Etiquetas

Las etiquetas HTML van a ayudarnos a brindar una estructura y semantica al contenido de nuestros webiste y cada una tiene caracteristicas y usos diferentes aunque visualmente den un resultado similar.

![label](/images/label.png)

#### Atributos

Los atributos dan caracteristicas extras a las etiquetas.

#### Semantica

La semantica le brinda sentido a cada elemento existente en un sitio web

[Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

#### Enlaces y rutas

- http://www.mozilla.org/logo.png, ruta absoluta
- /images/rutas.png, ruta absoluta busca desde el direcctorio root
- images/rutas.png, ruta relativa busca desde el directorio actual
- ./images/rutas.png, ruta relativa busca desde el directorio actual
- .../images/rutas.png, ruta relativa navegacion entre carpetas

#### Insertar codigo

[Escapa codigo](https://www.freeformatter.com/html-escape.html)

#### CSS

CSS Cascaing Style Sheets es el lenguaje de estilos utilizado para describir la presentacion de documentos HTML

#### 3 formas de agregar CSS

- A través de la etiqueta  *** link ***
- A través de la etiqueta *** <style> </style> ***

- A traves del atributo *** style ***

La etiqueta *** <style> </style> *** se utiliza para hacer aplicar estilos a una plantilla de correo.

#### Reglas de CSS

![Reglas de css](/images/rules-css.png)

#### Selectores

Los selectores definen sobre que elemento se aplicara un conjutno de reglas CSS

[practice selectors](https://flukeout.github.io/)

##### Global

Afecta a TODOS los elementos.
![Selector global](/images/selector-global.png)

##### Etiqueta

Hacen referencia a todos los elementos HTML que coincidan
![Selector etiqueta](/images/selector-etiqueta.png)

##### Clase

Las clases se puedan repetir y un elemento puede tener mas de una clase.
![Selector clase](/images/selector-clase.png)

##### Id

Solo un elemento puede tener el mismo id en una pagina.
![Selector id](/images/selector-id.png)

##### [atributo]

Todos los elementos que contengan el atributo o valor de atributo en cuestion.
![Selector atributo](/images/selector-atributo.png)

##### Grupo

N selectores se pueden configurar con las mismas propiedas.
![Selector grupo](/images/selector-grupo.png)

##### Descendente

Mas especificos.
![Selector descendente](/images/selector-descendente.png)

##### > Hijo directo

Los hijos directos del selector previo a >.
![Selector hijo directo](/images/selector-hijo-directo.png)

##### ~ Hermano

Los elementos en el mismo nivel.
![Selector hermano](/images/selector-hermano.png)

##### + Adyacente

Como el hermano pero solo el mas cercano.
![Selector adyacente](/images/selector-adyacente.png)

##### Pseudo Selectores

###### :PseudoClase

Representan estados de un elemento
![pseudoclase](/images/pseudoclase-hover.png)

###### :PseudoElemento

Crean elementos especiales
![pseudoelemento](/images/pseudoelemento.png)

---
#### User Agent Style
Las etiquetas reciben estilos particulares predefinidos por el navegador.

Para quitar esos estilos usar [Reset CSS](https://meyerweb.com/eric/tools/css/reset/) y que el estilo en varios navegadores sea homogeo con nuestras CSS.

![user agent style](/images/user-agent-style-1.png)

![user agent style](/images/user-agent-style-2.png)

---

#### Cascada, Especificidad y Herencia

##### Cascada
Cascada de arriba hacia abajo, una hoja de estilos css se lee de arriba hacia abajo, lo que venga va sobrescribir a lo otro.

##### Especificidad
- Cuando hay coincidencia de elementos se aplica la cascada y tambien se aplica la relevancia que tiene ese elemento. La relevancia de clase es mayor a la relevancia del tag.

- La clase es superior a la etiqueta, el id es superior a la clase.

##### Herencia
La herencia va en todos los niveles, la herencias mas usados, son tamaño, font-weight, fuente, color.

![propiedades herencia](/images/propiedades-herencia.png)

---

#### Content Component Layout

##### Contenido
Lo mas desglosado posible

![content](/images/content.png)

##### Componentes
Son conjunto un de contenidos

![component](/images/component.png)

##### Layout
Con los componentes componenmos un layout
![layout](/images/layout.png)


---

#### Display/Flow/inline-block

##### Display
Nos referimos a la propiedad que dice si un elemento o tag de HTML se comporta como block o inline

###### display:block
Toma el ancho de su línea y empuja al contenido siguiente.

###### display:inline
Toma todo el ancho de su contenido.

##### Flow
Es el flujo y la manera en como se va renderizando el contenido.

###### Flow Layout
Obecede la configuración writing-mode y direction.

###### writing-mode: horizontal-tb
Leemos de forma horizontal y de arriba hacia abajo.
###### direction: ltr
Leemos de izquierda a derecha.

Esto se puede modificar en CSS para poder ajustar nuestro website a otro idiomas como el Árabe por ejemplo.


---

#### Colors
Un color puede ser descrito como palabra clave, hexadecimal, rgb(a) y hls(a)
