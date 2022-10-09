git ini
git add .
git status 
git status -s para comprobar en que estado se encuentra
git commit -m "Comienzo del proyecto"  para subir cambios
-- ejemplo git add index.html --git commit -m "actualización del Readmen"

git config --global user.name "Noemi Martinez Couto"
git config --global user.mail "nmc_1988@hotmail.com"

git log --oneline para ver listado de todas las copias commit

git reset --hard c84f925  para restaurar el fichero con el anterior cambio

git commit --amend para editar los nombre de los commit

git remote add origin https://github.com/noemarco7/CursoGit.git   para subir al githab
************************git branch -M main
git push origin master  para actualizar información
git pull https://github.com/noemarco7/CursoGit.git -- para descargar/actualizar desde el github a local (cambios en remoto)

git tag 15-09-20v1 -m "Versión 1 del proyecto"  -- para versiones
git push --tags

git clone https://github.com/noemarco7/CursoGit.git para descargar el repositorio a local

**crear rama
git branch nombre que queremos ponerle 
git branch javascript
para ver en que rama se está es 
git branch

**para moverte a la rama que quieres trabajar es 
git checkout y nombre de la rama 
git checkout javascript

**se puede editar el mismo fichero desde distintas ramas, y parece como dos proyectos distintos,
y cada cambio se ve en cada rama.

1. para hacer un merge es necesario  ir a la rama master
2. git merge mas el normbre de la rama que se quiere fusionar
git merge javascript


**Para clonar el repositorio de github a local
git clone repositorio web de github








Para mostrar las ramas de manera muy visual: git log --oneline --decorate --all --graph