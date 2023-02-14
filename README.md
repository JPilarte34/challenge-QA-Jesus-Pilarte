# challenge-QA-Jesus-Pilarte
Descripción
1.- Hay un archivo Excel el cual tiene 3 hojas dentro del mismo archivo, donde están los casos de pruebas y demás contenido requerido por la prueba.

2.- Para Ejecutar la prueba automatizada en postman,  Importar el archivo (AutomatizacionPlaceHolder.postman_collection.json) en postman el cual contiene una colección de 18 Request con 36 casos de pruebas, también importar el archivo (placeHolder.postman_environment.json) el cual contiene las variables de entorno.

3.- Se adjunto un archivo con un reporte grafico generado en newman llamado (AutomatizacionPlaceHolder-2023-02-14-15-56-27-164-0.html), si se necesita volver a generar este archivo solo hay que ejecutar el comando (newman run AutomatizacionPlaceHolder.postman_collection.json -r htmlextra -e placeHolder.postman_environment.json) dentro de la ruta de los archivos, recordar tener instalado nodeJS y newman para generar.
