# Ejercicio 01 - Ératostenes

**Fecha:** 09-02-2026
**Estado:** 🟡 Con ayuda

## Consigna

Eratóstenes midió la circunferencia de la Tierra al ver que el Sol formaba un ángulo de $7^\circ12'$ al sur de la vertical en Alejandría, cuando al mismo tiempo, en Siena (su nombre actual es Asuán), a $800\ \text{km}$ al sur de Alejandría, el Sol aparece directamente en el cenit (en la vertical).

Suponga que Siena está directamente al sur de Alejandría.  
Con los datos anteriores, ¿cuál es la circunferencia de la Tierra, en kilómetros?

![Figura 1](../img/ej1fig1.png)

## Resolución

Para resolver este ejercicio es importante tomarse un tiempo previo para entender bien como interactua cada parte con las demás. El dato clave es que podemos tomar Siena como el punto de partida para calcular la circunferencia de la Tierra, donde la luz solar pega directamente en la vertical (como se puede ver en el dibujo con las flechas amarillas). Por otra parte, al avanzar 800km hacia el norte, el sol se muestra $7^\circ12'$ al sur de la vertical, por lo que esto establece una regla de tres, de la que queremos saber el valor al dar una vuelta entera de la tierra, es decir: cuando lleguemos a $360^{\circ}$.

Entonces:

- $800km \sim 7^{\circ}12'$
- $x\sim360^{\circ}$

Esto nos deja con la siguiente cuenta para obtener la circunferencia de la Tierra:

- $x=\frac{800km\cdot360^{\circ}}{7^{\circ}12'}\quad(*_1)$

Aunque llegados a este punto, nos podemos ver confundidos con como seguir la cuenta. Veamos que el camino es trabajar con una sola unidad, el grado; por lo tanto tendremos que convertir $7^{\circ}12'$ a una expresión que solo tenga grados.

Recordemos que $1^{\circ}=60'$, por lo tanto:

- $1^{\circ}\sim60'$
- $y^{\circ}\sim12'$

Que nos deja con:

- $y=\frac{1^{\circ}12'}{60'}=0.2^{\circ}$

Ahora si, podemos volver a $*_1$ con lo que obtuvimos:

- $x=\frac{800km\cdot360^{\circ}}{7.2^{\circ}}=40000km$

Por lo que la circunferencia de la Tierra, es aproximadamente $40000km$ según el razonamiento que hicimos.
Considerando que la circunferencia de la Tierra real es $40075km$ el razonamiento es extremadamente bueno.