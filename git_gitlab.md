# Trabajando con git y gitLab

## ¿Cómo comienzo una tarea?

1. Me hago una branch en gitLab desde development feature/nombreDeLaTarea.
2. En mi consola hago git fetch para traerme la nueva branch creada.
3. Git pull para traerme los ultimos cambios.
4. git checkout para irme a la rama creada.
5. realizo la tarea en la branch.
6. git add nombreDeArchivo que modifiqué.
7. git commit -m "nombre de la tarea de jira + descripcion de la misma".
8. git push origin branch.


**Ahora ya tengo mi commit en gitLab**

## ¿Y ahora que hago para que impacte en development?

1. Voy a gitLab.
2. Merge requests.
3. New merge request.
4. Del lado izquierdo selecciono la branch en la que estuve trabajando y del derecho dejo development que es a donde quiero llevar mi codigo.
5. Compare branch and continue. 

**Listo, ya puedo pasar mi tarjeta de Jira a code review y está lista para que hagan merge cuando corresponda!!!!**