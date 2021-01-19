# Informe de Laboratorio 3
## Teorea de superposición
### 1.	OBJETIVOS

**Principales**

 - Experimentar La superposición
 - Construir un circuito.

**Específicos**

- Distinguir entre lo que es corriente y voltaje
- Diferenciar las partes de una herramienta electrica
- Apreciar la diferencia de voltaje y corriente cuando se apaga una fuente
- Consultar la nomenclatura de colores y valores parar las resistencias.

### 2.	MARCO TEÓRICO 
##Principios de Superposición 
Cualquier circuito resistivo se puede modelar mediante la combinación lineal de variables en un sistema de ecuaciones. Como se mostró en linealidad y proporcionalidad.
Las ecuaciones que describen a un circuito se obtienes a partir de fórmulas como las de las leyes de Kirchhoff, en cada caso se tendrán ecuaciones como las que se relacionan a continuación. 

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio-3/blob/main/Foto/1.png)
 
 ###### _FIGURA 1_
Las primeras ecuaciones se refieren a la sumatoria de corriente, donde los coeficientes de cada variable son valores de resistencias o conductancias, y el valor (C) denota la suma de corrientes conocida en un nodo, generalmente debida a fuentes independientes de corriente. La segunda muestra la suma de tensiones alrededor de un lazo cerrado; en este caso, los coeficientes de las variables son nuevamente resistencias o conductancias, mientras que (C) es la suma de las tensiones conocidas, o de las producidas por fuentes independientes de tensión.

Al tomar la primera ecuación y utilizamos una fuente de corriente de valor Ca, esta producirá tensiones acordes con la magnitud de la corriente.

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio-3/blob/main/Foto/2.png)

 ###### _FIGURA 2_
Ahora si se toma un valor diferente para la fuente de corriente Cb, este producirá tensiones acordes con la magnitud de la corriente.

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio-3/blob/main/Foto/3.png)
 
 ###### _FIGURA 3_
Si se toman valores apropiados para Ca y Cb, de manera que la suma de ellos se constituya en el valor de C original, se tendrá que:

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio-3/blob/main/Foto/6.png)

 ###### _FIGURA 4_
 
Es de esta forma que se la tensión particular producida sobre una resistencia o una conductancia, por ejemplo (K1), se puede ver como la suma de dos tensiones particulares, cada uno de ellos producido por una fuente de tensión diferente.
 
 ![](https://github.com/SanchezMaiAndresSebastian/Laboratorio-3/blob/main/Foto/5.png)
 
 ###### _FIGURA 5_
Este es el principio de superposición y se puede extender a un número cualquiera   de combinaciones. La consecuencia más importante de la linealidad es la superposición. Es esencial desde el punto de vista conceptual y como método de cálculo. El principio de superposición como: La respuesta (una corriente o tensión) en un circuito lineal que tiene más de una fuente independiente se obtiene sumando las respuestas ocasionadas por las fuentes independientes separadas que actúan solas. Esto es, la respuesta a la acción   simultánea de varios estímulos es igual a la suma algebraica de las respuestas de cada estímulo individual. 

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio-3/blob/main/Foto/6.png)

 ###### _FIGURA 6_ 
 
### 3.	DIAGRAMAS

- Diagrama de bloques

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/9.png)

- Diagramas UML

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/10.png)

- Diagramas eléctricos

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/11.png)
 
 - Diagramas esquemáticos.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/7.png) 



### 4.	LISTA DE COMPONENTES

| Cantidad | Componentes | 
| -------- | ----------- | 
| 1 |Protoboard | 
| 2 |Fuente de voltaje de C.D. | 
| 2 |Multímetro | 
| 1 |Resistencia 1 kΩ | 
| 1 |Resistencia 2,2 kΩ | 
| 1 |Resistencia 820 Ω | 
| 1 |Resistencia 470 Ω | 
 
> (Herramientas utilizadas en simulación) 
> Simulador thinkercad


### 5.	EXPLICACIÓN
Armar el circuito

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/8.png) 

###### _FIGURA 4_

__5.1__ Calculos de forma teorica



- Calculo del error porcentual

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/17.png) 

__5.2__ Tabulacion de los datos

__5.2.1__ Medición de voltaje aplicando superposición.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/9.png) 

Tabla 1

__5.2.2__ Medición de corriente aplicando superposición.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/10.png) 
Tabla 2





En el circuito que hemos construido se ve como la unión de diferentes elementos eléctricos en un circuito eléctrico, el cual primero se pone la fuente de voltaje de corriente continua se une con alambres el color perteneciente a su fuente con el protoboard el cual es el positivo (rojo) y el negativo (negro)
Después se pone con el resistor en la parte de los nodos en la columna que sea necesario para que tenga un paso de corriente
Terminamos midiendo el voltaje de cada resistor 

### 6.	 DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

 - Siempre tener conectado a una fuente de corriente continua
 - Tener la fuente de voltaje configurada para la medición en voltios
 - Tener el multímetro siempre en la configurada en la medición de voltios 
 
### 7.	APORTACIONES

 - Para medir la corriente de una malla se tiene que utilizar el ultimetro midiendo en amperios cortando el circuito de la malla
- Para calcular por el teorema de superoposición las fuentes se tienen que hacer cero.
 
### 8.	CONCLUSIONES
 - Se demostro que las leeys de lkirchoff se rigen bajo los nodos que con ello se experimenta con los circuitos por ende siempre van a tener mediciones en cualquier parte del proyecto.
 - Al momento de construir el circuito se tiene que tener en cuenta que tiene que conectarse correctamenet los cabls en el positivo y negativo de todos los instrumentos electricos los cuales si no se hacen correctamente pueden sufrir una disminución de la vida útil.
 - Cuando en unn resistor se encuentra aplicado con el multímetro la medicion de su corriente, cambia el voltaje de los demas resistores que se tienen midiendo con los demás herraminetas.
 _ Siempre tener la guia del sentido para poder resolver las mmlas y cabia totalmemnet si se apaga una fuente o no
 

### 9.	BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos electricos. Mexico: Pearson Educacion. Serway,

R. (2001). Fisica II. Mexico: Pearson Educacion.
### 10.	 ANEXOS
