

# PI Videogames 馃幃
Es un sitio web desarrolado integramente en JavaScript. La SPA(Single Page Application) obtiene datos de una [API](rawg.io/apidocs)
a trav茅s de un Back-End desarrolado con Node Js. El Front-End se cre贸 utilizando React y Redux para administrar los estados de la aplicaci贸n.
La base de datos se implement贸 usando PostgreSQL y Sequelize.

* __Lo que se puede hacer__


1. Buscar videojuegos en la barra de busqueda.


2. Filtrar videojuegos por generos.


3. Ordenar por rating.


4. Ordenar los videojuegos por orden alfabetico.


5. Crear un nuevo juego que se almacena en una base de datos a trav茅s de un formulario controlado.

<p align="right">
  <img height="200" src="./videogame.png" />    
</p>

## Tecnolog铆as
* __HTML__
* __CSS__
* __JavaScript__
* __React__
* __Redux__
* __NodeJs__
* __Express__
* __Sequelize - Postgres__

## Imagenes del proyecto
* __HomePage__
<img height="350" src="https://github.com/nicolasburgueno/img-pi/blob/master/PI1.png?raw=true"  />


Al posicionar mouse por encima el borde se torna azul y se produce un efecto de desplazamiento hacia abajo.


<img height="350" src="https://github.com/nicolasburgueno/img-pi/blob/master/PI2.png?raw=true"  />

* __Detalle del juego__
<img height="350" src="https://github.com/nicolasburgueno/img-pi/blob/master/PI3.png?raw=true" />

* __Busqueda por coincidencia__
<img height="350" src="https://github.com/nicolasburgueno/img-pi/blob/master/PI4.png?raw=true" />

* __Formulario de creaci贸n de un nuevo juego, controlado__
<img height="350" src="https://github.com/nicolasburgueno/img-pi/blob/master/PI5.png?raw=true" />

Datos de formulario completados excepto la url de la imagen. En este caso no se incluy贸 pero se puede poner si asi se desea (si no se especifica una imagen, hay una predefinida por defecto).

<img height="350" src="https://github.com/nicolasburgueno/img-pi/blob/master/PI6.png?raw=true" />


* __Demostracion del filtro de creados y a su vez visualizacion del nuevo juego creado en la HomePage__
<img height="350" src="https://github.com/nicolasburgueno/img-pi/blob/master/PI7.png?raw=true" />

* __Pagina de detalle del nuevo juego creado__
<img height="350" src="https://github.com/nicolasburgueno/img-pi/blob/master/PI8.png?raw=true" />


## Instrucciones

 1. Clonar el repositorio
 2. Crear una base de datos en postgres llamada videogames
 3. En `api` crear un archivo llamado: `.env` que tenga la siguiente forma:

```
DB_USER=usuariodepostgres
DB_PASSWORD=passwordDePostgres
DB_HOST=localhost:5432
API=apikey
```
Reemplazar `usuariodepostgres` y `passwordDePostgres` con tus propias credenciales para conectarte a postgres y en API ingresar la `api key` obtenida de la siguiente [pagina](https://rawg.io/)

4. Ejecutar los siguientes comandos en las carpetas `/api` y `/client`


npm install


npm start


5. Por ultimo abra http://localhost:3000

__IMPORTANTE:__ Es necesario contar minimamente con la 煤ltima versi贸n estable de Node y NPM. Asegurarse de contar con ella para poder instalar correctamente las dependecias necesarias para correr el proyecto.

Actualmente las versi贸nes necesarias son:

 * __Node__: 12.18.3 o mayor
 * __NPM__: 6.14.16 o mayor

Para verificar que versi贸n tienen instalada:

> node -v
>
> npm -v
