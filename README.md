#   Universidad de las Fuerzas Armadas  "ESPE"

Carrera: Mecatrónica  
 
Materia: Fundamentos de los Circuitos Eléctricos.

![image](https://user-images.githubusercontent.com/116817673/201196227-89e9c919-809a-445a-9500-b0bc8ed32fe5.png)          


LAB 1

Integrantes: Joel Oña, Cristian Toaquiza, Dylan Taco.

NRC: 10063

Sangolquí, 15 de noviembre del 2022 


                                                            PRACTICA-No.-1-LEYES-DE-KIRCHHOFF

# 1. OBJETIVOS

OBJETIVO GENERAL

Conocer la ley de Kirchhoff, asi como hallar el voltaje, corriente y resistencia mediante la ley mencionada para lograr entender de mejor manera dichos conceptos y aplicarlos en cualquier campo que se requieran.

OBJETIVOS ESPECÍFICOS

•	Conocer las diferentes formas para encontrar voltaje, intensidad y resistencia mediante la ley de Kirchhoff.

•	Reconocer los diferentes instrumentos de medida que tenemos en el laboratorio asi como el funcionamiento del mismo.

•	Saber que es el voltaje, corriente y resistencia y su relacion con las leyes de Kirchhoff.

•	Resolver el laboratorio afin del perfecto conocimiento y utilizacion de la ley de Kirchhoff en los circuitos, para poder llevar lo teorico a lo practico.

# 2. MARCO TEORICO

![image](https://user-images.githubusercontent.com/116687152/201769490-679022b9-d6cc-41d3-a793-f71e8240fc78.png)


# 3. EXPLICACIÓN DEL PROCEDIMIENTO

MATERIAL Y EQUIPO REQUERIDO

![image](https://user-images.githubusercontent.com/116687152/201196258-347d85dc-2fba-4a2d-b951-b9b3393f8c5c.png)

Descripción de equipo y material

Protoboard: Un protoboard es una placa de pruebas se pueden insertar componentes electrónicos y cables en este se puede ensamblar un circuito sin la necesidad de soldar ningún componente.

Resistores: Una resistencia se utiliza para introducir una resistencia eléctrica determinada entre dos puntos de un circuito eléctrico.

Fuente de voltaje: El elemento activo que puede transferir energía se llama fuente de voltaje, y hay dos tipos, uno puede generar una diferencia de potencial entre sus dos extremos y el otro proporciona corriente para que funcionen otros circuitos.

Multímetro digital: Un multímetro digital es una herramienta que sirve para medir dos o más valores eléctricos se puede medir corriente, resistencias y voltaje.

Armado del circuito

a) Colocamos una energia de 5 voltios

![image](https://user-images.githubusercontent.com/116687152/201197198-ca390d78-2d40-47dd-9fb8-a87f06cd5bc0.png)

b) Buscamos los resistores con su codigo de colores.

![image](https://user-images.githubusercontent.com/116687152/201197581-63e3a8c6-d298-4c62-83ff-7753e656deed.png)

c) Conectamos el circuito

![image](https://user-images.githubusercontent.com/116817673/201891812-c115cfd8-75e1-4ba0-8076-c702448e69f3.png)

Procedemos a medir los voltajes

![image](https://user-images.githubusercontent.com/116817673/201891914-f75153dc-70b0-4359-ad53-e4ce5993c50d.png)

Procedemos a medir la corriente

![image](https://user-images.githubusercontent.com/116817673/201892050-c4ac3e8c-0447-459b-99c5-9895c83f2bdd.png)

A continuación calculamos los valores teóricos de corriente y voltaje de los elementos pasivos, para completar la siguiente tabla:

Aplicamos la Ley de Mallas de Kirchhoff

Planteamos la ecuación de la Malla de I1

1kΩ· I1 + 3.9kΩ· I1 + 1.8kΩ· I1 - 3.9kΩ· I2 = 5

Planteamos la ecuación de la Malla de I2

2.2kΩ· I2 + 2.2kΩ· I2 + 3.9kΩ· I2 - 3.9kΩ· I1 = 0

Unimos terminos semejantes 

6.7kΩ· I1 - 3.9kΩ· I2 = 5

8.3kΩ· I2 -3.9kΩ· I1 = 0

Resolver el sistema de ecuaciones por método de reducción de Gauss Jordan, obteniendo como resultado:

I1 = 1.027 mA

I2 = 0.4826 mA

Para encontrar I3 se despeja de la ecuación: I1 = I2 + I3

Nos queda que I3 = I1 – I2 

I3 = 1.027 - 0.4826 

Ahora aplicamos la Ley de Ohm para obtener los voltajes

Voltaje R1: VR1 = I1·R1 = 1.027 mA·1kΩ = 1.027 V

Voltaje R2: VR2 = I3·R2 = 0.5444 mA·3.9kΩ = 2.12 V

Voltaje R3: VR3 = I2·R3 = 0.4826 mA·2.2kΩ = 1.06 V

Voltaje R4: VR4 = I2·R4 = 0.4826 mA·2.2kΩ = 1.06 V

Voltaje R5: VR5 = I1·R5 = 1.027 mA·1.8kΩ = 1.84 V

Finalmente, completar la tabla con los resultados obtenidos:

![image](https://user-images.githubusercontent.com/116687152/201201629-85771e1c-1ce7-4215-829b-d0ca1ba0dd5e.png)

# 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR.

1.5.4 Mida el voltaje y corriente en cada uno de los elementos del circuito. Anote los resultados de las mediciones en la tabla 1.1

Tabla 1.1 Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.

![image](https://user-images.githubusercontent.com/116817673/201930047-9a598a0e-a77e-4889-bd4f-504b0719e21e.png)


1.5.3 Verifique si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada, considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con signo negativo. Anote los resultados en la tabla 1.2.

![image](https://user-images.githubusercontent.com/116817673/201894554-3b7cb8e9-7445-4b46-9a1f-43fde55969f9.png)

Tabla 1.2 Verificacion de la LVK.

![image](https://user-images.githubusercontent.com/116817673/201903672-e01ddf9b-5d30-4fd6-a6f2-a360d2394a3c.png)

1.5.4 Verifique si se cumple la Ley de Kirchhoff de Corrientes en cada nodo, tomando con signo positivo las corrientes que entran al nodo y con signo negativo las que salen del nodo. Anote los resultados en la tabla 1.3.

![image](https://user-images.githubusercontent.com/117781491/201826964-7b62a17a-36b2-4513-8ec3-4cfc77cdaead.png)

![image](https://user-images.githubusercontent.com/117781491/201829002-7faecba1-eeef-4d70-8371-2669b65d0289.png)

![image](https://user-images.githubusercontent.com/117781491/201830714-524e4030-dfc2-4d2b-89c1-6acc6d3f8c15.png)

![image](https://user-images.githubusercontent.com/117781491/201831279-2f625792-26a8-4fe2-b8c9-0d76abbd561e.png)

Tabla 1.3. Verificación de la LCK.

![image](https://user-images.githubusercontent.com/117781491/201827089-f3a69e8c-b9db-4f2f-ac18-4ff78f89fad1.png)

1.5.5. Compare los resultados medidos con los valores obtenidos al analizar el circuito analíticamente y concluya al respecto.
Calcular errores de las medidas y comentar los resultados.

Se puede observar que en este caso los valores calculados analíticamente coincidieron con los valores medidos en el simulador en casi todos los nodos, por lo que el margen de error de error en este circuito es mínimo. Además podemos decir que la L.C.K. se cumplió en este circuito.
Podemos decir que hemos verificado que las leyes Kirchhoff se cumplen el circuito planteado para el desarrollo del laboratorio y que los valores simulados coinciden con los calculados demostrando que la teoría va de la mano con la práctica.

![image](https://user-images.githubusercontent.com/117781491/201827201-e7b1b92e-976f-4dcf-a862-ecc309684d07.png)

Tambien podemos decir que los valores hallados poseen un error de 0% ya que en este caso el multímetro no presenta variación de medidas por ser simulado.

# 5. VIDEO

https://youtu.be/hiGNkd2tXUk

# 6. CONCLUSIONES

•	El perfecto conocimiento de las caracteristicas de los circuitos paralelos y en serio nos facilita la utilizacion de la ley de Kirchhoff.

• En un circuito en serie, podemos decir que la intensidad de la corriente que circula en un circuito cerrado siempre es la misma para cada elemento, ya que sigue una sola dirección, mientras que el voltaje es distinto, quedándonos que la suma algebraica de la fuente de alimentación y las caídas de voltaje siempre es cero.

•	En un circuito en paralelo, podemos decir que el voltaje es el mismo para cada elemento, mientras que la intensidad de corriente se reparte para las distintas direcciones del circuito, quedándonos que la suma algebraica de la intensidad de entrada y salida en los respectivos nodos siempre es cero.

•	Podemos decir que la suma de las corrientes que entran a un nodo es igual a la suma de las corrientes que salen de dicho nodo y los voltajes de ingreso son iguales a la suma de las caídas de tensión dentro de una malla.

•	Se pudo comprobar que la L.C.K. si se cumplió en el circuito, ya que la , se cumplió en casi todos los nodos, excepto en el nodo 3 y 4 con los valores medidos, donde el margen de error fue muy pequeño.

•	Se consiguió demostrar que la L.V.K si se cumple en cada trayectoria cerrada del circuito, también se pudo ver que la sumatoria algebraica de los voltajes (tanto de fuentes como de caídas) es cero.

•	Se observo que la corriente sigue una sola dirección, es decir sale del polo positivo de la fuente de energía y vuelve al polo negativo de la fuente, por lo que es necesario identificar la polaridad de los componentes en un circuito para poder realizar bien los cálculos, así como efectuar de forma correcta las mediciones de voltaje, corriente y resistencia.

•	Se pudo ver en la simulación que la corriente en un circuito serie es constante, es decir es la misma, y que el voltaje es distinto en todo el circuito, ya que se divide en los componentes de dicho circuito.

•	El desarrollo del laboratorio nos permitió afianzarnos más con los elementos que estaremos en contacto por nuestra carrera, lo que nos permitirá saber cómo usar dichos dispositivos para poder desarrollarnos de mejor manera en el ámbito profesional y educativo.

# 7. BIBLIOGRAFÍA

Bustamante M. J. (s.f.) Practica 3: Leyes de Ohm y Kirchhoff. Universidad Tecnologica de Pereira. Recuperado de: https://media.utp.edu.co/ingenieria-fisica/archivos/Practica_3Gen.pdf

Aldair T. (30 junio, 2018) Aplicación de las leyes de Kirchhoff en circuitos eléctricos. Prezi. Recuperado de: https://prezi.com/p/-nvyisxlzluh/aplicacion-de-las-leyes-de-kirchhoff-en-circuitos-electricos/#:~:text=Las%20leyes%20de%20Kirchhoff%20fueron,de%20conservaci%C3%B3n%20de%20la%20energ%C3%ADa.

# RUBRICA 

![image](https://user-images.githubusercontent.com/116687152/201770128-aa930635-b00e-45b1-87fa-0bd397c58bb3.png)
