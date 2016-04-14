#Práctica KC-GitNuestro</br>
</br>
planteamiento de consultas respecto a la práctica de Git

**- ¿Qué comando utilizaste en el paso 11? ¿Por qué?**</br>
**git reset --hard HEAD~1** con reset desaces un commit, el argumento --hard hace que no guarde los cambios y HEAD~1 hace que el commit a deshacer vaya al commit padre
</br>
**- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**</br>
**git reflog** para listar el seguimiento de toda la actividad realizada</br>
**git reset --hard 7182090** con el hash del commit que habíamos eliminado en el paso anterior, vuelvo a ese estado. 
</br>
**- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**</br>
no da conflicto ya que absorvemos una rama con unos commits que ya teníamos.
</br>
**- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**</br>
Si da conflicto; ambas ramas tienen modificaciones en las mismas líneas del archivo git-nuestro.md
</br>
**- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**</br>
No da conflicto, ya que la rama que absorve ya contiene los commits de la rama absorvida.
</br>
**- ¿Qué comando o comandos utilizaste en el paso 25?**</br>
git log --graph
</br>
**- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**</br>
si podría ser un fast-forward; es lieal y hubiese bastado mover el puntero con fast forward
</br>
**- ¿Qué comando o comandos utilizaste en el paso 27?**</br>
git reset HEAD~1
</br>
**- ¿Qué comando o comandos utilizaste en el paso 28?**</br>
git checkout -- git-nuestro.md para descartar los cambios
</br>
**- ¿Qué comando o comandos utilizaste en el paso 29?**</br>
git branch -D title
</br>
**- ¿Qué comando o comandos utilizaste en el paso 30?**</br>
git reflog</br>
git reset --hard 0d4c4f7
</br>
**- ¿Qué comando o comandos usaste en el paso 32?**</br>
git reflog</br>
git checkout 63733bb
</br>
**- ¿Qué comando o comandos usaste en el punto 33?**</br>
git reflog
git checkout d1a6f9a
</br>

