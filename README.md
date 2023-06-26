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



## El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
## El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
## El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
## ¿Qué comando o comandos utilizaste en el paso 25?
## El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
## ¿Qué comando o comandos utilizaste en el paso 27?
## ¿Qué comando o comandos utilizaste en el paso 28?
## ¿Qué comando o comandos utilizaste en el paso 29?
## ¿Qué comando o comandos utilizaste en el paso 30?
## ¿Qué comando o comandos usaste en el paso 32?
## ¿Qué comando o comandos usaste en el punto 33?
