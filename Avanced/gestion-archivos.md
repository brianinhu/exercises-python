# 9. Gestión de archivos

## 9.1. Subtemas aplicados

- Lectura y escritura
- Open
- Archivos csv
- Archivos json
- Archivos comprimidos

## 9.2. Ejercicio

| Análisis de datos de ventas |
| ------------ |
| Imagine que trabaja en una empresa de ventas y tiene un conjunto de datos de ventas en formato CSV. Debes desarrollar un programa que permita a los usuarios realizar diversas operaciones de análisis de datos en estos archivos, aplicando conceptos de lectura y escritura, el uso de la función open, procesamiento de archivos CSV, manipulación de archivos JSON y archivos comprimidos. |

### 9.2.1. Instrucciones

**1)** Crea un archivo CSV llamado **ventas.csv** que contenga datos de ventas con las siguientes columnas: *Fecha*, *Producto*, *Cantidad*, *PrecioUnitario*. Llena el archivo con datos de ventas ficticios.

**2)** Implementa una función llamada ***leer_csv*** que acepte la ruta de un archivo CSV como argumento y lea los datos del archivo CSV en una estructura de lista de diccionarios. Cada diccionario debe representar una fila de datos con las columnas como claves y los valores como valores.

**3)** Desarrolla una función llamada ***calcular_total_ventas*** que tome los datos leídos del archivo CSV y calcule el total de ventas (*Cantidad* * *PrecioUnitario*) para cada fila. Agrega esta información al diccionario de cada fila.

**4)** Crea una función llamada ***escribir_json*** que acepte los datos procesados y escriba los datos en un archivo JSON llamado **ventas.json**. Cada fila de datos debe representarse como un objeto JSON en una lista.

**5)** Implementa una función llamada ***leer_json*** que lea los datos del archivo **ventas.json** y los cargue en una lista de objetos JSON.

**6)** Desarrolla una función llamada ***comprimir_archivo*** que acepte un archivo (por ejemplo, **ventas.json**) y lo comprima en un archivo ZIP llamado **ventas.zip**.

**7)** Crea una función llamada ***descomprimir_archivo*** que acepte un archivo ZIP (por ejemplo, **ventas.zip**) y extraiga su contenido en un directorio específico.

**8)** En el programa principal, utiliza las funciones anteriores para realizar las siguientes operaciones:
- Leer los datos del archivo CSV **ventas.csv**.
- Calcular el total de ventas para cada fila y agregar esta información.
- Escribir los datos procesados en un archivo JSON **ventas.json**.
- Comprimir el archivo JSON en un archivo ZIP **ventas.zip**.
- Descomprimir el archivo ZIP en un directorio específico.

**9)** Muestra los resultados de cada operación al usuario y proporciona información sobre los archivos creados o modificados.

## 9.3. Solución del ejercicio

    # Comming soon
