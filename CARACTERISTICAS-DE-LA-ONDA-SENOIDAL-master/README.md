# CARACTERISTICAS-DE-LA-ONDA-SENOIDAL

### 1. PLANTEAMIENTO DEL PROBLEMA

En el siguiente informe de laboratorio se va a emplear los conocimientos aprendidos en la teoría de la materia de fundamentos de circuitos eléctricos. Ademas de investigar la representación de la onda senoidal, tanto en su forma gráfica como en su forma matemática aplicando al maximo la investigacion realizada, los elementos eléctricos como resistencias, condensadores e inductancias, que se conectan a entradas de voltaje sinusoidal, producen respuestas también sinusoidales. Las matemáticas que se utilizan en su descripción son relativamente sencillas y han sido minuciosamente estudiadas.

### 2. OBJETIVOS

*	Determinar experimentalmente las características de señales senoidales.

* Aprender a medir el periodo de una onda de C.A. con el osciloscopio y los valores de voltajes de pico con el osciloscopio.

*	Analizar y verificar en forma experimental el desfasamiento de las ondas senoidales de tensiones y corrientes entre el voltaje y la tensión en circuitos.

*	Completar el estudio de los circuitos con corriente alterna, medir la amplitud y la tensión eficaz de una onda senoidal y medir el periodo y calcular la frecuencia de una onda senoidal.

### 3. MARCO TEÓRICO 

Se denomina corriente alterna (ca) a la corriente eléctrica en la que la magnitud y dirección varían periódicamente. La forma de onda de la corriente alterna más comúnmente utilizada es la de una onda senoidal, puesto que se consigue una transmisión más eficiente de la energía.

Generalmente, la corriente alterna se refiere a la forma en la cual la electricidad llega a los hogares y a las empresas. Sin embargo, las señales de audio y de radio transmitidas por los cables eléctricos, son también ejemplos de corriente alterna.

Las ondas senoidales son patrones de ondas que matemáticamente pueden ser descritas mediante las funciones seno y coseno. Describen acertadamente eventos naturales y señales variables en el tiempo, tales como los voltajes generados por centrales eléctricas y luego utilizados en hogares, industrias y calles.

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/onda-senoidal1.jpg)

FIGURA 1: Una onda senoidal con algunas de sus principales características espaciales: amplitud, longitud de onda y fase.

Partes:

Período: Una función periódica como las mencionadas, la cual se repite a intervalos regulares, cumple siempre la siguiente propiedad:
f (t) = f (t+ T) = f (t + 2T) = f (t + 3T) = ….
Donde T es una cantidad denominada período de la onda, y es el tiempo que tarda en repetirse una fase de la misma. En unidades de Sistema Internacional, el período se mide en segundos.

Amplitud: De acuerdo a la expresión general de la onda senoidal v (t) = vm sen (ωt+φ), vm es el valor máximo de la función, que ocurre cuando sen (ωt+φ)= 1 (recordando que el mayor valor que admite tanto la función seno como la función coseno es 1). Este valor máximo es justamente la amplitud de la onda, también conocida como amplitud pico. En caso de tratarse de un voltaje se medirá en Voltios y si es una corriente será en Amperios. En la onda senoidal mostrada la amplitud es constante, pero en otros tipos de onda la amplitud puede variar.

Ciclo: Es una parte de la onda contenida en un período. En la figura anterior se tomó el período midiéndolo desde dos cimas o crestas consecutivas, pero puede comenzar a medirse desde otros puntos de la onda, mientras estén limitados por un período. Obsérvese en la siguiente figura como un ciclo abarca desde un punto hasta otro con el mismo valor (altura) y la misma pendiente (inclinación).

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/onda-senoidal2.JPG)

FIGURA 2: En una onda senoidal, un ciclo siempre transcurre durante un período. Lo importante es que el punto de inicio y el final estén a la misma altura.

Frecuencia: Es la cantidad de ciclos que ocurren en 1 segundo y se encuentra vinculada al argumento de la función seno: ωt. La frecuencia se denota como f y se mide en ciclos por segundo o Hertz (Hz) en Sistema Internacional.

La frecuencia es la cantidad inversa del período, por lo tanto:
f = 1/T
Mientras que la frecuencia f está relacionada con la frecuencia angular ω (pulsación) como:
ω = 2πf
La frecuencia angular se expresa en radianes /segundo en el Sistema Internacional, pero los radianes son adimensionales, así la frecuencia f y la frecuencia angular ω tienen las mismas dimensiones. Obsérvese que el producto ωt da radianes como resultado, debiendo tenerse en cuenta a la hora de utilizar la calculadora para obtener el valor de sen ωt.

