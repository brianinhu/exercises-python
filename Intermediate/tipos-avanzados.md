# 4. Tipos avanzados

## 4.1. Subtemas aplicados

- Listas
- Manipulación de listas
- Desempaquetamiento de listas
- Iteración de listas
- Agregación, eliminación y búsqueda de elementos
- Ordenación de listas
- Expresiones lambda
- Listas de comprensión
- map y filter
- Tuplas
- Sets
- Diccionarios
- Operador de desempaquetamiento

## 4.2. Ejercicio

| Administración de una biblioteca |
| ------------ |
| Desarrollar un sistema de gestión de bibliotecas donde creará una lista denominada "biblioteca", la cual contendrá información exhaustiva sobre los libros disponibles en dicha biblioteca. | 

### 4.2.1. Instrucciones

**1)** Definir una lista llamada **biblioteca** que contendrá información sobre los libros disponibles en la biblioteca. Cada elemento de la lista será un diccionario que represente un libro con los siguientes campos: *id*, *titulo*, *autor*, *genero*, *stock*.

**2)** Crear una función ***prestar_libro*** que tome el id de un libro y la cantidad que se prestará como argumentos y actualice la cantidad disponible (stock) en el inventario.

**3)** Crear una función ***mostrar_catalogo*** que itere sobre la lista **biblioteca** e imprima los detalles de cada libro de forma legible y ordenada.

**4)** Implementar funciones para agregar, buscar editar y eliminar libros del inventario. Por ejemplo, la función ***buscar_libro*** tomará el id de un libro y devolverá sus detalles si está en la biblioteca.

**5)** Crear una función ***ordenar_catalogo*** que ordene la lista **biblioteca** en función del *título*, *autor*, *género* o *stock* disponible.

**6)** Crear una funcion ***buscar_por_genero*** para encontrar libros de un género específico y la función ***libros_stock_minimo*** para encontrar libros con un stock superior a *n* unidades.

**7)** Extraer en una lista el stock disponible de cada libro e implementar una función que permita agregar 20 unidades más si el stock del libro es menor a 10. Además, implementar otra función que permita filtrar libros por autor o género.

**8)** Introducir datos adicionales como tuplas y sets en los diccionarios de libros para representar información adicional, como la fecha de publicación o las etiquetas.

**9)** Implementa una función que desempaquete los libros en bucle y muestre sus datos de forma ordenada.

### 4.2.2. Requisitos

-   [ ] Utiliza expresiones lambda para personalizar la ordenación en la función ***ordenar_catalogo***.
-   [ ] Utilizar listas de comprension para las funciones ***buscar_por_genero*** y ***libros_stock_minimo***.
-   [ ] En la instrucción 7, utilizar las funciones **map** (con **lambda**) y **filter**.
-   [ ] En la instrucción 9, utilizar el método **items()** para el correcto desempaquetamiento.

## 4.3. Solución del ejercicio

    # Comming soon
