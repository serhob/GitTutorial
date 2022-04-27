## Eliminado Archivos del repositorio.

#### Eliminar un archvo

Al eliminar un archivo ya sea mediante el comando `rm Archivo1.txt` o directamente desde el explorador este sera detectado por git y lo podemos ver con el comando de `git status` el cual nos indicara que esta en deleted y pendiente de agregar.

Para agregarlo a la etapa de stage se hace lo mismo que con un archivo nuevo.
`
git add Archivo1.txt
`

De igual manera para comprometer el cambio de la eliminacion a nuestro repositorio se usa:
`
git commit -m "Se elimina el archivo Archivo1.txt"
`
Y con `git status` comprobamos que ya no hay nada pendiente.

#### Eliminar y agregar a stage

Para eliminar y agregar a stage en un solo paso lo podemos hacer con el comando:
`git rm Archivo1.txt`
Si lo queremos comprobar con `git status` podemos ver que nos marcara el achivo como listo para ser conprometido (commit)


