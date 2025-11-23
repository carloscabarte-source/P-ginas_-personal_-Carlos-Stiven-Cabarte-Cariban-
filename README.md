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

print("\nEscalera terminada.")
