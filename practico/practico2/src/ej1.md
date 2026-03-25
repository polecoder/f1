# Ejercicio 01 - Movimiento unidimensional

**Fecha:** 25-03-2026
**Estado:** 🟢 Resuelto solo

## Consigna

Consideremos un ómnibus que viaja por la ruta entre Colonia del Sacramento y Montevideo como un movimiento en una dimensión. La distancia que separa las ciudades es de $178.8\ \text{km}$.

1. Si el ómnibus parte de Colonia a las 9:00 y su velocidad media en el recorrido resulta ser de $90\ \text{km/h}$, ¿a qué hora llega a Montevideo suponiendo que el trayecto es en línea recta?
2. ¿Es posible para el ómnibus mantener una velocidad instantánea constante, de $90\ \text{km/h}$, en todos los puntos del trayecto?
3. El ómnibus llega a Montevideo $10$ minutos antes de la hora calculada en la parte uno, ante lo cual un inspector decide multar al conductor del ómnibus por exceso de velocidad. El inspector sostiene que el conductor necesariamente superó la velocidad máxima autorizada de $90\ \text{km/h}$ en alguna parte de su recorrido. ¿Cómo es posible que el inspector esté tan seguro de esto?

## Resolución

### Parte 1

- Si el ómnibus parte de Colonia a las 9:00 y su velocidad media en el recorrido resulta ser de $90\ \text{km/h}$, ¿a qué hora llega a Montevideo suponiendo que el trayecto es en línea recta?

Queremos calcular la hora a la que llega a Montevideo, para esto queremos cálcular cuánto demora en recorrer los $178.8\ \text{km}$. Llamemos $t$ a este resultado, entonces:

- $t=\frac{178.8\ \text{km}}{90\text{km/h}}=2.0\ \text{h}$

Por lo tanto, como el ómnibus parte a las $9{:}00$, estaría llegando a Montevideo a las $11{:}00$.

### Parte 2

- ¿Es posible para el ómnibus mantener una velocidad instantánea constante, de $90\ \text{km/h}$, en todos los puntos del trayecto?

Interpretaremos esta pregunta como una pregunta conceptual.
Teóricamente es posible que exista un movimiento en el cual la velocidad instantánea sea constante, por ejemplo el movimiento representado por la función $x(t)=90t+5$ es un movimiento de velocidad constante que aumenta en 90 por cada unidad de tiempo que pasa.

Ahora para el ómnibus, es altamente improbable que pueda mantener una velocidad instantánea constante, ya que esto implicaría que nunca tiene que frenar por ejemplo.

### Parte 3

- El ómnibus llega a Montevideo $10$ minutos antes de la hora calculada en la parte uno, ante lo cual un inspector decide multar al conductor del ómnibus por exceso de velocidad. El inspector sostiene que el conductor necesariamente superó la velocidad máxima autorizada de $90\ \text{km/h}$ en alguna parte de su recorrido. ¿Cómo es posible que el inspector esté tan seguro de esto?

Como el ómnibus llega $10$ minutos antes a su destino, y vimos en la parte anterior que es básicamente imposible mantener una velocidad constante de $90\ \text{km/h}$, necesariamente el ómnibus tiene que haber superado la velocidad máxima autorizada para "compensar" con esos tramos donde el ómnibus tuvo que frenar (por ejemplo).
Más rigurosamente, recordemos que cuando la velocidad media valía $90\ \text{km/h}$ el viaje demoraba $2$ horas. Si el viaje demora menos de $2$ horas, necesariamente la velocidad media es mayor a $90\ \text{km/h}$, y por consecuencia en algún momento del viaje, la velocidad instantánea fue mayor a la máxima autorizada.