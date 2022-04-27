## Configuracion

Es necesario configurar git en nuestros equipos donde estaremos desarrollando.

#### Nombre de Usuario

Configurar el nombre del usuario que se registrara en los cambios que agamos.

`
git config --global user.name "Sergio.Ochoa"
`

>`--global` Indica que la configuracion se aplicara de manera global en la computadora y no por proyecto.

#### Email

Configurar nuestro correo electronico

`
git config --global user.email sergio.ochoa@asd-tech.mx
`

#### Editor de texto default

Configurar el editor de texto por default

`
git config --global core.editor "code --wait"
`

> `--wait` es para que la terminal se quede esperando a que cerremos el editor de texto.

#### Ver configuracion global
Una vez realizada la configuracion global basica podemos comprobar el archivo de configuracion con el siguiente comando.

`
git config --global -e
`

> Este comando nos abrira el archivo de configuracion desde el editor de textos configurado en este caso vs code.

---
### Configuracion Extra 

#### Auto CRLF

Cuando se trabaja con equipos que desarrollan tanto en windows como en linux o mac, existen diferencias en cuanto a lo que se guarda al final de cada archivo.
* En window automaticamente se agregan los caracteres especiales **CR** y **LF** _(Carriage Retun y Line Feed)_
* En linux o Mac unicamente se agrega el caracter especial **LF**

##### Configuracion para usuarios de Windows

Los usuarios de windows deberan tener activo el Auto CRLF utilizando el siguiente comando.

`
git config --global core.autocrlf true
`

##### Confguracion para linux y mac

En el caso de los usuarios de linux o mac estos no necesitan agregar o quitar el CR por que por defecto solo agregar el caracter LF, pero para asegurar que si por error se insertara el CR este se elimine de manera automatica se debera configurar de la siguiente manera.

`
git config --global core.autocrlf input
`

#### Mas configuraciones

Para ver vas opciones de configuracion de git podemos revisar la documentacion con el comando

`
git config -h
`




