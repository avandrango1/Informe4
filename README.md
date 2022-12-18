# Informe4
OBJETIVOS

Identificar circuitos en serie y circuitos en paralelo.

Analizar las fórmulas y componentes de circuitos serie y en paralelo.

Identificar los distintos métodos para resolver circuitos

MARCO TEÓRICO 

![image](https://user-images.githubusercontent.com/117759439/208227062-e6e6954a-3d32-47d0-896b-bf7168c5122d.png)
![image](https://user-images.githubusercontent.com/117759439/208269786-3cc31bf6-9c07-4764-b5c2-45a07af2d626.png)


RESOLUCIÓN DE EJERCICIOS 

CAPITULO 7 

SECCIÓN 7-1 Identificación de relaciones en serie-paralelo

1. Visualice y trace las siguientes combinaciones en serie-paralelo:

a)R1 en serie con la combinación en paralelo de R2 y R3
![image](https://user-images.githubusercontent.com/117759439/208213166-7e8a852a-79f3-4d70-a7fc-8dd3598084ae.png)
b)R1 en paralelo con la combinación en serie de R2 y R3
![image](https://user-images.githubusercontent.com/117759439/208213188-e4f920a4-c726-42a3-958e-a73d29c7e236.png)
c)R1 en paralelo con una rama que contiene R2 en serie con una combinación en paralelo de otros cuatro resistores
![image](https://user-images.githubusercontent.com/117759439/208213207-36a3ea0c-d85e-4efd-8bec-d55234a15218.png)

3. En cada circuito de la figura 7-62, identifique las relaciones serie-paralelo de los resistores vistas desde la fuente

a)R1 y R4 están es serie con la combinación en paralelo  de R2 y R3

b)R1 está en serie con la combinación en paralelo de R2, R3 y R4

c)La combinación en paralelo de R2 y R3 está en serie con la combinación en paralelo R4 y R5. Todo esto está en paralelo con R1.

5.Trace el diagrama esquemático de la configuración de la tarjeta de circuito impreso mostrada en la figura 7-64 indicando valores de resistor, e identifique las relaciones en serie-paralelo

![image](https://user-images.githubusercontent.com/117759439/208213413-1ff06dde-7274-498b-a1db-440317d42efc.png)

7.Configure una tarjeta de circuito impreso para el circuito de la figura 7-63(c). La batería tiene que conectarse externa a la tarjeta

![image](https://user-images.githubusercontent.com/117759439/208213436-b9a61408-103d-44b6-b092-4c7a474dbea4.png)

SECCIÓN 7-2 Análisis de circuitos resistivos en serie.paralelo

9.Para cada uno de los circuitos mostrados en la figura 7-62, determine la resistencia total presentada a la fuente

Para el circuito a la resistencia total es 133 ohm 

Para el circuito b la resistencia total es 779 ohm

Para el circuito c la resistencia total es 852 ohm 

11.Determine la corriente a través de cada resistor del circuito de la figura 7-62; calcule en seguida cada caída de voltaje

a)I1=11.3mA=I4
I2=5.64mA=I3
V1=633mV
V2=564mV=V3
V4=305mV

b)I1=3.85mA 
I2=563uA
I3=1.16mA
I4=2.13mA
V1=2.62V
V2=383mV=V3=V4

c)I1=5mA
I2=303uA
I3=586uA
I4=313uA
I5=558uA
V1=5V
V2=1.88V=V3
V4=3.13V=V5

13.Encuentre RT para todas las combinaciones de los interruptores de la figura 7-66

SW1 cerrado, SW2 abierto: 220 ohm 
SW1 cerrado, SW2 cerrado: 200 ohm 
SW1 abierto, SW2 abierto: 320 ohm 
SW1 abierto, SW2 cerrado: 300 ohm 

15.Determine el voltaje en cada nodo con respecto a tierra en la figura 7-67

Va=100 V
Vb=61.5 V 
Vc=15.7 V 
Vd=7,87 V 

17.En la figura 7-68,¿Cómo determinaría el voltaje entre los extremos de R2 por medición sin conectar directamente un medidor entre los extremos del resistor?

Midiendo el voltaje en A con respecto a tierra y el voltaje en B con respecto a tierra. La diferencia es VR2

19.Determine la resistencia del circuito mostrado en la figura 7-68 como se ve desde la fuente de voltaje.

La resistencia del circuito es 303k ohm 

21.Determine el valor de R2 en la figura 7-70; Encuentre la potencia en R2

a)El valor de la R2 es 110k ohm 
b)La potencia en R2 es 110mW

