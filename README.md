![image](https://user-images.githubusercontent.com/84390820/126413889-e0c11045-4b94-4a80-89f4-e7bbe829ac16.png)

# Informe Tarea

1. OBJETIVOS

General 

* Analizar las redes resistivas o capacitivas complejas en combinación de conexiones en serie y en paralelo, mediante métodos de análisis de corriente y voltaje de Kirchhoff, teoremas de superposición, el de Thévenin, el de Norton y el de máxima transferencia de potencia, en la cual se puedan aclarar los conceptos del comportamiento de la corriente, para entender las características de un circuito electrónico.

Específicos

* Estudiar los teoremas más útilies en el analísis de circuitos como Thévenin, Norton, superposicion, y el de Millman. 
* Conocer el coortamiento de los capacitores en un circuito eléctrico.
* Interpretar la relación entre voltaje y corriente en un circuito con elementos capacitivos. 

2. MARCO TEÓRICO

CAPÍTULO IX

![image](https://user-images.githubusercontent.com/85137398/126437428-726e9345-274b-42ec-add0-6e297677a101.png)

![image](https://user-images.githubusercontent.com/84390820/126432878-aaa82e88-883d-4484-b3fd-62d912a6be41.png)

CAPÍTULO X

![image](https://user-images.githubusercontent.com/85209614/126440199-47c919ab-f9f6-4e9c-aa09-533a7e1afcad.png)

![image](https://user-images.githubusercontent.com/85209614/126440281-e8bac75e-2254-4df5-886f-9532c7645148.png)

3. EXPLICACIÓN Y RESOLCIÓN DE EJERCICIOS O PROBLEMAS

EJERCICIOS CAPÍTULO IX

1.	Dado el circuito de la figura 9-75, use la superposicion para calcular la corriente a traves de cada uno de los resistores.

![image](https://user-images.githubusercontent.com/85137398/126437469-bf784a5e-5d95-4250-94e0-b0ff1fed586f.png)

Hacemos cortocircuito la funete  E2

RT= 200 OHM

E1= 20 V

IT = 20 / 200

IT = 100 mA  -> IT = I1 

Hacemos cortocircuito la funete E1

RT = 160 ohm 

E2 = 10 V

IT = 10/160

IT = 62.5 mA

I1 = 25 mA  I1 = - IR1

IR1 = - 25 mA

IR1 = IR1(1)+IR1(2)

IR1 = 100 + (-25) = 75 mA

IR2 = IR1

IR2 = 75 mA

IR3 = 87.5 mA

IR4 = 12.5 mA

3. Use la superposicion para encontrar el voltaje Va y la corriente I en el circuito de la figura 9-77.

![image](https://user-images.githubusercontent.com/85137398/126437593-5e116736-6ab5-4e01-8bed-9f47201b3b5d.png)

Req = 30 ohm || 60 ohm 

Req =  20 ohm

Va = -5 (20/30)

Va = -3.33 V

Req = 10 ohm || 30 ohm 

Req = 7.5 ohm 

Va (2) = 2 (7.5/67.5)

Va (2) = 0.22 V

Va = Va (1) + Va (2)

Va = -3.33 + 0.22

Va = -3.11

I1 = 0.166 A

I2 = 0.022 A

IT = I1 + I2

IT = 0.188 A

5. En el circuito de la figura 9-79, .cual debe ser el valor de la fuente de voltaje desconocida para asegurar que la corriente a traves de la carga sea IL5 mA, tal y como se muestra? Verifique los resultados mediante la superposicion.

![image](https://user-images.githubusercontent.com/85137398/126437690-d12f9af8-764e-4dd4-a19c-d58ea5b266c7.png)

V = IL * R

V = 5 mA * 5 Kohm

V = 25 V

E = (42.5 (v) – 462.5) / 20 V

E = (42.5 (25) – 462.5)/ 20 V

E = 30 V 

RT = 2.5 + 2.22

RT =  4.72 ohm

I = 30/4.72

I = 6.35 mA

I2 = 2.82 mA

IL = 5 mA

7. Encuentre el equivalente de Thevenin externo a RL en el circuito de la figura 9-81. Use el circuito equivalente para encontrar Vab.

![image](https://user-images.githubusercontent.com/85137398/126437755-90485a21-30b3-4b6b-ab20-3527d044b494.png)

Req = 40*10/40+10 = 8 ohm

VTH = 10/40+10 * 50 = 10 V

IL = 10 /20 = 0.5

Vab = RTH * RL/RT 

Vab = 10 * 30/50

Vab = 6V

9. Repita el problema 7 para el circuito de la figura 9-83.

![image](https://user-images.githubusercontent.com/85137398/126437803-86938237-0f3e-441c-88f7-ab155dbca395.png)

Req = 1.2 * 6.8 / 1.2+6.8 = 1.02 Kohm

RTH = 1.02 + 1 = 2.02

RT = 3.52

VTH = 1.2/6.8+1.8 * 8 = 1.2 V

Vab = RTH * RL / RT

Vab = 1.2 * 1.5/3.52

Vab = 0.51 V

11. Vea el circuito de la figura 9-85:

a Encuentre el circuito equivalente de Thévenin externo a RL.

b. Use el circuito equivalente para determinar Vab cuando RL =20 Ω y cuando RL = 50Ω.

RTH = R1 + R2

RTH = 40 OHM

VTH1 = 40 * 0.2

VTH1 = 8V

VTH 2 = 2.4 

VTH = 10.4 

I1 = 10.4 / 60 = 0.17 A

I2 = 10.4 / 90 = 0.11 A

17. Vea el circuito de la figura 9-91:

a. Encuentre el circuito equivalente de Thévenin externo a RL.

b. Use el circuito equivalente de Thévenin para encontrar la corriente I cuando RL= 0, 10 kΩ y 50 kΩ.

![image](https://user-images.githubusercontent.com/85137398/126437921-0c7b1018-26f7-40da-9be1-f79a527c635a.png)

Req1 = 15+25+20 = 60 

RTH = 60 ohm

VTH = Va – Vb

Va = 3 * 25

Va = 75 V

Vb = 5 * 20 

Vb = 100 V

I1 = 25/60 = 0.41 mA

I2 = VTH /Req1 = 25/100 = 0.22 mA

19. Repita el problema 17 para el circuito de la figura 9-93.

![image](https://user-images.githubusercontent.com/85137398/126437969-f45576c8-ce38-4b69-ae87-5a0e75db59fc.png)

Req = 10 * 16/10+16 = 6.15 ohm

RTH = Req + 24

RTH = 6.15 + 24

RTH = 30.15 Kohm 

IT 48 / 30.15 = 1.59

I1 = 1.59 * 24 = 38.20 V

VR50 = 9.77 * 50 / 80.15 = 6.09 V

21. Encuentre el circuito equivalente de Thévenin de la red externa a las ramas que se indican, como se muestra en la figura 9-95.

![image](https://user-images.githubusercontent.com/85137398/126438082-7fd8d97c-6686-45bb-af81-538360a6c094.png)

Req = 10*16/10+16 = 6.15 ohm

Req = 8 + 4 = 12 ohm

RTH = 12*18/12+18 = 7.2

VS = 0.8 * 12 = 9.6 V

VTH = Va – Vb 

VTH = 9.6 – 5

VTH = 4.5 V

27. Repita el problema 25 para el circuito de la figura 9-83.

![image](https://user-images.githubusercontent.com/84390820/126433497-f5feebf9-6d41-4e1a-919d-58b34866ebc0.png)

Req1=1.2x6.8/(1.2+6.8)= 1.02 KΩ

RTH = RN = 1.02KΩ + 1KΩ = 2.02 KΩ

RT = (1*12)/(1+12)+6.8

RT = 0.54+6.8

RT = 7.34KΩ

I = E/((R2∥R3)+R1)

I = 8/7.34 = 1.08 mA

I1=1.2/(1.2+1)*(1.08mA)

I1 = 0.594mA

IN = 0.594 mA

IL = 2.02Ω/(2.02+1.5) (0.594mA)

IL = 0.341 mA

29. Vea el circuito de la figura 9-85:

a. Encuentre el circuito equivalente de Norton externo a RL.

b. Use el circuito equivalente para determinar IL cuando RL=20 kΩ y cuando RL= 50 kΩ.

![image](https://user-images.githubusercontent.com/84390820/126433677-108ac7ae-d4bc-4a62-be52-995a823fa13c.png)

RN = (R2∥0)+R1

RN = 0+16= 16Ω

RT = (R1∥R2)

RT = (16*24)/(16+24)=9.6Ω

I = E/((R1∥R2) )

I = 2.4/9.6=0.25A

I2 = R2/(R2+R1)*I

I2 = 24/(24+16)*(0.25A)

I2 = Iab1 = 0.15A
 
Iab2 = R2/(R2+0)*I

Iab2 = I = 0.2A

IN = Iab1+Iab2

IN = 0.15+0.2

IN = 0.35A

RL = 20Ω
RL = 50Ω

PARA RL=20Ω

IL=IN*RN/(RN+RL)

IL=0.35*16/(16+20)

IL=0.156A

PARA RL=50Ω

IL=IN*RN/(RN+RL)

IL=0.35*16/(16+50)

IL=0.085A

31. a. Encuentre el circuito equivalente de Norton externo a las terminales que se indican en la figura 9-87.

b. Convierta el circuito equivalente de Thévenin del problema 13 en su equivalente de Norton.

![image](https://user-images.githubusercontent.com/84390820/126433949-5a34aae5-caa2-4e58-b05d-698b7a4a8a54.png)

RN = (20∥60)+35

RN = (20*60)/(20+60)+35

RN = 50Ω


RT = (60∥35)+20

RT = (60*35)/(60+35)+20

RT = 42.11Ω

I = 100/((60∥35)+20)=100/42.11=2.375A

IN = 60/((60+35) )*2.357A=1.50A

RN = RTH = 50Ω

ETH = 60/((60+20) )*100V

ETH = 75 V

I = ETH/RTH = 75/50 = 1.50A

33. Repita el problema 31 para el circuito de la figura 9-91.

![image](https://user-images.githubusercontent.com/84390820/126434270-448616fa-24f8-4943-b5d7-10e6dd3fb1ae.png)

RN = 15+25+20

RN = 60KΩ

Iab(1) = 25/(25+(15+20) )*(-3)

Iab(1) = -1.25mA

Iab(2) = 20/(20+(15+25) )*(5)

Iab(2) = 1.67mA

IN = Iab(1)+Iab(2)

IN = -1.25+1.67

IN = 0.417mA

RN = RTH = 60 KΩ

ETH(1)=-3*(25)

ETH(1)=-75V

ETH(2) = 5*(20)

ETH(2) = 100V

ETH = ETH(1)+ETH(2)

ETH = -75+100 = 25V

IN = ETH/RTH = 25/60 = 0.417mA

35. Repita el problema 31 para el circuito de la figura 9-95.

![image](https://user-images.githubusercontent.com/84390820/126434427-6fb4b986-ca4f-4954-afd2-77524d71b290.png)

RN = [(16∥16)+4]∥18

RN = [(16*16)/(16+16)+4]∥18

RN = 12∥18

RN = (12*18)/(12+18)

RN = 7.2Ω

(18∥0)=0

(4∥16)+16

(4*16)/(4+16)+16=19.2Ω

I = 8/16.2 = 0.416 A


Iab(1)=16/(16+4)*(0.416)

Iab(1)=0.33A

Iab(2)=7.2/(7.2+0)*(0.3)

Iab(2) = 0.3A

IN = Iab(1)+Iab(2)

IN = 0.33+0.3

IN = 0.633A

RN = RTH = 7.2Ω

(V1+8)/16+(V1-0)/16+(V1-V2)/4=0

(V1+8)+(V1)+4(V1-V2) = 0

6V1-4V2 = -8

(V2+V1)/4+(V2-0)/18 = 0

9(V2-V1)+2V2 = 0

11V2-9V1 = 0

V1 = -2.83V

V2 = -2.4V

ETH(2) = (300mA)*7.2

ETH(2) = 2.16V

ETH = ETH(1)+ETH(2)

ETH = 2.4V+2.16V

ETH = 4.56V

IN = ETH/RTH=4.56V/7.2 = 0.633mA

9-4 Teorema de transferencia de máxima potencia

37. a. Para el circuito de la figura 9-91 determine el valor de RL para que se suministre la máxima potencia a la carga.

b. Calcule el valor de la máxima potencia que puede ser suministrada a la carga.

c. Dibuje la curva de potencia contra resistencia cuando RL se ajusta de 0Ω a 50 kΩ en incrementos de 5 kΩ.

![image](https://user-images.githubusercontent.com/84390820/126434819-5dbe89c4-daf5-40db-a34f-580383548c14.png)

RTH = 15+25+20

RTH = 60KΩ

ETH(1) =-(3)*25

ETH(1) = -75V

ETH(2) = (5)*20

ETH(2) = 100V

ETH = ETH(1)+ETH(2)

ETH = -7.5V+100V

ETH = 25V

RL = RTH = 60KΩ

PL=〖ETH〗^2/4RTH

PL=〖(25V)〗^2/(4(60)) = 2.60mW

39. a. Para el circuito de la figura 9-99 encuentre el valor de R de manera que RL = RTh.

b. Calcule la máxima potencia disipada por RL.

![image](https://user-images.githubusercontent.com/84390820/126435037-0e04093f-ff4d-49f0-b52b-48be84385d45.png)

RTH=[(600∥R)+20]

RTH=[(600*R)/(600+R)+20]

RTH=RL

RTH = 50

50=(600*R)/(600+R)+20

R*570=18

R=31.58Ω

ETH = 31.58/(31.58+600)*(25)
ETH = 1.25 V

Pmax =〖ETH〗^2/4RTH
Pmax =〖(1.25V)〗^2/(4(50)) = 7.81mW

41. a. Para el circuito de la figura 9-101 determine los valores de R1 y R2 de manera que la carga de 32 kΩ reciba la máxima potencia.

b. Calcule la máxima potencia suministrada por RL.

![image](https://user-images.githubusercontent.com/84390820/126435189-2d6e6c4f-e7ff-4691-a176-9e685929ccf9.png)

R1+R2 = 200Ω

RL = RTH

RTH = 32KΩ

RTH = (R1∥R2)

32 = (R1*R2)/(R1+R2)

32R1+32R2 = R1*R2

32(R1+(200-R1)) = R1*(200-R1)

6400MΩ-(200kΩ)R1+〖R1〗^2 = 0

R1=160KΩ

R1+R2=200

160+R2=200

R2=40KΩ

ETH=40/(40+160)*(25)

ETH=5V

Pmax=〖ETH〗^2/4RTH

Pmax=〖(5V)〗^2/(4(32))=19.5mW

9-5 Teorema de sustitución

43. Si la porción indicada del circuito de la figura 9-102 se reemplaza con una fuente de voltaje y un resistor en serie de 50 _, determine la magnitud y polaridad la fuente de 

voltaje resultante.

![image](https://user-images.githubusercontent.com/84390820/126435435-7c9ea3de-1ce9-470b-9436-5d155436690a.png)

I = 6.25/200 = 31.25mA

31.25 = E1/50

E1 = 1.5625V

9-6 Teorema de Millman

45. Use el Teorema de Millman para encontrar la corriente y la potencia disipada por RL en el circuito de la figura 9-103.

![image](https://user-images.githubusercontent.com/84390820/126435605-333756fd-5215-440e-a5a5-f7f24405c448.png)

I1=20V/30Ω=0.667A

I2=10V/20Ω=0.667A

Ie1=∑_(x=0)^n〖Ix=I1+I2=E1/R1+E2/R2=0.667-0.5=0.167〗

Req=(R1*R2)/(R1+R2)=(30*20)/(30+20)=12Ω

V=(12)(0.167)=2.004V

I=2.004V/37Ω=0.054A

PL=(0.054)^2 (25) = 0.073 W

47. Repita el problema 45 para el circuito de la figura 9-105.

![image](https://user-images.githubusercontent.com/84390820/126435683-8609436c-6817-4d9b-9769-42a9ef258c85.png)

Req = ((5.1)(4.7)(5.6))/((5.1)(4.7)+(5.1)(5.6)+(4.7)(5.6))
Req = 134.23/78.85=1.702kΩ

I1 = 10V/5.1Ω = 1.9mA

I2 = 5V/4.7Ω = 1.06mA

I3 = 6V/5.6Ω = 1.07mA

Ix=1.96+1.06-1.07=1.95mA

Ex=(1.95)(1.702)=3.31V

VL=10/11.702*3.31=2.83V

IL=2.83V/10KΩ=0.283mA

PL=(0.283)^2 (10)=0.807W

9-7 Teorema de reciprocidad

49. a. Determine la corriente I en el circuito de la figura 9-107.

b. Demuestre que la reciprocidad se aplica en el circuito dado.

![image](https://user-images.githubusercontent.com/84390820/126435742-e1d8e188-664a-4cf6-964c-34b79d259bbe.png)


RTH=(30+22.5)∥(60)∥(30)

RTH=(52.5)(60)(30)/((52.5)(60)+(52.5)(30)+(30)(60) )

RTH=94500/6525=17.58Ω

VTH=Vab=28/58*24V=11.58V

VTH=30/52.5*11.58V=6.62V

I=11.59/((1.48+10) )=0.24A

I=6.62V/17.58Ω=0.24A

51. a. Determine el voltaje V en el circuito de la figura 9-109.

b. Demuestre que la reciprocidad se aplica en el circuito dado.

![image](https://user-images.githubusercontent.com/84390820/126437004-a543c55a-86f0-479e-9150-ad86ad76b272.png)

I*RT3 = VT = 48V

VRT3 = V20 Ω = VRT2

VRT = VRT2*37.5/80 = 22.5V

VRT = Vab = 22.5V


RT = ((62.5)(50)(150))/((62.5)(50)+(62.5)(150)+(50)(150))

RT = 62.5Ω

VT = VRT = 3(27.78) = 70.31V

V20Ω = Vab = 70.31*20/62.5 = 22.5V

EJERCICIOS CAPÍTULO X

1. para la Figura 10-31, determine la carga en el capacitor, su capacitancia o el voltaje en él, según se aplique a cada uno de los siguientes incisos:

![image](https://user-images.githubusercontent.com/85209614/126440727-df234b57-d639-41a3-ac06-bd3ae4ecdcc2.png)

Sabemos que Q = CE

a) E = 40V , C = 20uF

Q = CV

Q = (20uF)(40uF)

Q = 800uC

b) V = 500V , C = 1000uC

C = Q / V

C = 1000uC / 500V

C = 2uF

c) V = 200V , C = 500nF

Q = C V

Q = (500nF)(200V)

Q = 100uC

d) Q = 3*10^-4 , C = 40uF

Q = C E

3*10^-4 = (10*10^-6F)E

E = 3*10^-4C / 10*10^-6F

E = 30V

e) Q = 6mC , C = 40uF

V = Q / C

V = 6mC / 40uF

V = 150V

f) V = 1200V , Q = 1.8mC

C = Q / V

C = 1.8 mC / 1200V

C = 1.5uF

3. La carga en un capacitor de 50μF es de 10 × 10^(-3) C. ¿Cuál es la diferencia de potencial entre sus terminales?

E = Q / C

E = 10*10^-3C / 50uF

E = 200V

5. Se carga un capacitor 5μF con 150 V. Su compañero de laboratorio momentáneamente pone un resistor a traves de sus terminales y drena suficiente carga para que el voltaje caiga a 84 V. ¿Cuál es la carga final del capacitor?

Q = C V

Q = (5uF)(84V)

Q = 420uC

7. Un capacitor de placas paralelas con un dieléctrico de mica tiene las siguientes dimensiones 1 cm x 1.5 cm con una separación de 0.1 mm. ¿Cuál es su capacitancia?

C = E0 * A / d

C = 8.854*10^-12 * (0.00785m^2) / (0.1mm)

C = 0.69*10^-9F

C = 0.69nF

9. La capacitancia de un capacitor lleno de aceite es de 200 pF. Si la separación entre las placas es de 0.1 mm. ¿cuál es el área de las placas?

C = E0 * A / d

C = 8.854*10^-12 * (0.00785m^2) / (0.1mm)

C = 0.69*10^-9F

C = 0.69nF

11. Un capacitor con un dieléctrico de Teflón tiene una capacitancia de 33 _F. Un segundo capacitor con dimensiones físicas idénticas, pero con un dieléctrico de mylar lleva una carga de  55×10^(-4)C. ¿Cuál es su voltaje?

![image](https://user-images.githubusercontent.com/85209614/126443639-422d87dc-e278-4b17-82f0-0ec3b06d33a6.png)

![image](https://user-images.githubusercontent.com/85209614/126443651-2c387401-079a-4437-9bad-6e2192716c35.png)

13. 	a. ¿Cuál es la intensidad del campo eléctrico E a una distancia de 1 cm de una carga de 100 mC en aceite? 
b. ¿Cuál es E al doble de la distancia?

Q=100 mC≈100*10^-3C

a.  E=〖9*10〗^9 ((100*10^(-3))/(1*10^(-2) )^2 )

E=3.214*〖10〗^12  (N/C)

b.  d=1cm*2=2cm≈2*10^(-2)

E=〖9*10〗^9 ((100*10^(-3))/(2*10^(-2) )^2 )

E=2.25*〖10〗^12  (N/C)

15. Un capacitor con aire como dieléctrico tiene un espaciamiento de placas de 1.5 mm. ¿Cuánto voltaje se le puede aplicar antes de que ocurra una ruptura?

V=3 kV/mm (1,5 mm)=4,5 kV

17. Un capacitor con un dieléctrico de mica sufre una ruptura cuando se le aplican E volts. La mica se remueve y el espacio entre las placas se duplica. Si la ruptura ahora ocurre a 500 V, ¿cuál es el valor de E?

d=V/∈

d=(500 V)/(40*10^6  V/m)

d=12.5*10^(-6)  m

E=V/d

E=(500 V)/(12.5*10^(-6)  m)

E=4*10^5  V/m

19. La figura 10-32 muestra varios espaciamientos, entre ellos se incluye un capacitor de placas paralelas, un conjunto de pequeños puntos esféricos y un par de puntos afilados. Todos los espaciamientos miden lo mismo. Conforme el voltaje se incremente, ¿qué espaciamiento sufre ruptura en cada caso?

![image](https://user-images.githubusercontent.com/85209614/126444792-93b1074c-e775-45e3-b075-34eedf2491d8.png)

a) Puntos

b) Esferas

c) Puntos

23. ¿Cuál es la capacitancia equivalente de 10, 12, 22, 33 µF conectados en paralelo? 

CT=10+12+22+33=77 µF

25. Repita el problema 23 si los capacitores están conectados en serie. 

CT=1/(1/10+1/12+1/22+1/33)=3,86 µF
