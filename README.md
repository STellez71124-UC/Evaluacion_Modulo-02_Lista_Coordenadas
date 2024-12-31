# Evaluacion_Modulo-02_Lista_Coordenadas

DESARROLLO DEL PROGRAMA:
Evaluación de conocimientos adquiridos y técnica en el manejo de código de Python para generar una captura de texto y números ingresados por el usuario, conformando una lista de palabras y coordenadas dentro de un plano cartesiano respectivamente.

Para crear este programa se tuvo en consideración la necesidad de detectar palabras de extensión diversa, reconociendo como aceptables para la ejecución del programa aquellas en el rango de cuatro a ocho caracteres y las demas palabras posibles como texto no compatible para dar respuesta a la solicitud del programa, lo que también aplica a números y espacio dejado en blanco.

Se prepara un input donde el usuario escribe un total de seis palabras de forma consecutiva, haciendo uso de un contador de palabras y bucle while contador < 6 para establecer el limite de este bloque de código. Cada palabra que cumple la condición de 4 a 8 letras es añadida a una lista e incrementa el valor númerico del contador por uno.

La lista resultante es impresa con bucle for y enumarate para presentar datos registrados conforme a su posición dentro del índice de la lista y el texto asignado a cada elemento en lista.

Una nueva lista modificable con elementos prestablecidos 'X:' y 'Y:' y contador de números son preparados para atender lo que es el plano cartesiano.
Un bucle while, sentencias try y except se utilizan para ingresar números enteros que constituyen las coordenadas de un punto en cuadrantes I a IV en virtud a su valor positivo, negativo en eje horizontal y vertical. La posibilidad de un valor erróneo en int(input) o el ingreso de cifra cero, ubicando el punto encima de alguno de los ejes, entrega mensaje de error al usuario y solicita el ingreso de nuevos datos validos para el programa.

Se hace uso de condiciones if, elif para ubicar las coordenadas proporcionadas por el usuario en el cuadrante correspondiente.

---------------------

OBSERVACIONES DURANTE DESARROLLO DEL PROGRAMA:
Se desarrolló en base a los aprendizajes obtenidos a lo largo del Módulo 02, retroalimentación aportada en el proyecto Calculadora IMC y la prueba constante de código, bucles, sentencias y condiciones, cumpliendo con los objetivos planteados y la ejecución idónea del programa con datos correctos, datos incorrectos y datos no ingresados.

---------------------

REFLEXIONES DEL BOOTCAMP UTEL - FUNDAMENTOS DE PYTHON C28 - MODULO 02: Siento un mayor grado de confianza al tener un mejor entendimiento de las instrucciones necesarias para construir un código digital en Python, además de como debe de ser definido, implementado y terminado un bucle para que éste cumpla la función deseada y no se ejecute infinitamente.

Pienso que el Bootcamp Python me ha servido para entender la lógica y secuencia de un entorno de programación en Python, así como la organización de bloques de código para diferenciar cada proceso a ejecutar, su esencia y los resultados o modificaciones generados a partir de la operación automática del programa y el ingreso de datos por el usuario.
