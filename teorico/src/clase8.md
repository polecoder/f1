# Clase 08 - Fuerza y leyes de Newton

**Fecha:** 08-04-2026

## Masa

### Definición operacional de la masa inercial

En el marco de la mecánica clásica, la masa no se define mediante conceptos cualitativos como "cantidad de materia", sino a través de un procedimiento operacional estrictamente dinámico. Se define la masa como una propiedad intrínseca del cuerpo que cuantifica su inercia, es decir, su resistencia a los cambios en su estado de movimiento.

Para determinar la masa de un cuerpo, se establece un patrón de masa inercial ($m_0$) de $1kg$. El valor de una masa desconocida ($m_1$) se obtiene mediante la comparación de las aceleraciones producidas al aplicar una misma fuerza $F$ sobre ambos cuerpos en un entorno carente de fricción:

$$
\frac{m_1}{m_0}=\frac{a_0}{a_1}
$$

### Propiedades técnicas fundamentales

- **Independencia de la fuerza:** Experimentalmente se verifica que la razón de las masas $m_1/m_0$ es independiente de la magnitud de la fuerza $F$ empleada para el ensayo. Esto confirma que la masa es una propiedad inherente al objeto y no depende ni del entorno ni del estado de movimiento.
- **Naturaleza escalar:** La masa es una magnitud escalar; su valor es independiente de la dirección de la aceleración o de la orientación del cuerpo.
- **Aditividad:** Las masas se combinan mediante suma algebraica simple $(m=m_1+m_2)$. Un sistema compuesto por dos masas se comporta inercialmente como un único cuerpo cuya masa es la suma de sus constituyentes.

## Segunda ley de Newton

### Introducción

La segunda ley de Newton establece la relación fundamental entre la fuerza neta aplicada, la masa inercial y la aceleración resultante. Al igual que la primera ley, este enunciado es válido exclusivamente en **marcos de referencia inerciales**. La ecuación vectorial fundamental es:

- $\sum F=ma$

### Especificaciones operativas

- **Fuerza neta $(\sum F)$:** Representa la suma vectorial de todas las fuerzas externas que actuan sobre el cuerpo.
- **Componentes rectangulares:** Como ya hemos visto varias veces en este curso, la ecuación vectorial se descompone en tres ecuaciones escalares independientes:
    
    - $\sum F_x=ma_x$
    - $\sum F_y=ma_y$
    - $\sum F_z=ma_z$

- **Relación de proporcionalidad:** La aceleración es directamente proporcional a la fuerza neta, e inversamente proporcional a la masa inercial del cuerpo. Esto se deduce del siguiente despeje:

    - $\frac{\sum F}{m}=a$

### Unidades y dimensiones (SI)

El **Newton (N)** es una unidad derivada definida por la relación fundamental. En el Sistema Internacional, se selecciona una constante de proporcionalidad unitaria $(k=1)$, por lo que:

- $1N=1kg\cdot m/s^2$

Como vimos en la clase anterior, técnicamente, **un Newton es la fuerza neta necesaria para impartir una aceleración de $1m/s^2$ a un cuerpo de masa $1kg$.**

### Metodología de aplicación: Diagramas de cuerpo libre (DCL)

Cuando trabajemos con problemas relacionados a la dinámica de la partícula, es importante entender que es el diagrama de cuerpo libre.
Ésta es la herramienta técnica indispensable para el aislamiento analítico de un sistema. En mecánica clásica, los cuerpos se modelan como partículas, asumiendo que todas las fuerzas externas actúan sobre un único punto. Veamos como funciona dividiendo el proceso en varios pasos:

1. **Selección del sistema:** Identificar el cuerpo o sistema de partículas objeto de estudio.
2. **Aislamiento:** Representar el cuerpo separado de su entorno (superficies, cuerdas, resortes o campos).
3. **Representación vectorial:** Trazar todas las fuerzas externas que el entorno ejerce **sobre** el cuerpo. No se incluyen las fuerzas internas o de las fuerzas que el cuerpo ejerce sobre su entorno.

## Tercera ley de Newton

Este principio describe la naturaleza de las interacciones mutuas y simultáneas entre dos cuerpos. No existe una precedencia temporal; ambas fuerzas surgen y desaparecen en el mismo instante.
Cuando dos cuerpos $A$ y $B$ interactúan, la fuerza ejercida por $A$ sobre $B$, es decir $F_{BA}$, es igual en magnitud y opuesta en dirección a la fuerza ejercida por $B$ sobre $A$, es decir $F_{AB}$:

- $F_{AB}=-F_{BA}$

**Nota:** Las fuerzas de un par acción-reacción actúan siempre sobre cuerpos **distintos**. Por definición, estas dos fuerzas nunca pueden aparecer en el mismo diagrama de cuerpo libre ni sumarse para calcular la fuerza neta sobre un solo objeto.