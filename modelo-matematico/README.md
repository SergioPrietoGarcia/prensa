# Modelo matemático: Estimación en tablas de contingencia con marginales dadas

Esta publicación aborda el desarrollo de mi trabajo de fin de máster titulado "Estimación en tablas de contingencia con marginales dadas". La estimación de las probabilidades conjuntas en tablas de contingencia basadas únicamente en las frecuencias marginales representa un desafío ampliamente investigado en la actualidad.

A pesar de la existencia de varios métodos que calculan las probabilidades de las celdas de una tabla de contingencia, estos suelen imponer restricciones para las distribuciones marginales. En este contexto, el presente trabajo se centra en proponer un algoritmo de Expectation-Maximization (EM) para abordar este desafío. Este enfoque se aplicará a un problema específico: la estimación de la probabilidad de transferencia de votos entre diferentes opciones políticas en dos elecciones consecutivas en España.

En este caso particular, solo se cuentan con las frecuencias de voto para cada opción política a nivel de los colegios electorales, siendo las probabilidades conjuntas y condicionales inicialmente desconocidas. Por ende, esta investigación se enfrenta a un problema más desafiante y posiblemente sin precedentes, al abordar la estimación de las probabilidades de celda cuando solo se han observado las frecuencias marginales y no las frecuencias de las propias celdas.
