# NPS-2021

Listado de respuestas del NPS

Contiene datos de satisfacción del cliente y del NPS. 
El NPS es el Net Promoter Score, y es la regla de oro de las métricas de experiencia del cliente.

El Net Promoter Score es un indicador que se utiliza en los programas de experiencia del cliente. Sirve para determinar la lealtad de los clientes a una empresa. Se mide a través de una encuesta.

### Promotores: 
son aquellos que responden 9 o 10. Por lo general, son clientes leales y entusiastas.

### Neutros: 
son aquellos que responden 7 u 8. Están satisfechos con el servicio, pero no lo suficiente como para considerarse promotores.

### Detractores: 
son aquellos que responden de 0 a 6. Son clientes insatisfechos que es poco probable que vuelvan a comprar e, incluso, podrían desalentar a otros de hacerlo.

## NPS: % Promotores - % Detractores

## Análisis

Lo primero que analizamos es si la base de datos tiene datos atípicos (outliers).  En este caso había un dato, el cual se eliminó del dataset utilizado, ya que el puntaje que puede otorgar un clientes es del 0 al 10, cualquier valor mayor a 10 queda descartado. En este caso se pudo deber a un problema de tipeo en la encuesta:

![Gráfico de llamada según el tipo de contacto](https://github.com/vittoriadelsignore/NPS-2021/blob/master/Outliers%20Rta4.png) 

Luego se evaluó como fue la evolución del puntaje promedio obtenido en cada mes del año evaluado, en donde se puede apreciar que varia pero siempre en un rango comprendido entre 7 y 7.5, es decir, basándandonos en este puntaje el promedio de los clientes son neutros:

![Gráfico de puntaje mensual](https://github.com/vittoriadelsignore/NPS-2021/blob/master/Puntaje%20NPS%20mensual.png)

Por lo tanto, se deben tomar acciones que lleven a los clientes a tener una mejor experiencia tanto al momento de la compra, como durante el uso y especialmente cuando tienen un siniestro. Esto llevará a puntuaciones entre 9 y 10, y que el promedio de clientes sean promotores.

A continuación veremos un histograma con el puntaje obtenido a lo largo del año, en donde el mayor puntaje se encuentra en 9 y 10, pero hay otros dos valores importantes que son 0 y 5, los cuales son los que afectan el promedio obtenido, bajandolo a 7 puntos (aproximadamente):

![Gráfico de puntaje mensual](https://github.com/vittoriadelsignore/NPS-2021/blob/master/Histograma%20NPS.png)

Y así se ve el gráfico con el porcentaje de cada puntaje a lo largo del año, que concentra el 39.4% de la muesta en puntaje 10, y 51.5% de la muestra con el puntaje que agrupa a los promotores (9 y 10):

![Gráfico de puntaje mensual](https://github.com/vittoriadelsignore/NPS-2021/blob/master/Calificaci%C3%B3n.png)

Agrupando los valores y calculando el peso de cada grupo (promotores, neutros y detractores), vemos que hay 51,5% son promotores y 29,3% son detractores:

![Gráfico de puntaje mensual](https://github.com/vittoriadelsignore/NPS-2021/blob/master/Promotores%20Detractores%20y%20Neutros.png)

Esto da un NPS de 22,2 (51,5 - 29,3).
## NPS: 22,2.
