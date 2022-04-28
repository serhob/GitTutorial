## Recuperar archivos de Stage

#### Git Restore

Si hay un cambio en la estampa de stage que queramos restaurar como por ejemplo que hayamos eliminado un archivo, lo podemos hacer mediante el comando:

`
git restore --staged Archivo1.txt
`

Esto hará que el archivo ya no este dentro de la etapa stage, por lo tanto si hacemos un `git status` nos aparecerá que hay un cambio que no esta en la etapa de stage y si lo buscamos en la carpeta de nuestra computadora nos daremos cuenta que ya no existe el archivo. Si nosotros quisiéramos recuperar ese archivo del repositorio lo que tendríamos que hace ahora seria:

`
git restore Archivo1.txt
`

