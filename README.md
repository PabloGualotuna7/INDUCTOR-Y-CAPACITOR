# INDUCTOR Y CAPACITOR

### 1. PLANTEAMIENTO DEL PROBLEMA

En el siguiente informe de laboratorio se va a emplear los conocimientos aprendidos en la teoría de la materia de Fundamentos de Circuitos eléctricos. De este modo utilizaremos las definiciones tanto de inductor como de capacitor, así como también la parte matemática, esto será complementado con la investigación realizada. Adema de realizar los análisis que nos piden y a la vez responder a las preguntas planteadas.

### 2. OBJETIVOS

* Investigar los conceptos de bobina y capacitor en circuitos DC y AC, para aplicar en el desarrollo del informe. 

* Analizar las diferencias entre un inductor y capacitor, así como también la simbología que tiene cada uno y poder diferenciar en los circuitos y buscar un simulador online adecuado para desarrollar el informe y responder a las preguntas planteadas con la ayuda del mismo.

* Determinar experimentalmente la condición necesaria para hallar lo pedido tanto en el concepto de inductor y capacitor.

* Realizar tablas para así poder comparar los resultados de las mediciones realizadas tanto con el osciloscopio, multímetro y las calculadas.

### 3. MARCO TEÓRICO 

##### Qué es un inductor?

Es un componente eléctrico que produce inducción. Concretamente, induce un campo magnético cuando es atravesado por una corriente. También se le llama bobina o solenoide. En principio, cualquier conductor podría usarse para construir una bobina. Se elabora enrollando alambre conductor en círculos, dando varias vueltas, de modo de formar un helicoide. Para evitar que el alambre enrollado entre en cortocircuito al hacer contacto consigo mismo al enrollarse, se emplea alambre esmaltado en la confección del inductor. Cada vuelta que el alambre efectúa se llama espira.

En otras palabras: La bobina o inductor es un elemento que reacciona contra los cambios en la corriente a través de él, generando un voltaje que se opone al voltaje aplicado y es proporcional al cambio de la corriente.

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/2.JPG)

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/11.png)

Figura 1

#### Características técnicas generales del inductor.

* Permeabilidad magnética (m): Es una característica que tiene gran influencia sobre el núcleo de las bobinas respecto del valor de la inductancia de las mismas. Los materiales ferromagnéticos son muy sensibles a los campos magnéticos y producen unos valores altos de inductancia, sin embargo otros materiales presentan menos sensibilidad a los campos magnéticos. El factor que determina la mayor o menor sensibilidad a esos campos magnéticos se llama permeabilidad magnética.
Cuando este factor es grande el valor de la inductancia también lo es.

* Factor de calidad (Q): Relaciona la inductancia con el valor óhmico del material de la bobina. La bobina será buena si la inductancia es mayor que el valor óhmico debido al material de la misma.

##### Aplicaciones de una bobina / inductor:

En los sistemas de iluminación con lámparas fluorescentes existe un elemento adicional que acompaña al tubo y que comúnmente se llama balastro
En las fuentes de alimentación también se usan bobinas para filtrar componentes de corriente alterna y solo obtener corriente continua en la salida
En muchos circuitos osciladores se incluye una  bobina o inductor. Por ejemplo circuitos RLC serie o paralelo.

##### Funcionamiento

Cuando circula una corriente por las espiras, se induce un campo magnético que atraviesa el cilindro helicoidal en su longitud, y también en el exterior del solenoide. Esto se conoce como ley de Faraday. La capacidad inductiva de una bobina se puede medir a través de un parámetro propio de la misma llamado autoinductancia, o sencillamente inductancia. Cuando una bobina interactúa magnéticamente con otras, se produce un fenómeno llamado inductancia mutua, a tener en cuenta en algunos circuitos.

Se puede mejorar la inductancia de una bobina si las espiras están arrolladas alrededor de un núcleo de material ferromagnético.

En corriente continua, lo que más se aprovecha de los inductores es la capacidad magnética, en tanto que en corriente alterna, y en regímenes de señales eléctricas variables, se aprovecha el comportamiento del inductor como variador de la señal eléctrica en el tiempo.

##### Usos de los inductores

