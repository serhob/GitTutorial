## Ver cambios

Para ver los cambios que tenemos con respecto a un archivo que modificamos del repositorio lo podemos hacer mediante el comando:

`
git diff
`

De esta manera nos mostrara de una forma "gráfica" los cambios que estaríamos comprometiendo, y lo pone de una forma visual con colores y símbolos, si hay una linea que se elimino esta la pondrá en rojo y con el símbolo de **-** a la derecha para indicar que ese eliminó esa linea, y si por el contrario se agrega una linea esta aparece en verde con el símbolo **+** a la derecha.

> Para salir del visor de cambios presionamos la tecla `q`

Si nosotros quisiéramos ver los cambios que están en la etapa de stage lo podemos hacer con el comando:

`
git diff --staged
`
