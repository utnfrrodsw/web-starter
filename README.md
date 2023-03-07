# Html + CSS + Javascript
# Proyecto inicial simple

## Requerimientos
- Para poder levantar el sitio web se requiere de un servidor web local. Se puede utilizar http-server (https://www.npmjs.com/package/http-server)
`npm install -g http-server`
- Una vez instalado, utilizar la consola para posicionarse en el directorio raíz del proyecto, y ejecutar: `http-server`
- Luego, podrá ver el sitio web corriendo en http://localhost:8080

## Ejercicios a realizar
En base al proyecto inicial, realizar las siguientes modificaciones:

1. Agregar favicon al sitio web (en todas sus páginas) y cambiar el título de la página a "Desarrollo de Software"
https://developer.mozilla.org/en-US/docs/Glossary/Favicon

2. En la sección Bio: cambiar la alineación del texto a centrado, poner alto de línea 1 y marcar en negrita las palabras: "Homer", "Mr. X" y "Springfield".

3. En la sección Contacto: 
 - Cuando se cargan correctamente todos los datos, mostrar el mensaje: ***"Mensaje enviado correctamente!"*** en color verde.
 - Agregar un campo para que el usuario pueda ingresar un teléfono de contacto. Si el mensaje se envía correctamente, mostrar el teléfono junto con el resto de los datos.

4. En la sección donde obtenemos un usuario desde una api externa:
 - En el caso de darse un error (por ej por desconexión de internet), manejar el error y mostrar un mensaje al usuario: "No se ha podido recuperar el usuario. Por favor inténtelo más tarde."
 - En el caso de que la request se ejecute correctamente, además de mostrar el nombre del usuario, agregar una etiqueta img y mostrar la imagen del usuario obtenido como respuesta de la api

5. Estilos CSS:
 - Escribir una versión alternativa del archivo styles.css pero aplicando sass. Crear un archivo llamado styles.scss.
  - Siguiendo la estrategia Mobile First, modificar el archivo styles.css para que en la vista mobile:
  	-  quitar al container-right el borde negro (en todas las páginas).
  	-  las opciones de menu se vean horizontalmente, uno al lado del otro
