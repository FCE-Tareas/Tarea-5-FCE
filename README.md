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

![image](https://user-images.githubusercontent.com/84390820/126432878-aaa82e88-883d-4484-b3fd-62d912a6be41.png)

3. EXPLICACIÓN Y RESOLCIÓN DE EJERCICIOS O PROBLEMAS

EJERCICIOS CAPÍTULO IX

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

RN=(20∥60)+35
RN=(20*60)/(20+60)+35
RN=50Ω


RT=(60∥35)+20
RT=(60*35)/(60+35)+20
RT=42.11Ω

I=100/((60∥35)+20)=100/42.11=2.375A
IN=60/((60+35) )*2.357A=1.50A

RN=RTH=50Ω

ETH=60/((60+20) )*100V
ETH=75V

I=ETH/RTH=75/50=1.50A


