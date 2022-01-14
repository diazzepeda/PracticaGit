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

