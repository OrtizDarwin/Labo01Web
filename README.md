Pregunta 7

Al actualizar la página después de agregar las etiquetas <meta> realmente no se nota ningún cambio en la visualización, 
ya que estas etiquetas no afectan el diseño ni el contenido que se ve en pantalla.La función de las etiquetas meta es distinta: 
sirven para proporcionar información sobre la página, como el autor, las palabras clave, la descripción y también detalles técnicos 
(por ejemplo, la codificación de caracteres o la configuración del viewport en móviles).
Esta información la usan principalmente los navegadores y los motores de búsqueda para interpretar mejor el sitio web, no el usuario directamente.

Pregunta 9

El atributo src en la etiqueta <img> indica la ruta donde está guardada la imagen que se quiere mostrar.

Si la imagen está en la misma carpeta que el archivo HTML, basta con escribir solo el nombre del archivo, por ejemplo:
<img src="foto(aqui debemos colocar el nombre que tenga la imagen).jpg" alt="Foto">

Si la imagen está en una carpeta superior (es decir, un nivel arriba de donde está el HTML), hay que usar ../ para retroceder un nivel, por ejemplo:
<img src="../foto.jpg" alt="Foto">

Y si está en una subcarpeta dentro del proyecto, simplemente se coloca el nombre de la carpeta y después el archivo, por ejemplo:
<img src="imagenes/foto.jpg" alt="Foto">

lo importante es que la ruta que pongamos en src debe coincidir con la ubicación real de la imagen respecto al archivo HTML.
