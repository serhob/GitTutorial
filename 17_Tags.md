## Tags

Es posible guardar una foto del estatus de un branch mediante tags con la cual podremos guardar versiones de nuestro repo a medida que se suben los releases.

#### Ver los tags

Para ver los tags guardados en el repositorio usaremos el comando:

`
git tag
`

#### Crear tag

Para crear un tag utilizaremos:

git tag -a v0.1.2 -m "Nuevo tag v0.1.2"

> **`-a`** crea un annotated tag con el nombre **v0.1.2**

#### Subir Tag al Repositorio

Una vez creado el tag solo esta en nuestra maquina, para subirlo al servidor utilizamos el comando:

`
git push origin v0.1.2
`

#### Ver Tag del branch

Para ver cual es el ultimo tag de un branch usaremos el comando:

`
git describe master
`

