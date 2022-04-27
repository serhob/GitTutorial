## Ramas

Es necesario que cada desarrollador trabaje sobre su propia rama para que no afecte directamente a la rama master que es la que debería tener la ultima version estable del proyecto.

Una vez terminados sus cambios el desarrollador puede subirlos a la rama principal mediante un merge.

Para saber en que rama estamos lo podemos hacer con:
`
git brach
`

#### Crear una nueva rama

Ahora para hacer un nuevo branch a partir de la rama en la que estamos lo haremos con el siguiente comando:

`git checkout -b ramab`

Aquí el nombre del branch seria el `ramab` el branch puede ser el numero de ticket, Issue, BackLog, Feature para identificar mejor este branch.

Este comando ademas de crearnos una rama nueva llamada `ramab` también nos posiciona en esa rama.

#### Cambiar de rama

para cambiar de rama lo podemos hacer con:

`
git checkout master
`

En este caso nos cambiaríamos a la rama master nuevamente.
