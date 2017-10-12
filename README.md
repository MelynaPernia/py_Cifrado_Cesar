# **PROYECTO CIFRADO CESAR**
EL presente proyecto elaborado por el Squad *POWERWOMEN* te permitira conocer el empleo del Codigo Cesar.


 El cifrado César es uno de los primeros métodos de cifrado conocidos históricamente. Julio César (Emperador romano)lo utilizo como estrategia de batalla.

EN QUE CONSISTE?

El cifrado César mueve cada letra un determinado número de espacios en el alfabeto. En este ejemplo se usa un desplazamiento de 33 espacios, así que una A en el texto original se convierte en una H en el texto codificado.

![Texto alternativo](http://1.bp.blogspot.com/-uzMxVVxV3uE/VSRopn20F5I/AAAAAAAAFZ8/TdfnHbQFhw0/s1600/caesar.png"Título de la imagen").


EJEMPLO:

var str = "ABC";

str = "HIJ"

Si queremos descifrar una determinada letra del alfabeto, tenemos que retroceder los 33 espacios.

var str = "HIJ";

str = "ABC"

# ** PSEUDOCODIGO**

1. **Objetivo**

Encriptar y descrifrar la frase que el usuario proporciona a través del algoritmo de Cifrado César.

2. **Contenido**

2.1 Creando 2 funciones cipher y decipher

2.2) Creamos una variable que por medio de un prompt te pida ingreses tu frase
var text = prompt("EMPEZEMOS, INGRESA TU FRASE");

2.3)  No acepta campos vacios ni numeros.
2.4)  Uso ciclo for

2.5) Condicional if (mayusculas, minusculas, espacios)

2.6) Uso de los metodos charCodeAt y String.fromCharCode

2.7) return cipher y decipher

# ** DIAGRAMA DE FLUJO **
En el siguiente link se muestra el diagrama de flujo del código césar.
!(http://subefotos.com/ver/?0af734d077d1463204932c336f9274eco.png"Diagrama").
