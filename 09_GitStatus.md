## git status

Para ver el estatus de lo que estamos modificando hemos estado utilizando el comando:

`
git status
`

La cual nos da de manera mas detalla el estatus de los archivos pendiente. Pero hay una forma mas reducida de ver el estatus la cual es mucho mas elegante y mas fácil de seguir una vez que te has acostumbrado a trabajar con git y lo podemos ver con el comando:

`
git status -s
`

Este comando nos regresa una Letra y el nombre del archivo.

`
M Archivo1.txt
`

La letra a la derecha indica el estatus del archivo en este caso `M` es por Modificado, ademas esa letra vendrá con un color rojo para el caso de que no ha sido agregado al stage o verde cuando ya se encuentre en stage. Cuando el archivo es nuevo aparecerá de la siguiente manera:

`
?? Archivo3.txt
`

Los ?? indican el estatus de untracked. Al momento de agregarlo con `git add` el estatus se vera:

`
A Archivo3.txt
`