Fase: Se corresponde al desplazamiento horizontal experimentado por la onda, respecto a un tiempo tomado como referencia. En la siguiente figura la onda verde está adelantada respecto a la roja en un tiempo td. Dos ondas sinusoidales están en fase cuando su frecuencia y su fase son las mismas. Si la fase difiere, entonces están en desfase. Las ondas de la figura 2 también están desfasadas.

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/onda-senoidal6.JPG)

FIGURA 3: Ondas senoidales desfasadas.

Generador de onda senoidal, hay muchas formas de obtener una señal en forma de onda senoidal. Las tomas de corriente caseras las proporcionan.

1) Aplicación de la ley de Faraday
Una forma bastante simple de obtener una señal senoidal es haciendo uso de la ley de Faraday. Esta indica que en un circuito cerrado de corriente, por ejemplo una espira, colocado en medio de un campo magnético, se genera una corriente inducida cuando el flujo de campo magnético a través de ella cambia en el tiempo. En consecuencia se genera igualmente un voltaje inducido o fem inducida. El flujo del campo magnético varía si la espira se hace girar con rapidez angular constante en medio del campo creado entre los polos N y S del imán mostrado en la figura.

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/onda-senoidal3.JPG)

FIGURA 4: Generador de onda basado en la Ley de inducción de Faraday.

La limitación de este dispositiva es la dependencia que tiene el voltaje obtenido con la frecuencia de rotación de la espira, como se verá con mayor detalle en el ejemplo 1 de la sección de ejemplos más adelante.

2) Oscilador de Wien
Otra forma de obtener una onda senoidal, esta vez con electrónica, es mediante el oscilador de Wien, que requiere de un amplificador operacional en conexión con resistencias y condensadores. De esta forma se obtienen ondas senoidales cuya frecuencia y amplitud el usuario puede modificar según su conveniencia, mediante el ajuste con interruptores. En la figura se muestra un generador de señales senoidales, con el cual también se pueden obtener otras formas de onda: triangulares y cuadradas entre otras.

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/onda-senoidal4.JPG)

FIGURA 5: Un generador de señales.

¿Cómo calcular las ondas senoidales?

Para realizar cálculos que involucren ondas senoidales se utiliza una calculadora científica que disponga de las funciones trigonométricas seno y coseno, así como sus inversas. Estas calculadoras disponen de modos para trabajar los ángulos ya sea en grados o en radianes, y es sencillo convertir de una forma a la otra. El factor de conversión es:

180 º = π radianes.

Según el modelo de la calculadora, deberá navegar mediante la tecla MODE para encontrar la opción DEGREE, que permite trabajar las funciones trigonométricas en grados, o bien la opción RAD, para trabajar directamente los ángulos en radianes.

Por ejemplo sen 25 º = 0.4226 con la calculadora puesta en modo DEG. Al convertir 25 º a radianes se obtiene 0.4363 radianes y sen 0.4363 rad = 0.425889 ≈ 0.4226.

El osciloscopio es un aparato que permite visualizar en una pantalla señales de voltajes y corrientes tanto alternas como directas. Tiene perillas para ajustar el tamaño de la señal sobre una cuadrícula como se muestra en la siguiente figura:

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/onda-senoidal5.JPG)

FIGURA 6: Una señal sinusoidal medida con un osciloscopio.

A través de la imagen que provee el osciloscopio y conociendo el ajuste de la sensibilidad en ambos ejes, es posible calcular los parámetros de la onda que se describieron anteriormente.

En la figura se muestra la señal de voltaje senoidal en función del tiempo, en la cual cada división del eje vertical vale 50 milivoltios, mientras que en el eje horizontal, cada división vale 10 microsegundos.

La amplitud pico a pico se encuentra contando las divisiones que abarca la onda en lo vertical, ayudándose con la flecha roja:

Se cuentan 5 divisiones con ayuda de la flecha roja, entonces el voltaje pico-pico es:

Vpp = 5 divisiones x 50 mV/división = 250 mV.

El voltaje pico Vp se mide a partir del eje horizontal, siendo de 125 mV.

Para encontrar el período se mide un ciclo, por ejemplo el delimitado por la flecha verde, que abarca 3.2 divisiones, entonces el período es:

T = 3.2 divisiones x 10 microsegundos/división = 32 microsegundos = 32 μs

### 4. DIAGRAMAS

Circuito Eléctrico

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/Figura%202.png)

FIGURA 7: Circuito eléctrico.

Circuito Eléctrico en Tinkercad

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/Circuito_Tinker.jpg)

FIGURA 8: Implementación del circuito en Tinkercad

Circuito Eléctrico en Proteus

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/Proteus%202.png)

FIGURA 9: Circuito eléctrico, realizado en el simulador Proteus.

Opciones del menu del Osiloscopio

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/Proteus%201.png)

FIGURA 10: Configuración del osiloscopio

Descripción del circuito

