# Ejercicio 07 - Movimiento relativo

**Fecha:** 07-04-2026
**Estado:** 🟢 Resuelto solo

## Consigna

Una banda móvil de un aeropuerto se mueve a $1.0m/s$ y tiene $35.0m$ de largo. Si una mujer entra en un extremo y camina a $1.5m/s$ relativa a la banda móvil:

1. ¿Cuánto tardará en llegar al otro extremo si camina en el mismo sentido en que se mueve la banda?
2. ¿Cuánto tardará en llegar al otro extremo si camina en el sentido opuesto al que se mueve la banda?

## Resolución

### Parte 1

- ¿Cuánto tardará en llegar al otro extremo si camina en el mismo sentido en que se mueve la banda?

Para empezar, tenemos que establecer quienes son los observadores con los que estamos trabajando. En este caso tenemos la mujer por un lado y un observador imaginario que mira la banda móvil desde otro lugar.
Llamemos $S$ al plano de referencia del observador imaginario, y $S'$ al plano de referencia de la mujer. Con esta nomenclatura, tenemos algunos datos para ingresar en la ecuación de la velocidad.

- $v_{S'S}=1.0m/s$ es la velocidad relativa entre los dos marcos mencionados
- $v_{MS'}=1.5m/s$ es la velocidad de la mujer en su plano de referencia

Con esto entonces podemos hallar $v_{MS}$ usando la ecuación de la velocidad:

- $v_{MS}=v_{S'S}+v_{MS'}=2.5m/s$

Entonces para el observador imaginario que no está en la banda móvil, la posición de la mujer está dada por la función:

- $r_{MS}(t)=2.5m/s\cdot t$

**Nota:** Estamos considerando como posición inicial el comienzo de la cinta, por eso no estamos sumando ninguna posición inicial.

Ahora si, hallemos $t$ para que $r_{MS}(t)=35m$:

$$
\begin{aligned}
&r_{MS}(t)=35m\\
&\iff\scriptstyle{(\text{reemplazando por la función conocida})}\\
&2.5m/s\cdot t=35m\\
&\iff\scriptstyle{(\text{operatoria})}\\
&t=\frac{35m}{2.5m/s}\\
&\iff\scriptstyle{(\text{operatoria})}\\
&t=14s
\end{aligned}
$$

Por lo tanto, la mujer tarda catorce segundos en recorrer toda la banda móvil si camina en el mismo sentido que ella.

### Parte 2

- ¿Cuánto tardará en llegar al otro extremo si camina en el sentido opuesto al que se mueve la banda?

En este caso lo que cambia es que la banda tiene una velocidad negativa, pues consideramos la dirección hacia la que va la mujer como la positiva.
Entonces la ecuación de velocidad para este caso es:

- $v_{MS}=v_{S'S}+v_{MS'}=-1.0m/s+1.5m/s=0.5m/s$

Lo que se traduce en una función posición $r_{MS}(t)=0.5m/s\cdot t$.
Despejando para hallar el tiempo $t$ que buscamos:

$$
\begin{aligned}
&r_{MS}(t)=35m\\
&\iff\scriptstyle{(\text{reemplazando por la función conocida})}\\
&0.5m/s\cdot t=35m\\
&\iff\scriptstyle{(\text{operatoria})}\\
&t=\frac{35m}{0.5m/s}\\
&\iff\scriptstyle{(\text{operatoria})}\\
&t=70s
\end{aligned}
$$