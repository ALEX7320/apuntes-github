GUIA DE GITHUB

CONFIGURACION DE INICIO /*/*/*/*/*/*/*/*/*/*/*/*/

// insertar datos de perfil (obligatorio)
git config --global user.name "Bailon"
git config --global user.email paucarmontesbailon@gmail.com

// ver datos ingresados
git config --global user.name 
git config --global user.email

// ver configuraciones realizadas
git config --global --list

COMANDOS GIT /*/*/*/*/*/*/*/*/*/*/*/*/

// iniciar el proyecto 
git init

// nos muestra el estado de nuestro proyecto
git status -- 

// hace lo mismo que git status pero con seguimiento 
git status -s 

// seguimineto a todo el proyecto
git add .

// seguimiento a modulo especifico
git add archivo.py

// guarda modulo / proyecto agregado
git commit "version"

// comando de  commit y add 
git commit -am "version" 

// muestra nuestras versiones(los commit que hacemos)
git log --oneline  


// restablece a la version guardada (por codigo de verision)
git reset --hard 8ca58a7 


// subir de local  a github
git push origin master

// github a local
git pull origin master



// eliminar archivos
git rm miarchivo.php

// eliminar carpetas
git rm -r micarpeta

CONFIGURAR EL GITHUB/*/*/*/*/*/*/*/*/*/*/*/*/

// eliminar acceso a repositorios
git remote rm origin

// lista de repositorios disponible
git remote -v 


ERROR INDEX /*/*/*/*/*/*//

// elimiar dicho archivo
rm -f .git/index.lock


---------------------1--------------------------------
GIT PULL <link de su repositorio> = cambios hechos en github actualizarlos en local
GIT TAG <FECHA Y VERSION> -m "titulo" (nos permite especificar versiones del proyecto)
GIT PUSH --TAGS = SUbira nuestra version al github
GIT CLONE <link de repositorio > = clonas el proyecto desde github


EDITOR VIND /*/*/*/*/*/*/*/*/*/*/*/*/
"para cambiar descripcion de alguna version"

// ingresar a la consola
git commit --amend

// para borra el texto
:i
"una vez activado borramos el texto superior y presionamos esc"

// para cambiar
:i
"aca se escribe la nueva descripcion enter + esc"

// para guardar y salir
:wq



-----------------------------------------------------
DOCUMENTACION

https://bluuweb.github.io/tutorial-github/guia/fundamentos.html#comandos-basicos