* En motores: En los motores eléctricos, se usan bobinas para construir máquinas cuyo movimiento rotatorio se genera por interacción de los campos magnéticos producidos en dichas bobinas.

* Transformadores eléctricos: Estos equipos usan el principio de Faraday para propagar una corriente eléctrica de cierta tensión a otro flujo de corriente bajo otra tensión de forma inalámbrica. Los transformadores, además de modificar el voltaje/corriente al deseado, sirven como una línea de protección para los equipos eléctric.s

* Cerraduras eléctricas: El campo producido dentro de las espiras puede usarse para que la barra ferromagnética que forma el núcleo se desplace a lo largo de si misma. Esto sirve para que el núcleo trabaje como elemento actuador que libere o asegure una cerradura.

* Timbres: En algunos timbres se usa el campo magnético oscilante para producir sonido a través de la vibración

* Interruptores diferenciales: Usan inductores de núcleo móvil como elemento que sirve para disparar el interruptor de seguridad.

* Circuitos de modulación: Tradicionalmente se han usado inductores como elementos que juegan importante papel en la transmisión y recepción de señales moduladas, como en el caso de los sistemas de radio. Aquí se aprovechan los fenómenos asociados al comportamiento de los inductores en corriente alterna para construir circuitos que permitan la transmisión y recepción de señales de radio.

##### ¿Cómo saber el valor de un inductor?

Los valores importantes que debemos conocer son la inductancia eléctrica, y tolerancia. Estos valores se indican en el encapsulado dependiendo del tipo de éste.

El primer paso para la lectura de un Inductor es la comprensión de lo que significa cada banda.

1) La primera banda que corresponde al extremo izquierdo es la que representa el dígito más significativo del inductor.
2) La segunda banda representa el segundo dígito más significativo.
3) La tercera banda representa el tercer dígito más significativo del inductor.
4) La cuarta banda representa la potencia de 10 elevada al color correspondiente y multiplicado por la primera, segunda y tercer banda.
5) La quinta banda representa la tolerancia del inductor.

##### Qué es un capacitor?

También conocido como condensador es un dispositivo capaz de almacenar  energía a través de campos eléctricos (uno positivo y uno negativo). Este se clasifica dentro de los componentes pasivos ya que no tiene la capacidad de amplificar o cortar el flujo eléctrico.

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/3.JPG)

Figura 2

Los capacitores se utilizan principalmente como filtros de corriente continua, ya que evitan cambios bruscos y ruidos en las señales debido a su funcionamiento.

Esto se puede expresar matemáticamente como:

q = CV

Donde:

q es la carga almacenada [Coulomb].

C es la capacitancia del capacitor [Farad].

V es la tensión aplicada al capacitor [Volt].

##### Partes de un capacitor 

Este dispositivo en cuanto a construcción es demasiado sencillo en comparación con otros componentes, ya que solo consta de tres partes esenciales.

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/4.JPG)

Figura 3

Placas metálicas: Estas placas se encargan de almacenar las cargas eléctricas.

Dialéctico o aislante: Sirve para evitar el contacto entre las dos placas.

Carcasa de plástico: Cubre las partes internas del capacitor.

#### ¿Cómo funciona un capacitor?

En su estado natural cada una de las placas internas tiene el mismo numero de electrones. Cuando conectamos una fuente de voltaje una de las placas pierde electrones (siendo esta la terminal positiva), mientras que la otra los gana ( terminal negativa). Este movimiento de electrones se detiene cuando el capacitor alcanza el mismo voltaje que la fuente de alimentación.

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/5.JPG)

Figura 4

El material dialéctico se coloca entre las dos placas y sirve para evitar que estas hagan contacto entre sí, también sirve para que los electrones no pasen de una hacia la otra. Cuando se desconecta la fuente de alimentación los electrones ganados por una de las placas regresan a la otra placa para alcanzar su estado natural con el mismo numero de electrones en cada una.

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/6.JPG)

Figura 5


#### Tipos de capacitores.

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/7.jpg)

Figura 6

### 4. DIAGRAMAS
Diagrama circuito con capacitores

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/DIAGRAMA%201.jpg)

Figura 7

