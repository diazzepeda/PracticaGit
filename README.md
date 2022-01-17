-'git config --global user.name "Aaron"' # Asignarle un nombre de usuario al git bash.

-'git config --global user.name'# Ver nombre de usuario del git bash. 

-'git config --global user.email "diazzepeda@github.com"' # Asignar un correo al git bash. 

-'git init' # Iniciar a monitorear todo el proyecto con Git. 

-'git status' # Archivos que no se han guardado en repositorio local. 

-'git add <nombredearchivo.tipoarchivo>' # Agrega un archivo unico para mandar a guardar en el repositorio. 

-'git add .' #Agrega todos los archivos con cambios al "Stating Area". 

-'git commit -m "Iniciamos"' #Commitiar con un mensaje.

-'git log' # Listar los ultimos commit's que se realizaron. 

-'git checkout <hashdelcommit>' # Se restablecen los cambios hasta el commit que se esta indicando. 
  
-'git checkout <nombrerama>' # Vuelve a la ultimo commit de la rama que se le esta indicando. 
  
-'git log > commits.txt ' # Crea y guarda en un archivo de texto todos los commit realizados. 
  
-'git reset --soft <hashdelcommit>' # Borra el commit pero no toca ninguna parte del codigo o "Working Area".
  
-'git reset --hard <hashdelcommit>' # Borra el commit "Stating Area" y tambien el codigo "Working Area". 
  
-'git branch' # Nos lista las ramas disponibles, y marca en la que estamos alojados actualmente. 
  
-'git branch <nombrerama>' # Nos crea una rama nueva. 
  
-'git checkout <nombrerama>' # Nos mueve a una rama en especifico. 
  
-'git checkout -b <nombrerama>' # Nos crea y mueve a una rama en especifico. 
  
-'git merge <nombrerama>' # Situarse en la rama que se actualizara, con este comando se adsrovera los cambios de la rama que se esta indicando. 
  
-'git branch -D <nombrerama>' #Situarse en otra rama valida, con este comando se eliminara la rama que se le indique. 

-'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' # Token HTTP Aaron Diaz

-'git clone <urlrepositorio> ' # Se clonara el proyecto indicado en nuestra computadora local, en el pasword indicar el token si es por HTTPS.

-'git remote add origin <urlrepositorio> ' # Indica que nuestro proyecto local y nuestro proyecto remoto en la url son los mismos.

-'git remote -v' # Verifica si los proyectos estan correctamnete conectados.

-'git remote remove origin' # Elimina la conexion entre el poryecto local y remoto que este en ese momento.

-'git push origen master' # Envia los cambios hacia el repositorio remoto.

-'git tag -a v<numversion> -m <mensaje> # Crear un tag para la version del proyecto.

-'git tag -a v<numversion> -m <mensaje> <idcommit>' # Añadir commit a tags de la version del proyecto.

-'git push origin v<numversion>' #Enviar al repositorio remoto el tag creado.

-'git push origin --tags' # Subir todos los tags al repositorio remoto.

-'git fetch origin' # Bajar los cambios del repositorio remoto a la rama oculta de origin/master.

-'git merge origin/master' #Combinar el commit del equipo con el tuyo.

-'ssh -keygen' # Situarse en donde quieres instalar la llave SSH.


-'' #

-'' #

###Comentarios adicionales

Issues # Crear tareas por realizar para el proyecto en estilo foro.

Milestone # Crear un Issue para el proyecto y asignar un milestone con fechas.

Labels # Asignar una etiqueta descriptiva al Issues.

Intalacion de llave SSH #  -https://www.youtube.com/watch?v=Q5kQmlslOwA&list=PL9xYXqvLX2kMUrXTvDY6GI2hgacfy0rId&index=9

Rebase # Fusiona las ramas en una sola linea copiando los commits en una sola linea.
