## Agregando archivos al repositorio

#### Agregar arcivos al proyecto

Agregamos nuestros primeros archivos al proyecto. 
Archivo1.txt

#### Estatus

Verificamos el estatus actual de nuestro repositorio mediante el comando:
`
git status
`

Este nos regresará que tenemos un archivo "Archivo1.txt" Untracked en color rojo.

#### Agregar los archivos al repo.

Para seleccionar los archivos que deseamos se agreguen al repositorio se hace con el comando:
`
git add Archivo1.txt
`
> `git add` puede agregar mas de un archivo a la vez y fuanciona agreando los de mas nombres de archivos separados por un espacio, tambien se puede usar expresiones reculares como por ejemplo `*.txt` para todos los archivos con extencio ".txt".

> Podriamos agregar todos los archivos que aparecen en el listado como pendientes mediante el comando "`git add .`" pero esto es considerado una mala practica ya que podriamos olvidar que movimos algun archivo pero que no queriamos subir al repositorio y se podria ir tambien.txt

Una vex agregados los archivos al repositorio si le volvemos a dar `git status` nos mostrara el archivo en verde que estan listos para ser comprometidos en este punto estan en la estapa de **Stage**




