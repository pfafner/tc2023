# Teoría de la Computación 2023

Este es un curso introductorio a la teoría de la computación, la cual se ocupa de determinar cuáles problemas pueden ser resueltos computacionalmente y con qué eficiencia, así como de entender el límite entre los problemas computables y los no-computables, y clasificarlos de acuerdo a su simpleza o dificultad.  

El curso inicia con el estudio de distintos modelos de cómputo, como los autómatas finitos (que son los más sencillos), y sus diferentes tipos y aplicaciones; las máquinas de Turing (que son las computadoras usuales de hoy en día) y las computadoras cuánticas (cuyo funcionamiento no es digital). Una vez formulado un modelo de computación, nos interesa conocer la cantidad de recursos computacionales que es necesario utilizar para resolver un problema. El primero de estos recursos es el tiempo: cuántos pasos o cuántas acciones debemos realizar para resolver el problema. También son importantes el espacio ocupado, la necesidad de utilizar una fuente de números aleatorios, la posibilidad de resolver subproblemas en paralelo, entre otros.

La formalización de un modelo computacional como objeto matemático permite expresar de manera precisa preguntas sobre problemas o algoritmos. En particular, si L es un problema. ¿Puede L ser resuelto por un algoritmo? ¿Puede ser L resuelto de manera eficiente? ¿Cómo podemos construir un algoritmo eficiente para L? ¿Es L un problema para el cual no existe un algoritmo que lo resuelva? Contestaremos a algunas de estas preguntas, mientras que otras se verán en los cursos de Lógica Matemática y en Análisis de Algoritmos.


# Prerrequisitos

Se recomienda que los estudiantes antes del curso estén habituados con los siguientes temas:
* Álgebra lineal (matricial).
* Matemática discreta (conteo, permutaciones, divisibilidad, congruencias).
* Grafos (representaciones, propiedades, algoritmos).
* Cálculo (funciones, límites, derivadas).
* Estructuras y algoritmos (pilas y colas, árboles, grafos).

Bastará con haber cursado una materia de cálculo y una de mátemática discreta. En el caso de programación, conviene conocer muy bien los temas de estructuas de datos y algoritmos.

El curso tiene una carga fuerte en el tema de matemática y estructuras abstractas. Cuando sea conveniente, dedicaremos una parte del curso a cubrir algunos prerrequisitos necesarios en los temas.


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-tc2023.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Lunes de 19:00 a 21:25 CIT-503, y Miércoles de 19:00 a 20:35 CIT-301.

### Office Hours
<div id='id-office'/>

* Viernes de 18:00 a 19:00.

