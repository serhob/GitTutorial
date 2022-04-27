## Flujo de trabajo general

#### PC desarrollo

El simple hecho de agregar, modificar o eliminar archivos esto no significa que afectará al repositorio. Para eso utilizaremos el comando `git add`

#### Stage

Cuando seleccionemos los archivos que queremos agregar al repositorio mediante el comando `git add` estos seran pasados a la etapa de Stage. El estar en la etapa de stage no significa que estos cambios se veran reflejados en nuestro repositorio esta es solamente una etapa intermedia para que nosotros podamos indicar cuales son los cambios que nosotros efectuamos para que estos pasen al repositorio mediante el comando `git commit`.

#### Commit

Cuando se pasan los archivos de stage a commit, estos dejan de estar en la etapa de stage. En este punto los cambios estan en nuestro repositorio pero no en el servidor o la nube.

#### Server

Para subir los cambios al servidor o la nuve donde se encuentra nuesto proyecto se hace mediante el comando

`git push`

