# Ejercicio 05 - Movimiento unidimensional

**Fecha:** 26-03-2026
**Estado:** 🟢 Resuelto solo

## Consigna

Consideremos una partícula que se puede mover a lo largo de un eje $x$. Contesta las siguientes preguntas:

1. ¿Puede la velocidad de la partícula tener una componente siempre negativa?
2. ¿Puede la partícula tener velocidad cero y aún así acelerar?
3. ¿Puede la partícula invertir el sentido de su velocidad cuando su aceleración tiene módulo, dirección y sentido constantes?

Justifica tus respuestas. Si la respuesta es afirmativa, proporciona algún ejemplo. En caso contrario, explica por qué la situación no es posible.

## Resolución

### Parte 1

- ¿Puede la velocidad de la partícula tener una componente siempre negativa?

Intrepretamos la pregunta como: ¿Puede la velocidad instantánea de la partícula ser siempre negativa?

Sí, pues si consideramos un movimiento que empieza en una posición inicial $x_0$, y se mueve con velocidad constante $v$ hacia una posición final $x_1$ tal que $x_1<x_0$, entonces la velocidad que mencionamos $v$ será negativa.

### Parte 2

- ¿Puede la partícula tener velocidad cero y aún así acelerar?

Intuitivamente esto puede tener sentido, veamos el detalle considerando funciones genéricas $x(t),v(t)$ y $a(t)$.

- $x=A+Bt+Ct^2$
- $v=B+2Ct$
- $a=2C$

Queremos buscar un caso donde $C\neq0$ (para tener aceleración distinta de cero), pero $v=0$. Esto sucede cuando $B=-2Ct$. Entonces si el movimiento de la partícula estuviera descrito por la función $v(t)=-2+2t$, tendríamos que:

- En $t=1$ la función se anula, por lo que $v(1)=0$, es decir que la velocidad instantánea en $t=1$ es cero.
- En $t=1$ la aceleración está descrita por la función $a(t)=2$, entonces está acelerando.

Concluímos entonces que es posible que la partícula tenga velocidad cero y aún así acelerar.

### Parte 3

- ¿Puede la partícula invertir el sentido de su velocidad cuando su aceleración tiene módulo, dirección y sentido constantes?

En este ejemplo, invertir el sentido de su velocidad significa cambiar el sentido del movimiento.
Nuevamente, de forma intuitiva es fácil entender que esto si es posible, pero vayamos a un ejemplo. Si la aceleración es constante, entonces la posición de la partícula está dada por la función lineal:

- $x(t)=v_0+at$

Por lo tanto, si consideramos $v_0=5$ y $a=-2$, entonces la velocidad empezará siendo positiva, y terminará siendo negativa.

Concluímos entonces que es posible qe la partícula invierta el sentido de su velocidad con una aceleración constante.
