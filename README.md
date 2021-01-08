# Laboratorio2
# Análisis de Mallas

1. OBJETIVOS

1.1 OBJETIVOS GENERALES

* Comprobar experimentalmente el Análisis de Mallas.

1.2 OBJETIVOS ESPECIFICOS

* Determiar los pasos para realizar el Análisis de Mallas.
*	Comprender cual es la función principal del Análisis de Mallas.
* Determinar que es una Malla.

2. MARCO TEORICO

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Ana%CC%81lisis%20de%20mallas-3.jpg)

3. DIAGRAMAS

Ejercicio Propuesto

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Diagrama%20Circuito%20A%20Realizar.png)

Armado Circuito Completo

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/TotalVacio.png)

Circuito de la Corriente Completo

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Total1.png)

Armado Circuito 1

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Corriente1.png)

Circuito de la Corriente 1 

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Corriente1Vacio.png)

Armado Circuito 2

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Corriente2Vacia.png)

Circuito de la Corriente 2

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Corriente2.png)

Armado Circuito 3

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Corriente3Vacia.png)

Circuito de la Corriente 3

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Corriente3.png)

Resolución Ejercicios

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Calculos1.png)
![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Calculos2.png)

4. LISTA DE COMPONENTES

| CANTIDAD | MATERIAL O EQUIPO |
| ------------- | ------------- |
| 2 | Fuentes de Voltaje CD  |
| 3 | Multímetros Digitales |
| 1 | Resistor de 820 Ω |
| 1 | Resistor de 390 Ω |
| 1 | Resistor de 1 kΩ  |
| 1 | Resistor de 1.2 kΩ  |
| 1 | Resistor de 2.2 kΩ  |
| 1 | Protoboard  |

5. EXPLICACIÓN

El Analisis de Mallas esta diseñado con el objetivo de analizar los circuitos de tal forma que podamos determinar el movimiento de la corriente por el circuito, este analisis forma parte de la segunda ley de Kirchhoff, ya que esta se enfoca en circuitos cerrados.
La segunda ley de Kirchhoff nos dice que la suma algebraica de todos los voltajes en una malla o bucle cerrado, debe ser igual a cero.
Al referirnos a la suma algebraica, implica el cuidado de las polaridades de la fuente de energía, así como todos los signos de las caídas de tensión de cada uno de los componentes eléctricos.
De modo que, al momento de aplicar la segunda ley de Kirchhoff, hay que ser muy precavidos en sentido de la orientación de la corriente y, por ende, con los signos de los voltajes de los componentes contenidos dentro de la malla.

6. MANUAL DE USUARIO

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Manual.jpg)

1 Es el espacio de trabajo de TinkerCAD. Es de color naranja para saber que contiene nuestro espacio de trabajo, el cuadrado grande es la superficie de trabajo y el pequeño son las opciones de dicha superficie: tamaño total, tamaño de la rejilla y unidades de medición.

2 Son las formas de visualizar un objeto. El primero es el cubo de visualización, después tenemos zoom, ajuste de pantalla, cambio de vista, y vista de inicio.

3 Esta es la zona de edición de piezas, aquí podremos ocultar objetos si nos molestan, hacer simetrías, agrupar, desagrupar y alinear. Es unas de las herramientas que mas se usaran a partir de hoy.

4 Esta es la zona ‘random’, donde podrás acceder a tu zona de usuario, importar y exportar archivos o acceder a algunas funcionalidades adicionales de TinkerCAD.

5 Este es el espacio de trabajo donde tenemos todo el banco de piezas de TinkerCAD. Además, encima tienes las herramientas de plano de trabajo y reglas.

6 Contiene todas las herramientas de edición de documento del TinkerCAD: Copiar, Pegar, Duplicar, Eliminar, Rehacer, Deshacer y si damos al panel justo al lado del nombre podremos cambiar la visibilidad del archivo.

7. CONCLUSIONES

*	Al realizar el analisis de mallas de forma experimental podemos comprobar la divición de las corrientes dentro de cada malla del circuito y de igual forma comprobamos como la segunda ley de Kirchhoff se cumple al verificar que la suma de todos los voltajes es igual a cero.

*	Para realizar el análisis de mallas es necesario seguir los siguientes pasos:

  1)	Identifica las mallas (las ventanas abiertas del circuito).

  2)	Asigna una corriente a cada malla, usando una dirección consistente (a favor o en contra de las manecillas del reloj).

  3)  Escribe las ecuaciones para la ley del voltaje de Kirchhoff alrededor de cada malla.

  4)	Resuelve el sistema de ecuaciones resultante para todas las corrientes de malla.

  5)	Determina las corrientes y los voltajes de los demás elementos del circuito por medio de la ley de Ohm.

*	El método de la corriente de malla facilita el análisis, y produce un número relativamente pequeño de ecuaciones a resolver.

*	En un circuito eléctrico, una malla es un camino cerrado formado por elementos de circuitos.

--------------------------------------------------------------------------

1) Mida cada una de las corrientes y anote los resultados en la tabla 3.1

* Para resolver las corrientes de cada una de la mallas se ha implementado la Ley de Ohm y la Ley de Voltaje de Kirchhoff.

* Para las mallas se utilizo las sumatoria de voltajes que deben dar el valor de 0, y obtenemos las 3 ecuaciones en funcion de las corrientes.

* Para resolver es necesario implementar un sistema de 3 ecuaciones con 3 incognitas que nos an arrojado los siguientes valores:

* I1 = 11.45 mA    ;  I2 = 2.847 mA   ;  I3 = 0.488 mA

2) Simulación en Tinkercad

* Los datos obtenidos en el circuito diseñado en la plataforma de Tinkercad nos han arrojado ciertos valores que son respectivamente las corrientes de cada una de las mallas, son 3 mallas las cuales se dividen como I1, I2 e I3.

* Los siguientes valores son los siguientes:

* I1 = 11.5 mA    ;  I2 = 2.85 mA   ;  I3 = 0.49 mA

Tabla 3.1

| MALLA | RESULTADOS ANALÍTICOS | RESULTADOS EXPERIMENTALES |
| ------------- | ------------- | ------------- |
| 1 | 11.45mA  | 11.5mA |
| 2 | 2.847mA | 2.85mA |
| 3 | 0,488 | 0.49mA |

3) Comparación de Resultados:

* Como se puede evidenciar en la Tabla 3.1 estan reflejados los valores obtenidos tanto cálculos analíticos como cálculos experimentales, notamos una cierta diferencia en los valores ya que la plataforma de Tinkercad realiza un redondeado a sus valores, en cambio en los cálculos analíticos se ven reflejados los numeros decimales sin una respectiva redondeada.

* Podemos conlcuir que existe un Porcentaje de Error en los Calculos de la tabla que se veran reflejados a continuacion:

![](https://github.com/JosueCamp2020/Laboratorio2/blob/main/Imagenes/Error.png)

8. BIBLIOGRAFIA

* Lorenzo, J. (03 de 06 de 2019). ofelia.com. Obtenido de https://of3lia.com/tinkercad-tutorial-completo/

* McAllister, W. (2017). khanacademy.org. Obtenido de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method

* pr-ser-uj. (04 de 04 de 2020). hetpro-store.com. Obtenido de https://hetpro-store.com/TUTORIALES/ley-de-kirchhoff-analisis-de-mallas/