23.Encuentre la resistencia entre cada uno de los siguientes juegos de nodos (AB,BC Y CD)

Rab=1.32k ohm 
Rbc=1.32k ohm 
Rcd=0 ohm 

SECCIÓN 7-3 Divisores de voltaje con cargas resistivas

25.Un divisor de voltaje está compuesto por dos resistores de 56k ohm y una fuente de 15V. Calcule el voltaje de salida sin carga.¿Cuál es el voltaje de salida si se conecta un resistor con carga de 1M ohm a la salida?

El voltaje sin carga es 7.5V 
El voltaje con carga es 7.29V

27.¿Cuál de dos cargas, una de 10k ohm y otra de 47k ohm, provocará una disminución más pequeña en el voltaje de salida de un divisor de voltaje dado?

La carga de 47k ohm provoca una disminución más pequeña 

29.Determine en 7-74 el voltaje de salida con una carga de 33k ohm conectada entre A y B

El voltaje es de 8.77 V 

31.Determine los valores de resistencia para un divisor de voltaje que debe satisfacer las siguientes especificaciones: la corriente extraída de la fuente sin carga no debe exceder de 5mA; el voltaje de fuente tiene que ser de 10V, y las salidas requeridas deber ser de 5 y 2.5V. Trace el circuito. Determine el efecto en los voltaje de salida si se conecta una carga de 1k ohm a cada  toma, una a la vez

R1=1000 ohm 
R2=500 ohm= R3
toma inferior cargada: V inferior=1.82V -> V superior=4.55 V 
toma superior cargada: V inferior=1.67V -> V superior=3.33 V 

33.La figura 7-76 muestra un circuito polizador de cd para amplificador de transistor de efecto de campo. La polarización es un método común empleado para establecer ciertos niveles de voltaje de cd para la operación apropiada de un amplificador. a)Encuentre VG y vS   b)Determine I1,I2,IDeIS c)Encuentre VDS y vdg 

a) VG=1.75 V -->  Vs=3.25 V
b)I1=I2=6.48u A  --> ID=IS=2.17m A
c)VDS=2.55 V  --> VDG=4.05 V 

SECCIÓN 7–4 Efecto de carga de un voltímetro

35. ¿En cuál de los siguientes intervalos de voltaje presentará un voltímetro la mínima carga que haya en un circuito?
(a) 1 V 
(b) 10 V 
(c) 100 V 
(d) 1000 V

Presenta la carga minima en 1000 V 

37. El voltímetro descrito en el problema 36 se utiliza para medir voltaje entre los extremos de R4 en la figura 7-62(a).
(a) ¿Qué intervalo se deberá utilizar? En un intervalo de 0.5
(b) ¿En cuánto se reduce el voltaje medido por el medidor con respecto al voltaje real? Se reduce en aproximadamente 1mV 

SECCIÓN 7–5 Redes en escalera

39. Para el circuito mostrado en la figura 7-77, calcule:
(a) La resistencia total entre las terminales de la fuente --> 271 ohm  
(b) La corriente total suministrada por la fuente --> 221mA 
(c) La corriente a través del resistor de 910 ohm --> 58.7mA 
(d) El voltaje desde el punto A hasta el punto B --> 12V

41. Determine la resistencia total entre las terminales A y B de la red en escalera de la figura 7-79. Asimismo, calcule la corriente en cada rama con 10 V entre A y B.


43. Determine IT y VSALIDA en la figura 7-80.

971 mA 

45. Repita el problema 44 para las siguientes condiciones
(a) SW3 y SW4 conectados a 112 V, SW1 y SW2 a tierra --> 9V
(b) SW3 y SW1 conectados a 112 V, SW2 y SW4 a tierra --> 3.75 V 
(c) Todos los interruptores conectados a 112 V --> 11.25

SECCIÓN 7–6 El puente Wheatstone

47. Una celda de carga tiene cuatro medidores de deformación idénticos con una resistencia ilimitada de
120,000 Æ para cada medidor (un valor estándar). Cuando se agrega una carga, los medidores a tensión incrementan su resistencia en 60 mΩ, a 120,060 Ω, y los medidores a compresión disminuyen su resistencia en 60 mΩ, a 119.940 Ω, como se muestra en la figura 7-82. ¿Cuál es el voltaje de salida con carga?

El voltaje de salida con carga es 6mV 

SECCIÓN 7–7 Localización de fallas

49. ¿Es correcta la lectura del voltímetro de la figura 7-84?

No, ya que deberia ser una medida de 4.39 V 

