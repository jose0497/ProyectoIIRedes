# FilesRepoJ&L📤📥
Nuestro proyecto FilesRepoJ&L está diseñado para usuarios que requieren almacenar archivos de manera remota con el fin de tenerlos en un lugar seguro y poder accesarlos cuando los necesitemos.
Este software permite almacenar cualquier tipo de archivo en el servidor. El cliente debe seleccionar el archivo a subir y el servidor se encargará de asignarle una carpeta para el debido almacenamiento.

# Pre-requisitos 📋
Para poder hacer  uso de este Software se debe tener algún IDE de desarrollo(preferiblemente NetBeans), tener acceso a internet pues en este proyecto el servidor maneja una conexión a una base de datos para almacenar la información de cada uno de los clientes, el proyecto está realizado en código Java por lo que se debe tener toda la configuración para poder correr la aplicación en el dispositivo, pude utilizar una máquina virtual con Java si cuenta cond distintos sistemas operativos y debe contar con almacenamiento suficiente para que el servidor aloje los archivos enviados por los clientes.

# Comenzando 🚀

1) En GitHub, visita la página principal del repositorio.
2) Debajo del nombre del repositorio, da clic en Clonar o descargar.
3) Abre la Git Bash.
4) Cambia el directorio de trabajo actual a la ubicación en donde quieres clonar el directorio.
5) Escribe git clone, y luego pega la URL que copiaste antes.
$ git clone https://github.com/SU-USUARIO/SU-REPOSITORIO.

6) Presiona Enter para crear tu clon local.

$ git clone https://github.com/SU-USUARIO/SU-REPOSITORIO.

    "Cloning into `Spoon-Knife`.

    remote: Counting objects: 10, done.

    remote: Compressing objects: 100% (8/8), done.

    remove: Total 10 (delta 1), reused 10 (delta 1).

    Unpacking objects: 100% (10/10), done."

# Paso a paso 🔧

Lo primero es que el cliente esté registrado en el servidor y así poder alojar los archivos, para ello se le asigna un nombre de usuario una contraseña y una ruta de archivo(única para cada usuario) en el servidor.

El cliente primeramente se  loguea para poder hacer la transferencia de los archivos, de otro modo no podrá realizarlo. Una vez que se loguea el usuario podrá ya sea enviar o recibir archivos del servidor.

Cuando se desea enviar un archivo, el cliente selecciona el archivo que desea enviar al servidor, y después pulsa el botón "Subir" para enviar  el archivo.

Si se desea ver los archivos que se encuentran en el servidor, el usuario selecciona la opción de ver archivos y esta los despliega automáticamente. Ahora el usuario puede elegir cualquier archivo y descargarlo. 


# Contruído con 🛠️

Para la elaboración de este proyecto utilizamos las herramientas:

### NetBeans IDE 8.2 
- Para la codificación del proyecto.
### MySQL 
- Para la creación de la base de datos que utiliza el servidor para alojar la información de los clientes.

# Autores ✒️

Miembros que hicieron posible tener listo este proyecto:

-José Hidalgo  - Codificación/Documentación.

-Luis Hidalgo - Codificación/Documentación.
