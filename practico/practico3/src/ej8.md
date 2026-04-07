# Ejercicio 08 - Movimiento relativo

**Fecha:** 07-04-2026
**Estado:** 🟢 Resuelto solo

## Consigna

Un avión ligero alcanza una velocidad en el aire de $480km/h$. El piloto se dispone a salir hacia un destino situado $810km$ al norte, pero descubre que el avión debe enfilar a $21^\circ$ NE para poder volar hacia allí directamente. El avión llega en $1.9h$. ¿Cuál fue el vector de la velocidad del viento?

**Nota:** El noreste, NE, dirección entre el norte el este, se usa aquí para indicar que el ángulo se mide desde el norte, girando hacia el este.

## Resolución

Parte de la dificultad de este ejercicio está en entender a nivel gráfico que es lo que está pasando y como interviene cada dato.

El vector velocidad del avión es una suma de la velocidad que tiene hacia la dirección $21^{\circ}$ más la velocidad que tiene el viento. Llamemos $v_P$ a la dirección que establece el piloto, para ésta podemos calcular sus componentes a partir de los datos dados.

- $|v_P|=480km/h$
- $\theta_P=90^{\circ}-21^{\circ}=69^{\circ}$ (basado en la nota que trae la consigna)

Con esto tenemos los componentes del vector velocidad $v_P$:

- ${v_P}_x=480km/h\cdot\cos(69^{\circ})=172.0$
- ${v_P}_y=480km/h\cdot\sin(69^{\circ})=448.1$

Por otra parte, también conocemos la velocidad constante (hacia el norte) que tiene que haber mantenido el avión para llegar a su destino en $1.9h$, la llamaremos $v_A$:

- $\text{velocidad}=\frac{\text{distancia recorrida}}{\text{tiempo}}$, entonces:
- $v_A=\frac{810km}{1.9h}=426.3km/h$ hacia el norte, y por lo tanto en forma vectorial:
- $v_A=(0,\ 426.3)km/h$

Por lo tanto queremos encontrar la velocidad del viento $v_V$ tal que:

- $v_A=v_P+v_V$

Operando para despejar la velocidad del viento:

$$
\begin{aligned}
&v_V=v_A-v_P\\
&\iff\scriptstyle{(\text{reemplazando por los valores conocidos})}\\
&v_V=(0,\ 426.3)-(172.1,\ 448.1)\\
&\iff\scriptstyle{(\text{operatoria})}\\
&v_V=(-172.1,\ -21.8)\\
\end{aligned}
$$

Con esto se concluye el ejercicio.