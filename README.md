# P-ginas_-personal_-Carlos-Stiven-Cabarte-Cariban-

https://photos.app.goo.gl/oMxbYqoeHXm5rrbVA
## Carlos Stiven Cabarte Cariban

Soy un joven profesional en formación, con **22 años de edad**, originario del municipio de **Barranco Minas**, en el departamento del **Guainía (Colombia)**.  
Actualmente curso la carrera de **Tecnología en Desarrollo de Software** en la **Institución Universitaria Digital de Antioquia (IU Digital)**.

Mi principal objetivo es fortalecer mis conocimientos en el área del desarrollo tecnológico, enfocado en la creación de **soluciones digitales innovadoras** que aporten al crecimiento educativo y social de mi región.  
Me caracterizo por ser **responsable**, **comprometido** y con una gran disposición para el **aprendizaje continuo** y el **trabajo en equipo**.

---

## Objetivos Profesionales

- Desarrollar competencias técnicas en **programación**, **análisis** y **gestión de proyectos tecnológicos**.  
- Contribuir con **soluciones digitales** que beneficien a comunidades educativas y sociales.  
- Formarme como un profesional íntegro, capaz de **liderar procesos tecnológicos y educativos**.  

---

##  Intereses y Habilidades

- **Programación y desarrollo de software**.  
- **Metodologías ágiles** y **gestión de proyectos**.  
- **Innovación tecnológica aplicada a la educación**.  
- **Trabajo colaborativo** y **aprendizaje constante**.  

---

## Contacto

- **Correo electrónico:** cabartecaribancarlosstiven82@gmail.com  
- **Ubicación:** Barranco Minas, Guainía – Colombia  



## Aprendizaje del curso de pensamiento algoritmo ##
Lo que aprendí sobre programación, software y hardware

Yo aprendí en la clase que la programación es una parte fundamental de la tecnología, porque gracias a ella las computadoras pueden realizar muchas tareas. Entendí que programar significa darle instrucciones a la máquina para que haga exactamente lo que necesitamos, usando diferentes lenguajes como Python, Java o C++.

También aprendí que todo programa necesita del software y del hardware para funcionar correctamente. El software son todos los programas, aplicaciones y sistemas que usamos a diario, mientras que el hardware es la parte física de la computadora, como el teclado, el monitor, el procesador o el disco duro.

Comprendí que el software y el hardware trabajan juntos: el hardware ejecuta las órdenes y el software las controla. Sin uno, el otro no podría funcionar.
En conclusión, esta clase me ayudó a entender mejor cómo se relacionan estos componentes y cómo la programación es la herramienta que une el software con el hardware para crear soluciones tecnológicas útiles en nuestra vida diaria.









##Tarea 2 unidad 2 ##

# Reto 1: Simulación de una tortuga moviéndose hacia la derecha

print("Bienvenido al simulador de tortuga horizontal")
print("Aquí la tortuga avanzará hacia la derecha usando solo texto.\n")

# El usuario ingresa cuántos pasos quiere que la tortuga avance
pasos = int(input("¿Cuántos pasos quieres que avance la tortuga? "))

print("\nCreando una tortuga simulada... que da", pasos, "pasos.")

# Para simular el movimiento horizontal, repetimos el símbolo "-" muchas veces
# Cada "-" representa un paso hacia la derecha
linea = "-" * pasos

# Se imprime la línea y una flecha para indicar la dirección
print(linea + ">")

print("\nMovimiento completado.")


# Reto 2: Tortuga bajando verticalmente

print("Simulador de tortuga bajando\n")

# Pedimos al usuario cuántos pasos quiere bajar
pasos = int(input("¿Cuántos pasos debe bajar la tortuga? "))

print("\nTortuga bajando...\n")

# Cada línea tendrá un símbolo que representa la bajada
for i in range(pasos):
    print("↓")   # Se imprime hacia abajo, una línea a la vez

print("\nLa tortuga ha terminado de bajar.")

# Reto 3: Dibujar una L usando texto

print("Simulación gráfica de una L con una tortuga virtual\n")

# Primera parte: movimiento horizontal
pasos_h = int(input("¿Cuántos pasos hacia adelante (derecha) debe dar la tortuga? "))

# Segunda parte: movimiento vertical hacia abajo
pasos_v = int(input("¿Cuántos pasos debe bajar la tortuga después de girar? "))

