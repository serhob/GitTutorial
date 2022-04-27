## Ignorar archivos

Hay veces que requerimos tener archivos de configuracion que sean especificos solamente para nuestra maquina como por ejemplo variables de entorn, en estos casos nesecitaremos tener el archivo en nuestra maquina pero que este no se suba al repositorio ni que nos este marcando que esta pendente o untracked.

Para este ejemplo supongamos que agregamos el archivo `.env` para nuestras variables de entorno en donde pondremos por ejemplo un usuario y password. 

Para lograr que ese archivo sea ignorado por git deberemos crear un nuevo archivo llamado `.gitignore` en el cual debemos agregar el nombre del archivo que queremos ignorar en este caso `.env` podemos agregar los archivos que necesitemos y tambien podemos agregar carpetas para este caso se pone de la siguiente manera `NombreCarpeta/`.

Una vez agregado el archivo `.env` a `.gitignore` si queremos ver el status `git status` veremos que ya no aparece el archivo `.env` pero si aparece el archivo `.gitignore` en este caso lo que haremos es agregar el archivo de `.gitignore` y darle commit.