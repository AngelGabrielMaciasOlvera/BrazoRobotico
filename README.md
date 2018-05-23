# BrazoRobotico
## ========Brazo robótico industrial de 4 grados de libertad=======
Proyecto de simulación del funcionamiento de un brazo robótico industrial capaz de grabar pasos de ejecución 
y notificar vía  voz artificial secuencia de ejecución mediante control de aplicativo Java y uso 
de microcontrolador ARDUINO UNO.

# Descripción General
El circuito desarrollado ejemplifica el trabajo de un brazo robótico industrial, 
el cual cuenta con dos modos de trabajo: programador y ejecución. El brazo robotico 
plantedo puede ser controlado y programdo en secuancia de pasos de ejecución mediante
un aplicativo desarrollado con la tecnología Java. El brazo róbtico posee 
cutro grados de libertad para el movimiento, por lo cual tendrá la capacidad de movimeinto 
en cuatro motores distintos (tres servomotores y un motor a pasos). Además de poder ser
controlado por un aplicativo en Java, el brazo planteado  cuenta con la funcionalidad de
guardar pasos de ejecución (en memoria EEPROM de del dispositivo Arduino) según el usuario 
lo desee y ejecutarlos en cualquier momento a menos que un botón de aborto sea accionado. 
Finalmente, cuando se trabaja en modo de ejecución el brazo debe seguir con su flujo normal 
de ejecución de pasos, sin importar si ocurrió un fallo en energía y perdida de comunicación 
serial con el aplicativo Java. 

## Versión y precio 
*Versión 1.0 realizada al 17/05/2018*
El código de funcionamiento y circuito ilustrado es completamente gratuito
para su uso, distribución y modificación.

## Requisistos Básicos
Para la elaboración y ejecución del circuito digital se necesita lo 
siguiente:
* Microcontrolador Arduino UNO
* Protoboard
* Equipo de computo trabajando con Sistema Operativo Windows, MacOS o alguna distribución Linux
* Arduino IDE y drivers instalados en el equipo de computo para conexión de placa Arduino UNO al computador
* 3 servomotores (microservomotores)
* 1 Motor a pasos con controladora 28BYJ-48
* 1 Resistencia de 220 Ohms
* 1 Pulsador
* Conectores rápidos MM (20 Apróximadamente)
* 4 Conectores rápidos HM
* Pantalla LCD de 16x2
* Driver i2c
* Contar con JDK y/o JVM en la computadora en la cual se ejecutará la aplicación Java 
* IDE de desarrollo Java (NetBeans, Eclipse, etc)
* Kit de armado para brazo robótico de 4 grados de libertad (material de plastico, cartón, etc)
* Libreria para emisión de voz FreeTTS (libre y disponible en https://sourceforge.net/projects/freetts/files/)
* Librería y archivos para comunicación vía puerto serial Panamahitek(libre y disponible en https://sourceforge.net/projects/arduinoyjava/files/v2.7.0/)


## =============Información de Contacto=============
Elaborado por: Nancy Lizette Castañeda Morales y Angel Gabriel Macias Olvera
correos electronicos de contacto: nancycast96@gmail.com y angelmacias@live.com
Correo institucional de contacto: 14241097@itleon.edu.mx y 14240623@itleon.edu.mx

## Derechos de Autor 
El material mostrado para la elaboración del circuito digital 
planteado es libre para su uso y modificación futura por cualquier
colaborador
