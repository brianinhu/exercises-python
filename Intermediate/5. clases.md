# 5. Clases

## 5.1. Subtemas aplicados

- Constructor
- Propiedades y métodos
- Decorador property
- Métodos mágicos
- Destructor 
- Comparación de objetos 
- Contenedores
- Herencia y herencia múltiple
- Anulación de método
- Clases abstractas
- Polimorfismo
- Duck typing
- Extensión de tipos nativos

## 5.2. Ejercicio

| Gestión de Personajes y Héroes |
| ------------ |
| Crear un juego de rol en el que los jugadores pueden crear personajes y héroes con diferentes atributos y habilidades. El objetivo es desarrollar un sistema de clases que permita crear y gestionar personajes y héroes. | 

### 5.2.1. Instrucciones

**1)** Crea una clase base llamada **Personaje** que tenga las siguientes propiedades:
- *nombre* (cadena): El nombre del personaje.
- *nivel* (entero): El nivel del personaje.
- *vida* (entero): La cantidad de puntos de vida del personaje.
- *energia* (entero): La cantidad de puntos de energía del personaje.

**2)** Implementa un constructor en la clase **Personaje** que acepte el nombre y el nivel del personaje como parámetros e inicialice las propiedades correspondientes. Establece valores predeterminados para *vida* y *energia*.

**3)** Crea métodos en la clase **Personaje** para mostrar la información del personaje (*nombre*, *nivel*, *vida* y *energía*).

**4)** Desarrolla una clase llamada **Heroe** que herede de la clase **Personaje**. Agrega las siguientes propiedades adicionales:
- *habilidades* (lista de cadenas): Una lista de habilidades que el héroe posee.
- *arma* (cadena): El arma equipada por el héroe.

**5)** Implementa un constructor en la clase **Heroe** que llame al constructor de la clase base (**Personaje**) y también acepte la lista de habilidades y el arma como parámetros.

**6)** Crea métodos en la clase **Heroe** para agregar nuevas habilidades, cambiar el arma y mostrar las habilidades y el arma del héroe.

**7)** Utiliza el decorador **@property** para crear propiedades calculadas en la clase **Heroe** que muestren la cantidad de habilidades del héroe y la longitud del nombre del arma.

**8)** Implementa el método mágico **______str______** en ambas clases (**Personaje** y **Heroe**) para que al imprimir un objeto se muestre su información de manera legible.

**9)** En la clase **Heroe**, agrega una lista llamada habilidades para almacenar las habilidades que el héroe posee. Deberás implementar métodos para agregar nuevas habilidades a esta lista, cambiar el arma y mostrar las habilidades y el arma del héroe. Además, asegúrate de que estas habilidades sean accesibles desde fuera de la clase **Heroe**.

**10)** Agrega un destructor en las clases **Personaje** y **Heroe** para que se ejecute cuando los objetos de estas clases sean destruidos. El destructor debe imprimir un mensaje que indique que el personaje o héroe ha sido destruido.

**11)** Permite la comparación de objetos en las clases **Personaje** y **Heroe** implementando los métodos especiales **______eq______** y **______lt______**. Por ejemplo, para poder comparar el nivel de los heroes. 

**12)** Crea una clase abstracta llamada **Entidad** que sirva como base para las clases **Personaje** y **Heroe**. Define métodos abstractos que todas las clases derivadas deben implementar, como ***atacar*** y ***recibir_danio***.

**13)** Implementa una clase llamada **Enemigo** que herede de Entidad y tenga propiedades como *nombre*, *vida* y *danio*. Implementa los métodos abstractos de manera que el enemigo pueda atacar y recibir daño.

**14)** Utiliza el concepto de herencia múltiple para crear una clase llamada **Jugador** que herede tanto de **Personaje** como de **Entidad**. Implementa métodos para que el jugador pueda atacar enemigos y recibir daño.

**15)** Aplica el concepto de polimorfismo al crear una función llamada ***combate*** que acepte dos objetos de tipo **Entidad** y simule un combate entre ellos.

**16)** Crea una clase llamada **ListaPersonajes** que herede de la clase **list**. Esta clase debe permitir agregar personajes y héroes a la lista. Luego, crea métodos que permitan organizar batallas, buscar personajes y héroes por su nombre y generar las estadísticas de cada uno.

## 5.3. Solución del ejercicio

    # Comming soon
