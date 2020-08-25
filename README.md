# Entrada y salida de datos con Wyliodrin  para Raspberry Pi.
## 1.Planteamiento del Problema

## 2.Objetivos:

## 3.Estado del Arte
![](img/1.png)
![](img/2.png)
![](img/3.png)


Las 3 investigaciones analizadas anteriormente cuenta con su aportación propia para nuestro trabajo de investigación, las cuales son:
 - Recopilar y enviar datos mediante los distintos puertos de nuestra Raspberry nos puede ayudar en procesos industriales y de automatización ya que nos permite procesar información a bajo costo.
 - Plataformas como Wyliondrin nos permite desarrollar habilidades dentro del campo del IoT, permitiéndonos diseñar un sistema de IoT sin la necesidad de contar con los componentes físicos.
 - Raspberry nos permite adquirir conocimientos de computación y programación a muy bajo costo al ser una plataforma muy asequible.
 
## 4.Marco Teórico
## 5.Diagramas
**Juego de luces**

Para realizar pruebas de raspberry y Wyliodrin debemos contar con un generador de circuitos que nos permite exportar nuestros proyectos en formato SVG y XML. En este caso nuestro circuito será realizado con la plataforma Fritzing la cual es recomendada por Wyliodrin para subir nuestros esquemas.

![](img/4.png)

El siguiente diagrama representa de manera visual y esquemática un juego de luces compuesto con 5 diodos led y 3 pulsadores, cada pulsador mostrará un ciclo distinto al ser pulsado.

![](img/5.png)

Al momento de subir nuestro circuito a Wyliodrin se nos mostrará una tabla de componentes con la información de cada pin de nuestra GPIO y el elemento que tiene conectado  en caso de haber un error no se mostrará la tabla y no funcionara nuestra simulación.

## 6.Lista de Componentes

**Juego de Luces**
Según el diagrama mostrado anteriormente solo se usaban diodos y pulsadores conectados directamente, esto no es lo más recomendable de realizar en la implementación real ya que podríamos generar excesos de corrientes o voltajes por lo que es necesario agregar componentes adicionales:
 - Raspberry Pi
 - 5 Diodos LED
 - 5 Resistencias de 220 ohm
 - 3 Botones
 - 3 Resistencias de 4.7k
 






