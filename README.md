# Prueba - Mamma Mia!

● Para realizar esta prueba debes haber estudiado previamente todo el material disponible en el LMS correspondiente al módulo.

● Desarrollo prueba:

○ La prueba se debe desarrollar de manera Individual.

○ Para la realización de la prueba necesitarás apoyarte del archivo _Apoyo Prueba - Mamma Mia!_

## Habilidades

● Utilizar React Router para controlar rutas y redireccionamientos.

● Utilizar Context API almacenar y modificar el estado global.

## Descripción

La pizzería italiana Mamma Mia! SPA le solicita realizar su aplicación web para mostrar y vender sus pizzas. Esta app deberá mostrar los distintos tipos de pizzas y sus ingredientes a través de una archivo JSON que estará a tu disposición en el material de apoyo y en donde encontrarás un arreglo de objetos correspondientes a cada tipo de pizza con su nombre, ingredientes, imagen, descripción, ID y precio.

La aplicación debe incluir un carrito y una vista de detalle por cada pizza seleccionada en el catálogo ubicado en la vista principal.

Para la estética de esta aplicación contará con algunas imágenes de referencia, sin embargo, el diseño quedará a su criterio siempre y cuando cumpla con los requerimientos.

<p align="center">
  <img src="https://github.com/Felipe-M-dev/react2-practical-work/blob/main/public/01.png?raw=true?raw=true" alt="Imagen 01"><br>
Imagen 1. Pantalla inicial<br>
Fuente: Desafío Latam
</p>

<p align="center">
  <img src="https://github.com/Felipe-M-dev/react2-practical-work/blob/main/public/02.png?raw=true?raw=true" alt="Imagen 02"><br>
Imagen 2. Descripción del producto<br>
Fuente: Desafío Latam
</p>

<p align="center">
  <img src="https://github.com/Felipe-M-dev/react2-practical-work/blob/main/public/03.png?raw=true?raw=true" alt="Imagen 03"><br>
Imagen 3. Detalle del pedido<br>
Fuente: Desafío Latam
</p>

## Requerimientos

1. Crear vistas y componentes para desarrollar las interfaces de las siguientes rutas __(2 puntos):__<br/>
a. __/Home:__ Mostrar el catálogo de pizzas<br/>
b. __/pizza/:id__ Mostrar el detalle de una pizza seleccionada en el catálogo<br/>
c. __/carrito:__ Mostrar las pizzas añadidas al carrito con sus precios y total a pagar

2. Usar React Router como gestor de rutas de la aplicación __(4 puntos)__

3. Manejar el estado global de la aplicación con Context API __(4 puntos)__

4. Crear la lógica en el carrito para incrementar y decrementar la cantidad de pizzas a comprar __(Opcional)__

5. Calcular el total de la compra y mostrarlo en los componentes que correspondan según las imágenes de referencia __(Opcional)__

<p align="center">
  <strong>😊¡Mucho éxito!</strong>
</p>

## Solución

1. Descargar el proyecto.

2. Desde una terminal, posicionarse sobre la carpeta del proyecto y lanzar el siguiente comando:

```npm install```

3. Al terminal la instalación de los módulos del proyecto, levantar servidor con el siguiente comando:

```npm start```

4. Cuando el server ya se encuentre arriba, ingresar al navegador y validar sitio en la siguiente URL:

```http://localhost:3000/```

## Sitio desplegado en Netlify

__URL:__

https://mamma-mia-dlatam.netlify.app/
