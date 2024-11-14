
**INTEGRANTES DEL GRUPO:**
-Paula  Arroyo
-Kevin Crespo
-Adrian Ramses Muñoz



---------------------------------------------------------------****ADRIAN RAMSES MUÑOZ:****--------------------------------------------------------------

Se inició el proceso creando las carpetas y archivos en mi ordenador de manera local, al mismo tiempo que se creó el repositorio remoto. Luego, se hizo un primer commit para subir la estructura de carpetas con sus archivos correspondientes a la rama master.

Posteriormente, se creó la rama developer, en la cual se hizo un commit para guardar los cambios en el repositorio remoto. En esta misma rama (developer), creé el archivo adrianMunoz.html, que contiene una lista desordenada con mis pasatiempos. Se realizó un commit para guardar los cambios del nuevo archivo en el repositorio remoto.

Luego, mis compañeros de grupo crearon sus propias ramas como copias de la rama developer. Empezamos a trabajar en conjunto para crear y resolver conflictos, realizando cambios y añadiendo archivos en sus ramas. Después, cada uno hizo un merge de sus ramas en developer con los cambios realizados.

Resolvimos conflictos en la rama developer en el archivo index.html, el cual contiene un pequeño menú de navegación hacia los diferentes archivos HTML.

****RESUMEN DE ALGUNAS OPERACIONES REALIZADAS:****
**Verificación de las ramas locales:**
 Ejecutaste el comando git branch y verificaste que estabas trabajando en la rama developer, que era la rama activa en tu repositorio.

**Realizaste un pull de la rama developer:**
 Al ejecutar git pull origin developer, Git comprobó que no había cambios nuevos en el repositorio remoto y te informó que ya estabas actualizado.

**Verificación del estado de la rama developer:**
 Al usar git checkout developer, confirmaste que estabas en la rama correcta (developer) y que tu rama local estaba sincronizada con la versión remota de la misma rama.

**Ejecutaste un pull y obtuviste actualizaciones:**
 Volviste a ejecutar el comando git pull origin developer y, en esta ocasión, Git descargó nuevas actualizaciones, específicamente un archivo index.html con 11 líneas añadidas, realizando un "fast-forward" para actualizar tu rama local.

**Verificación de los archivos en tu directorio de trabajo:**
 Usaste ll para listar los archivos en tu directorio y confirmaste la presencia de varios archivos HTML, incluido index.html, que había sido actualizado.

**Editaste el archivo index.html:**
 Abriste el archivo index.html en Visual Studio Code (code index.html) y realizaste cambios en él.

**Añadiste el archivo modificado al área de preparación:**
 Después de editar el archivo, usaste git add index.html para añadir los cambios al área de preparación.

**Commit de los cambios:**
 Intentaste realizar un commit con el mensaje "se arregló conflicto", pero Git te informó que no había cambios pendientes, ya que estos ya estaban comprometidos. Sin embargo, ejecutaste git commit -m "se arregló conflicto" y los cambios fueron finalmente comprometidos con éxito.

**Push de los cambios a GitHub:**
 Finalmente, usaste git push origin developer para subir tus cambios al repositorio remoto en GitHub. La operación fue exitosa, y Git transfirió los objetos modificados y actualizó la rama developer en el repositorio remoto.

**Verificación del estado final:**
 Ejecutaste git status y confirmaste que tu rama local estaba actualizada y sincronizada con el repositorio remoto, sin cambios pendientes.




---------------------------------------------------------------****PAULA ARROYO:****--------------------------------------------------------------











---------------------------------------------------------------****KEVIN CRESPO:****--------------------------------------------------------------

