![Image text](/Imagenes/Portada.jpg)
# TEMA 
 
Creación de Mano Robótica programada mediante Arduino 
 
## INTRODUCCIÓN 
 <p style='text-align: justify;'> En este trabajo se plantea el desarrollo de una mano robótica como prototipo didáctico, a través del cual se podrá acceder de manera interactiva a las temáticas propias de la programación en Arduino. De esta forma se espera incrementar y fortalecer el área de tecnología, a la vez que se mejoran las competencias de programación. A continuación, se presenta el planteamiento del problema que dio origen al trabajo presente.  
En este trabajo se presenta el desarrollo de una mano robótica didáctica, indicando en primer lugar cuáles son las partes que conforman el prototipo. El control electrónico se efectuó a través de una tarjeta Arduino, la cual permite leer el estado de los sensores, flexo resistencias en este caso, a la vez que genera las señales para controlar los servomotores responsables del movimiento. La versión final se construyó con materiales disponibles en casa, dando como resultado un prototipo didáctico que puede ser utilizado como herramienta motivadora para el aprendizaje de programación en Arduino. 
 La implementación se acompañó de varias reuniones en online y ayudas didácticas, cuyo propósito consistía en la explicación teórica de los conceptos que se iban a trabajar y posteriormente la aplicación de estos sobre la mano robótica. </p> 
 
## PROBLEMÁTICA 
 <p style='text-align: justify;'> Construir una mano robótica con control de movimiento con un pedazo de cartón diseñando una mano, mediante servos de 5 o 6 grados de libertad cuales transmiten el movimiento a través de hilos de nailon a cada uno de los dedos, haciendo la función de tendones y músculos de la mano humana real y con un Arduino uno utilizándolo para su programación, los cuales que nos ayudarán para que sea realizado el movimiento de las falanges de los dedos robóticos. También se colocará en la parte trasera cinta elástica para que los dedos retrocedieran.  </p>
 
 
## OBJETIVOS 
### OBGETIVOS GENERALES  
 
-	Definir ¿Para qué sirve el programa “Arduino”?  
 
-	Explicar ¿Qué es un Servomotor?  
 
-	Explicar ¿Qué es Arduino?  
 
-	Detallar funciones y características del Componente Arduino  
 
### OBJETIVOS ESPECÍFICOS 
 
- Programar con la herramienta Arduino el funcionamiento de la mano robótica. 
 
-	A través de programas de simulación, comprobar el funcionamiento de la  - mano robótica. 
 
## MARCO TEÓRICO 
 
### ARDUINO (PROGRAMA) 
<p style='text-align: justify;'> Arduino es un programa disponible en ordenadores que sirve para programar códigos para luego implementarlos en microchips Atmega.  
Según la página oficial del programa Arduino, este es una plataforma de desarrollo basada en una placa electrónica de hardware libre que incorpora un microcontrolador reprogramable y una serie de pines hembra. Estos permiten establecer conexiones entre el microcontrolador y los diferentes sensores y actuadores de una manera muy sencilla (principalmente con cables dupont).  
Este programa nos permite programar todos los modelos de Arduino disponibles, entre ellos destacan los siguientes:
 </p> 

 ![Image text](/Imagenes/TiposArduino.jpg)
 
<p style='text-align: justify;'> Arduino Nació en el año 2005 el Instituto de Diseño Interactivo de Ivrea (Italia). Arduino apareció por la necesidad de contar con un dispositivo para utilizar en aulas que fuera de bajo coste. La idea original fue, fabricar una placa para uso interno de la escuela. 
Sin embargo, el instituto se vio obligado a cerrar sus puertas precisamente en 2005. Ante la perspectiva de perder todo el proyecto Arduino en el proceso, se decidió liberarlo y abrirlo al público para que todo el mundo pudiese participar en la evolución del proyecto, proponer mejoras y sugerencias. 
Los principales responsables de la idea y diseño de Arduino fueron Massimo Banzi, David Cuartielles, David Mellis, Tom Igoe y Gianluca Martino.  </p>

## SERVOMOTOR

Un servomotor (o servo) es un tipo especial de motor con características especiales de control de posición. Al hablar de un servomotor se hace referencia a un sistema compuesto por componentes electromecánicos y electrónicos.

Este es un actuador rotativo o motor que permite un control preciso en términos de posición angular, aceleración y velocidad, capacidades que un motor normal no tiene. En definitiva, utiliza un motor normal y lo combina con un sensor para la retroalimentación de posición

