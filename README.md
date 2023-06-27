
# PRACTICA 01 MODULO 01- EJERCICIO GIT


## ¿Qué comando utilizaste en el paso 11? ¿Por qué?

Utilicé el comando siguiente:
```
git reset --hard HEAD~1
```
Esto lo hice así para poder recuperar en el working copy los archivos originales en el commit inicial. 


## ¿Que comando utilizaste en el paso 12? ¿Por qué?

Como estaba en el commit inicial y con git log no podía ver el commit anterior, usé el comando siguiente:
```
git reflog
```
Obteniendo así los pasos dados anteriores, con los identificadores de los commits. De esta forma pude obtener el id del commit el cual utilicé para rescatar usando el comando:
```
git reset --hard <id_commit>
```
Utilicé ese comando para restaurar en el working copy el archivo.

<img width="498" alt="image" src="https://github.com/inmiti/PRACTICA01_GIT/assets/118215654/57bba532-5180-413a-b7fd-f7b9b7e7a7c2">


## El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No sale conflicto, sale: 
```
Already up to date
```
Se debe a que al haber recuperado el commit anterior, no se ha creado ningun nuevo commit, y entonces las ramas *style* y *master* están alineados, no siendo necesario hacer merge. 

<img width="680" alt="image" src="https://github.com/inmiti/PRACTICA01_GIT/assets/118215654/5767983e-ef44-49c9-90d4-bfa3a57ced19">


## El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si, porque había diferencias entre los git-nuestros.md de la rama *styled* con respecto al archivo git-nuestro.md de la rama *htmlify*.
Los resolví quedando:

<img width="673" alt="image" src="https://github.com/inmiti/PRACTICA01_GIT/assets/118215654/35e8b77c-affc-4e2d-86b9-e5f5d2e7772a">

PASO 21
## El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No ha habido conflicto porque ha hecho un fast forward, master se ha movido a la rama styled, por lo que el archivo mantenido  

## ¿Qué comando o comandos utilizaste en el paso 25?
## El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
## ¿Qué comando o comandos utilizaste en el paso 27?
## ¿Qué comando o comandos utilizaste en el paso 28?
## ¿Qué comando o comandos utilizaste en el paso 29?
## ¿Qué comando o comandos utilizaste en el paso 30?
## ¿Qué comando o comandos usaste en el paso 32?
## ¿Qué comando o comandos usaste en el punto 33?
