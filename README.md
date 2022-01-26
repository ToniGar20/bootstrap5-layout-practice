# Project 4 - Bootstrap5 Layout

Proyecto en el que los estilos de la web de referencia se han pasado de CSS estándar a Bootstrap con el uso de SCSS.

* Utilizada la versión 5.1.3 de Bootstrap
* https://xayona-tonigarcia.netlify.app/

### 1. Componentes
#### Cards
Clase utilizada para montar las fotografías con texto de la parte inferior de la homepage. 
También en el apartado blog ha sido utilizado el componente para las entradas del blog.
Se ha hecho uso de las clases relacionadas "card-body", "card-img-top" y "card-text" entre otras.
#### Navbar
Utilizado para el menú de navegación del header.
#### Collapse
En la versión responsive del header, el menú de navegación pasa aestar en un "hamburguer icon" con el uso de la clase _collapse_ y _navbar-collapse_.
#### Buttons
Utilizadas las clases correspondientes para los botones con tamaño especificado.
#### Pagination
Para la sección "blog" se ha hecho uso de este componente aunque no era obligatorio.

### 2. Utilidades

#### margin 
Diferentes usos incluso con breakpoints para ajustar en las vistas responsive.
#### padding
Usado bastante para la separación y respetar espacios entre contenedores generales o bien los elementos que los componen.
#### border
Tanto en la "home" como en el "blog" se tocan bordes para distinguir o dividir contenidos.
#### display
Usado para ordenar mediante columnas y/o filas. Se ha usado principalmente _flex_ aunque también algún _block_.
#### justify-content y align-items
Colocación de contenedores.
#### Otras
* w-100 o h-100 - para ocupar todo el espacio de los contenedores.
* list-unstyled - para quitar el formato al emplear listas.
* text-decoration-none - para evitar subrayados o formato en algunos enlaces.
* small - para tener el tamaño de la fuente reducido.

### 3. Fichero "custom.scss" y customización
* Definidos cuatro colores principales.
* Importado todo Bootstrap.
* Realizada sobre-escrituras de clases para:
  * Cambiar cómo son los links de los paginados.
  * Quitar los estilos a las listas desordenadas que se usan en los ficheros HTML.
  * Ajustes en las filas.
  * Definir el font family para el body.
* Customización de clases: se han creado en base a breakpoints para esconder o cambiar la posición de elementos. Se ha utilizado principalmente para el paginado o elementos del responsive.

### 4. Paleta de colores & Fuente

* Colores Definida paleta en el siguiente enlace de [Google Sheets](https://docs.google.com/spreadsheets/d/1-biUi1vZVS5SleXQP1T8RBObWmf-Ot4lB9_KTArs3X8).
* Fuente: Rokkitt 600. [Google Font](https://fonts.googleapis.com/css2?family=Poppins:wght@600&family=Rokkitt&display=swap).
