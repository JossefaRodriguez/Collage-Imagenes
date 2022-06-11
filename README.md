# Desafio Collage Imagenes

### El desafío se encuentra basado en lo siguiente:

- Express-fileupload 
- Postman y body-parser
- Eliminando archivos

###REQUERIMIENTOS

1. Integrar express-fileupload a Express.
2. Definir que el límite para la carga de imágenes es de 5MB.
3. Responder con un mensaje indicando que se sobrepasó el límite especificado.
4. Crear una ruta POST /imagen que reciba y almacene una imagen en una carpeta pública del servidor. Considerar que el formulario envía un payload con una propiedad “position”, que indica la posición del collage donde se deberá mostrar la imagen.
5. Crear una ruta GET /deleteImg/:nombre que reciba como parámetro el nombre de
una imagen y la elimine de la carpeta en donde están siendo alojadas las imágenes.
Considerar que esta interacción se ejecuta al hacer click en alguno de los números
del collage.