![Image text](/Imagenes/Servomotor.jpg)

Los servomotores poseen tres cables, a diferencia de los motores comunes que solo tienen dos. Estos tres cables casi siempre tienen los mismos colores, por lo que son fácilmente reconocibles.

- Voltaje = Rojo
- Tierra/GND = Negro/Café
- Señal de Control = Amarillo, Blanco o Naranja

## Tipos de servomotores

Los servos vienen en muchos tamaños y en tres tipos básicos:

![Image text](/Imagenes/TiposServo.jpg)

Servo de rotación posicional: Este es el tipo más común de servomotor. El eje de salida gira aproximadamente la mitad de un círculo, o 180 grados. Tiene topesfísicos colocados en el mecanismo de engranaje para evitar que se gire más allá de estos límites para proteger el sensor de rotación.
Estos servos comunes se encuentran en coches y aviones con control remoto de agua, juguetes, robots y muchas otras aplicaciones.

Servo de rotación continua: Este tipo es muy similar al servomotor de rotación posicional común, excepto que puede girar en cualquier dirección indefinidamente. La señal de control, en lugar de ajustar la posición estática del servo, se interpreta como la dirección y la velocidad de rotación.

El rango de posibles comandos hace que el servo gire en el sentido de las agujas del reloj o en sentido contrario a las agujas del reloj según se desee, a una velocidad variable, dependiendo de la señal de comando. Este tipo de servo se puede utilizar en un plato de radar si se monta en un robot. O se puede utilizar como motor de accionamiento en un robot móvil.

Servo lineal: Es similar al servomotor de rotación posicional descrito
anteriormente, pero con engranajes adicionales (normalmente un mecanismo de cremallera y piñón) para cambiar la salida de circular a vaivén. Estos servos no son fáciles de encontrar, pero a veces se pueden encontrar en tiendas de modelismo donde se utilizan como actuadores en aviones de modelos más grandes.

## Ventajas y desventajas de los servomotores.

Los servomotores ofrecen bastantes ventajas, pero como todas las cosas, también plantean algunos problemas y dificultades a las empresas que utilizan este dispositivo.

### Ventajas

- Si se coloca una carga pesada en el motor, el conductor aumentará la
corriente en la bobina del motor mientras intenta girar el motor.
Básicamente, no hay ninguna condición fuera de los pasos.

- El funcionamiento a alta velocidad es posible.

- Son siempre constantes y trabajan al mismo ritmo.

### Desventajas:

- Dado que el servomotor trata de girar de acuerdo a los pulsos de mando, no es adecuado para el control de precisión de la rotación.

- Suelen tener un coste elevado en cuanto a mantenimiento y
funcionamiento.

- Cuando está parado, el rotor del motor continúa moviéndose hacia
adelante y hacia atrás con un pulso, por lo que no es adecuado si necesita evitar la vibración.

## ARDUINO UNO

Arduino es una plataforma de creación electrónica de código abierto basada en hardware y software libre que es flexible y fácil de usar para creadores y desarrolladores, la plataforma admite la creación de diferentes tipos de microcomputadoras de placa única, para que la comunidad de creadores las use para diferentes propósitos.

- Hardware libre: esto nos quiere decir que es de acceso público donde cualquier persona puede modificarlos utilizando la misma placa base para diferentes proyectos que realicen

- Software libre: son los programas informáticos cuyo código es accesible por cualquier persona y pueda modificarlos

## Características

![Image text](/Imagenes/arduino_uno.jpg)

## ¿Cuál es su funcionamiento?

Una de las ventajas más importantes frente a otro tipo de placas es que
Arduino permite cargar directamente los programas o sketches en el
microcontrolador sin la necesidad de un componente de hardware aparte.

Arduino es una placa basada en microcontroladores, específicamente ATME, Los microcontroladores son circuitos integrados que pueden grabar
instrucciones (podemos hablar de microchips). Estas instrucciones están
escritas en lenguajes de programación que permiten a los usuarios crear
programas que interactúan con circuitos electrónicos. 

Por lo general, los microcontroladores tienen entradas y salidas digitales,entradas y salidas analógicas y entradas y salidas para protocolos de comunicación. Un Arduino es una placa que cuenta con todos los elementos necesarios para conectar periféricos a las entradas y salidas de un microcontrolador, es una placa impresa con todos los componentes necesarios para el micro funcionamiento y se comunica con la computadora a través de comunicación serial. 


