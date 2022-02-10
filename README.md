# Manipulando elementos del DOM con Javascript

## Objetivo:

Utilizar Javascript, desde el frontend, para manipular elementos del DOM.

### Consignas:
### *Home

- Desde el archivo /public/js/index.js, capturar los siguientes elementos: *main, h2, a y p,* ubicados en el archivo: /views//index.ejs.

- Haciendo uso del prompt, indicar al usuario que: “Ingrese su nombre”.

- En caso de que el usuario no coloque su nombre, a la etiqueta *h2*, se le debe agregar la palabra “Invitado”. En caso contrario, se le debe agregar el nombre que el usuario ingresó.

- Agregar a la etiqueta *h2* el estilo uppercase. A la etiqueta *a*, colocarle el estilo correspondiente para que cambie el color.

- Mediante el confirm, preguntar al usuario “¿Desea colocar un fondo de pantalla?”. Si la respuesta es afirmativa por parte del usuario, agregar al *body* la clase “fondo”.

- A todos los párrafos que fueron capturados, asignar a los pares la clase: “descatadoPar”. Y a los impares agregar la clase: “destacadoImpar”.

- Finalmente, establecer como visible a la etiqueta *main* en el browser o navegador, aplicando el estilo: display : block.

***

#### *Listado de películas

- Crear un archivo JavaScript: /public/js//moviesList.js, y vincularlo con el archivo: /views//moviesList.ejs. Desde el archivo /public/js/moviesList.js, capturar los siguientes elementos: *body y h1*, ubicados en el archivo /views//moviesList.ejs.

-  Haciendo uso del prompt, preguntar al usuario: “¿Desea modo oscuro?”. Si la respuesta es afirmativa, agregar a la etiqueta body un color de fondo oscuro​, y la clase: fondoMoviesList.

-  Agregar a la etiqueta *h1* el mensaje: “LISTADO DE PELÍCULAS”.

- Agregar a la etiqueta *h1* los siguientes estilos: Color de la fuente: white, color de fondo: oscuro (a elección), Relleno: 20px

***

#### *Agregar película

- Crear un archivo JavaScript: /public/js//moviesAdd.js, y vincularlo con el archivo; /views//moviesAdd.ejs.

- Desde el archivo /public/js/moviesAdd.js, capturar los siguientes elementos: *h1, section y article*, ubicados en el archivo: /views//moviesAdd.ejs.

- Agregar a la etiqueta *h1* el mensaje: “AGREGAR PELÍCULAS”.

- Agregar a la etiqueta *h1* la clase: “titulo”.
- Agregar al artículo la clase: “fondoTransparente”.
- Agregar a la sección la clase: “fondoCRUD


## Tecnologías usadas

<p align="left">
<!-- javascript -->
<a href=https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" data-bs-toggle="tooltip" title="JavaScript"> <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="javaScript"/> </a>
<!-- express -->
<a href="https://developer.mozilla.org/es/docs/Learn/Server-side/Express_Nodejs/Introduction" alt="Express Js" ><img src= "https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" /></a>
<!-- MYSQL -->
<a href="https://www.mysql.com/" alt="Express Js" ><img src= "https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" /></a>
<!-- HTML -->
<a href="https://developer.mozilla.org/es/docs/Web/HTML" alt="HTML5" ><img src= "https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" /></a>
<!-- css -->
<a href="https://www.w3schools.com/css/" target="_blank" data-bs-toggle="tooltip" title="CSS3"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="css3"/> </a>
</p>

## Instalación de la base de datos relacional *movies-db.sql*:

- Debe tener instalado un gestor de base de datos, por ejemplo: MYSQL Workbench (https://www.mysql.com/products/workbench/) o Heidi db (https://www.heidisql.com/).

- Desde su gestor de base de datos, correr el script que se encuentra en:

   `manipulando-elementos-js/src/database/script/movies-db.sql`

- Levantar el servidor para la base de datos desde su gestor de base de datos.

## ¿Cómo instalar el proyecto?

### Desde la terminal:
  
- Clonar el proyecto:

````
 git clone https://github.com/LorenaCoheneBaez/manipulando-elementos-js.git 
 ````

- Ingresar a la carpeta del proyecto: 
````
cd manipulando-elementos-js
````

- Para instalar las dependencias correr: 

```
npm install
```

### Levantar el servidor del proyecto: 

````
npm test
````

### Rutas:

- Home http://localhost:3001/
- Listado de películas http://localhost:3001/movies
- Agregar película http://localhost:3001/movies/add