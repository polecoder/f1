# Clase 01 - Mediciones

**Fecha:** 02-02-2026
**Estado:** 🟢 Completado

## Resumen en 3 líneas



## Preguntas Clave



## Contenido

### Cantidades físicas, patrones y unidades

El material fundamental que constituye la física lo forman las cantidades físicas, en función de las cuales se expresan las leyes de esta ciencia. Conocemos coloquialmente muchas de ellas, como por ejemplo: longitud, masa, tiempo, fuerza, velocidad, densidad, resistividad, temperatura, intensidad luminosa, intensidad del campo magnético, y muchas más. A pesar de que conocemos muchas de las cantidades físicas, nuestra idea de estas en general está bastante alejado de las definiciones científicas precisas de longitud y fuerza; por ejemplo.
Históricamente, surgió la necesidad de comparar, por ejemplo, entre diferentes longitudes, con lo que rápidamente se tuvo que encontrar un **patrón** para que las personas acordaran con las unidades de medición. Antiguamente, por ejemplo, la unidad de medición inglesa era la yarda, determinado por el tamaño de cintura del rey.

En definitiva, esto resulta en que se crea un patrón internacional llamado el **sistema internacional de unidades**, con el que todos acordamos en las medidas para las cantidades físicas **elementales**, éstas son aquellas que se utilizan para definir nuevas cantidades físicas **derivadas**. Veamos en detalle cuales son y cual es el patrón para medirlas.

### El sistema internacional de unidades

| Cantidad                  | Nombre    | Símbolo |
|---------------------------|-----------|---------|
| Tiempo                    | Segundo   | $s$     |
| Longitud                  | Metro     | $m$     |
| Masa                      | Kilogramo | $kg$    |
| Cantidad de sustancia     | Mol       | $mol$   |
| Temperatura termodinámica | Kelvin    | $K$     |
| Corriente eléctrica       | Ampere    | $A$     |
| Intensidad lumínica       | Candela   | $cd$    |

Un ejemplo de una cantidad física derivada de las elementales es por ejemplo el Newton, con el que medimos la fuerza. Veremos más detalladamente que éste se define por:

- $1N=1kg\cdot m/s^2$

Otro aporte importante del sistema internacional de unidades, es el de los prefijos. Estos se introducen pues a menudo se necesitan expresar cantidades muy grandes o muy pequeñas y buscan facilitar la expresión de este tipo de cantidades. Por ejemplo una longitud de $1.3\times 10^9\ m$ se expresa más fácilmente como $1.3\ Gm$ o $1.3$ gigametros.
Vemos a continuación todos los prefijos más detalladamente.

| Factor     | Prefijo | Símbolo |
|------------|---------|---------|
| $10^{18}$  | exa-    | E       |
| $10^{15}$  | peta-   | P       |
| $10^{12}$  | tera-   | T       |
| $10^9$     | giga-   | G       |
| $10^6$     | mega-   | M       |
| $10^3$     | kilo-   | k       |
| $10^2$     | hecto-  | h       |
| $10^1$     | deca-   | da      |
| $10^{-1}$  | deci-   | d       |
| $10^{-2}$  | centi-  | c       |
| $10^{-3}$  | mili-   | m       |
| $10^{-6}$  | micro-  | $\mu$   |
| $10^{-9}$  | nano-   | n       |
| $10^{-12}$ | pico-   | p       |
| $10^{-15}$ | femto-  | f       |
| $10^{-18}$ | atto-   | a       |

### Análisis dimensional

Asociada con cada cantidad medida o calculada hay una dimensión. De igual manera que anteriormente definimos a algunos patrones de medición como fundamentales, podemos definir también un juego de dimensiones fundamentales basadas en patrones de medición independientes. Las cantidades mecánicas independientes y elementales son masa, longitud y tiempo, por lo que servirán de dimensiones fundamentales. Las representamos como $M,L$ y $T$.
Como las ecuaciones tienen que ser dimensionalmente compatibles, es decir que las dimensiones en ambos lados deben ser iguales, podemos realizar determinados razonamientos lógicos para prevenir errores o incluso deducir algunos comportamientos como veremos en el siguiente ejemplo.

#### Ejemplo

Para mantener un objeto que se mueve en un círculo a velocidad constante, se requiere una fuerza llamada fuerza centrípeta. Veamos un análisis dimensional de esta fuerza.

En primer lugar, nos preguntamos: "¿de cuántas variables mecánicas puede depender la fuerza centrípeta $F$?" El objeto en cuestión tiene sólo tres propiedades que son igualmente importantes, su masa $m$, su velocidad $v$ y el radio de su trayectoria circular $r$. Por lo tanto la fuerza centrípeta $F$ deberá darse, aparte de constantes cualesquiera sin dimensión, por una ecuación de la forma:

- $F\propto m^av^br^c$

Donde el símbolo $\propto$ significa "es proporcional a", y las constantes $a,b$ y $c$ son exponentes numéricos que deben ser determinados por el análisis dimensional. Cómo vimos brevemente en la sección anterior (y expandiremos más adelante), las unidades de la fuerza son $kg\cdot m/s^2$, por lo que sus dimensiones son $[F]=MLT^{-2}$. 
Con esto podemos escribir la ecuación de la fuerza centrípeta en función de sus dimensiones así:

$$
\begin{aligned}
&[F]=[m^a][v^b][r^c]\\
&=\scriptstyle{(\text{considerando que }[F]=MLT^{-2})}\\
&MLT^{-2}=M^a(L/T)^bL^c\\
&=\scriptstyle{(\text{operando})}\\
&MLT^{-2}=M^aL^{b+c}T^{-b}\\
\end{aligned}
$$

De donde obtenemos que:

- $a=1$
- $b+c=1\implies c=-1$
- $-b=-2\implies b=2$

Por lo que la expresión resultante es:

- $F\propto \frac{mv^2}{r}$

Resulta que esta es la expresión real para la fuerza centrípeta, derivada de las leyes de Newton y la geometría del movimiento circular. En general esto no sucede pues el análisis dimensional no tiene en cuenta el peso de las constantes que no tienen dimensión, resulta en este caso particular que la constante es 1, por esto tenemos el mismo resultado.