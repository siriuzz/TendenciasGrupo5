
# <center>Práctica MongoDB</center>

----------------------------------

## <center>Grupo 5</center>

| Nombre | ID |
|:------:|:--:|
|    Donato Machado   |  1104502 |
|    Elián Matos    |  1106901  |
|   John Del Rosario     | 1106940   |
|  Juan Ubiera    |    |
|  Kelvin Aristides    |    |
|  Leonel Sepúlveda    |    |


1. 

2.

3.

4.

5.

6.

7.

8. **Demografía del Comprador para Autos Nuevos vs. Usados: ¿Atraen los autos nuevos y usados a diferentes demografías? ¿Existen ciertos grupos de edad o géneros más inclinados a comprar autos nuevos o usados?**
    Las siguientes capturas demuestran que los mínimos y máximos entre los autos usados y nuevos son los mismos, sugiriendo que en este caso, el estado de uso del auto no atrae diferentes demografías.<br>
    * Autos nuevos
    ![](./8/nuevo%20maxAge.png)
    ![](./8/nuevo%20minAge.png)
    * Autos usados
    ![](./8/usado%20maxAge.png)
    ![](./8/usado%20minAge.png)

    ---------------------

    Con las siguientes capturas de pantalla se evidencia que las cantidades de carros nuevos y usados de cada grupo de edades (divididos en intervalos de 10 años) son muy similares. No se encuentran variaciones notables en las cantidades de compra en los diferentes grupos de edades.<br>
    ![](./8/cantidad%20carros%20nuevos.png)
    ![](./8/comparacion%20cantidad%20carros%20usados.png)

9.

10. **Correlación entre Edad del Comprador y Color del Auto: ¿Existe alguna correlación entre la edad del comprador y el color del automóvil que compran? ¿Los compradores más jóvenes prefieren ciertos colores sobre otros?**<br>
    En este caso, primero listé todos los colores que existen en la base de datos y tomé el promedio de edades que compran cada color. En los resultados de la consulta se puede ver que la diferencia de edades relacionados con el color es mínima y se mantiene alrededor de 42 años.

    ![](./10/lista%20de%20colores.png)
    ![](./10/promedio%20de%20edades%20por%20color.png)<br>
    Además se puede observar que la cantidad de compras agrupadas por el color no varían significativamente. El único color que llega a las 600 ventas es el rojo.

    ![](./10/cantidad%20de%20ventas%20por%20color.png)

    <br>
    Cuando revisamos las edades máximas y mínimas de cada color, vemos que los colores son comprados por todas las edades por igual, la edad máxima es de 65 y la edad mínima son 20 años.

    ![](./10/max%20y%20min%20edad%20por%20colores.png)

