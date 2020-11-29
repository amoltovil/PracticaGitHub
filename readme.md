#Respuestas Ejercicio 1
* ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1
Lo he hecho así para volver a la situación inicial que teniamos en el working copy (sin los cambios hechos en git-nuestro.md)

* ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

git reflog
para ver el identificador del commit al que quiero volver

git reset c9b2c73
no me devolvio el fichero modificado al working copy

git status 
me dice que lo añada de nuevo al staging area, pero no es lo que yo queria, rectifico con el siguiente comando:

git reset --hard c9b2c73
con este comando si consigo tener en el working copy el archivo git-nuestro modificado

* El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
muestra el mensaje "Already up-to-date", parece que no hay nada que actualizar o todos los cambios se han efectuado

* El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si, existe conflicto porque el archivo git-nuestro.md es distinto en cada una de las ramas styled y htmlify

* El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No causa conflicto, realiza un merge fast forward, integra el commit en el proyecto.

* ¿Qué comando o comandos utilizaste en el paso 25?
git graph

* El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, de hecho lo es, porque no existe ningún commit entre las dos ramas que estamos uniendo.

* ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

* ¿Qué comando o comandos utilizaste en el paso 28?
git reset --hard HEAD~1

* ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

* ¿Qué comamdo o comandos utilizaste en el paso 30?
git reflog
git reset --hard 0e390c3

* ¿Qué comando o comamdos utilizaste en el paso 32?
git reflog 
git reset 1c60f0f

* ¿Qué comando o comandos utlizaste en el paso 33?
git reflog
git reset 0e390c3

**Alicia Moltó**
