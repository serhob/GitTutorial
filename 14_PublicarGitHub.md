## Publicar a GitHub

Para publicar a la nube de GitHub lo primero que hay que hacer es entrar a https://github.com y crearnos una cuenta.

#### Nuevo repositorio en GitHub

Una vez que creamos la cuenta y nos logeamos en github lo siguiente que seguiria es crear el nuevo repositorio, para esto de lado derecho de la pantalla prncipal donde aparecen los repositorios se encuentra el boton de **new** el cual nos abrira la pantalla para crear el nuevo repositorio.

Aqui lo que nos pide es el nombre del repositorio, una descripcion, si queremos que sea Publico o Privado, Opcion de crear un README para que de una descripcion de lo que se trata nuestro proyecto y el tipo de licencia que queremos para el proyecto.

Una vez terminado de llenar los datos del repositorio le damos al boton de **create repository**. Luego nos dirigira a una pantalla con varios comandos que podemos usar para iniciar en nuestro equipo con el repositorio.

La linea que nos interesa es:

`
git remote add origin https://github.com/usuario/Practica1.git
`

> **`git remote`** nos sirve para que podamos indicar si vamos a tener un servidor remoto en el cual nosotro podemos subir nuestros cambios.
> En este caso cuando le decimos **`add origin`** es que le estamos indicando de donde tenemos que ir a obtener nuestro codigo y tambien a donde tenemos que subir nuestros cambios que realicemos.

### Git Push

Lo siguiente que tenemos que hacer es subir los cambios al repositorio mediante el comando Push

`
git push -u origin master
`

> **`git push`** nos permite subir nuestros cambios realizados en la rama en que estemos trabajando en este caso master.

> La opcion **`-u`** sirve para crear la rama en el servidor ya que esta aun no existe alli.

> la opcion de **`origin`** es para indicar donde queremos que sera creada la rama y **`master`** es el nombre de la rama en el repositorio.

Al darle enter nos pedira el nombre de usuario del github y una contraseña sin embargo esta contraseña no es la de nuestra cuenta de github para esto tenemos que hacer una key.

### Crear una key en GitHub

Desde el boton donde esta el usuario desplegar el menu y seleccionar **Settings**, luego en el menu de **Developer Settings** y dentro de la opciones en **Personal access tokens** dentro es esa pantalla daremos click al boton que dice **Generate new token**.

En esta pantalla nos pide el nombre el token, el tiempo que estara activo el token y los permiso que tiene ese token en el repositorio (Le damos en repo para que tenga todas las opciones del repositorio solo para esta practica). Le damos generar y nos muestra el token que se generó el cual utilizaremos en el `push`

Cada vez que queramos subir de nuevo al repositorio solo hay que ejecutar el comando:

`git push`

