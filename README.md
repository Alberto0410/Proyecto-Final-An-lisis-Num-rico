# Proyecto Final Análisis Numérico

En estre proyecto se ponen en práctica los conocimientos adquiridos en el curso de Análisis Numérico.
El documento está dividido en tres secciones, en cada uno de ellas se utilizan  datos extraidos del INEGI.

## Interpolación Polinomial
Se ajusta un polinomio a los porcentajes de subocupación en México. 
![interpolacion1](https://user-images.githubusercontent.com/79923122/209577598-3c9c8c5f-df51-4842-854d-22457c56a1b2.PNG)

## Ajuste por Mínimos Cuadrados Lineales
Se utilizaron los incrementos del PIB de México y se ajustaron polinomios de grado 1 hasta grado 10 usando el método de mínimos cuadrados
![Minimos_cuadrados](https://user-images.githubusercontent.com/79923122/209577686-1c7ce9af-0937-4562-89fb-c242d14fa3c0.PNG)

También se utilizaron los datos de la población de México desde 1910 hasta el 2020 y se ajustaron polinomios de grados 1, 3, 7 y 10.
En los ultimos dos polinomios observamos que hay errores debido a los overflows de la aritmética de punto flotante
![Minimos_cuadrados2](https://user-images.githubusercontent.com/79923122/209577778-8b5244af-30d3-4852-a200-03fd6e21d827.PNG)

## Integración Numérica

Se usó la regla del trapecio compuesta para calcular el valor de la producción de la industria de construcción en México
