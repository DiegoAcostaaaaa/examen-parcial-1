Bitacora del Examen Parcial 1 
Creo la carpeta con sus cuatro archivos para después darle seguimiento con git init, git add *.py, y por último un git commit -m “Confirmamos cambios”.

Creo un nuevo repositorio en git llamado examen-parcial-1 que sea público y sin el README, después de eso copiamos la URL del repositorio.

Ahora vamos a subir el repositorio local al repositorio remoto, con los siguientes comandos: 
git remote add origin https://github.com/DiegoAcostaaaaa/examen-parcial-1.git
git branch -M main
git push -u origin main
Esto se comprueba refrescando el repositorio remoto y ver que tenga los archivos de nuestro directorio.
Ahora desde el repositorio remoto creamos el README para después escribirle dentro, por ahora solo “Bitácora del Examen Parcial 1” y guardarlo.

Desde el repositorio local vamos a recuperar los cambios hechos desde el remoto, esto con el comando “git pull origin main”

Ahora vamos a modificar dos archivos de nuestro repositorio local, en mi caso los dos primeros, después en el archivo README vamos a agregar todas las instrucciones hasta ejecutadas hasta ahora, para finalmente confirmar estos cambios con el git commit -a -m "Agregamos a preparacion y confirmamos camb
ios" y subirlos al repositorio remoto con el "git push origin main".