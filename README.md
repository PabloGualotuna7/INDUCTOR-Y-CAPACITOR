# AMPLIFICADOR-OPERACIONAL

### 1. PLANTEAMIENTO DEL PROBLEMA


### 2. OBJETIVOS

### 3. MARCO TEÓRICO 

##### ¿Qué es un Amplificador operacional?

Un amplificador operacional, a menudo conocido opamp por sus siglas en inglés (operational amplifier) es un dispositivo amplificador electrónico de alta ganancia acoplado en corriente continua que tiene dos entradas y una salida. En esta configuración, la salida del dispositivo es, generalmente, de cientos de miles de veces mayor que la diferencia de potencial entre sus entradas.

##### Estructura

El símbolo de un amplificador es el mostrado en la siguiente figura:

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

* Lazo abierto: Si no existe realimentación la salida del A. O. será la resta de sus dos entradas multiplicada por un factor. Este factor suele ser del orden de 100.000 (que se considerará infinito en cálculos con el componente ideal). Por lo tanto si la diferencia entre las dos tensiones es de 1V la salida debería ser 100.000V. Debido a la limitación que supone no poder entregar más tensión de la que hay en la alimentación, el A. O. estará saturado si se da este caso. Esto será aprovechado para su uso de comparador analógico]], como se verá más adelante. Si la tensión más alta es la aplicada a la patilla + la salida será la que corresponde a la alimentación VS+, mientras que si la tensión más alta es la del pin - la salida será la alimentación VS-.

* Lazo cerrado o realimentado: Se conoce como lazo cerrado a la realimentación en un circuito. Aquí se supondrá realimentación negativa. Para conocer el funcionamiento de esta configuración se parte de las tensiones en las dos entradas exactamente iguales, se supone que la tensión en la pata + sube y, por tanto, la tensión en la salida también se eleva. Como existe la realimentación entre la salida y la pata -, la tensión en esta pata también se eleva, por tanto la diferencia entre las dos entradas se reduce, disminuyéndose también la salida. Este proceso pronto se estabiliza, y se tiene que la salida es la necesaria para mantener las dos entradas, idealmente, con el mismo valor. Siempre que hay realimentación negativa se aplican estas dos aproximaciones para analizar el circuito: · V+ = V- (lo que se conoce como principio del cortocircuito virtual). · I+ = I- = 0 Cuando se realimenta negativamente un amplificador operacional, al igual que con cualquier circuito amplificador, se mejoran algunas características del mismo como una mayor impedancia en la entrada y una menor impedancia en la salida. La mayor impedancia de entrada da lugar a que la corriente de entrada sea muy pequeña y se reducen así los efectos de las perturbaciones en la señal de entrada. La menor impedancia de salida permite que el amplificador se comporte como una fuente eléctrica de mejores características. Además, la señal de salida no depende de las variaciones en la ganancia del amplificador, que suele ser muy variable, sino que depende de la ganancia de la red de realimentación, que puede ser mucho más estable con un menor coste. Asimismo, la frecuencia de corte superior es mayor al realimentar, aumentando el ancho de banda. Asimismo, cuando se realiza realimentación positiva (conectando la salida a la entrada no inversora a través de un cuadripolo determinado) se buscan efectos muy distintos. El más aplicado es obtener un oscilador para el generar señales oscilantes.

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
