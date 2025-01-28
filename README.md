# Ahorcado_game
#### Descripción
Construir una aplicación que emule un ahorcado utilizando Python.

Condiciones:

-Código original
-Uso de herramientas vistas en el curso
-Interacción y manejo a través de la consola
-Base de datos de al menos 1000 palabras
-Dibujo de hangman en integraz gráfica
-Definidido por el usuario:
-Ingreso de las letras
-Nivel de dificultad: Asociado a la cantidad de intentos para dibujar el ahorcado, cantidad de caracteres de la palabra.
-Foco: Función core del juego, a partir de las letras validar existencia en la palabra e ir actualziando interfaz.

Features extra:

Cuenta regresiva
Manejo de puntajes
Soporte para otros idiomas (inglés, francés, aleman)
Manejo de jugadores (2 juegos simultaneos)

#### Puntos importantes
-Se debe elaborar un repo donde presente la solución al problema planteado. El repo debe contener la explicación de la solución, cómo se abordo el problema, diagramas. Y una sección de como instalar y usar el desarrollo.
-El repo debe tener como colaboradores a todos los miembros del equipo, de forma que se evidencie que trabajaron de forma colectiva.
-Los códigos elaborados deben estar apropiadamente comentados.
-Todos los programas deben incorporar el uso de funciones
-El repo debe estar muy bien hecho, ya que esa es la manera de presentar.
#### Valor del avance
Avance (10%)
Definición de alternativa - Diagramas preliminares - Solución preliminar -> Exposición oral, 10 minutos.
Criterios evaluación avance: claridad de la exposición (20%), calidad de entregables (40%), temas del curso adecuadamente empleados (40%).
#### Paginas
- Pseudocodigo:
https://openwebinars.net/blog/como-programar-el-juego-del-ahorcado-paso-paso/
- Dibujos:
https://www.aplitop.com/products/tcpMDT/v8/help/es/referencia/dibujar_a_partir_de_codigos.htm
- Base de datos:
https://es.py4e.com/html3/15-database

---

En este repositorio abarcaremos la alternativa número 2: El ahorcado. 

1. Solución planteada:
Para realizar el ahorcado hemos decidido usar diversas funciones relacionadas a la selección de palabras, las cuales estarán almacenadas en una lista y se escogerá cualquiera de ellas para iniciar el juego. De igual manera una con la que, dependiendo de la posición de cada letra de la palabra y la letra que se ingrese por consola, se hará un acierto y se podrá continuar con la siguiente letra, actualizando la palabra escogida; o se empezara a dibujar el ahorcado por medio de prints, reduciendo el número de oportunidades y actualizando el dibujo del ahorcado en cada intento erróneo hasta que el dibujo se complete.

2. Como abordamos el problema:


3. Diagrama:

4. Notebook de python
