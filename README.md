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

##Tarea 2 Unidad 2 
# Reto 1: Tortuga avanzando con texto

pasos = int(input("¿Cuántos pasos quieres avanzar? "))

print("Tortuga avanzando →")
print("-" * pasos)   # Dibuja una línea horizontal

# Reto 2: Tortuga bajando con texto

pasos = int(input("¿Cuántos pasos hacia abajo avanza la tortuga? "))

print("Tortuga bajando ↓")
for i in range(pasos):
    print("|")   # Dibuja la caída vertical


# Reto 3: Movimiento en forma de L

adelante = int(input("¿Cuántos pasos hacia adelante? "))
abajo = int(input("¿Cuántos pasos hacia abajo? "))

print("Tortuga dibujando una L:")

# Parte horizontal
print("-" * adelante)

# Parte vertical
for i in range(abajo):
    print("|")


# Reto 4: Encapsular comportamiento en funciones

# Variable global para recordar en qué columna queda la tortuga
posicion = 0

def adelante(n):
    global posicion
    print("-" * n)
    posicion += n

def abajo(n):
    global posicion
    for i in range(n):
        print(" " * posicion + "|")  # Mantiene alineación vertical

# Ejemplo de prueba
adelante(5)
abajo(3)


# Reto 5: Tortuga bajando escalones

posicion = 0  # Posición horizontal actual

def adelante(n):
    global posicion
    print("-" * n)
    posicion += n

def abajo(n):
    global posicion
    for i in range(n):
        print(" " * posicion + "|")   # Mantener alineación vertical

# Ejemplo solicitado
# Escalón 1
adelante(5)
abajo(2)

# Escalón 2
adelante(5)
abajo(2)

# Escalón 3
adelante(5)
abajo(2)

-----  
          |
          |
----------  
                    |
                    |
---------------  
                              |
                              |

