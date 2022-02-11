# INFORME LABORATORIO 7

##  1) Objetivos

### 1.1) Objetivo general

- Realizar una simulación en DCACLAB con el uso de inductores y capacitores, para verificar los comportamientos de los componentes en diferentes circuitos.

### 1.2) Objetivos específicos

- Analizar los valores que arroja el multímetro al momento de medir el voltaje en el circuito de corriente alterna, para reconocer qué tipo de valor reconoce el instrumento de medida.

- Observar los gráficos sinusoidales que muestre el osciloscopio, para determinar el comportamiento del inductor y capacitor en el circuito de corriente alterna.

- Analizar los valores medidos de la corriente dentro del rango especificado de frecuencia de corriente alterna, para verificar el comportamiento de los componentes sobre la corriente.

## 2)  Marco Teórico

### El capacitor 

Un capacitor es un componente eléctrico pasivo que guarda energía eléctrica y tiene la propiedad de capacitancia. Su construcción se la realiza con dos placas conductoras paralelas separadas por una cortsa distancia entre sí; en esta distancia se encuentra un material aislante denominado dieléctrico, que es donde se almacena toda la energía.

Al inducirse un voltaje en el capacitor, los electrones libres de una de las placas conductoras paralelas, se traslada hacia la otra, entonces el capacitor queda cargado positivamente en un lado, y negativamente en el otro, produiendo que exista energía en el espacio dejado por las placas. La cantidad de carga que un capacitor puede guardar se llama capacitancia, cuya unidad de medida es el Farad (F).

![LAB7 INFORME3](https://user-images.githubusercontent.com/99141342/153509275-ccecd462-6d0c-4e72-ae3b-88d628916412.PNG)

Dentro de la corriente directa, un capacitor no permite el pao de corriente. Sim embargo, en corriente alterna el capacitor deja pasar cierta cantidad de corriente con oposición, denominada "reactancia capacitiva".

### El inductor

El inductor es un componente elétrico, cuya estructura es un alambre enrollado. Al enrollar el cable, se genera un campo electromagnético a lo largo de todo el cable, que se va sumando conforme aumenta el número de vueltas dada por el cable.

![LAB7 INFORME4](https://user-images.githubusercontent.com/99141342/153510985-49505a47-af75-4976-9f78-2ef947b07fc4.PNG)

De aquí surge el término inductancia, que es una medida de la capacidad que tiene una bobina para establecer un voltaje inducido provocado por un cambio de corriente. El voltaje actúa en dirección opuesta al cambio de corriente. La unidad de medida es el henry (H).

El inductor deja pasar corriente en un circuito de corriente alterna, con cierta oposición que se llama "reactancia inductiva".

## 3) Explicación del procedimiento

1.- Construya en el protoboard el circuito mostrado en la figura 1

a) Utilice el osciloscopio para observar el voltaje Vo variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 Hz. Anote los valores pico de las ondas observadas.

b) Utilice un multímetro para medir el voltaje Vo variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 Hz. Anote los resultados.

c) Utilice un multímetro para medir la corriente que atraviesa la resistencia variando la frecuencia entre los valores 0, 10, 50, 100, 500, 1000 Hz. Anote los resultados.


![LAB7 INFORME](https://user-images.githubusercontent.com/99141342/153498022-591d9476-2fdb-4dae-8255-f9aaa5460ec2.PNG)

2.- Construya el circuito mostrado en la Figura 2

![LAB7 INFORME2](https://user-images.githubusercontent.com/99141342/153503716-e67cef1e-30e7-4433-a367-b80b8fc4931f.PNG)

Se realizan los pasos a), b), c) que se siguieron para la figura 1, aplicadas en la figura 2.  

### Simulación en DCACLAB

#### OSCILOSCOPIO - FIGURA 1

##### Frecuencia de 0 Hz

