### Investigacion de Metodos HTTP

# Introducción
En esta hoja se explican los principales elementos del  protocolo HTTP usado en las aplicaciones web. El  protocolo  HTTP  define  un  conjunto operaciones. Todas las peticiones HTTP deben incluir el tipo de operación que se desea realizar y el recurso sobre el cual se desea hacer la operación. Los métodos  más  comunmente  utilizados  incluyen opciones  para  obtener,  grabar  o  borrar recursos.

# Marco Teórico

### GET

  El método GET  solicita una representación de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos.

### HEAD

  El método HEAD pide una respuesta idéntica a la de una petición GET, pero sin el cuerpo de la respuesta.

### POST
    
  El método POST se utiliza para enviar una entidad a un recurso en específico, causando a menudo un cambio en el estado o efectos secundarios en el servidor.

### PATCH
    
  El método PATCH  es utilizado para aplicar modificaciones parciales a un recurso.

### PUT

  El modo PUT reemplaza todas las representaciones actuales del recurso de destino con la carga útil de la petición.
  
### DELETE
  
  El método DELETE borra un recurso en específico.

### OPTIONS

  El método OPTIONS es utilizado para describir las opciones de comunicación para el recurso de destino.






# REFERENCIAS

https://developer.mozilla.org/es/docs/Web/HTTP/Methods

https://profesores.virtual.uniandes.edu.co/~isis3710/dokuwiki/lib/exe/fetch.php?media=temas:http-guia.pdf