# Ejercicio 08 - Movimiento bidimensional

**Fecha:** 30-03-2026
**Estado:** 🟢 Resuelto solo

## Consigna

Una partícula sale del origen en $t = 0\ \text{s}$ con una velocidad inicial $\vec{v}_0 = 3{,}6\,\hat{\imath} \ \text{m/s}$ y una aceleración constante de $\vec{a} = -1{,}2\,\hat{\imath} - 1{,}4\,\hat{\jmath} \ \text{m/s}^2$.

1. ¿En qué tiempo llega la partícula a su coordenada $x$ máxima?
2. ¿Cuál es la velocidad de la partícula en ese momento?
3. ¿Dónde está la partícula en ese momento?

## Resolución

### Parte 1

- ¿En qué tiempo llega la partícula a su coordenada $x$ máxima?

Utilizaremos la ecuación $x=x_0+{v_0}_xt+\frac{1}{2}at^2$ para determinar la coordenada $x$ máxima.
Al sustituir todos los valores que conocemos, tenemos que:

- $x=3{,}6\ \text{m/s}\cdot t-0{,}6\ \text{m/s}^2\cdot t^2$

Esto nos da la función posición, por lo que para hallar el máximo tenemos que hallar las raíces de la derivada primera y el signo de la derivada segunda.

- $\frac{dx}{dt}=3{,}6\ \text{m/s}-1{,}2\ \text{m/s}^2t$

Fácilmente encontramos la única raíz $t=3$. Ahora hay que verificar si el punto es negativo o positivo en la derivada segunda.

- $\frac{dx^2}{d^2t}=-1{,}2\ \text{m/s}^2$

Cómo es negativo (pues la función es constante negativa), confirmamos que el punto $t=3$ es un máximo local de la función original (la función posición).

Esto responde a la pregunta, el tiempo buscado es $t=3\ \text{s}$

### Parte 2

- ¿Cuál es la velocidad de la partícula en ese momento?

Recordemos que la velocidad está dada por la ecuación **vectorial**:

- $\vec{v}=\vec{v_0}+\vec{a}t$

Sustituimos lo conocido y por $t=3$:

- $\vec{v}=\begin{pmatrix}3{,}6&0\end{pmatrix}+\begin{pmatrix}-1{,}2&-1{,}4\end{pmatrix}\cdot 3=\begin{pmatrix}0&-4{,}2\end{pmatrix}$

Expresando el resultado con versores, tenemos que:

- $\vec{v}(3)=-4{,}2\hat{j}\ \text{m/s}$

### Parte 3

- ¿Dónde está la partícula en ese momento?

Recordemos que la posición está dada por la ecuación vectorial:

- $\vec{r}(t)=\vec{r_0}+\vec{v_0}t+\frac{1}{2}\vec{a}t^2$

Sustituimos lo conocido y por $t=3$:

$$
\begin{aligned}
\vec{r}(3)&=\begin{pmatrix}0&0\end{pmatrix}m+3s\begin{pmatrix}3{,}6&0\end{pmatrix}m/s+\tfrac{9}{2}s^2\begin{pmatrix}-1{,}2&-1{,}4\end{pmatrix}m/s^2\\
&=\begin{pmatrix}10{,}8-5{,}4&-6{,}3\end{pmatrix}m\\
&=\begin{pmatrix}5{,}4&-6{,}3\end{pmatrix}m
\end{aligned}
$$

Expresando el resultado con versores tenemos que:

- $\vec{r}(3)=5{,}4m\hat{i}-6{,}3m\hat{j}$