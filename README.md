# MCOC2020_P2_G2_Entrega5
 
# Primer diseño:

![alt text](https://github.com/jmbarriga1/MCOC2020_P2_G2_Entrega5/blob/main/Disen%CC%83o_v04.png?raw=true)

* Este Cumple con la combinacion de carga 1 y Cumple con la combinacion de carga 2.
* Tiene un peso total de : 97692109.99036838 Kg.

Este diseño cumple debido a que el radio de las barras y sus dimensiones esta exagerada.

Luego, se siguió a optimizar el diseño anterior del reticulado, disminuyendo los radios y espesores de las barras.

* Esta optimización del puente dara un peso : 4727550.409182751 Kg.

Luego de optimizar No Cumple con la Combinacion de Carga 1 ni 2.

* Con este cambio se puede apreciar que la barra 52 como muchas otras no cumple por Resistencia Nominal.
* Tambien la barra 75 como otras no cumplira por pandeo.
* Finalmente la barra 87 y otras no cumplira, ya que, es esbelta.

# Segundo diseño:

![alt text](https://github.com/jmbarriga1/MCOC2020_P2_G2_Entrega5/blob/main/Disen%CC%83o_v02.png?raw=true)

* Este Cumple con la combinacion de carga 1 y Cumple con la combinacion de carga 2.
* Tiene un peso total de :  82594975.05769514 Kg.

Se puede apreciar que el diseño pesa menos que el primer diseño, pero al igual que este cumple porque sus radios y dimensiones estan exageradas.

De la misma manera que en el primer diseño se siguio a optimizar reticulado, disminuyendo los radios y espesores de las barras.

* Esta optimización del puente dara un peso : 6074837.875991005 Kg.

Luego de optimizar, no cumple con la Combinacion de Carga 1 ni 2.

* Con este cambio, se puede apreciar que de la barra 1 hasta la 85 si cumplen para ambas combinaciones de carga. 
* Pero desde la barra 86 hasta la barra 174 no cumple ya que son Esbeltaz, a excepción de la barra 151 que no cumple por Pandeo.

# Tercer diseño:

![alt text](https://github.com/jmbarriga1/MCOC2020_P2_G2_Entrega5/blob/main/Disen%CC%83o_v00.png?raw=true)

* Este Cumple con la combinacion de carga 1 y Cumple con la combinacion de carga 2.
* Tiene un peso total de :  45232027.58245079 Kg.

Se puede apreciar que el diseño pesa menos que los dos primeros diseños y a su vez cumple con ambas combinaciones de cargas. Estas cumpliran en primer lugar porque los radios y dimensiones de las barras se exageran.

Luego se siguio a optimizar los R y t, se tuvieron que rediseñar las barras 256, 348 y 379 porque no cumplían con la Esbeltez. Una vez hecho esto el reticulado si cumplia con las Combinaciones de Carga 1 y 2, luego se calculo el nuevo peso total.

* Esta optimización del puente dara un peso : 3086947.68288914 Kg.

# Cuarto diseño:

![alt text](https://github.com/raimolid/MCOC2020_P2_G2_Entrega5/blob/main/v07.png)

Para este diseño del puente, se siguió iterando el reticulado anterior con la lógica de ir disminuyendo el peso total de la estructura. Aquí se agregaron 2 apoyos más en los puntos #14 y #25 sumados al apoyo central en el punto #18 de la quebrada. Al agregar más apoyos, las barras pueden ser de menor dimensión y por ende, de menor peso, para resistir la fuerza. 

* El peso total disminuye notablemente a 1085523 Kg
* Sin embargo, al rededor de 10 barras fallan los criterios de diseño, por lo que este diseño no cumple con las Solicitaciones de cargas 1 y 2.

# Diseño final óptimo:

![alt text](https://github.com/raimolid/MCOC2020_P2_G2_Entrega5/blob/main/v08_diseno.png)

Iterando nuevamente con el diseño anterior, se llegó a un diseño que, si bien aumentaba un poco el peso anterior, cumplía todos los criterios de diseño. Este diseño se hizo desplazando el primer apoyo a la izquierda desde el punto #14 de la quebrada hacia el punto #11.
Estos apoyos permiten disminuir la carga hacia barras críticas, pudiendo disminuir su sección y el peso total de la estructura, cuidando siempre la esbeltez y la carga crítica del sistema.

Los radios (R) y espesores (t) de todas las barras se hicieron optimizando dentro de la funcion rediseñar, donde se obtuvieron los datos de esos parámetros en una lista con los datos para cada barra. Los radios van desde los 3 cm a los 49 cm y los espesores desde los 2 mm a los 25 mm, dependiendo de la barra.


![alt text](https://github.com/raimolid/MCOC2020_P2_G2_Entrega5/blob/main/v08_tensiones1.png)
![alt text](https://github.com/raimolid/MCOC2020_P2_G2_Entrega5/blob/main/v08_tensiones2.png)

* El peso total de la estructura es de 1488317 kg = 1488 ton 
* Se cumplen las 2 combinaciones de cargas solicitadas y los factores de utilización se pueden apreciar en las imágenes:

![alt text](https://github.com/raimolid/MCOC2020_P2_G2_Entrega5/blob/main/v08_FU1.png)
![alt text](https://github.com/raimolid/MCOC2020_P2_G2_Entrega5/blob/main/v08_FU2.png)

