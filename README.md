# Argentina Programa 4.0

## Practica de git

# configuracion de git


git init   --->solo se configura una vez
git config --global user.name "Aldo2022"   --->solo se configura una vez
git config --global user.email "-- mi correo--"   --->solo se configura una vez

git add .   o   git add index.html
git commit -m "--se escribe un comentario---"

##
git remote add origin https://github.com/Aldo2022/ ---aca va el nombre del repositorio de github---.git  --->solo se configura una vez
git push -u origin main    --->solo se configura una vez luego solo se escribe asi.
git push

## Para crear una rama dev .->Tengo que estar posicionado en mi rama Main
git branch dev

## Para crear una Rama dev desde mi pc hacia git hub
git push -u origin dev
siempre tengo q estar posicionado en dev

## Para borrar una rama dev .->No tengo que estar posicionado en dev
git branch -D dev

## Para ver en que rama me encuentro ubicado
git branch

## Para cambiar el nombre de una rama se agrega  -M  
git branch -M


## Para cambiar a otra Rama
git checkout --nombre de la rama--

## Para traer todo los cambios a mi rama main
### Tengo que posicionarme en mi rama main luego y traer los cambios
git merge --rama donde estan los cambios--


## Para trabajar con una version anterior hard
git reset --hard sdjhsadjhsajdas
## En este caso se va borrando versiones de commit hasta encontrar el codigo selecionado sdjhsadjhsajdas


## Para trabajar con una version anterior soft
git reset --hard sdjhsadjhsajdas
## En este caso se trae como ultima version un commit guardado como anterioridad

## Para ver y buscar versiones de commits anteriores
git log

## Para ver como es el estado de mi archivos antes de copiarlos
git status

# CLONAR PROYECTO
Si es con un archivo Zip no voy a tenr el historial de cambios

utilizando el
git clone ---url de github---


# TRAER CAMBIOS DE UN PROYECTO
git pull


## Crear una Release