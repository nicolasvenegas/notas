# Comportamiento

El comportamiento de las aves en bandada se rige por tres reglas simples, y se puede entender con la física del vuelo y el Principio de Bernoulli: 

1. __Separación__: Cada pájaro se mueve para evitar chocar con los demás.
2. __Alineación__: Cada pájaro intenta seguir la dirección de sus vecinos.
3. __Cohesión__: Cada pájaro sigue la posición media de sus vecinos. 

El vuelo de las aves se basa en el __Principio de Bernoulli__, que establece que la presión del aire disminuye a medida que aumenta su velocidad. Las aves utilizan esta fuerza de empuje para crear sustentación en sus alas. 
Las aves también tienen adaptaciones que les permiten volar en bandadas sin chocarse, como: 

1. Sus alas y músculos de vuelo
2. La rigidez y forma asimétrica de sus plumas
3. La capacidad de controlar la alineación de sus plumas 

El comportamiento de las aves en bandada es similar al de otros animales, como los peces y los insectos. En 1986, se desarrolló un programa de simulación llamado boids, que imita el comportamiento de las aves en bandada


> En su libro Vehicles: Experiments in Synthetic Psychology (Bradford Books, 1986), el neurocientífico y cibernético italiano Valentino Braitenberg describe una serie de vehículos hipotéticos con estructuras internas simples y escribe: “Este es un ejercicio de ciencia ficticia, o ciencia ficción, si así lo prefiere”. Braitenberg sostiene que sus vehículos mecánicos extraordinariamente simples manifiestan conductas como el miedo, la agresión, el amor, la previsión y el optimismo. Craig Reynolds (Steering Behaviors for Autonomous Characters, 1999) se inspiró en Braitenberg, y yo tomaré la mía de Reynolds.
https://natureofcode.com/autonomous-agents/

> El artículo de Reynolds describe muchos objetivos y acciones asociadas, como __buscar un objetivo, evitar un obstáculo y seguir un camino__. 

Un vehículo de Braitenberg es un agente que puede moverse en derredor de manera autónoma. Tiene sensores primitivos (midiendo algún estímulo en un punto) y ruedas (cada una dirigida por su propio motor) que funcionan como actuadores o efectores. Un sensor, en la configuración más simple, está directamente conectado a un efector, de modo que una señal percibida produce inmediatamente un movimiento de la rueda. Dependiendo de cómo los sensores y las ruedas están conectados, el vehículo exhibe diferentes comportamientos (que pueden estar orientados a un objetivo). Esto quiere decir que parecen esforzarse por alcanzar determinadas situaciones y evitar otras, cambiando de rumbo cuando la situación cambia.1​ 

- la historia se escribe mientras se  filma/monta > analoga o digital   