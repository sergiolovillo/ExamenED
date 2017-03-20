# ExamenED

## Descripción:
Se trata de un programa sencillo que recibe una key, le asocia un valor y lo imprime.

## Utilización del proyecto:
- Utilizamos el comando git clone con la url del proyecto.
- Ejecutamos el comando mvn package en la carpeta raíz.
- Con este comando se creará todo lo necesario para su ejecución.
  
## Ejecución:
- Una vez creado el repositorio local, importamos el proyecto en STS o trabajamos desde la consola.
- Ejecutamos mvn jetty:run para que se ejecute el servidor local que hosteará nuestra aplicación web.
- Este servidor local está alojado en el puerto 9999. Así está en el pom.xml, pero se puede cambiar. 
- Escribimos localhost:9999/ en el navegador, y se abrirá el cliente de nuestra aplicación.
- El programa recibirá dos argumentos, una key y un value, y los imprimirá.

