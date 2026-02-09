# Ejercicio 02 - Acertijo

**Fecha:** 09-02-2026
**Estado:** 🟡 Con ayuda

## Consigna

Considere el acertijo clásico siguiente:

> "Un bate y una pelota cuestan \$1.10 en total.
> El bate cuesta \$1.00 más que la pelota.
> ¿Cuánto cuesta la pelota?"

1. Intente predecir la respuesta de la pregunta, sin demasiados cálculos. Explique de qué forma se podría verificar si su resultado es o no correcto.
2. Explique un camino formal que permita obtener la respuesta de la pregunta. Identifique cuáles son las variables que aparecen en el acertijo y qué relaciones se indican entre las mismas. Utilice ecuaciones matemáticas para representar la información brindada y aplique operaciones matemáticas a sus ecuaciones para despejar la respuesta. ¿Cómo se puede verificar la respuesta?
3. ¿Cómo cambiaría la parte anterior si el precio total fuese de \$2.00?

## Resolución

### Parte 1

- Intente predecir la respuesta de la pregunta, sin demasiados cálculos. Explique de qué forma se podría verificar si su resultado es o no correcto.

La primer respuesta de la pregunta que se me ocurre es \$0.10, sin hacer cálculos ni plantear el problema más precisamente.
Verifiquemos si esto es correcto rápidamente, identificando por $c_p$ y $c_b$ los costos de la pelota y el bate respectivamente.

- $c_p=\$0.10$
- $c_b=c_p+\$1.00=\$1.10$
- $c_b+c_p=\$1.20$

Entonces el costo total es \$1.20, es decir que fallamos con nuestra primer intuición, pues el costo total tenía que ser \$1.10.

### Parte 2

- Explique un camino formal que permita obtener la respuesta de la pregunta. Identifique cuáles son las variables que aparecen en el acertijo y qué relaciones se indican entre las mismas. Utilice ecuaciones matemáticas para representar la información brindada y aplique operaciones matemáticas a sus ecuaciones para despejar la respuesta. ¿Cómo se puede verificar la respuesta?

Identifiquemos primero las variables que nos da la letra del acertijo:

- Costo de la pelota
- Costo del bate
- Costo total de los productos

Aunque... Quizás no necesitemos tantas variables, el costo del bate, está directamente relacionado con el costo de la pelota, de hecho hasta sabemos como está relacionado:

- El bate cuesta \$1.00 más que la pelota.

De esta relación, se desprende que si el costo de la pelota es $x$, entonces el costo del bate es $x+1$. Por lo que la solución al problema está dada por encontrar la $x$ en la siguiente ecuación:

- $x+(x+1)=1.1$

Despejemos entonces y obtengamos la respuesta:

$$
\begin{aligned}
&x+(x+1)=1.1\\
&\iff\scriptstyle{(\text{operatoria})}\\
&2x+1=1.1\\
&\iff\scriptstyle{(\text{operatoria})}\\
&x=\frac{0.1}{2}\\
&\iff\scriptstyle{(\text{operatoria})}\\
&x=0.05\\
\end{aligned}
$$

Para verificar si la respuesta es correcta, podemos sustituir en nuestra ecuación:

- $0.05+(0.05+1)=1.1$

Que efectivamente se cumple, por lo tanto la solución que encontramos es correcta.

### Parte 3

- ¿Cómo cambiaría la parte anterior si el precio total fuese de \$2.00?

La respuesta es muy fácil, basta con cambiar la variable del precio total y resolver la nueva ecuación obtenida con esto para obtener la solución.

$$
\begin{aligned}
&x+(x+1)=2\\
&\iff\scriptstyle{(\text{operatoria})}\\
&2x+1=2\\
&\iff\scriptstyle{(\text{operatoria})}\\
&2x=1\\
&\iff\scriptstyle{(\text{operatoria})}\\
&x=0.5\\
\end{aligned}
$$