Diagrama circuito con inductores 

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/DIAGRAMA%202.jpg)

Figura 8

Circuito con capacitores implementado en el simulador proteus

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/Captura%20circuito%201.png)

Figura 9

Circuito con inductores implementado en el simulador proteus

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/Captura%20circuito%202.png)

Figura 10

### 5. LISTAS DE COMPONENTES

| Cantidad | Materiales |
| --- | --- |
| 1 | Generador de señales |
| 1 | Osciloscopio |
| 1 | Multímetro |
| 1 | Resistencia |
| 2 | Bobinas | 
| 2 | Capacitores |

### 6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

1. Abrimos el simulador proteus, seguidamente buscamos y seleccionamos todos los materiales a usar.

2. Armamos los circuitos pedidos siguiendo los diagramas establecidos.

3. Configuramos el generador de señales para el dato del voltaje pico y de los distintos valores de frecuencias.

4. Configuramos los valores de la resistencia, de los capacitores y de las bobinas.

5. Conectamos el osciloscopio, siempre con una de sus terminales a tierra, para que produzca señal.

6. Variamos los valores de frecuencias y medimos tanto voltaje y corriente con el multimetro, como el voltaje pico con el osciloscopio.

7. Anotamos cada valor arrojado por el simulador.

8. Guardamos y Salimos.

### 7. TABLAS DE MEDICIONES Y CÁLCULOS

Valores de voltaje eficaz y pico en el circuito 1

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/tabla%20capacitor.png)

Tabla 1

Valores de corriente en el circuito 1

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/Corriente%20capacitor.png)

Tabla 2

Valores de corriente en la resistencia del circuito 1

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/Resistencia%20circuito%201.png)

Tabla 3

Valores de voltaje eficaz y pico en el circuito 2

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/tabla%20bobina.png)

Tabla 4

Valores de corriente en el circuito 1

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/Corriente%20bobina.png)

Tabla 5

Valores de corriente en la resistencia del circuito 2

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/Resistencia%20circuito%202.png)

Tabla 6

Valores de reactancia del circuito 1 (capacitancias)

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/Circuito%201.png)

Tabla 7

Valores de reactancia del circuito 2 (inductancias)

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/Circuito%202.png)

Tabla 8


Análisis Tabla 7:

Se deduce que mientras la frecuencia va en aumento, la reactancia tiene a disminuir, esto debido a que la corriente de igual forma decrece.

Análisis Tabla 8:

Se concluye que al momento que la frecuencia aumenta, la reactancia sigue los mismos pasos y tiende a crecer, sucediendo lo contrario con la corriente que decrece.

### 8. PREGUNTAS

##### 8.1 Justifique los errores cometidos en las mediciones.

Los errores que se obtuvieron en la práctica tienen varios factores por los que se dan, uno de ellos es el factor numerico, como puede ser los decimales, que dependiendo del simulador varian respecto a los calculos. Otro error es por los elementos utilizados en el circuito, como son los capacitores y los inductores, ya que desde la programación vienen diseñados de distinta forma, es decir se ajustan a los valores exactos como especifica la figura, mientras por ejemplo una calculadora comun no tiene tanta precisión al momento de operar con respecto a las configuraciones de los capacitores e inductores en el simulador.

##### 8.2 ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?

El capacitor se comporta como un circuito abierto para corriente continua y la bobina como un cortocircuito. En un circuito complementado en corriente continua se puede entender un condensador como un interruptor abierto es decir no deja pasar corriente (por lo que no hay presencia de intensidad) sin embargo esta la presencia de voltaje debido a que en el condensador posee una reactancia. Una bobina en corriente continua actúa diferente que un condensador, es decir deja pasar corriente (ya que las bobinas son realmente cables enrollados que solo conducen), sin embargo, no posee voltaje debido a que las bobinas en cc actúan como un corto circuito (se unen los polos positivo y negativo sin tener una carga).

##### 8.3 ¿Cómo se comportan la bobina y el capacitor en corriente alterna?

Bobinas AC:

