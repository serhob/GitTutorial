## Agregando archivos al repositorio

#### Agregar archivos al proyecto

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

> `git add` puede agregar mas de un archivo a la vez y funciona agregando los de mas nombres de archivos separados por un espacio, también se puede usar expresiones reculares como por ejemplo `*.txt` para todos los archivos con extensión ".txt".

> Podríamos agregar todos los archivos que aparecen en el listado como pendientes mediante el comando "`git add .`" pero esto es considerado una mala practica ya que podríamos olvidar que movimos algún archivo pero que no queríamos subir al repositorio y se podría ir también.

Una vex agregados los archivos al repositorio si le volvemos a dar `git status` nos mostrara el archivo en verde que están listos para ser comprometidos en este punto están en la etapa de **Stage**

#### Commit de los archivos

Para comprometer los archivo en el repositorio utilizamos el comando:

`
git commit -m "Commit inicial"
`

> Al utilizar `-m` nos permite escribir en ese momento una descripción de lo que se esta incluyendo en ese commit dentro de las `""`

También podemos utilizar simplemente

`git commit`

Este comando nos abrirá el editor de texto configurado para que nosotros escribamos el texto correspondiente a la descripción del commit.

Si volvemos a ejecutar `git status` nos dirá que ya no hay nada para commit.




