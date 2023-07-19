1. Prerequisitos:
	- Maquina local con el sistema operativo Windows 10
	- Postman v10.16.0 

2. Comandos de instalación
Descargar postman de la pagina oficial y seguir los pasos https://www.postman.com/downloads/
Se debe descargar el archivo “Ejercicio2 PA.postman_collection.json” del github
Una vez descargado, abrir Postman, e importar el archivo dentro del Workspaces

3. Instrucciones para ejecutar los test
Ejecutar en orden numérico cada solicitud, la cual corresponde a cada item del ejercicio 2



4. Información adicional
Se agregaron test en cada solicitud, como:
Para todos los casos, la validación del statud code, para saber si la petición da un código 200, lo cual indica que está respondiendo correctamente el servicio
Para el caso 1, validación que el servicio que crea la mascota responda "status": "available"
Para el caso 2, validación que en el body de respuesta se encuentre el id creado, en este caso el “9998”
Para el caso 4, validación que en el body de respuesta se encuentre el nombre modificado de la mascota 
Se uso postman ya que es una herramienta facil de entender y cuenta con los test para las validaciones necesarias










