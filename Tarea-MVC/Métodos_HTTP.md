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

##  Códigos de estado HTTP

### 1XX Respuestas informativas 

  100 Continue. El servidor ha recibido los headers del request y el cliente debería proceder a enviar el cuerpo de la respuesta.
  
  101 Switching Protocols. El requester ha solicitado al servidor conmutar protocolos.
  
  102 Processing (WebDAV; RFC 2518). Usado en requests para reanudar peticiones PUT o POST abortadas.

### 2XX Peticiones correctas

200 OK. El request es correcto. Esta es la respuesta estándar para respuestas correctas.

201 Created. El request se ha completado y se ha creado un nuevo recurso.

202 Aceptada. El request se ha aceptado para procesarlo, pero el proceso aún no ha terminado.

204 No Content. El request se ha procesado correctamente, pero no devuelve ningún contenido.

205 Reset Content. El request se ha procesado correctamente, pero no devuelve ningún contenido y se requiere que el requester recargue el contenido.

### 3XX Redirecciones

300 Multiple Choices. Es una lista de enlaces. El usuario puede seleccionar un enlace e ir a esa dirección. Hay un máximo de cinco direcciones.

301 Moved Permanently. La página solicitada se ha movido permanentemente a una nueva URI.

302 Found. La página solicitada se ha movido temporalmente a una nueva URI.

303 See Other. La página solicitada se puede encontrar en una URI diferente.

304 Not Modified. Indica que la página solicitada no se ha modificado desde la última petición.

305 Use Proxy (desde HTTP/1.1). El recurso solicitado sólo está disponible a través de proxy, cuya dirección se proporciona en la respuesta. Muchos clientes HTTP como Mozilla o Internet Explorer no manejan bien estas respuestas con estos códigos de estado, sobre todo por seguridad.

###  4XX Errores del cliente

400 Bad Request. El servidor no puede o no va a procesar el request por un error de sintaxis del cliente.

404 Not Found. El recurso del request no se ha podido encontrar pero podría estar disponible en el futuro. Se permiten requests subsecuentes por parte del cliente.

405 Method Not Allowed. Se ha hecho un request con un recurso usando un método request no soportado por ese recurso (por ejemplo usando GET en un formulario que requiere POST).

406 Not Acceptable. El recurso solicitado solo genera contenido no aceptado de acuerdo con los headers Accept enviados en el request.

407 Proxy Authentication Required (RFC 7235). El cliente se debe identificar primero con el proxy. 

### 5XX Errores del servidor

  500 Internal Server Error. Error genérico, cuando se ha dado una condición no esperada y no se puede concretar el mensaje.
    
  501 Not Implemented. El servidor o no reconoce el método del request o carece de la capacidad para completarlo. Normalmente es algo que se ofrecerá en el futuro, como un nuevo servicio de una API.
  
  502 Bad Gateway. El server actuaba como puerta de entrada o proxy y recibió una respuesta inválida del servidor upstream.
  
  503 Service Unavailable. El servidor está actualmente no disponible, ya sea por mantenimiento o por sobrecarga.
  
  504 Gateway Timeout. El servidor estaba actuando como puerta de entrada o proxy y no recibió una respuesta oportuna por parte del servidor upstream.
  
  505 HTTP Version Not Supported. El servidor no soporta la versión del protocolo HTTP usada en el request.
  
  511 Network Authentication Required (RFC 6585). El cliente necesita autentificarse para poder acceder a la red.


# REFERENCIAS

https://developer.mozilla.org/es/docs/Web/HTTP/Methods

https://profesores.virtual.uniandes.edu.co/~isis3710/dokuwiki/lib/exe/fetch.php?media=temas:http-guia.pdf

https://diego.com.es/codigos-de-estado-http