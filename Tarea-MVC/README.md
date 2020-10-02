


#### Investigacion de Modelo MVC

# Introducción
En este repositorio se dara una introducció de lo que es el Patron **MVC** y sus framworks en donde se pueden implementar con unos ejemplos de como se Utiliza.

# Marco Teórico

 **MVC y  su relación con los patrones de diseño de software**
El MVC es un patrón de diseño arquitectónico de software, que sirve para clasificar la información, la lógica del sistema y la interfaz que se le presenta al usuario. En este tipo de arquitectura existe un sistema central o controlador que gestiona las entradas y la salida del sistema, uno o varios modelos que se encargan de buscar los datos e información necesaria y una interfaz que muestra los resultados al usuario final.
Su fundamento es la separación del código en tres capas diferentes, acotadas por su responsabilidad, en lo que se llaman Modelos, Vistas y Controladores, o lo que es lo mismo, Model, Views & Controllers.

![](http://codingornot.com/wp-content/uploads/2017/10/mvc-modelo-vista-controlador.png) 

**Modelo:**
Este componente se encarga de manipular, gestionar y actualizar los datos. Si se utiliza una base de datos aquí es donde se realizan las consultas, búsquedas, filtros y actualizaciones.

**Vista:**
Este componente se encarga de mostrarle al usuario final las pantallas, ventanas, páginas y formularios; el resultado de una solicitud. Desde la perspectiva del programador este componente es el que se encarga del frontend; la programación de la interfaz de usuario si se trata de un aplicación de escritorio (CSS, HTML, HTML5 y Javascript).

**Controlador:**
Este componente se encarga de gestionar las instrucciones que se reciben, atenderlas y procesarlas. Por medio de él se comunican el modelo y la vista: solicitando los datos necesarios; manipulándolos para obtener los resultados; y entregándolos a la vista para que pueda mostrarlos.

**¿Que frameworks utiliza el modelo MVC?** 

Ruby: ruby on rails, Sinatra

JS : express, sails, backbone, angular

PHP: cakePhp, code Igniter, laravel

PYTHON: Django, Flask

NET: ASP MVC

**¿Qué ventajas ofrece el modelo MVC?**

   • El uso del patrón MVC ofrece múltiples ventajas sobre otras maneras de desarrollar aplicaciones con interfaz de usuario, y en especial para la Web

   • La clara separación de responsabilidades impuesta por el uso del patrón MVC hace que los componentes de las aplicaciones tengan sus misiones bien definidas. Por lo tanto, los sistemas serán más limpios, simples, más fácilmente mantenibles y, a la postre, más robustos.

   • Mayor velocidad de desarrollo en equipo, ya que al estar separado en tres partes tan diferenciadas, diferentes programadores pueden ocuparse de cada parte en paralelo. Esto la hace ideal para el desarrollo de aplicaciones grandes.

   • Múltiples vistas a partir del mismo modelo, pudiendo reaprovechar mucho mejor los desarrollos y asegurando consistencia entre ellas.

   • Facilidad para realización de pruebas unitarias.


**¿Que otros modelos/frameworks existen de patrones de diseño?**  


   Dependiendo de su finalidad pueden ser:

   • Patrones de creación: utilizados para crear y configurar de clases y objetos.

   • Patrones estructurales: su objetivo es desacoplar las interfaces e implementar clases y objetos. Crean grupos de objetos.

   • Patrones de comportamiento: se centran en la interacción entre asociaciones de clases y objetos definiendo cómo se comunican entre sí.
      

**Observer** 
 • Es un patrón de comportamiento que permite relacionar diferentes objetos entre si en torno a uno Principal.

**Adapter**
 • Permite la cooperación entre clases para extender sus funcionalidades a clases de diferentes tipos, que no pueden usarlas por mecanismos comunes como la herencia.

**Decorator**
 • Este patrón permite agregar funcionalidades o responsabilidades a objetos de forma transparente y dinámica, sin ser dependiente de la herencia en su totalidad.



**Ejemplifique un modelo MVC en el lenguaje de preferencia (Se consideran la organización de los archivos)**

**EL modelo a utilizar el en php** 
1. MVC
   - Controladores
   - Modulos
   - Views
     - Usuario
   - Index.php

**El modelo a utilizar ASP.NET MVC**
1. MVC
   - App_Data
   - App_Start
   - Contenido
   - COntroladores
   - Fuentes
   - Modelo
   - Js
   - Views

**El modelo a utilizar JS MVC**
1. MVC
   - Model
   - View
     - JSP
     - ASP
     - PHP
   - View Model
 
 # REFERENCIAS

 http://codingornot.com/mvc-modelo-vista-controlador-que-es-y-para-que-sirve