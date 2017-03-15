# Proyecto-Web-Keys
## Informacion:
Esto es un proyecto que hemos tenido que realizar para el examen de Entorno de Desarrollo, el programa real se encarga de evaluar y guardar keys, pero este, es solo una pequeña parte del real, es cual hemos usado como prueba.

## Construir:
  - Para construirlo, primero nos bajamos es proyecto, ya sea en zip o mediante git clone
  - Nos colocamos en la carpeta raiz (Donde esta el pom.xml)
  - Ejecutamos el comando mvn package
  - Ya hemos obtenido el war.

## Ejecución:
  - Nos colocamos el la carpeta raiz del proyecto.
  - Lo primero que tendremos que hacer, es inicializar el servidor ya que es una aplicacion web.
  - El servidor lo trae envevido, ejecutamos el comando mvn jetty:run
  - Nos pillara la terminal y el puerto 9999
  - Accedemos a nuestro navegador a la direccion localhost:9999
  - Y listo, ya tenemos nuestro programa en funcionamiento.
  - Para parar el servidor, en la terminal pulsamos Ctrl + c
