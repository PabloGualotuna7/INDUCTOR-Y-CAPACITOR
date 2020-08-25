# AMPLIFICADOR-OPERACIONAL

### 1. PLANTEAMIENTO DEL PROBLEMA


### 2. OBJETIVOS

### 3. MARCO TEÓRICO 

##### ¿Qué es un Amplificador operacional?

Un amplificador operacional, a menudo conocido opamp por sus siglas en inglés (operational amplifier) es un dispositivo amplificador electrónico de alta ganancia acoplado en corriente continua que tiene dos entradas y una salida. En esta configuración, la salida del dispositivo es, generalmente, de cientos de miles de veces mayor que la diferencia de potencial entre sus entradas.

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL/blob/master/img/1.jpg)

Figura 1.

##### Estructura

El símbolo de un amplificador es el mostrado en la siguiente figura:

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL/blob/master/img/2.png)

Figura 2.

Los terminales son:

· V+: entrada no inversora

· V-: entrada inversora

· VOUT: salida

· VS+: alimentación positiva

· VS-: alimentación negativa

Los terminales de alimentación pueden recibir diferentes nombres, por ejemplos en los A.O basados en FET VDD y VSS respectivamente. Para los basados en BJT son VCC y VEE. Normalmente los pines de alimentación son omitidos en los diagramas eléctricos por claridad.

Los Amplificadores operacionales se pueden encontrar:

1 operacional en un encapsulado de 8 pines, como es el UA741.
2 operacionales en un encapsulado de 8 pines, como el LM1458.
4 operacionales en un encapsulado de 14 pines, como es la LM324.

##### Características

El A.O ideal tiene una ganancia infinita, una impedancia de entrada infinita, un ancho de banda también infinito, una impedancia de salida nula, un tiempo de respuesta nulo y ningún ruido. Como la impedancia de entrada es infinita también se dice que las corrientes de entrada son cero.

Parámetro Valor ideal Valor real Zi ∞ 1 MΩ Zo 0 100 Ω Bw ∞ 1 MHz Av ∞ 100.000 Ac 0

Nota: Los valores reales dependen del modelo, estos valores son genéricos y son una referencia. Si van a usarse amplificadores operacionales, es mejor consultar el datasheet o características del fabricante.

##### Para qué sirve un amplificador operacional

Estos quipos, en un principio, fueron diseñados con la finalidad de amplificar la potencia de la corriente. Sin embargo, también son ampliamente utilizados para otros usos como el del acondicionamiento de señales, lo cual quiere decir que ayuda a aumentar la potencia y la intensidad.

De esta manera durante la medición no habrá una disminución o distorsión en caso de que la impedancia no sea alta en el circuito sensor. Así la señal que será medida tendrá el nivel requerido con respecto a la potencia entregada. También el acondicionamiento de señales permite tener el control de la modulación, estabilidad, polaridad entre otros.

También, se relaciona con el acoplamiento de las impedancias. De esta forma este dispositivo permite el paso de las frecuencias que tengan un menor valor con respecto a una de referencia determinada, igualmente sucede con las más altas. También el dispositivo permite el paso de un grupo de frecuencias que cumplan con los estándares del rango de filtro, igualmente puede impedir el paso de las frecuencias que sean mayores o menores al filtro.

Incluso un amplificador operacional interviene en el procesamiento tanto análogo como lógico de señales. Estos dispositivos proporcionan un valor de voltaje que puede ser saturado o de “0” en el caso del procesamiento lógico. El cuanto al procesamiento analógico estos funcionan como rectificadores, sumadores, comparadores, integradores o para realizar cambios en las fases o retardando.

##### Comportamiento en corriente continua (DC)

* Lazo abierto: Cuando se aplica una señal a la entrada, la ganancia es el cociente entre la tensión de salida Vs y la de entrada Ve que tiene el amplificador operacional cuando no existe ningún lazo de realimentación entre la salida y alguna de las dos entradas. Ver en la figura 3.

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL/blob/master/img/2.png)

Figura 3

La ganancia del amplificador en lazo abierto está dada por la siguiente fórmula:

AV = Vs / Ve
Donde:
AV = ganancia de tensión
Vs = tensión de salida
Ve = tensión de entrada

En un amplificador operacional ideal, esta ganancia es infinita. Sin embargo, cuando el operacional es real, su ganancia está entre 20,000 y 200,000 (en el amplificador operacional 741C). Este tipo de configuración se utiliza en comparadores, donde lo que se desea es, saber cual de las dos entradas tiene mayor tensión, de ahí su nombre, amplificador diferencial. La señal de salida Vs del amplificador diferencial ideal debería ser:

Vs = Av (V1 – V2).

En la realidad, no es así ya que la salida depende de la tensión diferencial (Vd) y del nivel medio llamado señal en modo común (Vc), o sea:

Vd = V1 -V2;    y     Vc = 1/2 (V1 + V2).

* Lazo cerrado o realimentado: Como decimos los amplificadores operacionales prácticos tienen ganancia de tensión muy alta (típicamente 10^5), sin embargo esta ganancia varía con la frecuencia. La forma de compensar esto es, controlar la ganancia de tensión que tiene el amplificador operacional, utilizando elementos externos para realimentar una parte de señal de la salida a la entrada, que hará que el circuito sea mucho más estable.

![](https://github.com/PabloGualotuna7/AMPLIFICADOR-OPERACIONAL/blob/master/img/4.JPG)

Figura 4

Con la realimentación, la ganancia de lazo cerrado, depende de los elementos empleados en la realimentación y no de la ganancia básica de tensión del amplificador operacional, por lo que, para modifica la ganancia modificaremos los valores de R1 y R2. Como veremos a continuación, los circuitos con amplificadores operacionales, resistencias y condensadores, los podemos configurar para obtener diversas operaciones analógicas como sumas, restas, comparar, integrar, filtrar y por supuesto amplificar. La ganancia se obtiene por la siguiente fórmula: AV= – Vo / Vin. El sigo negativo indica que la señal en la salida será la opuesta a la entrada (se confirma que una señal positiva aplicada a la entrada produce una tensión negativa a la salida y viceversa).

### 4. DIAGRAMAS

### 5. LISTAS DE COMPONENTES

### 6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

### 7. PREGUNTAS

##### 7.1 Anote parámetros técnicos importantes de un amplificador operacional que deben ser tomados en cuenta al momento de utilizarlos en un proyecto.

##### 7.2 Investigue las características de amplificadores operacionales distintos a los utilizados en esta práctica.

##### 7.3 Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores operacionales. 


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
