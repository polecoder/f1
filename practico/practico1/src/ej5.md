# Ejercicio 05 - Análisis dimensional

**Fecha:** 10-02-2026
**Estado:** 🟡 Con ayuda

## Consigna

Considera un péndulo constituido por una masa $m$ colgando de un hilo inextensible y sin masa de largo $l$.

Mediante un análisis dimensional, determina la relación funcional entre el período $p$ de las oscilaciones del péndulo y los parámetros del problema ($m$, $l$ y la aceleración de la gravedad $g$).

- ¿Cómo podría determinarse empíricamente la validez del resultado?
- ¿Cómo podríamos, a partir de los experimentos, determinar el valor de una constante de proporcionalidad adimensionada en la ecuación?

## Resolución

Queremos determinar la relación funcional entre el periodo $p$ de las oscilaciones del péndulo y los parámetros del problema. Primero tengamos en cuenta que:

- $[p]=T$

Por otra parte, sabemos que la aceleración es la velocidad que tiene un objeto por unidad de tiempo. A su vez, la velocidad es la longitud que recorre un objeto por unidad de tiempo. Eso nos deja con:

$$
\begin{aligned}
&[g]\\
&=\scriptstyle{(\text{definición de aceleración})}\\
&[v]\cdot T^{-1}\\
&=\scriptstyle{(\text{definición de velocidad: }[v]=LT^{-1})}\\
&LT^{-2}\\
\end{aligned}
$$

Por lo tanto, de forma general, los parámetros del problema tienen una dimensión:

- $[p]=[g^{a}][m^{b}][l^{c}]=L^aT^{-2a}M^bL^c=L^{a+c}T^{-2a}M^b$

Sabiendo que $[p]=T$, podemos obtener un sistema de ecuaciones:

$$
\begin{cases}
a+c=0\\
-2a=1\\
b=0
\end{cases}
$$

De donde obtenemos que:

- $b=0$
- $a=-0.5$
- $c=0.5$

Por lo tanto, tenemos que $p\propto\sqrt{\frac{l}{g}}$. Vayamos ahora con las preguntas:

1. **¿Cómo podría determinarse empíricamente la validez del resultado?**

El resultado obtenido nos dice que el período **NO** depende de la masa y que crece como $\sqrt{l}$. Consideremos $p_0$ como el período para una masa $m_0$ y una longitud de hilo $l_0$, entonces:

- Si aumentamos la masa, mantenemos la longitud del hilo igual y el período se mantiene igual a $p_0$, entonces el resultado es válido
- Por otra parte, si aumentamos el largo del hilo a $2l_0$, entonces el período tiene que valer $\sqrt{2}p_0$. Si esto sucede entonces el resultado es válido.

Si las dos condiciones se cumplen, entonces el resultado que obtuvimos es correcto.

2. **¿Cómo podríamos, a partir de los experimentos, determinar el valor de una constante de proporcionalidad adimensionada en la ecuación?**

La respuesta a esta pregunta es bastante simple, la proporcionalidad nos dice que:

- $p=C\sqrt{\frac{l}{g}}$

Por lo tanto, sabiendo la longitud del hilo, podemos despejar sin problema la constante $C$ de proporcionalidad.
La precisión del valor de la constante va a estar dada según la cantidad de veces que hagamos el experimento.