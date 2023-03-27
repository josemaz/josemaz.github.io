---
layout: post
title: "Teoría de la computación vs tecnología"
date: 2023-03-04
tags: Computación Tecnología
---

Existen limitaciones computacionales. En general, todos los problemas que pueden ser resueltos en una computadora están descritos por una máquina de Turing (MT). Usando la MT se desarrolló una herramienta matemática conocida como **notación-O**. Uno de los objetivos de estas herramientas era conocer las limitaciones de las computadoras. Vale la pena destacar que estos conceptos se desarrollaron dentro del marco de la Teoría de la Computación que poco o nada tiene que ver con las computadoras que conocemos y más bien tienen que ver con matemáticas.

Utilizando la MT como modelo matemático se puede conocer el orden, es decir, una cota en tiempo de cálculo para un algoritmo. Vale la pena recordar que un algoritmo representa el conjunto de instrucciones (la receta) los cuales resuelven un problema computacional. 

El orden de un algoritmo puede ser determinado en dos parámetros: 1) tiempo y 2) espacio de memoria. Por ejemplo, un algoritmo para resolver las correlaciones entre *n* puntos es *O(n^2)* (léase: es orden n cuadrada) en tiempo y es *O(n)* en espacio de memoria. Si las correlaciones se guardan en un disco duro el espacio en disco crece como *O(n^2)*.

Algunas aplicaciones de estas herramientas matemáticas son:

1.	Comparar algoritmos en velocidad y espacio de memoria.
2.	Conocer las limitaciones de una computadora real. Por ejemplo, sabemos que es inútil con una CPU convencional romper una contraseña encriptada en RSA. También es inútil simular una hora de interacción entre un fármaco y una membrana celular. 
3.	Comparar alternativas cómputo. Por ejemplo, ¿Es más rápida una supercomputadora o una computadora cuántica? Si, una computadora cuántica.

Es importante notar que la MT puede modelar computadoras paralelas, computadoras distribuidas, computadoras de DNA, computadoras cuánticas, GPUs, etc. El concepto de MT es mucho más potente que una computadora o una tecnología en particular. La MT es capaz de modelar cualquier tecnología, siempre dentro de un contexto puramente matemático.

El concepto de MT también nos ayuda a determinar los alcances de cualquier tecnología. Por ejemplo, saber si un programa terminara o no (*Healting Problem*) es NP-completo. Además, se sabe que es irresoluble por una MT, ergo, ninguna tecnología lo puede resolver.

En su momento, con este modelo los matemáticos se dieron cuenta que una sola computadora estaba muy restringida en velocidad y memoria para resolver ciertos problemas. Por ejemplo, encontrar una ruta entre dos puntos en una red de rutas. Por lo tanto, se utilizó una mejor idea: **Comunicar varias computadoras para resolver un problema único**. Claro, mientras la tecnología de comunicaciones lo permitiera. Este concepto es el principio fundamental de las supercomputadoras actuales.

Hoy en día existen preguntas abiertas muy interesantes. Por ejemplo: ¿Una computadora puede simular un cerebro humano?, esto no es posible en el contexto de una MT. Sin embargo, siendo más específicos: ¿Un modelo de redes neuronales entrenado por una GPU, puede simular un cerebro humano? El modelo convencional de la MT indica que tampoco. Sin embargo, las computadoras ya están muy cerca de imitar una conversación con un humano (con sus limitaciones también) que no es lo mismo que simular un cerebro. Una pregunta enorme es la siguiente: ¿Algún tipo de computadora podrá procesar todas las elecciones dentro de un mercado financiero?, la MT indica que no. Sin embargo, como siempre, algún truco encontraremos para darle la vuelta a esta limitación.