print("\nDibujando forma de L...\n")

# Dibujar la parte horizontal
print("-" * pasos_h + ">")     # la flecha indica el final

# Dibujar la parte vertical
for i in range(pasos_v):
    print(" " * pasos_h + "↓")   # Se alinea con el final de la línea horizontal

print("\nDibujo completado.")

# Reto 4: Crear funciones que simulen movimientos de una tortuga

print("Simulador con funciones: adelante() y abajo()\n")

# Posición horizontal acumulada
posicion = 0

def adelante(n):
    """
    Dibuja una línea horizontal usando '-' y una flecha '>'
    n = número de pasos hacia la derecha.
    """
    global posicion
    print("-" * n + ">")
    posicion += n  # Guardamos cuántos pasos llevamos para alinear la bajada

def abajo(n):
    """
    Dibuja una línea vertical hacia abajo usando '↓'.
    Mantiene la posición horizontal actual.
    """
    global posicion
    for i in range(n):
        print(" " * posicion + "↓")

# Prueba del ejercicio
print("Dibujando una L usando funciones...\n")
adelante(6)
abajo(4)

# Reto 5: Dibujar una escalera usando los movimientos de la tortuga

print("Simulador de ESCALERAS con tortuga virtual\n")

# posición actual de la tortuga (horizontal)
posicion = 0

def adelante(n):
    """
    Mueve la tortuga hacia la derecha n pasos.
    Aumenta la posición acumulada.
    """
    global posicion
    print("-" * n + ">")
    posicion += n

def abajo(n):
    """
    Mueve la tortuga hacia abajo manteniendo
    la posición horizontal actual.
    """
    global posicion
    for i in range(n):
        print(" " * posicion + "↓")

# DIBUJAR 3 ESCALONES
print("\nDibujando escalones...\n")

# Escalón 1
adelante(5)
abajo(2)

# Escalón 2
adelante(5)
abajo(2)

# Escalón 3
adelante(5)
abajo(2)

