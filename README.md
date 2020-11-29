# PracticaGitGithub
Practica donde aplico mis conocimientos en Git y GitHub

 
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    R: git reset --hard HEAD~1, esto hace que se borra el commit, ademas de lo que esta en el working copy
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
    R: git reset --hard d76964c , esto hace que vuelva el commit, ademas de posicionarse
    en la rama que se encontraba, que en este cas es styled.
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
    R: no me causo conlficto, esto es por el uso del comando anterior, al volver un paso atras
    me dejo en la rama styled, por lo que solo absorbi a master.
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
    R: si causo conlficto, esto es porque se chocaban los contenidos de la rama styled y la rama htmlify,
    lo que tuve que hacer fue modificar el archivo, dandole prioridad al contenido de la rama styled.
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
    R: No me causo conflicto, esto es porque al revisar ambos archivos en las distintas ramas, note que eran
    exactamente iguales, por lo que solo tuve que hacer git merge styled.
- ¿Qué comando o comandos utilizaste en el paso 25?
    R: utilice el comando: git log --pretty=oneline --graph.
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
    R:Podria ser fast forward, pero en ese caso deberiamos combinar el contenido de los dos archivos
    de cada rama. en este caso se crea un nuevo commit por lo que no genera conflicto.
- ¿Qué comando o comandos utilizaste en el paso 27?
    R: hice: git reset HEAD~1, esto es para mantener lo que se encuentra en el working copy.
- ¿Qué comando o comandos utilizaste en el paso 28?
    R: git checkout -- git-nuestro.md
- ¿Qué comando o comandos utilizaste en el paso 29?
    R: git branch -D title
- ¿Qué comando o comandos utilizaste en el paso 30?
    R: git reset --hard HEAD~1
- ¿Qué comando o comandos usaste en el paso 32?
    R: git checkout 1166d1a393c02cf65a067a7180e2582c27ee959d
- ¿Qué comando o comandos usaste en el punto 33?
    R: git reset --hard 7808ec28279ef5b49ca118f719fbf1a284e0e1cb
