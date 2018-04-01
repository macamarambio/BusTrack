# BusTrack

Verifica los tiempos de llegada de tu bus, obtén alertas de retraso del servicio e información en ruta durante tu experiencia de viaje

![alt text](https://image.ibb.co/e72g77/Captura_de_pantalla_2018_03_28_a_la_s_9_22_43_p_m.png)


Proyecto realizado en forma colaborativa por [Macarena Marambio](https://macamarambio.github.io/)

---

## Objetivos
Mejorar la experiecia actual que vive el usuario al momento de viajar en bus. 

## Research

### Research Cualitativo

#### Entrevistas
Se realizaron entrevistas en el Terminal de Villa Alemana y 4 terminales de la comuna de Santiago: Terminal Alameda, Terminal San Borja, Pájaritos, Terminal Los Héroes. [Revisar registro de audio](https://drive.google.com/open?id=1JoxWu37AwOk8YRdc0Gej38Np61dzQOx-)

![FotosEntrevista](https://image.ibb.co/fN5tn7/entrevistasbus.jpg)

Esto con el objetivo de identificar posibles problemas durante todo el proceso de viaje, esto quiere decir desde la hora de decidir donde viajar, al momento de comprar el ticket, llegar al terminal,encontrar el  subir al bus y hasta llegar a destino. Para poder conocer mejor las necesidadesde nuestros usuarios y resolver sus problemas de manera óptima. 

#### Benchmark 
Análisis competitivos y comparativos de los principales empresas de buses de chile y el extranjero.
Tomando en cuenta 2 áreas, la [venta de pasajes online](https://drive.google.com/open?id=1fJSvvYUKI8YE6wkzkRARnX5idnQNvfhjk1YfYGYKl0E) y el [track del viaje](https://drive.google.com/open?id=1jD62VQwBN8dfEJD_j6CrkZ7DbMheVGNygkRcxhqMeKM).

Se analizó su contenido, funcionalidad y opinión de sus usuarios, evaluando principalmente: si era fácil de navegar, tenía información clara, si era una plataforma web o aplicación móvil.

 <p align="center"> 
<img src="https://image.ibb.co/bULZS7/Captura_de_pantalla_2018_03_28_a_la_s_9_06_57_p_m.png">
</p>


### Research Cuantitativo

Se realizaron encuestas en grupos de viajeros y de empresas de buses, con el fin de entender los motivos por los que más viaja la gente, cuáles son las cosas que más les frustran a la hora de viajar en bus. También se revisaron los principales reclamos en redes sociales y en Sernac, en la sección transporte terrestre de pasajeros. 

Identificando que existe un gran número de personas que viaja diariamente por trabajo, que los reclamos más frecuentes en intenet son debido al alza de los pasajes en epocas de vacaciones o feriados, que otro reclamo que se repite bastante es el mal estado de los buses y mal trato de parte del personal de éstos. 

 <p align="center"> 
<img src="https://image.ibb.co/fCDFZn/reclamos_01.jpg">
</p>

## Definición

### Affinity Map

Luego de realizar la investigacion, como ejercicio para sintentizar la inforamción y poder obtener nuevos hallazgos se realizó un brainstorming como equipo de todos los conceptos que nos parecian relevantes, ya sea de las entrevistas, encuestas, paginas de reclamos, etc. Para posteriormente agruparlos segun afinidad y similitud creando un Affinity Map

 <p align="center"> 
<img src="https://image.ibb.co/jA7ZAS/bustrakaffiniti.jpg">
</p>


### Arquetipos

Ya recopilada y sintetizada toda la información, y ya entendiendo las principales molestias de los pasajeros a la hora de viajar en bus se desarrollaron 3 User Persona, resaltando distintas dificultades que viven nuestros usuarios. 
Este ejercicio ayudó a identificar nuevos problemas y a comprender de que manera impactan en la vida de los usuarios y en su estado de ánimo. 

Turista: Adriana Almeida
Padre de Familia: Juan Pablo Aguilar
Estudiante: Antonia Carrasco

*“Cada uno nos ayudó para poder aclarar dudas con respecto con la creación de nuestra plataforma”*

 <p align="center"> 
<img src="https://image.ibb.co/fiFeAS/personasbus.jpg">
</p>

 <p align="center"> 
<img src="https://image.ibb.co/eRwmqS/primarypersonabus_01.jpg">
</p>

### Customer Journey Map

Ya definido un problema específico para abordar se definió la experiencia del usuario al momento de viajar en bus, y asi poder identificar frustraciones y motivaciones del usuario, además de vacíos en el servicio. 

 <p align="center"> 
<img src="https://image.ibb.co/kDFhx7/Captura_de_pantalla_2018_02_05_a_la_s_10_07_44_a_m.png">
</p>

Luego de este ejercicio pudimos identificar que el hecho de que el bus llegue atrasado en reiteradas veces produce frustración y angustia en el usuario: 

* Angustia por no saber por qué su bus se retrasó
* Llegar tarde a sus compromisos
* Que hablen mal de ella como futura profesional

### Problem Statement

A partir del Customer Journey Map se definieron las principales necesidades de los clientes frente a este problema:

* Conocer horarios exactos de llegada de los buses para organizar el poco tiempo disponible.
* Le gustaría saber si existe retraso en la llegada de los buses para no perder tiempo esperando y avisar en su trabajo posibles atrasos.
* Tener información de posibles accidentes o dificultades que pueda encontrar en la ruta hacia su destino, para avisar posibles atrasos. 

### HMW / What if?

Luego del planteamiento del problema se definieron las preguntas claves ¿Cómo podríamos? (HMW), estas preguntas sirvieron de canal entre los problemas y las posibles ideas (What if?), que se convertirán en oportunidades de diseño:

 <p align="center"> 
<img src="https://image.ibb.co/h4MbQS/Captura_de_pantalla_2018_03_29_a_la_s_2_44_48_p_m.png">
</p>

Tomando la decision de focalizar nuestra solucion en lo siguiente: 

Problem Statement

* Estudiante necesita saber si existe retraso en la llegada de los buses para organizar sus tiempos limitados. 

HMW -  ¿Cómo podríamos?

* ¿Cómo podríamos dar a conocer la información en tiempo real del bus a los pasajeros, incluyendo retrasos?

WHAT IF?  (¿Y SI?)

* Que pasaría si a los usuarios les llegará una notificación, cuando los buses vayan atrasados.

* Que pasaría si tuviéramos un track en tiempo real de la ubicación del bus.

## Ideación

### Propuesta de valor

Ya con las posibles soluciones claras creamos una propuesta de valor de nuestro MVP:

*“Verifica los tiempos de llegada de tu bus, obtén alertas de retraso del servicio e información en ruta durante tu experiencia de viaje”*

Decidimos realizar una app en vez de una web sitio mobile por 2 razones que benefician la experiencia de nuestro usuario al utilizarla.
* La app da la posibilidad que nuestros usuarios vean en tiempo real donde esta el bus antes y durante el viaje, gracias a la geolocalización.
* La app permite notificar o enviar alertas en tiempo real al usuario, cuando haya algún retraso del bus, ya sea por accidente, atochamiento u otra razón.

### Content Prototipe

 <p align="center"> 
 <img src="https://image.ibb.co/iXROS7/Captura_de_pantalla_2018_04_01_a_la_s_8_46_48_p_m.png">
</p>


### Sketch, prototipo en Pop y primer testeo

Luego del content prototipe fue más sencillo realizar los primeros sketchs

 <p align="center"> 
<img src="https://image.ibb.co/eO5p0S/Captura_de_pantalla_2018_04_01_a_la_s_8_34_41_p_m.png">
</p>

Cada integrante del equipo realizó un sketch, y luego votamos por el que considerabamos mejor para testearlo en POP (Prototyping on Paper)
[Ver prototipo](https://marvelapp.com/3hh8ji3)




[Primer prototipo en Sketch e Invision](https://invis.io/MAFJZ542YEP)

### Wireflow

 <p align="center"> 
<img src="https://image.ibb.co/csRPvS/User_flow.jpg">
</p>



---
*Proyecto desarrollado para Laboratoria por [Macarena Marambio](https://macamarambio.github.io/)*
