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

Calcular la intensidad I que pasará por la resistencia 5Ω utilizando Thevenin 





## 5. BIBLIOGRAFÍA

https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-superposition

https://personales.unican.es/peredaj/pdf_apuntes_ac/presentacion-teoremas.pdf

https://es.lambdageeks.com/maximum-power-transfer-theorem/