# Material del curso
<div id='id-material'/>

 **No.**  | **Fecha**    | **Tópicos**                                                               | **Recursos**
 -------- | ------------ | ------------------------------------------------------------------------- |  ---------------------------------
  01      | 05.07.2023   | Introducción al curso. Aspectos generales de la teoría de la computación. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 1.1
  02      | 10.07.2023   | Autómatas Finitos Deterministas (AFD). Tabla de transiciones. <br/> [Aula 02a](aulas/Aula02a.pdf){:target="_blank"} [Aula 02b](aulas/Aula02b.pdf){:target="_blank"} | Hopcroft-Ullman, Secciones 2.1, 2.2  
  03      | 12.07.2023   | Expresiones regulares. Árboles sintáctivos para *regexp*. Notación infix y postfix. <br/> [Aula 03a](aulas/Aula03a.pdf){:target="_blank"} [Aula 03b](aulas/Aula03b.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.1  
  L1      | 17.07.2023   |   | [Lab 01](labs/Lab01.pdf){:target="_blank"}  
  04      | 19.07.2023   | Función de transición extendida. Implementación de AFDs. [Aula 04](aulas/Aula04.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 2.2  
  05      | 19.07.2023   | Autómatas Finitos No Deterministas (AFN). [Aula 05](aulas/Aula05.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 2.3  
  06      | 24.07.2023   | Conversión de AFN a AFD. <br/> Cerradura y épsilon-transiciones. | Hopcroft-Ullman, Sección 2.5 
  L2      | 26.07.2023   |   | [Lab 02](labs/Lab02.pdf){:target="_blank"}  
  07      | 31.07.2023   | Conversión de *Regexp* a AFN. Algoritmo de Thompson. Algoritmo de Glushkov. [Aula 06a](aulas/Aula06a.pdf){:target="_blank"} [Aula 06b](aulas/Aula06b.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.2 
  08      | 07.08.2023   | Conversión de AFN a *Regexp*. Algoritmo de Reducción. Método de Arden. [Aula 07](aulas/Aula07.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.4 
  L3      | 09.08.2023   |   | [Lab 03](labs/Lab03.pdf){:target="_blank"}  
  09      | 14.08.2023   | Propiedades de lenguajes regulares: vacuidad, finitud, *Pumping Lemma*. [Aula 08](aulas/Aula08.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.4
  10      | 16.08.2023   | Producto de autómatas. Algoritmo de equivalencia. Algoritmo de minimización. [Aula 09a](aulas/Aula09a.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.4
  11      | 16.08.2023   | Propiedades de cerradura. Algoritmos para unión, intersección, diferencia. [Aula 09b](aulas/Aula09b.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.4
  L4      | 21.08.2023   |   | [Lab 04](labs/Lab04.pdf){:target="_blank"}  
  L5      | 23.08.2023   |   | [Lab 05](labs/Lab05.pdf){:target="_blank"}  
  12      | 28.08.2023   | Gramáticas libres del contexto. <br/> [Aula 12](aulas/Aula12.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 4.2
  13      | 30.08.2023   | Examen Corto 1. <br/>  | [Corto 1](cortos/corto1.pdf){:target="_blank"}  
  14      | 18.09.2023   | Árboles sintácticos. Derivaciones *leftmost* y *rightmost*. [Aula 13](aulas/Aula13.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 4.3  
  15      | 20.09.2023   | Ambigüedad en gramáticas. <br/> [Aula 14](aulas/Aula14.pdf){:target="_blank"} | 
  16      | 25.09.2023   | Algoritmo de simplificación de gramáticas. <br/> [Aula 15](aulas/Aula15.pdf){:target="_blank"} | 
  17      | 27.09.2023   | Entrega del proyecto 1. | 
  18      | 02.10.2023   | Forma Normal de Chomsky (CNF). Conversión a la CNF. <br/> [Aula 16](aulas/Aula16.pdf){:target="_blank"} | 
  19      | 04.10.2023   | Ejemplos de reducción y conversión a CNF. <br/> [Ejemplo Reducción](aulas/Ejemplo_Reduccion.txt){:target="_blank"} [Ejemplo Binarización](aulas/Binarizacion.txt){:target="_blank"} <br/> [Ejemplo CNF](aulas/Ejemplo_CNF.txt){:target="_blank"} 
  20      | 09.10.2023   | Autómatas de pila (PDA). Ejemplos. <br/> [Aula 17](aulas/Aula17.pdf){:target="_blank"} [Aula 18](aulas/Aula18.pdf){:target="_blank"}|  
  L6      | 11.10.2023   |    | [Lab 06](labs/Lab06.pdf){:target="_blank"}
  21      | 16.10.2023   | Ejemplos. Conversión entre PDA y CFG. *Pumping Lemma* para PDA. [Aula 19](aulas/Aula19.pdf){:target="_blank"} [Aula 20](aulas/Aula20.pdf){:target="_blank"} |  
  L7      | 18.10.2023   |    | [Lab 07](labs/Lab07.pdf){:target="_blank"}
  22      | 23.10.2023   | Máquinas de Turing. <br/> [Aula 21](aulas/Aula21.pdf){:target="_blank"} [Aula 22](aulas/Aula22.pdf){:target="_blank"} |   
  23      | 25.10.2023   | Ejemplos de máquinas de Turing. <br/> [Aula 23](aulas/Aula23.pdf){:target="_blank"} | 
  24      | 30.10.2023   | Entrega del proyecto 2. |  
  25      | 06.11.2023   | Análisis de algoritmos. |  
  L8      | 08.11.2023   |    | [Lab 08](labs/Lab08.pdf){:target="_blank"}
  26      | 08.11.2023   | Complejidad computacional. |  
  
  
# Lecturas complementarias
### (Autores: T. Gálvez, B. Pojoy, P. Mejía y A. Reyes-Figueroa, 2022).
<div id='id-notas'/>

  **No.**  | **Fecha**    | **Tópicos**                                                                | **Recursos**
  -------- | ------------ | -------------------------------------------------------------------------- |  -------------------------------------
  01       | 31.07.2023   | Lectura 1 - Expresiones regulares y AFNs.                                  | [Lectura 1](lecturas/Lectura01.pdf){:target="_blank"}
  02       | 07.08.2023   | Lectura 2 - Conversión de AFNs a AFDs y construcción directa del AFD.      | [Lectura 2](lecturas/Lectura02.pdf){:target="_blank"}
  03       | 21.08.2023   | Lectura 3 - Minimización de AFDs.                                          | [Lectura 3](lecturas/Lectura03.pdf){:target="_blank"}
  04       | 23.10.2023   | Lectura 4 - Máquinas de Turing.                                            | [Lectura 4](lecturas/Lectura04.pdf){:target="_blank"}


# Proyectos
<div id='id-proyectos'/>

En el curso se desarrollarán tres proyectos.

  **No.**  | **Fecha**    | **Tópicos**                                                     | **Recursos**
  -------- | ------------ | --------------------------------------------------------------- |  ---------------------
  1        | 21.08.2023   | Proyecto 1 - Algoritmos sobre AFDs, AFNs y *regexp*.            | [Proyecto 1](proyectos/Proyecto1.pdf){:target="_blank"} <br/> **Fecha de Entrega: 25-29 septiembre.**
  2        | 27.09.2023   | Presentación y revisión del proyecto.
  3        | 29.09.2023   | Entrega del reporte final.


  **No.**  | **Fecha**    | **Tópicos**                                                     | **Recursos**
  -------- | ------------ | --------------------------------------------------------------- |  ---------------------
  1        | 01.10.2023   | Proyecto 2 - Algoritmo CYK para gramáticas.                     | [Proyecto 2](proyectos/Proyecto2.pdf){:target="_blank"} <br/> **Fecha de Entrega: lunes 30 de octubre.**
  2        | 30.10.2023   | Presentación y revisión del proyecto.
  3        | 02.11.2023   | Entrega del reporte final.


  **No.**  | **Fecha**    | **Tópicos**                                                     | **Recursos**
  -------- | ------------ | --------------------------------------------------------------- |  ---------------------
  1        | 05.11.2023   | Proyecto 3 - Máquinas de Turing.                     | [Proyecto 3](proyectos/Proyecto3.pdf){:target="_blank"} <br/> **Fecha de Entrega: miércoles 22 de noviembre.**
  2        | 22.11.2023   | Presentación y revisión del proyecto.
  3        | 24.11.2023   | Entrega del reporte final.

  
# Referencias
<div id='id-ref'/> 

### Textos:

* [J. Hopcroft, R. Motwani, J. Ullman (2006). *Automata Theory, Languages and Computation*.](http://library.lol/main/CAC409C1878AC487AF3A39687C924FFC){:target="_blank"}

* [J. Hopcroft, R. Motwani, J. Ullman (2007). *Teoría de automatas, lenguajes y computación*.](libros/Hopcroft_Ullman.pdf){:target="_blank"}

### Referencias adicionales:

* [H. Lewis, C. Papadimitriou (1998). *Elements of the Theory of Computation*.](http://library.lol/main/586BEB94A1648CF624F74496477E92DB){:target="_blank"}

* [J. G. Brookshear (1988). *Theory of Computation: Formal Languages, Automata, and Complexity*.](http://library.lol/main/EE4EB25060E76527E13F904C99DE2D98){:target="_blank"}

* [J. G. Brookshear (1993). *Teoría de la Computación, Lenguajes Formales, Autómatas y Complejidad*.](libros/Brookshear.djvu){:target="_blank"}

* [R. de Castro Korgi (2004). *Teoría de la Computación, Lenguajes Autómatas, Gramáticas*.](http://library.lol/main/60501AE7549BF7B67BB11709240CE5B7){:target="_blank"}

* [E. Gaudioso Vásquez *et al.* (2017). *Introduccón a la Teoría de Autómatas, Gramáticas y Lenguajes*.](http://library.lol/main/7B969A8129A16B2F3679F4D4A20FFF5D){:target="_blank"}

* [H. Pedrycz (2022). *Automata Theory and Formal Languages*.](http://library.lol/main/AEC2FE8B00CE16488082B14183D31727){:target="_blank"}

### Referencias avanzadas:

* [C. Papadimitriou, K. Steiglitz (1994). *Computational Complexity*.](http://library.lol/main/2E57188472ACBBBB8B5860A1327FBA94){:target="_blank"}

---