print("\nEscalera terminada.







##Actividad 03##

##Mini Turtle – Ejercicio 1 (Versión Funcional)

Descripción

Este ejercicio tiene como finalidad aplicar el principio de modularidad en Python, organizando funciones simples dentro de un paquete llamado mini_turtle. Se busca separar claramente la lógica del programa de la interfaz pública, logrando un código más ordenado y fácil de mantener.


---

Objetivo del ejercicio

Organizar funciones en un paquete Python.

Separar la lógica interna de la interfaz del usuario.

Implementar una función adicional llamada reiniciar().

Permitir la importación directa de funciones desde el paquete.



---

Estructura del proyecto

mini_turtle_task/
│
├── mini_turtle/
│   ├── __init__.py
│   └── drawer_logic.py
│
├── main.py
├── README.md
└── pyproject.toml


---

Desarrollo del ejercicio

1. Archivo drawer_logic.py

En este archivo se define toda la lógica del programa. Se utiliza una variable global llamada posicion_x, que representa la posición horizontal de la tortuga.

Funciones implementadas:

adelante(pasos): incrementa la posición de la tortuga según los pasos indicados.

abajo(pasos): simula el movimiento hacia abajo mediante un mensaje.

reiniciar(): restablece la posición de la tortuga a 0 utilizando la palabra clave global.


Este módulo no es utilizado directamente por el usuario final.


---

2. Archivo init.py

El archivo __init__.py funciona como la interfaz pública del paquete. Desde aquí se importan las funciones definidas en drawer_logic.py y se exponen al usuario.

Gracias a este archivo, el usuario puede utilizar el paquete de la siguiente forma:

from mini_turtle import adelante, abajo, reiniciar

Además, se define la variable __all__ para indicar qué funciones son públicas.


---

3. Archivo main.py

El archivo main.py actúa como un script de prueba. En él se importan las funciones desde el paquete mini_turtle y se utilizan para simular el movimiento de la tortuga, comprobar el funcionamiento de reiniciar() y validar la correcta separación entre lógica e interfaz.


---

Conclusión

Con este ejercicio se demuestra la correcta aplicación de la modularidad en Python, la organización de un paquete, la separación entre lógica e interfaz y el uso controlado de variables globales. Esta solución funcional sirve como base para una futura implementación utilizando Programación Orientada a Objetos.






##Ejercicio 2: Versión Orientada a Objetos (POO)##

Objetivo

El objetivo de este ejercicio es refactorizar el paquete anterior aplicando el paradigma de Programación Orientada a Objetos (POO), utilizando clases y objetos, eliminando el uso de variables globales y aplicando correctamente el encapsulamiento.


---

Descripción General

En esta versión se implementa una clase llamada Tortuga, la cual contiene toda la lógica del programa. Cada objeto creado a partir de esta clase mantiene su propio estado de manera independiente, permitiendo crear múltiples tortugas sin que interfieran entre sí.

# turtle_class.py

class Tortuga:
    """
    Clase que representa una tortuga con su propia posición.
    """

    def __init__(self):
        # Atributo de instancia (NO global)
        self.posicion_x = 0

    def adelante(self, pasos):
        """
        Mueve la tortuga hacia adelante.
        """
        self.posicion_x += pasos
        print(f"Tortuga avanzó {pasos} pasos. Posición actual: {self.posicion_x}")

    def abajo(self, pasos):
        """
        Simula un movimiento hacia abajo.
        """
        print(f"Tortuga bajó {pasos} pasos.")

    def reiniciar(self):
        """
        Reinicia la posición de la tortuga.
        """
        self.posicion_x = 0
        print("Posición reiniciada a 0")

from mini_turtle_oo import Tortuga

# Creamos dos objetos distintos
t1 = Tortuga()
t2 = Tortuga()

# Movemos la primera tortuga
t1.adelante(10)
t1.abajo(2)

# Movemos la segunda tortuga
t2.adelante(3)
t2.adelante(4)

# Mostramos que no interfieren
print("Reiniciando la primera tortuga")
t1.reiniciar()

print("La segunda tortuga sigue igual")
t2.adelante(1)


---

Requerimientos Funcionales

Toda la lógica se encuentra dentro de una clase Tortuga.

El estado de la tortuga se maneja mediante un atributo de instancia llamado self.posicion_x.

El atributo posicion_x se inicializa en 0 dentro del constructor __init__.

No se utilizan variables globales.

Se permite crear múltiples objetos Tortuga, cada uno con su propia posición independiente.

El usuario importa la clase desde el paquete utilizando:

from mini_turtle_oo import Tortuga



---

Estructura de Archivos

mini_turtle_oo_task/
│
├── mini_turtle_oo/
│   ├── __init__.py        # Exporta la clase Tortuga
│   └── turtle_class.py   # Define la clase Tortuga
│
├── main.py                # Script de prueba con objetos
├── pyproject.toml         # Configuración (opcional)
└── README.md              # Documentación


---

Implementación

1. Clase Tortuga (turtle_class.py)

Se define la clase Tortuga, donde:

El constructor __init__ inicializa la posición en 0.

Los métodos permiten mover la tortuga hacia adelante y mostrar su posición actual.

Todo el comportamiento depende del objeto (self).


Ejemplo conceptual:

Cada tortuga tiene su propio self.posicion_x.

Al mover una tortuga, solo cambia su propio estado.



---

2. Interfaz del Paquete (__init__.py)

El archivo __init__.py expone la clase Tortuga para que pueda ser importada fácilmente desde el paquete:

from .turtle_class import Tortuga

Esto permite al usuario trabajar con la clase sin acceder directamente al archivo interno.


---

3. Prueba del Programa (main.py)

En el archivo main.py se crean dos objetos Tortuga distintos:

Se instancia la primera tortuga (t1) y se mueve una distancia.

Se instancia la segunda tortuga (t2) y se mueve una distancia diferente.

Se demuestra que cada objeto mantiene su posición de forma independiente.


Esto confirma el correcto uso de POO, encapsulamiento e independencia de objetos.


---

Resultados Esperados

Cada tortuga conserva su propia posición.

No existe interferencia entre objetos.

El código es más organizado, reutilizable y fácil de mantener.

Se cumple completamente con el enfoque de Programación Orientada a Objetos.



---

Conclusión

Este ejercicio demuestra cómo transformar un programa procedural en uno orientado a objetos, aplicando conceptos fundamentales como clases, objetos, encapsulamiento e independencia de estado, logrando un diseño más limpio y escalable.

