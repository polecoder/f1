# Ejercicio 03 - Movimiento unidimensional

**Fecha:** 26-03-2026
**Estado:** 🟢 Resuelto solo

## Consigna

Una partícula se mueve a lo largo del eje $x$ según la ecuación $x = At + Bt^2$ donde $A = 50\ \text{m/s}$ y $B = 10\ \text{m/s}^2$.

Calcular:

1. la velocidad promedio de la partícula durante los primeros $3\ \text{s}$ de movimiento,
2. la velocidad instantánea de la partícula en $t = 3\ \text{s}$,
3. la aceleración instantánea de la partícula en $t = 3\ \text{s}$.

¿Cómo se interpretan gráficamente los cálculos realizados?

## Resolución

### Parte 1

- la velocidad promedio de la partícula durante los primeros $3\ \text{s}$ de movimiento

Este cálculo es bien sencillo, sabemos que en $t=0$ tenemos $x=0$, por lo tanto nos falta calcular que pasa en $t=3$.
Utilizando la función dada calculamos la posición:

- $x=50\ \text{m/s}\cdot 3\ \text{s}+10\ \text{m/s}^2\cdot 9\ \text{s}^2=240m$

Con esto obtenemos la velocidad promedio:

- $\overline{v}=\frac{180\ \text{m}}{3\ \text{s}}=80\ \text{m/s}$

### Parte 2

- la velocidad instantánea de la partícula en $t = 3\ \text{s}$

Como tenemos la expresión de la función posición, la velocidad instantánea es simplemente la derivada de la misma en el punto solicitado.

- $v(t)=\frac{d}{dt}(At+Bt^2)=A+2Bt$

Reemplazando con $A = 50\ \text{m/s}$ y $B = 10\ \text{m/s}^2$ y evaluando en $t=3$:

- $v(3)=50\ \text{m/s}+20\ \text{m/s}^2\cdot3\ \text{s}=110\ \text{m/s}$

### Parte 3

- la aceleración instantánea de la partícula en $t = 3\ \text{s}$

Ahora, como tenemos la expresión de la función velocidad, la aceleración instantánea es simplemente la derivada de la misma en el punto solicitado.

- $a(t)=\frac{d}{dt}(A+2Bt)=2B$

Reemplazando con $B=10\ \text{m/s}^2$ y evaluando en $t=3$:

- $a(3)=20\ \text{m/s}^2$
