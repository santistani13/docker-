El comando HEALTHCHECK comprueba si el contenedor esta funcionando le dice cómo probar un determinado container de Docker para verificar si aún se encuentra realizando sus labores. Permite detectar errores. Verifica el estado del container y proceso de inhabilitación de cualquiera de los controles de salud que pudieran haber sido heredados por la base imagen o imagen base.

El comando ONBUILD permite establecer disparadores dentro de una imagen. Los disparadores se disparan mas tarde, cuando la imagen se utilice como base para otra. Se convertirán en parte del nuevo contexto de la imagen descendente y no serán niveles de sistema de archivos en su docker build.

El comando VOLUME es una carpeta física en nuestro equipos donde se almacenan datos del contenedor. Los volúmenes de Docker son utilizados para persistir los datos que manejan los contenedores. Esto nos permite crear contenedores e indicarles donde tienen que persistir nuestros datos.
Son simplemente archivos y directorios en el host que esté corriendo docker. Estos son utilizados por los contenedores para persistir y/o leer datos. 

A la hora de usar volúmenes tenemos dos opciones:

Crear un volumen utilizando el CLI de Docker. Al momento de crear un contenedor y montarlo con un volumen de este tipo estamos usando ‘Volume mounting’
Usar un directorio del host que esté corriendo docker. Este tipo de montaje se denomina ‘Bind mounting’ 