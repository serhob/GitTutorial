## Git Log

Para ver el log de todos los commit que se han hecho en el repositorio donde estemos situados lo podemos hacer mediante el comando:

`
git log
`

Este nos mostrara la información referente de cada commit como el ID del commit, la rama en la que esta, el nombre del autor del commit seguido de su email, la fecha y La descripción que le pusimos al commit:


    commit 818d0135af2c42a3a7dba0b2115c7289b009d587 (HEAD -> master)
    Author: Sergio Ochoa <sergio.ochoa@asd-tech.mx>
    Date:   Tue Apr 26 22:42:31 2022 -0500

    Agregando archivos

También hay una forma mas reducida de ver este logo y es con la instrucción:

`
git log --oneline
`

Este nos mostrara el historial con un pequeño hash que funciona como identificador del commit

    818d013 (HEAD -> master) Agregando archivos.
    419f39d Segundo commit con cambios.
    31b57b1 Primeros archivos agregados.

> Al igual que con la pantalla de diff para salir de la la pantalla de log lo haremos con la letra `q`

