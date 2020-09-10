# Python - manejo de archivos

Para clonar este repositorio en su computadora:

1. Bifurque (*fork*) a su cuenta en GitHub el repositorio ubicado en [https://github.com/tpb708-programacionsig-2020/leccion-07-python-archivos](https://github.com/tpb708-programacionsig-2020/leccion-07-python-archivos).
2. Ejecute los siguientes comandos desde la terminal del sistema operativo o desde alguna interfaz que incluya las herramientas de Git, como la línea de comandos (*prompt*) de Anaconda:

```shell
# 0. Posiciónese en el directorio en el que va a residir el repositorio clonado.
# Por ejemplo, en el directorio del usuario.
$ cd C:\Users\mfvargas

# 1. Especifique el nombre y de la dirección de correo de su usuario en GitHub.
# Debe modificar la dirección de correo y el nombre del usuario con sus propios datos.
$ git config --global user.email "usuario@correo.com"
$ git config --global user.name "Nombre de usuario"
# Para revisar:
$ git config --global --list

# 2. Clonación del repositorio remoto a la estación de trabajo local.
# Debe sustituir "usuario" por su nombre de usuario en GitHub.
$ git clone https://github.com/usuario/leccion-07-python-archivos.git

# 3. Cambio al directorio del repositorio recién clonado.
$ cd leccion-07-python-archivos

# 4. En este punto, realice algunas modificaciones en el archivo README.md del repositorio recién clonado (ej. agregue una nueva línea).

# 5. Revisión de los archivos con modificaciones.
$ git status

# 6. Adición de los archivos modificados al "área de espera".
# El punto (.) indica que se agregarán todos los archivos modificados.
$ git add .

# 7. Almacenamiento (commit) del conjunto de archivos modificados, junto con un mensaje explicativo.
$ git commit -m "Agregar contenido"

# 8. "Subida" (push) de las modificaciones al repositorio remoto.
$ git push
```

- [Manejo de archivos]()
