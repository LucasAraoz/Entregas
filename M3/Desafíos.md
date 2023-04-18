# Ejercicio 1
Te encuentras trabajando en el repositorio website en el branch custom-navbar. 
Debes pausar tu trabajo en el commit actual y borrar el archivo status.js del
branch master de este repositorio. No hay tiempo para terminar el commit.

1. ``` git stash ```
Este comando pausará temporalmente el commit y lo guardará para después.
2. ``` git checkout master ```
Cambia a la rama master para trabajar en el fix.
3. ``` git rm status.js ```
Elimina el archivo en conflicto.
4. ``` git commit -m "mantenimiento" ``` 
5. ``` git switch custom-navbar ```
Cambia a la rama del commit sin terminar.
6. ``` git stash pop ```
Regresa al ultimo stash guardado para continuar trabajando en el commit.
# Ejercicio 2
Debemos subir a producción el proyecto que se encuentra en la rama front-react. La rama master se usa para producción.

1. ```git checkout master```
2. ```git pull``` Nos aseguramos que sea la versión mas reciente de master.
3. ```git merge front-react``` Mergeamos el branch del proyecto con master.
4. ```git push origin master``` Pusheamos a master.
