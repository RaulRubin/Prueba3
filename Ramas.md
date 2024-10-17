# TAREA RAMAS
## 1. Creamos la rama
> Aqui cremos la rama nueva llamada primera con *git branch*
![image]()

## 2. Fusionamos las ramas
> Despues de hacer creado la rama haremos un archivo desde la rama primera, para ello haremos un *git checkout primera* para entrar en la rama primera.

> Luego de eso haremos un fichero en la rama y le hacemos un *git add* y *git commit* para guardarlo, cambiamos a la rama principal y hacemos un *git merge primera* para fusionarlas.
![image]()

## 3. Borramos la rama
> Para borrar una rama haremo *git branch -d primera* para borrar la rama, el valor -d es para borrar.
![image]()

## 4. Creamos un conflicto
> Deberemos de crear otra rama la cual llamaremos segunda, cuando esta sea creada hacemos lo mismo que hicimos con la rama primera, crear un fichero desde la rama segunda y modificarlo.

> Pero para que salga el comflicto deberemos de editar tambien ese fichero desde la rama principal, y cuando se haga un *git merge segunda* saldra un error debido a que este archivo se esta modificando desde las 2 ramas.
![image]()

> Para arreglarlo solo deberemos de borrar los ultimos cambios y fusionarlo ahora si con la rama.
