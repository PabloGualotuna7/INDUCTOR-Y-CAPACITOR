# INDUCTOR Y CAPACITOR

### 1. PLANTEAMIENTO DEL PROBLEMA

En el siguiente informe de laboratorio se va a emplear los conocimientos aprendidos en la teoría de la materia de Fundamentos de Circuitos eléctricos. De este modo utilizaremos las definiciones tanto de inductor como de capacitor, así como también la parte matemática, esto será complementado con la investigación realizada. Adema de realizar los análisis que nos piden y a la vez responder a las preguntas planteadas.

### 2. OBJETIVOS

* Investigar los conceptos de bobina y capacitor en circuitos DC y AC, para aplicar en el desarrollo del informe. 

* Analizar las diferencias entre un inductor y capacitor, así como también la simbología que tiene cada uno y poder diferenciar en los circuitos.

* Buscar un simulador online adecuado para desarollar el informe y responder a las preguntas planteadas con la ayuda del mismo.

* Determinar experimentalmente la condición necesaria para hallar lo pedido tanto en el concepto de inductor y capacitor.

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

### 5. LISTAS DE COMPONENTES

### 6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

### 7. PREGUNTAS

##### 7.1 Justifique los errores cometidos en las mediciones.

##### 7.2 ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?

##### 7.3 ¿Cómo se comportan la bobina y el capacitor en corriente alterna?

##### 7.4 ¿Qué cree usted que ocurriría con el voltaje 𝑉𝑜 y la corriente de la resistencia en los circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores distintos?

##### 7.5 ¿Qué son los valores eficaces de voltaje y corriente?

### 8. PORCENTAJE DE ERROR.

### 9. CONCLUSIONES 

### 10. RECOMENDACIONES 

### 11. CRONOGRAMA

Actividades desarrolladas a lo largo de la practica de laboratorio.

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/Cronograma.png)


### 12. BIBLIOGRAFÍA 

Alexander, C, & Sadiku, M. (2006). Fundamentos de Circuitos Eléctricos. 3ra. Edición. Mc Graw Hill.

Boylestad, R. (2011). Introducción al Análisis de Circuitos.2da. Edición. Pearson.

Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
