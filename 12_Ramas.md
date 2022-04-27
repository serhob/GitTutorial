## Ramas

Es nesesario que cada desarrollador trabaje sobre su propia rama para que no afecte directamente a la rama master que es la que deberia tener la ultima version estable del proyecto.

Una vez terminados sus cambios el desarrollador puede subirlos a la rama principal mediante un merge.

Para saber en que rama estamos lo podemos hacer con:
`
git brach
`

#### Crear una nueva rama

Ahora para hacer un nuevo branch a patir de la rama en la que estamos lo haremos con el siguiente comando:

`git checkout -b ramab`

Aqui el nombre del branch seria el `ramab` el branch puede ser el numero de ticket, Issue, BackLog, Freature para identificar mejor este branch.

Este comando ademas de crearnos una rama nueva llamada `ramab` tambien nos posiciona en esa rama.

#### Cambiar de rama

para cambiar de rama lo podemos hacer con:

`
git checkout master
`

En este caso nos cambiariamos a la rama master nuevamante.
