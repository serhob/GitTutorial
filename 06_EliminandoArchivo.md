## Eliminado Archivos del repositorio.

#### Eliminar un archivo

Al eliminar un archivo ya sea mediante el comando `rm Archivo1.txt` o directamente desde el explorador este sera detectado por git y lo podemos ver con el comando de `git status` el cual nos indicara que esta en deleted y pendiente de agregar.

Para agregarlo a la etapa de stage se hace lo mismo que con un archivo nuevo.

`
git add Archivo1.txt
`

De igual manera para comprometer el cambio de la eliminación a nuestro repositorio se usa:

`
git commit -m "Se elimina el archivo Archivo1.txt"
`

Y con `git status` comprobamos que ya no hay nada pendiente.

#### Eliminar y agregar a stage

Para eliminar y agregar a stage en un solo paso lo podemos hacer con el comando:

`
git rm Archivo1.txt
`

Si lo queremos comprobar con `git status` podemos ver que nos marcara el archivo como listo para ser comprometido (commit)


#### Renombrar un archivo

Si nosotros renombramos un archivo y le damos `git status` nos aparecerá que hay 2 archivos pendientes de staged el primero nos dice que el archivo original se elimino y el segundo nos aparece como nuevo untracked. Para pasar el cambio a stage hay que agregar los 2 nombres de archivos con `git add`. Al igual que con la eliminación existe una herramienta en git para renombrar y pasar a stage en una sola instrucción y seria con el siguiente comando:

`
git mv Archivo1.txt Archivo2.txt
`
