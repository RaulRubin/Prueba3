# TAREA RAMAS
## 1. Creamos la rama
> Aqui cremos la rama nueva llamada primera con *git branch*
![image](https://github.com/RaulRubin/Prueba3/blob/main/Ej3/Creando%20branch%20primera.png)

## 2. Fusionamos las ramas
> Despues de hacer creado la rama haremos un archivo desde la rama primera, para ello haremos un *git checkout primera* para entrar en la rama primera.

> Luego de eso haremos un fichero en la rama y le hacemos un *git add* y *git commit* para guardarlo, cambiamos a la rama principal y hacemos un *git merge primera* para fusionarlas.
![image](https://github.com/RaulRubin/Prueba3/blob/main/Ej3/Creando%20el%20fichero%20y%20lo%20fusiono.png)

## 3. Borramos la rama
> Para borrar una rama haremo *git branch -d primera* para borrar la rama, el valor -d es para borrar.
![image](https://github.com/RaulRubin/Prueba3/blob/main/Ej3/Borro%20la%20rama.png)

## 4. Creamos un conflicto
> Deberemos de crear otra rama la cual llamaremos segunda, cuando esta sea creada hacemos lo mismo que hicimos con la rama primera, crear un fichero desde la rama segunda y modificarlo.

> Pero para que salga el comflicto deberemos de editar tambien ese fichero desde la rama principal, y cuando se haga un *git merge segunda* saldra un error debido a que este archivo se esta modificando desde las 2 ramas.
![image](https://github.com/RaulRubin/Prueba3/blob/main/Ej3/Sale%20conflicto.png)

> Para arreglarlo solo deberemos de borrar los ultimos cambios y fusionarlo ahora si con la rama.
