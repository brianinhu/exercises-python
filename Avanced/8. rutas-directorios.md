# 8. Rutas y directorios

## 8.1. Subtemas aplicados

- Rutas
- Directorios
- Inyección de dependencias
- Importación dinámica de paquetes

## 8.2. Ejercicio

| Gestión de Archivos y Directorios |
| ------------ |
| Programar una aplicación de gestión de archivos y directorios. El objetivo es crear un programa que permita a los usuarios realizar diversas operaciones en archivos y directorios, aplicando conceptos de rutas y directorios. | 

### 8.2.1. Instrucciones

**1)** Crea una función llamada ***listar_directorio*** que acepte una ruta de directorio como argumento y muestre una lista de los archivos y subdirectorios en ese directorio.

**2)** Implementa una función llamada ***crear_directorio*** que permita al usuario ingresar el nombre de un nuevo directorio y lo cree en la ubicación actual.

**3)** Crea una función llamada ***renombrar_archivo*** que permita al usuario ingresar el nombre de un archivo o directorio existente y su nuevo nombre, y luego renombre el archivo o directorio.

**4)** Define las funciones ***eliminar_archivo***, ***copiar_archivo*** y ***mover_archivo*** que permita al usuario eliminar, copiar y mover un archivo o directorio específico.

**5)** Utiliza inyección de dependencias para permitir que las funciones definidas en los pasos 1 al 4 reciban como argumento una instancia de un objeto que maneje las operaciones de sistema de archivos. Este objeto debe tener métodos para listar directorios, crear directorios, renombrar archivos, eliminar archivos, copiar archivos y mover archivos.

**6)** Implementa dos clases diferentes que actúen como implementaciones de sistema de archivos: **SistemaArchivosLocal** y **SistemaArchivosRemoto**. Ambas clases deben implementar los métodos necesarios para realizar operaciones en el sistema de archivos local y remoto, respectivamente.

**7)** En el programa principal, permite al usuario seleccionar si desea trabajar con el sistema de archivos local o remoto utilizando un argumento de línea de comandos o una entrada de usuario. Luego, crea una instancia del objeto adecuado según la elección del usuario y utiliza esa instancia para realizar operaciones de archivo y directorio.

**8)** Utiliza la importación dinámica de paquetes para cargar dinámicamente el módulo correspondiente (local o remoto) según la elección del usuario en el paso 9.

## 8.3. Solución del ejercicio

    # Comming soon
