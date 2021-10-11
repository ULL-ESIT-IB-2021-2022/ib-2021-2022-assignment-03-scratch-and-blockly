# Práctica 03. Algoritmos, Sentencias y Programas. Scratch y Blockly

### Objetivos

Los objetivos de esta práctica son que el alumnado:

* Conozca los conceptos de Algoritmo y Programa.
* Conozca formas básicas de describir algoritmos sencillos.
* Conozca los entornos de programación de [Scratch](https://scratch.mit.edu/) y [Blockly](https://developers.google.com/blockly).
* Sea capaz de desarrollar programas simples en [Scratch](https://scratch.mit.edu/) y [Blockly](https://developers.google.com/blockly).

### Rúbrica de evaluacion de esta práctica

Se señalan a continuación los aspectos más relevantes (la lista no es exhaustiva) que se tendrán en cuenta a la hora de evaluar esta práctica:
* El alumnado ha de acreditar que es capaz de realizar programas simples en [Scratch](https://scratch.mit.edu/) similares a los que se proponen en este documento.
* El alumnado ha de acreditar conocer los conceptos expuestos en el material de referencia de esta práctica.

### Introducción

De manera simple se puede decir que un algoritmo es una secuencia ordenada de pasos que persiguen la consecución de un fin, de un objetivo claro y especifico. En la vida cotidiana se emplean algoritmos en multitud de situaciones para resolver diversos problemas como por ejemplo para hacer la colada con una lavadora (instrucciones pegadas en la tapa de la máquina), para tocar música (partituras), para construir un avión a escala (expresados en las instrucciones), para hacer trucos de magia (pasos para hacer el truco) o, incluso para elaborar un plato de comida (pasos de la receta). Estos algoritmos se conocen como algoritmos cualitativos, ya que su resultado es un hecho u objeto. Hay otros ejemplos, conocidos como algoritmos cuantitativos, que se refieren a algoritmos que resuelven problemas cuyo resultado es numérico, por ejemplo el algoritmo de la división para calcular el cociente de dos números o el [algoritmo de Euclides](https://es.wikipedia.org/wiki/Algoritmo_de_Euclides) para calcular el máximo común divisor de dos enteros positivos.

El interés en esta asignatura por los algoritmos radica en que se pretende introducir al alumnado en la programación de ordenadores. En este contexto, las máquinas algorítmicas son aquellas capaces de ejecutar algoritmos (realizar cada uno de sus pasos) y una de este tipo de máquinas son los ordenadores. Cuando se trabaja con ordenadores, los algoritmos se expresan como programas. Los programas son algoritmos escritos en un lenguaje no ambiguo cuya sintaxis y semántica "entiende" el ordenador. Hay muchos lenguajes de programación, entre ellos [C](https://en.wikipedia.org/wiki/C_(programming_language)), [Java](https://en.wikipedia.org/wiki/Java_(programming_language)), [Python](https://en.wikipedia.org/wiki/Python_(programming_language)) o [JavaScript](https://en.wikipedia.org/wiki/JavaScript).  Así pues, si se quiere que un ordenador ejecute una tarea, primero se ha de idear un algoritmo para llevarla a cabo; programar el algoritmo, es decir representar ese algoritmo de modo que se pueda comunicar al ordenador. Se debe transformar el algoritmo conceptual en un conjunto de instrucciones o sentencias y representar éstas en un lenguaje sin ambigüedad. En esta asignatura se utilizará el lenguaje [C++](https://en.wikipedia.org/wiki/C%2B%2B), pero antes de programar en C++ se pretende con esta práctica que el alumnado realice sus primeros programas en un lenguaje más simple, en el que la programación se realiza de forma visual combinando diferentes tipos de bloques.

### Trabajo previo

1. Vea el vídeo [Problemas, Algoritmos y
Programas](https://media.upv.es/#/portal/video/a8d70173-71c5-884e-8308-f72541d8d7c8)

2. Visualice también [este otro](http://www.upv.es/visor/media/26c336b0-19d1-2648-be94-f0d72d9af755/c) que
introduce los conceptos de Algoritmo y Programa.

3. Estudie detenidamente el contenido de las 3 páginas [“Designing an algorithm”](https://www.bbc.co.uk/bitesize/guides/z3bq7ty/revision/1)
y estudie en ellas los conceptos de Algoritmo, Pseudocódigo, Datos de Entrada, Datos de Salida, Instrucciones y Diagramas de Flujo.

4. Para la realización de los ejercicios que aquí se proponen se utilizarán un par de lenguajes de programación visual: [Blockly](https://developers.google.com/blockly) y [Scratch](https://scratch.mit.edu/). En ambos casos los algoritmos se codifican utilizando “bloques” que representan los diferentes tipos de instrucciones disponibles en cualquier lenguaje de programación: asignaciones, instrucciones de repetición, instrucciones condicionales, funciones,... En los lenguajes de programación a estas instrucciones se les denomina sentencias (*statements*).

    En [Blockly](https://developers.google.com/blockly), una vez programado un algoritmo en el lenguaje de bloques de [Blockly](https://developers.google.com/blockly), es posible obtener el programa correspondiente a dicho algoritmo en otros lenguajes de programación: Python, JavaScript, Lua,... La sintaxis de JavaScript es muy similar a la de C++, el lenguaje que se utilizará en esta asignatura. Un primer programa en [Blockly](https://developers.google.com/blockly) que imprima los cuadrados de los `N` primeros números naturales podría ser el que se muestra en [esta figura](https://github.com/ULL-ESIT-IB-2021-2022/ib-2021-2022-scratch-and-blockly/blob/main/blockly1.png).

    Escriba este programa en [Blockly](https://developers.google.com/blockly) y ejecútelo. Vea cómo el programa es “traducido” a diferentes lenguajes (panel de la derecha). Realice diferentes cambios en el programa para familiarizarse con el entorno de programación de [Blockly](https://developers.google.com/blockly).

5. En el caso de [Blockly](https://developers.google.com/blockly) los programas que realice no se pueden guardar, mientras que en [Scratch](https://scratch.mit.edu/) sí es posible hacerlo. Comience por [crear una cuenta en Scratch](https://scratch.mit.edu/join) para poder almacenar sus proyectos. En cuanto tenga su cuenta, desarrolle en [Scratch](https://scratch.mit.edu/) un programa que imprima en pantalla el doble de los `N` primeros números naturales. [Esta podría ser una solución](https://scratch.mit.edu/projects/406186813/editor/) al problema propuesto. Igual que en el caso anterior, realice cambios en el programa para que aprenda los fundamentos de [Scratch](https://scratch.mit.edu/).

6. Estudie [este documento](https://www.futurelearn.com/courses/block-to-text-based-programming/0/steps/39492). En él se insiste en la idea de pseudocódigo y se muestra la solución al famoso problema [FizzBuzz](https://en.wikipedia.org/wiki/Fizz_buzz) tanto en [Scratch](https://scratch.mit.edu/) como en pseudocódigo.

### Ejercicios 

7. Estudie [este otro documento](http://www.agropolis.org/miss-abms/initiationto-algorithmics-with-scratch.pdf) y estudie con detenimiento las explicaciones que se aportan sobre los siguientes conceptos:
  * Secuencia de sentencias
  * Introducción a las variables
  * Sentencias Condicionales
  * Sentencias de bucle (repetición)
  * Manipulación de conjuntos de valores
  * Procedimientos y Funciones 
  * Introducción a la programación orientada a objetos

    Desarrolle en [Scratch](https://scratch.mit.edu/) todos los ejercicios que se proponen en [el documento](http://www.agropolis.org/miss-abms/initiationto-algorithmics-with-scratch.pdf) a partir de la página 7.

    Desarrolle en [Scratch](https://scratch.mit.edu/), y guarde cada programa en su cuenta de [Scratch](https://scratch.mit.edu/) para mostrarla al profesorado durante la sesión de evaluación de esta práctica, los programas que se proponen a continuación:

8. Es una tradición en Informática que el primer programa que se escribe en un lenguaje de programación es uno que simplemente imprime `Hello World!` en la pantalla del ordenador. Escriba en [Scratch](https://scratch.mit.edu/) el programa `Hello World!`.

9. Una variable es un elemento donde almacenar un valor. Se puede pensar como una cajita o un recipiente que contiene algo. En realidad es una pequeña porción de la memoria del ordenador, que en función del tipo de valor que almacena ocupa más o menos espacio. Se denomina "asignación" a una sentencia que permite cambiar el valor de una variable. Desarrolle un programa en [Scratch](https://scratch.mit.edu/) que pregunte al usuario su nombre y edad y los imprima en pantalla.

10. La parte derecha de una asignación es una *expresión*. Una expresión es esencialmente una fórmulita que permite calcular un valor. 
La expresión puede ser desde un literal (un `2` por ejemplo) hasta una fórmula compleja que involucre a muchas variables. Calcular el valor de una expresión es lo que se llama evaluar una expresión.

    Desarrolle un programa que solicite al usuario un par de números enteros positivos e imprima en pantalla la suma, el producto, la diferencia y la división de ambos valores.

11. Una constante es una variable que no se puede modificar (decir "variable constante" sería un oxímoron). Para los nombres (identificadores) de constantes se usará un convenio que consiste en hacer que comiencen por `k` y para el resto del nombre se usan mayúsculas y minúsculas como en `kAñoEnCurso`.

    Desarrolle un programa en [Scratch](https://scratch.mit.edu/) que solicite al usuario su año de nacimiento y le muestre como salida la edad que tiene.

12. Desarrolle un programa en [Scratch](https://scratch.mit.edu/) que dado un número `N` entero mayor que `1`, determine si `N` es divisible entre `3`. 
Nótese que un número es divisible entre `3` si al dividirlo entre `3` el resto es igual a `0`.

13. Desarrolle un programa en [Scratch](https://scratch.mit.edu/) que dado un número `N` entero mayor que `1`, muestre todos los números menores o iguales que él y que sean divisibles entre `3`.

14. Desarrolle un programa en [Scratch](https://scratch.mit.edu/) que proporcione la suma de los números impares inferiores a uno, `N`, introducido por el usuario.
    
15. Desarrolle un programa en [Scratch](https://scratch.mit.edu/) que calcule el área y el perímetro de un cuadrado. El programa solicitará la longitud del lado del cuadrado y luego mostrará en pantalla un mensaje con el perímetro y el área.

16. Realice un programa en [Scratch](https://scratch.mit.edu/)que convierta de kilómetros a millas, teniendo en cuenta que una milla son `1,60934` kilómetros. Compruebe [aquí](https://www.metric-conversions.org/es/longitud/millas-a-kilometros.htm) la corrección de su programa. ¿Cómo cree Ud. que puede funcionar esa página web en la que puede Ud. convertir de unidades diferentes magnitudes?.

17. Desarrolle un programa en [Scratch](https://scratch.mit.edu/) que dado un número `N` entero mayor que `1`, determine si `N` es un número primo.

18. Escriba un programa en [Scratch](https://scratch.mit.edu/) que calcule los años que le faltan para jubilarse. El programa solicitará que introduzca la edad y luego mostrará un mensaje con los años que le faltan para jubilarse. Pese a los tiempos que corren, suponga que la jubilación es a los 67 años y utilice una constante para almacenar ese dato.

### Referencias

[Initiation to Algorithmics with Scratch](https://drive.google.com/file/d/1DIU-bqgAurT-F9Ltnlam9QYWaZVeLlRJ/view?usp=sharing) Benoit Gaudou.