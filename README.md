# Offly – Fast Prompting POC

Este repositorio presenta una prueba de concepto (POC) desarrollada para el curso 
"Inteligencia Artificial: Generación de Prompts".  
El objetivo del proyecto es demostrar cómo el uso de técnicas de Fast Prompting 
permite generar mensajes de concentración personalizados para jóvenes de manera 
eficiente, coherente y viable.

## Introducción
Offly es una propuesta de aplicación orientada a jóvenes que buscan mejorar su 
concentración y reducir las distracciones digitales. A diferencia de otras 
herramientas similares, Offly propone un enfoque empático y educativo, que acompaña 
al usuario durante su proceso de concentración sin juzgar ni imponer.

## Presentación del problema
En la actualidad, los jóvenes están expuestos a una gran cantidad de estímulos 
digitales constantes, como notificaciones, redes sociales y videojuegos. Esta 
sobreestimulación dificulta mantener la atención, impacta negativamente en el 
rendimiento académico y genera frustración al intentar concentrarse.

Si bien existen aplicaciones que bloquean el acceso a ciertas plataformas, muchas 
de ellas no contemplan el aspecto emocional del usuario ni ofrecen acompañamiento 
personalizado. Esto genera una oportunidad para desarrollar una solución que combine 
tecnología, empatía y educación digital.

## Propuesta de solución
La propuesta consiste en utilizar modelos de inteligencia artificial para generar 
mensajes de concentración personalizados, adaptados al estado emocional, nivel de 
distracción y momento del día del usuario.

En esta POC, se implementa un sistema basado en técnicas de Fast Prompting que permite 
utilizar un único prompt base, parametrizado mediante variables, para generar 
distintos mensajes sin necesidad de realizar múltiples consultas redundantes a la IA.

## Objetivos del proyecto
- Demostrar el uso de técnicas de Fast Prompting.
- Generar mensajes de concentración personalizados para jóvenes.
- Optimizar la cantidad de consultas realizadas al modelo de IA.
- Mantener coherencia en el tono y la identidad emocional de Offly.
- Analizar mejoras respecto a la propuesta planteada en la primera entrega.

## Metodología
El proyecto se desarrolla a través de una prueba de concepto implementada en un 
Jupyter Notebook. En primer lugar, se define un prompt base que representa la identidad 
y el tono de Offly. Luego, se incorporan variables que permiten personalizar los 
mensajes según distintos escenarios.

Se realizan pruebas con diferentes configuraciones de entrada para evaluar la 
consistencia de los resultados y comparar el uso de prompts optimizados frente a 
enfoques menos eficientes.

## Herramientas y tecnologías
- Python
- Jupyter Notebook
- Modelos de lenguaje de IA
- Técnicas de Fast Prompting:
  - Prompt base reutilizable
  - Uso de variables
  - Reducción de tokens
  - Minimización de consultas a la API

## Implementación
La implementación se encuentra documentada en el archivo 
`offly_fast_prompting.ipynb`, donde se muestra el diseño del prompt base, su uso 
parametrizado y ejemplos de mensajes generados para distintos perfiles de usuario.

## Análisis de viabilidad
El proyecto es técnicamente viable debido a su alcance acotado y a la optimización en 
el uso de la inteligencia artificial. Al utilizar un único prompt base y minimizar 
las consultas innecesarias, se reduce el costo operativo y se mejora la escalabilidad 
de la solución, haciéndola aplicable a un entorno real.