* En el diagrama se observa una fuentes independientes de voltaje AC, conectadas a al extremo izquierdo del circuito.
* Además, dentro del circuito se aprecia 2 resistencias medidas en KOhms.
* Se identifica la resistencia de carga RL que será el centro del analisis de la practica de laboratorio.
* Además se puede identificar 1 malla, por donde circulara una corriente.


### 5. LISTAS DE COMPONENTES
![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/LISTA_COMPOTENTES.jpg)

FIGURA 11: Descripción de los componenentes usados en el simulador Tinkercad.

### 6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

* Abrimos el sitio web "tinkercad" y creamos una cuenta.

* Hacemos clic izquierdo en "Circuits" y comenzamos con la práctica.

* Seleccionamos una placa de pruebas pequeñas (Protoboard).

* Se selecciona el suministro de energía que nos permite usar voltaje en ac, conectamos y colocamos el valor de la guía que es de 20V.

* Escogemos dos resistencias y las conectamos siguiendo el diagrama visto en el archivo de la práctica, que en este caso son de valores de 1 KOhm y 2.2 KOhm.

* Haciendo clic izquierdo en los pines del protoboard conectamos con cables las resistencias y pasamos corriente a donde hace falta.

* Colocamos un osciloscopio y conectamos en paralelo con la resistencia RL, el color negro es el negativo mientras que el color rojo es el positivo. 

* Realizamos las mediciones de volatje pedidas en la guía.

* Anotamos los valores obtenidos.

* Guardamos y salimos.

### 7. PREGUNTAS

##### 7.1 ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida? 

3.45 divisiones

##### 7.2 ¿En qué valor está posicionada la perilla VOLTS/DIV?

2 V

##### 7.3 ¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida? 

4 divisiones

##### 7.4 ¿En qué valor está posicionada la perilla TIME/DIV? 

0.1 ms

##### 7.5 ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?

Amplitud: 6.9 Voltios

Perioido: 0.0004 segundos

##### 7.6 Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida

Frecuencia: 2500 Hz

Frecuencia angular: 5000π rad/s

##### 7.7 Con el multímetro digital mida el voltaje de salida en RL:

4.86 V

##### 7.8 Compare el voltaje medido en el punto 7.5 y el obtenido en el punto 7.7 ¿Coinciden? ¿Por qué?

Los valores no coinciden dado que la medición del multimetro es el valor del voltaje rms o voltaje eficaz, mientras que en el osiloscopio el pico de la curva o la amplitud es el valor del voltaje pico, entonces para dichos valores coincidan se deberia hallar el valor del voltaje rms de la medicion del osiloscopio, se lo hace con una operación sencilla dividiendo el valor pico para raiz de dos, arrojandonos un valor de 4.8 V, mientras que el medido por el multimetro fue de 4.86 V, en ese caso los dos valores son tan cercanos que validan la fundamentacion teorica.

### 8. PORCENTAJE DE ERROR.

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/Error%20calculado.png)

TABLA 1: Porcentaje de error del voltaje eficaz y el valor pico en la resistencia RL.

### 9. CONCLUSIONES 

El tipo de onda más común en señal alterna es la onda senoidal:

* En el caso  de que la onda sea simétrica se  tendrá  que trabajar con la parte positiva.

* El osciloscopio va a tener mayor precisión que el multímetro debido a que el diseño de este fue creado para medir corrientes alternas.

* El servicio de energía provisto por las compañías que generan electricidad está en forma senoidal.

* Cuando el voltaje cambia la polaridad, la corriente cambia de dirección.

* Cuando voltaje   senoidal  es aplicado a un circuito  resistivo, resulta una corriente senoidal.

* El uso y la manipulación del osciloscopio va a ser muy requerida, ya que gracias a este instrumento podremos encontrar valores como el valor eficaz, el valor pico, la frecuencia de la onda, etc.

* El error no va a ser una excepción en esta práctica, debido a la menor exactitud que presenta el multimetro con respecto al osciloscopio.

* El valor eficaz va a poder definirse como una corriente rigurosamente constante.

### 10. RECOMENDACIONES 

* Utilizar diferntes simuladores para la realizacion de la practica, que permitan hacer uso de los aparatos requeridos, con una similitud a los de un laboratorio fisico.

*  Al momento de conectar el osiloscpio, colocar un terminal GND ya que en CA no existe una polaridad como tal, ademas revisar la teoria del osciloscopio para facilitar y acelerar el proceso.

* Se debe tener cuidado en la confusion al momento de trabajar en AC O DC ya que podrian provocar erros en las mediciones o en la resolución de las preguntas.

### 11. CRONOGRAMA

Actividades desarrolladas a lo largo de la practica de laboratorio.

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/Cronograma.png)


### 12. BIBLIOGRAFÍA 

Alexander, C, & Sadiku, M. (2006). Fundamentos de Circuitos Eléctricos. 3ra. Edición. Mc Graw Hill.

Boylestad, R. (2011). Introducción al Análisis de Circuitos.2da. Edición. Pearson.

Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