Cuando las bobinas son sometidas a corriente con frecuencia (A.C.), cumplen su función de inductancia, es decir además de poseer corriente esta también tiene la presencia de voltaje, debido al efecto de frecuencia. Las bobinas se pueden utilizar para “Adelantar voltaje y retrasar corriente”, dependiendo de cómo se utiliza para mejorar el factor de potencia.

Condensadores en AC:

En este caso, sucede todo lo contrario: el condensador deja pasar corriente, y tiene la presencia del voltaje, todo debido al efecto que tiene la corriente alterna en el elemento. Los condensadores se utilizan para “Adelantar corriente y atrasar voltaje”, dependiendo para mejorar el factor de potencia.

##### 8.4 ¿Qué cree usted que ocurriría con el voltaje 𝑉𝑜 y la corriente de la resistencia en los circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores distintos?

Al colocar dos capacitores o dos bobinas de diferente denominación en el circuito, se facilita los cálculos al momento de encontrar el valor de Vo porque podemos reducir el circuito a su mínima expresión usando el concepto de fasores, en los cuales a las impedancias y a las inductancias las convertimos al dominio fasorial y se representaría como una caja en el circuito a la cual podemos reducirle por el concepto de serie y paralelo.

##### 8.5 ¿Qué son los valores eficaces de voltaje y corriente?

Se llama valor eficaz de una corriente alterna, al valor que tendría una corriente continua que produjera la misma potencia que dicha corriente alterna, al aplicarla sobre una misma resistencia. En otras palabras, el valor RMS es el valor del voltaje o corriente en CA que produce el mismo efecto de disipación de calor que su equivalente de voltaje o corriente directa.

### 9. PORCENTAJE DE ERROR.

Porcentaje de error en las mediciones y calculos del circuito 1

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/Porcentaje%20de%20error%201.png)

Tabla 9

Porcentaje de error en las mediciones y calculos del circuito 2

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/Porcentaje%20de%20error%202.png)

Tabla 10

### 10. CONCLUSIONES 

* La presencia de condensadores y bobinas en un circuito de corriente alterna desfasa la intensidad de corriente respecto a la fem, además de suponer una variación de la resistencia efectiva del circuito, dependiente de la frecuencia de la corriente.

* Los condensadores no son más que dispositivos que permiten la carga y descarga de energía y por lo tanto el almacenamiento de estas en el tiempo que sea necesario. Por tanto, son dispositivos que evitan el disparo repentino del flujo de energía almacenando una cantidad de esta dentro de ellos.

* Los condensadores conectados en serie se comportan como resistores en paralelo; y cuando se conectan en paralelo se comportan como resistores en serie. Por lo tanto, la capacidad de los capacitores es inversamente proporcional a la tensión aplicada.

* Una bobina ideal en corriente continua se comporta como un cortocircuito, ya que, al ser la corriente constante, no habría autoinducción de ninguna fem. En corriente AC ofrece una resistencia al paso de la corriente eléctrica que recibe el nombre de reactancia inductiva

### 11. RECOMENDACIONES 

* Se debe reconocer la función de cada capacitor y de cada inductor y relacionar con las ondas observadas en el osciloscopio.

* Se debe analizar las ondas observadas en el osciloscopio ya que cada una de ellas presenta una frecuencia diferente por eso tener conocimiento de la funcionalidad de los instrumentos a utilizar.

* Para obtener mejores resultados en el osciloscopio es más recomendado configurarlo, para poder tener una vision mas amploa de la onda que se observa.

* Se recomienda saber que en un circuito con corriente alterna, un condensador ideal ofrece una resistencia al paso de la electricidad que recibe el nombre de reactancia capacitiva, cuyo valor viene dado por la inversa del producto de la pulsación por la capacidad.

### 12. CRONOGRAMA

Actividades desarrolladas a lo largo de la practica de laboratorio.

![](https://github.com/PabloGualotuna7/INDUCTOR-Y-CAPACITOR/blob/master/img/Cronograma%201.png)

### 13. BIBLIOGRAFÍA 

Alexander, C, & Sadiku, M. (2006). Fundamentos de Circuitos Eléctricos. 3ra. Edición. Mc Graw Hill.

Boylestad, R. (2011). Introducción al Análisis de Circuitos.2da. Edición. Pearson.

Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
