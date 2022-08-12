# Laboratorio extra

## 1. OBJETIVOS

## Objetivo general

Resolver los ejercicios de circuitos eléctricos sobre Teorema de Superposición, Teorema de Thevenin y Máxima transferencia de potencia en los simuladores de AUTODESK Tinkercad y DCAClab aplicando los conocimientos recibidos en clase y si es necesario realizar una breve invetigación para desarrollar los ejercicios.

## Objetivos específicos

- Aplicar los temas Teorema de Superposición, Teorema de Thevenin y Máxima transferencia de potencia de acuerdo a cada ejercicio y responder cada una de las preguntas

- Desarrollar los ejercicios de circuitos eléctricos en su simulador correspondiente y explicar su procedimiento.

## 2. MARCO TEÓRICO

### Teorema de Superposición

El Teorema de Superposición es una técnica muy útil para añadir a tu conjunto de herramientas que sirve para analizar circuitos. S usa la superposición cuando se tenga un circuito con entradas múltiples o múltiples fuentes de poder.

Establece que la tensión entre los extremos (o corriente a través) de un elemento de un circuito lineal es la suma algebraica de las tensiones (o corrientes) a través de ese elemento debidas a cada una de las fuentes independientes cuando actúa sola. Ayuda a analizar un circuito lineal con más de una fuente independiente mediante el cálculo de la contribución de cada fuente independiente por separado. 
La aplicación del principio de superposición tiene los siguientes pasos:

1. Apagar todas las fuentes independientes excepto una.
   Encontrar la salida (tensión o corriente) debido a la fuente activa.
2. Repetir el paso anterior para cada una de las fuentes independientes presentes en el circuito.
3. La contribución total vendrá dada por la suma algebraica de las contribuciones de cada una de las fuentes independientes.

Hay que tener en cuenta que:

- Apagar una fuente independiente de tensión implica reemplazarla por una fuente de tensión de 0V (cortocircuito)
- Apagar una fuente independiente de corriente implica reemplazarla por una fuente de corriente de 0A (circuito abierto)
- Las fuentes dependientes no se modifican

### Teorema de Thevenin

Recordemos que el circuito equivalente de Thevenin siempre aparece en la forma de una fuente de voltaje equivalente en serie con una resistencia equivalente haciendo caso omiso del circuito original que reemplaza. La importancia del teorema de Thevenin es que el circuito equivalente puede reemplazar al circuito original en cuanto a cualquier carga externa. Cualquier resistor de carga conectado entre las terminales de un circuito equivalente de Thevenin tendrá la misma corriente
a través de él y el mismo voltaje entre sus extremos como si estuviera conectado a las terminales del circuito original.

Los pasos para aplicar el teorema de Thevenin son los siguientes:

![image](https://user-images.githubusercontent.com/105259381/183979806-f9ad3e1e-79b9-4eb4-9f8a-fd3b4535672e.png)

El teorema de Thevenin es en gran medida una herramienta analítica que se aplica teóricamente para simplificar el análisis de circuitos. Sin embargo, se puede encontrar el equivalente de Thevenin de un circuito existente utilizando los siguientes métodos de medición generales. 

![image](https://user-images.githubusercontent.com/105259381/183984212-d260e26d-dcf7-407f-8707-65809d1f1552.png)

### Máxima Transferencia de Potencia 

El teorema de transferencia de máxima potencia no es tanto un medio de análisis como una ayuda para el diseño del sistema. En pocas palabras, la cantidad máxima de energía se disipará por una resistencia de carga cuando esa resistencia de carga sea igual a la resistencia de Thévenin / Norton de la red que suministre la energía. Si la resistencia de carga es menor o mayor que la resistencia Thévenin / Norton de la red de origen, su potencia disipada será menor que la máxima.

En general, se siguen los pasos mencionados a continuación para resolver problemas de teoría de transferencia de potencia. Hay otras formas, pero seguir estos pasos conducirá a una ruta más eficiente.

- Paso 1: Descubra la resistencia de carga del circuito. Ahora retírelo del circuito.
- Paso 2: Calcule la resistencia equivalente de Thevenin del circuito desde el punto de vista de la rama de resistencia de carga en circuito abierto.
- Paso 3: Ahora, como dice la teoría, la nueva resistencia de carga será la resistencia equivalente de Thevenin. Esta es la resistencia responsable de la máxima transferencia de potencia.
- Paso 4: Entonces se deriva la potencia máxima. Viene como sigue.

![image](https://user-images.githubusercontent.com/105259381/184034208-84808cfb-f504-4b1e-a22a-af897b22653f.png)

## 3. EXPLICACIÓN DEL PROCEDIMIENTO 

### PREGUNTA 1 

Encontrar la corriente y el voltaje a través de la resistencia de 12Ω mediante el teorema de superposición

![image](https://user-images.githubusercontent.com/105259381/182975642-ff1470d2-21cf-4539-93d9-50e32b748fd3.png)

#### MATERIALES

1 resistencia de 4Ω

1 resistencia de 2Ω

1 resistencia de 12Ω

1 fuente de alimentación de 16V

1 fuente de alimentación de 12V

![image](https://user-images.githubusercontent.com/105259381/184048686-d465ef4f-7e46-49f6-8547-d5998661743f.png)

#### Solución:

![image](https://user-images.githubusercontent.com/105259381/184052894-0519f6d0-2dda-475f-b92a-3684ad0b6c80.png)

![image](https://user-images.githubusercontent.com/105259381/184052792-204b5b00-42c2-4cdb-b83e-2182032edc83.png)

#### Procedimiento:

Se desconecta la fuente de alimentación de 16V

![image](https://user-images.githubusercontent.com/105259381/184053356-b3d9925c-8a19-4bd2-8265-939838bc66b8.png)

Se desconecta la fuente de alimentación de 10V

![image](https://user-images.githubusercontent.com/105259381/184053496-11d04240-1c83-407e-8de1-d0ae95aad79b.png)

Se calcula la corriente en la resistencia de 12Ω

![image](https://user-images.githubusercontent.com/105259381/184053743-7272a465-9109-4519-a030-e7214e6bb5fd.png)

Se calcula el voltaje en la resistencia de 12Ω

![image](https://user-images.githubusercontent.com/105259381/184053841-1de0119d-1ea3-4aba-9773-384136c588bf.png)

### PREGUNTA 2

Calcular la intensidad I que pasará por la resistencia 5Ω utilizando Thévenin

![image](https://user-images.githubusercontent.com/105259381/184282466-f9e37212-6843-47ab-8054-580229dcddc0.png)

#### MATERIALES

2 resistencia de 3Ω

1 resistencia de 6Ω

1 resistencia de 5Ω

1 fuente de alimentación de 20V

1 fuente de alimentación de 10V

![image](https://user-images.githubusercontent.com/105259381/184283840-c28fce10-ede5-43e7-bb1e-96df454fc251.png)

#### Solución:

![image](https://user-images.githubusercontent.com/105259381/184284848-cd828b74-e190-4080-93b1-038453e06863.png)

#### Procedimiento:

Se mide el voltaje de Thévenin

Se obtiene que VTH=10V

![image](https://user-images.githubusercontent.com/105259381/184285108-f92e454d-d09b-4489-be1d-6506dc58ff08.png)

Se retira la resistencia de 5Ω y se mide la resistencia de Thévenin

Se obtiene que RTH= 5Ω

![image](https://user-images.githubusercontent.com/105259381/184285443-f11e12e5-7494-4eb8-a060-0535eef5eea8.png)

Por último se mide la corriente que pasa por la resistencia de 5Ω en el circuito de Thévenin

![image](https://user-images.githubusercontent.com/105259381/184286218-5da134ac-6668-412d-bae7-5da3366baddd.png)

### PREGUNTA 3

Empleando el circuito equivalente de Thévenin determine la potencia suministrada a la resistencia R3

Mediante instrumentos encuentre el circuito equivalente de Thévenin

Emplee el vatímetro para determinar la potencia

![image](https://user-images.githubusercontent.com/105259381/184282352-37516f6c-d9e2-4f8d-aa1b-ccad129b431e.png)

#### MATERIALES

1 resistencia de 9.1 kΩ

1 resistencia de 3.3 kΩ

1 resistencia de 2.2 kΩ

1 resistencia de 7.5 kΩ

1 resistencia de 6.8 kΩ

1 fuente de alimentación de 18V

1 fuente de alimentación de 3V

![image](https://user-images.githubusercontent.com/105259381/184287031-7149164a-f7fe-49ea-a19f-5c5d29decf44.png)

#### Solución:

![image](https://user-images.githubusercontent.com/105259381/184286531-3481ae61-c8fd-4d24-8ef6-38f755f77822.png)

#### Procedimiento:

Se retira la resistencia de 2.2 kΩ y se mide el voltaje de Thévenin.

Se obtiene que VTH=8.32v

![image](https://user-images.githubusercontent.com/105259381/184286531-3481ae61-c8fd-4d24-8ef6-38f755f77822.png)

Se mide la resistencia de Thévenin

![image](https://user-images.githubusercontent.com/105259381/184287400-afbdc67d-ce19-4034-b385-eff61c75d1a0.png)

Se mide el voltaje y la corriente en el circuito de Thévenin




## 5. BIBLIOGRAFÍA

https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-superposition

https://personales.unican.es/peredaj/pdf_apuntes_ac/presentacion-teoremas.pdf

https://es.lambdageeks.com/maximum-power-transfer-theorem/





