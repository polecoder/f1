# Ejercicio 06 - Movimiento unidimensional

**Fecha:** 26-03-2026
**Estado:** 🟢 Resuelto solo

## Consigna

Se dejan caer dos esferas pesadas, de distintas alturas, una $2{,}2\ \text{s}$ después que la otra. Si las dos llegan al suelo al mismo tiempo, $4\ \text{s}$ después de haber soltado la primera, ¿desde qué alturas se dejaron caer?

## Resolución

Para empezar, como el ejercicio es de caída libre, recordemos la constante de aceleración gravitatoria de la tierra:

- $g=9{,}8\ \text{m/s}^2$

Consideraremos el piso como la posición $x=0$ y tomaremos el sentido *hacia abajo* como el sentido negativo.
Como se trata de un movimiento de aceleración constante las posiciones de las esferas están descritas por la siguiente ecuación:

- $x=x_0+v_0\cdot t-4{,}9\ \text{m/s}^2\cdot t^2$

Donde $v_0$ representa la velocidad inicial de cada esfera que es cero. Además $x_0$ representa la posición inicial de cada esfera. Para diferenciarlas, llamemóslas $x_{e_1}$ y $x_{e_2}$ y despejemos:

**Esfera #1**:

$$
\begin{aligned}
&0=x_{e_1}-4{,}9\ \text{m/s}^2\cdot 1{,}8^2\ \text{s}^2\\
&\iff\scriptstyle{(\text{operatoria})}\\
&x_{e_1}=4{,}9\ \text{m/s}^2\cdot 3{,}2\ \text{s}^2\\
&\iff\scriptstyle{(\text{operatoria})}\\
&x_{e_1}=16\ m
\end{aligned}
$$

**Esfera #2**:

$$
\begin{aligned}
&0=x_{e_2}-4{,}9\ \text{m/s}^2\cdot 4{,}0^2\ \text{s}^2\\
&\iff\scriptstyle{(\text{operatoria})}\\
&x_{e_2}=4{,}9\ \text{m/s}^2\cdot 16\ \text{s}^2\\
&\iff\scriptstyle{(\text{operatoria})}\\
&x_{e_2}=78\ m
\end{aligned}
$$

Por lo tanto, la primera esfera se lanza desde $78\ \text{m}$ de altura, mientras que la segunda desde los $16\ \text{m}$ (aproximadamente).