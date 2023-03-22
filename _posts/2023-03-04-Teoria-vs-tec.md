---
layout: post
title: "Teoría de la computación vs tecnología"
date: 2023-03-04
tags: Computación Tecnología
---

Existen limitaciones computacionales. En general, todos los problemas que pueden ser resueltos en una computadora están descritos por una máquina de Turing (MT). En este contexto se desarrolló una herramienta matemática conocida como notación-O. 

Utilizando la MT como modelo matemático se puede conocer el orden, es decir, una cota en tiempo de cálculo para un algoritmo. Vale la pena recordar que un algoritmo representa el conjunto de instrucciones (la receta) los cuales resuelven un problema computacional. 

El orden de un algoritmo puede ser determinado en dos parámetros: 1) tiempo y 2) espacio de memoria. Por ejemplo, un algoritmo para resolver las correlaciones entre n puntos es O(n^2) (léase: es orden n cuadrada) en tiempo y es O(n) en espacio de memoria. Si las correlaciones se guardan en un disco duro el espacio en disco es O(n^2).

Algunas aplicaciones de estas herramientas matemáticas son:

1.	Comparar algoritmos en velocidad y espacio de memoria.
2.	Conocer las limitaciones de una computadora real. Por ejemplo, sabemos que es inútil con una CPU convencional romper una contraseña encriptada en RSA. También es inútil simular una hora de interacción entre un fármaco y una membrana celular. 
3.	Comparar alternativas cómputo. Por ejemplo, ¿Es más rápida una supercomputadora o una computadora cuántica? Si, una computadora cuántica.

Es importante notar que la MT puede modelar computadoras paralelas, computadoras distribuidas, computadoras de DNA, computadoras cuánticas, etc. El concepto de MT es mucho más potente que una computadora o una tecnología en particular. 

En su momento, con este modelo los matemáticos se dieron cuenta que una sola computadora estaba muy restringida en velocidad y memoria para resolver ciertos problemas. Por ejemplo, encontrar una ruta entre dos puntos en una red de rutas. Por lo tanto, se utilizó una mejor idea: Comunicar varias computadoras para resolver un problema único.

Actualmente, existen preguntas abiertas muy interesantes. Por ejemplo: ¿Una computadora puede simular un cerebro humano?, esto no es posible. Sin embargo, siendo más específicos: ¿Un modelo de redes neuronales entrenado por una GPU, puede simular un cerebro humano? El modelo convencional de la MT indica que tampoco. Sin embargo, estos modelos ya están muy cerca de imitar que no es lo mismo que simular. Una pregunta enorme es la siguiente: ¿Algún tipo de computadora podrá procesar todas las elecciones de un mercado financiero?, la MT indica que no. Pero como siempre, algún truco encontraremos para darle la vuelta a esta limitación.