![OSC 0 FIGURA 1](https://user-images.githubusercontent.com/99141342/153544825-e9f80991-179f-4504-884f-fb5b46e6ab64.PNG)

##### Frecuencia de 10 Hz

![OSC 10 FIGURA 1](https://user-images.githubusercontent.com/99141342/153544841-4c15b0d7-0958-49c3-a874-018ca056a3af.PNG)

##### Frecuencia de 50 Hz

![OSC 50 FIGURA 1](https://user-images.githubusercontent.com/99141342/153544864-dda1e247-6577-4631-b7bd-6383f3b9bc01.PNG)

##### Frecuencia de 100 Hz

![OSC 100 FIGURA 1](https://user-images.githubusercontent.com/99141342/153544880-4deef12b-7af8-4d39-875e-6ba243a465c6.PNG)

##### Frecuencia de 500 Hz

![OSC 500 FIGURA 1](https://user-images.githubusercontent.com/99141342/153544887-de597d80-a791-4f0f-aa2d-0ec7ce686ae8.PNG)

##### Frecuencia de 1000 Hz

![OSC 1000 FIGURA 1](https://user-images.githubusercontent.com/99141342/153544897-74e67bf4-a045-4b2d-9099-f9a55a8cf01e.PNG)

#### MULTÍMETRO(VOLTAJE) - FIGURA 1

##### Frecuencia de 0 Hz

![MULTVOL 0 FIGURA 1](https://user-images.githubusercontent.com/99141342/153544972-c27bf4fa-e752-43e3-9b00-197faed04332.PNG)

##### Frecuencia de 10 Hz

![MULTVOL 10 FIGURA 1](https://user-images.githubusercontent.com/99141342/153544985-a5024c5a-2976-478c-8e76-f53d3fbbef4a.PNG)

##### Frecuencia de 50 Hz

![MULTVOL 50 FIGURA 1](https://user-images.githubusercontent.com/99141342/153545019-a54949a2-ccb8-4ef1-a357-e54e1b52b6dc.PNG)

##### Frecuencia de 100 Hz

![MULTVOL 100 FIGURA 1](https://user-images.githubusercontent.com/99141342/153545029-2c56420d-7e0d-4e3e-bf54-92ce52866b81.PNG)

##### Frecuencia de 500 Hz

![MULTVOL 500 FIGURA 1](https://user-images.githubusercontent.com/99141342/153545034-e80fb5fc-d471-4a07-b9d2-24b6b4b83b40.PNG)

##### Frecuencia de 1000 Hz

![MULTVOL 1000 FIGURA 1](https://user-images.githubusercontent.com/99141342/153545049-8bd5b9ea-1476-4b6c-9c6d-88e0330f38a4.PNG)

#### MULTÍMETRO(CORRIENTE) - FIGURA 1

##### Frecuencia de 0 Hz

![MULTCOR 0 FIGURA 1](https://user-images.githubusercontent.com/99141342/153545078-df6bbeb5-ec44-4d54-b0b7-0306fd8a4414.PNG)

##### Frecuencia de 10 Hz

![MULTCOR 10 FIGURA 1](https://user-images.githubusercontent.com/99141342/153545081-82a2fc22-2d2a-4889-b886-95dcfd49f029.PNG)

##### Frecuencia de 50 Hz

![MULTCOR 50 FIGURA 1](https://user-images.githubusercontent.com/99141342/153545091-3d3ef663-b6dc-49f8-b72b-0af9d4c6ca57.PNG)

##### Frecuencia de 100 Hz

![MULTCOR 100 FIGURA 1](https://user-images.githubusercontent.com/99141342/153545111-9ddc7b2b-1614-45f1-bb75-e2cbbd15c3be.PNG)

##### Frecuencia de 500 Hz

![MULTCOR 500 FIGURA 1](https://user-images.githubusercontent.com/99141342/153545118-aa413375-8ecc-4719-acce-c075146f9006.PNG)

##### Frecuencia de 1000 Hz

![MULTCOR 1000 FIGURA 1](https://user-images.githubusercontent.com/99141342/153545134-869f006a-85ce-43e8-a711-be7c9f03e4c9.PNG)

#### OSCILOSCOPIO - FIGURA 2

##### Frecuencia de 0 Hz

![OSC 0 FIGURA 2](https://user-images.githubusercontent.com/99141342/153545187-b8cfc6f1-f266-4adb-b8c0-8f7d3689f7b9.PNG)

##### Frecuencia de 10 Hz

![OSC 10 FIGURA 2](https://user-images.githubusercontent.com/99141342/153545212-14218e7c-6520-4af5-9286-3bd818fa1c47.PNG)

##### Frecuencia de 50 Hz

![OSC 50 FIGURA 2](https://user-images.githubusercontent.com/99141342/153545229-0d7ceac7-589b-4b5f-856f-ee9b3f41f8c7.PNG)

##### Frecuencia de 100 Hz

![OSC 100 FIGURA 2](https://user-images.githubusercontent.com/99141342/153545239-8799343d-59f9-45ee-942b-f8379a067b97.PNG)

##### Frecuencia de 500 Hz

![OSC 500 FIGURA 2](https://user-images.githubusercontent.com/99141342/153545253-14e06377-314d-4489-bcee-a594fbcc1d68.PNG)

##### Frecuencia de 1000 Hz

![OSC 1000 FIGURA 2](https://user-images.githubusercontent.com/99141342/153545269-d024e0a1-531a-43bf-89c9-2bc4ffc6519d.PNG)

#### MULTÍMETRO(VOLTAJE) - FIGURA 2

##### Frecuencia de 0 Hz

##### Frecuencia de 10 Hz

##### Frecuencia de 50 Hz

##### Frecuencia de 100 Hz

##### Frecuencia de 500 Hz

##### Frecuencia de 1000 Hz

#### MULTÍMETRO(CORRIENTE) - FIGURA 2

##### Frecuencia de 0 Hz

##### Frecuencia de 10 Hz

##### Frecuencia de 50 Hz

##### Frecuencia de 100 Hz

##### Frecuencia de 500 Hz

##### Frecuencia de 1000 Hz


## 4) Análisis de resultados y respuestas a interrogantes



## 5)  Video



## 6) Conclusiones



## 7) Bibliografía



