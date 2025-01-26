- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    git reset --hard HEAD~1. Esto se usa para deshacer el ultimo commit y perder los cambios en el working copy. Ponemos --hard para eliminar el último commit y HEAD-1 hace referencia al commit anterior

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
    Usé git reflog para encontrar el commit que ha queedado inacceesible ya que con este comando permite ver el historial de cambios. Y luego de la lista mostrada hice un git reset --hard 2b54193 para recuperar el commit

-  El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
    Ninguno, la rama main no tiene cambios nuevos. Todo su historial ya está incluido en la rama styled 

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
    Si, al hacer el merge de la rama htmlify ha detectado diferencias en las mismas lineas del archivo git-nuestro.md

 - El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
    No causó conflicto, porque main y styled no tienen cambios en las mismas partes de los archivos y se ha podido fusionar automáticamente

- ¿Qué comando o comandos utilizaste en el paso 25?
    git log --graph --all    

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
    Si, ya que la rama main no tiene nuevos commits desde que se creó la rama title   

- ¿Qué comando o comandos utilizaste en el paso 27?
    git reset --merge ORIG_HEAD 

- ¿Qué comando o comandos utilizaste en el paso 28?
	git restore .

- ¿Qué comando o comandos utilizaste en el paso 29?
	git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
	git merge title

- ¿Qué comando o comandos usaste en el paso 32?
	git log  y git reset --hard aeb3a20 

- ¿Qué comando o comandos usaste en el punto 33?
	git reflog y >git reset --hard 5c74456