51. En la figura 7-86 hay una falla. Con base en las indicaciones del medidor, determine cuál es la falla.

La resistencia R3 de 2.2k ohm está abierto 

53. Revise las lecturas de los medidores de la figura 7-88 y localice cualquier falla que pudiera existir.

La resistencia R4 de 3.3k ohm está abierto

CAPITULO 8 

SECCIÓN 8–3 Conversiones de fuente

1. Una fuente de voltaje tiene los valores VS 5 300 V y RS 5 50 Æ. Conviértala en una fuente de corriente equivalente.

Is= 6 A
Rs= 50 ohm 

3. Una batería tipo D nueva tiene entre sus terminales un voltaje de 1.6 V y puede suministrar hasta 8.0A a un cortocircuito durante muy poco tiempo. ¿Cuál es la resistencia interna de la batería?

La resistencia interna es 200m ohm 

5. Una fuente de corriente tiene una IS de 600 mA y una RS de 1.2 kohm. Conviértala en una fuente de voltaje equivalente.

Vs=720 V 
Rs=1.2k ohm 

SECCIÓN 8–4 El teorema de superposición

7. Con el método de superposición, encuentre la corriente a través de R5 en la figura 8-69.

La corriente es de 845uA

9. Con el teorema de superposición, determine la corriente a través de R3 en la figura 8-70.

La corriente es de 1.6mA 

11. En la figura 8-72 se muestra un circuito comparador. El voltaje de entrada, VENTRADA, se compara con
el voltaje de referencia, VREFERENCIA, y se genera una salida negativa si VREFERENCIA > VENTRADA; de lo contrario es positiva. El comparador no carga a una u otra entrada. Si R2 es de 1.0 kΩ, ¿cuál es el intervalo del voltaje de referencia?

Voltaje máximo: 3.72 V 
Voltaje minimo:1.32 V 

13. Determine el voltaje del punto A al punto B en la figura 8-73.

El voltaje del punto A al B es 90.7 V 

15. La figura 8-75 muestra dos redes en escalera. Determine la corriente producida por cada una de las baterías cuando se conectan las terminales A (A a A) y las terminales B (B a B).

Is1=2.28mA 
Is2=1.35mA 

SECCIÓN 8–5 Teorema de Thevenin

17. Con el teorema de Thevenin, determine la corriente a través de la carga RL en la figura 8-77.

La corriente es 116uA

19. Determine el equivalente de Thevenin para el circuito externo al amplificador de la figura 8-79.

R=88.6 OHM 
V=1.09 V 

21. Determine la corriente a través del resistor de carga en el circuito puente de la figura 8-81.

La corriente es de 100uA

SECCIÓN 8–6 Teorema de Norton

23. Para cada uno de los circuitos mostrados en la figura 8-76, determine el equivalente Norton visto por RL.

a)I=110mA --> R=76.7 ohm 
b)I=11.1mA --> R=73 ohm 
c)I=50uA  -->  R=35.9k ohm 
d)I=68.8mA --> R=1.3k ohm 

25. Con el teorema de Norton, determine el voltaje entre los extremos de R5 en la figura 8-78.

El voltaje es de 17.9 V

27. Determine el circuito equivalente Norton para el puente que aparece en la figura 8-81 sin RL.

I=953uA 
R=1175 ohm 

29. Aplique el teorema de Norton al circuito de la figura 8-84.

I=-48.2mA 
R=56.9 ohm 

SECCIÓN 8–7 Teorema de transferencia de potencia máxima

31. En el circuito de la figura 8-86, determine el valor de RL para transferencia de potencia máxima.

El valor de R para la P máx es 11.1 ohmm 

33. ¿Cuáles son los valores de R4 y RTH cuando la potencia máxima se transfiere de la fuente thevenizada a la red en configuración de escalera de la figura 8-87?

Rt= 48 ohm 
R4= 160 ohm

SECCIÓN 8–8 Conversiones delta a Y (D a Y) y Y a D

35. En la figura 8-89, convierta cada red Y en una red delta.

a)RA=39.8 ohm  -->  RB=73 ohm  -->  RC=48.7 ohm 
b)RA=21.2k ohm -->  RB=10.3k ohm --> RC=14.9k ohm 

VIDEO 
https://youtu.be/DXsMjjFqXU4

CONCLUSIONES

Al finalizar el informe ya podemos identificar circuitos en serie y circuitos en paralelo 

Tambien identificamos las propiedades y elementos de cada elemento

Identificamos la importancia de cada método y como es su resolución.
