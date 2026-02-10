# Ejercicio 04 - Física de fluidos

**Fecha:** 10-02-2026
**Estado:** 🟡 Con ayuda

## Consigna

Considera un fluido que recorre un tubo. Comparando las dimensiones físicas, determina una relación funcional entre el flujo de masa, el flujo volumétrico y la densidad del fluido.

Los significados de estas magnitudes son:

1. **Flujo de masa o flujo másico**: la cantidad de masa del fluido que pasa por una sección del tubo por unidad de tiempo.
2. **Flujo volumétrico**: el volumen de fluido que pasa por una sección del tubo por unidad de tiempo.
3. **Densidad**: la cantidad de masa por unidad de volumen. Se simboliza habitualmente con la letra griega $\rho$.

## Resolución

Representaremos el flujo másico y volumétrico por $f_m$ y $f_v$, estableceremos en base a lo que se nos menciona las dimensiones de cada cantidad.

- **Flujo másico**: $[f_m]=MT^{-1}$
- **Flujo volumétrico**: $[f_v]=L^3T^{-1}$
- **Densidad**: $[\rho]=ML^{-3}$

Este es el primer paso, mirando bien las dimensiones de cada cantidad, se encuentra fácilmente la relación que tienen entre ellas:

$$
\begin{aligned}
&[f_m]=MT^{-1}\\
&\iff\scriptstyle{(\text{operatoria})}\\
&[f_m]=(ML^{-3})(L^3T^{-1})\\
&\iff\scriptstyle{(\text{dimensiones de la densidad y el flujo volumétrico})}\\
&[f_m]=[f_v][\rho]\\
&\iff\scriptstyle{(\text{operatoria})}\\
&[f_m]=[f_v\rho]\\
\end{aligned}
$$

Por lo tanto la relación que tenemos entre estas cantidades físicas es:

- $f_m\propto f_v\rho$