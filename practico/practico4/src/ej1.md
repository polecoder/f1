# Ejercicio 01 - Fuerzas y leyes de Newton

**Fecha:** 09-04-2026
**Estado:** 🟢 Resuelto solo

## Consigna

1. Sobre un objeto se ejercen las fuerzas $\vec{F}_1 = \frac{75}{\sqrt{2}}(\hat{\imath} - \hat{\jmath})$ y $\vec{F}_2 = \frac{150}{\sqrt{2}}(\hat{\imath} + \hat{\jmath})$ expresadas en $N$. ¿Qué tercera fuerza, $\vec{F}_3$, se necesita para equilibrarlas?
2. Dos perros, $A$ y $B$, tiran horizontalmente de cuerdas atadas a un poste. El ángulo entre las cuerdas es de $60{.}0^\circ$. Si el perro $A$ ejerce una fuerza de $270\ \text{N}$, y el $B$, de $300\ \text{N}$, calcule el módulo de la fuerza resultante y su ángulo con respecto a la cuerda del perro $A$.

## Resolución

### Parte 1

- Sobre un objeto se ejercen las fuerzas $\vec{F}_1 = \frac{75}{\sqrt{2}}(\hat{\imath} - \hat{\jmath})$ y $\vec{F}_2 = \frac{150}{\sqrt{2}}(\hat{\imath} + \hat{\jmath})$ expresadas en $N$. ¿Qué tercera fuerza, $\vec{F}_3$, se necesita para equilibrarlas?

Expresemos las fuerzas como vectores usando las expresiones que nos dió la consigna:

- $\vec{F_1}=(\frac{75}{\sqrt{2}},-\frac{75}{\sqrt{2}})$
- $\vec{F_2}=(\frac{150}{\sqrt{2}},\frac{150}{\sqrt{2}})$

Con esto podemos sumar las vectores para obtener la fuerza neta del objeto antes de sumar la tercera fuerza.

- $\vec{F_1}+\vec{F_2}=(\frac{75}{\sqrt{2}},-\frac{75}{\sqrt{2}})+(\frac{150}{\sqrt{2}},\frac{150}{\sqrt{2}})=(\frac{225}{\sqrt{2}},\frac{75}{\sqrt{2}})$

Entonces, si necesitamos que la fuerza neta sea cero, tendríamos que agregar un vector opuesto al que obtuvimos sumando $\vec{F_1}$ y $\vec{F_2}$. Con esto concluimos que:

- $\vec{F_3}=-(\vec{F_1}+\vec{F_2})=(-\frac{225}{\sqrt{2}},-\frac{75}{\sqrt{2}})N$

### Parte 2

- Dos perros, $A$ y $B$, tiran horizontalmente de cuerdas atadas a un poste. El ángulo entre las cuerdas es de $60{.}0^\circ$. Si el perro $A$ ejerce una fuerza de $270\ \text{N}$, y el $B$, de $300\ \text{N}$, calcule el módulo de la fuerza resultante y su ángulo con respecto a la cuerda del perro $A$.

**Nota:** Llegamos a un punto débil de este tipo de ejercicios: es díficil hacer buenas representaciones gráficas del problema para esta forma de tomar apuntes. De tener la posibilidad, SIEMPRE hacer un dibujo para entender que está pasando.

Elegiremos una convención para representar el problema en un plano de coordenadas cartesianas. En ésta, el poste está ubicado en el origen, el perro $A$ forma un ángulo de $0$ con respecto al eje $x$, mientras que el perro $B$ forma un ángulo de $60^{\circ}$. Esta es una fiel representación del problema ya que se dan las condiciones que nos piden.

Bajo estas condiciones, expresamos las fuerzas usando las funciones trigonométricas:

- $F_A=(270.0,0)$
- $F_B=(300\cdot\cos(60^{\circ}),300\cdot\sin(60^{\circ}))=(150.0,259.8)$

Entonces la fuerza resultante es la suma entre éstas:

- $F_N=F_A+F_B=(270.0,0)+(150.0,259.8)=(420.0,259.8)$

Como nos piden el módulo, calculemos usando Pitágoras:

- $|F_N|=\sqrt{420.0^2+259.8^2}\approx\sqrt{176400+67496}=\sqrt{243896}\approx493.9$

Y como nos piden el ángulo con respecto al perro $A$ (que coincide con el ángulo respecto al eje $x$).

$$
\begin{aligned}
&\theta=arctan\left(\frac{259.8}{420.0}\right)\\
&\iff\scriptstyle{(\text{operatoria})}\\
&\theta\approx31.74^{\circ}
\end{aligned}
$$

Esto concluye el ejercicio.