- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    git reset --hard HEAD~1. Esto se usa para deshacer el ultimo commit y perder los cambios en el working copy. Ponemos --hard para eliminar el último commit y HEAD-1 hace referencia al commit anterior

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
    Usé git reflog para encontrar el commit que ha queedado inacceesible ya que con este comando permite ver el historial de cambios. Y luego de la lista mostrada hice un git reset --hard 2b54193 para recuperar el commit

-  El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
    Ninguno, la rama main no tiene cambios nuevos. Todo su historial ya está incluido en la rama styled    
