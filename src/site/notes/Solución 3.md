---
{"dg-publish":true,"permalink":"/solucion-3/","noteIcon":""}
---


**Descomposición en Fracciones Parciales**

A primera vista, la fracción pareciera tener un factor cuadrático en el denominador. Sin embargo, podemos factorizar esta expresión de la siguiente forma:

$$x^2 - x - 12 = (x + 3)(x - 4)$$

Entonces, la expresión solo tiene factores lineales:

$$\frac{9x^2+34x+14}{(x+2)(x^2-x-12)} = \frac{9x^2+34x+14}{(x+2)(x+3)(x-4)}$$


Dado que solo tenemos factores lineales, las fracciones parciales tienen la siguiente forma:

$$\frac{9x^2+34x+14}{(x+2)(x+3)(x-4)} = \frac{A}{x+2} + \frac{B}{x+3} + \frac{C}{x-4}$$

$$\frac{9x^2+34x+14}{(x+2)(x+3)(x-4)} = \frac{x+2}{x+2}A + \frac{x+3}{x+3}B + \frac{x-4}{x-4}C$$


Ahora, vamos a multiplicar a toda la expresión por: $$(x+2)(x+3)(x-4)$$

$$9x^2+34x+14 = A(x+3)(x-4) + B(x+2)(x-4) + C(x+2)(x+3)$$


Podemos encontrar el valor de A al usar: $$x=-2$$

$$9(-2)^2+34(-2)+14 = A(-2+3)(-2-4) + B(-2+2)(-2-4) + C(-2+2)(-2+3)$$

$$-18 = -6A$$

$$A = 3$$

Podemos encontrar el valor de B al usar: $$x=-3$$

$$9(-3)^2+34(-3)+14 = A(-3+3)(-3-4) + B(-3+2)(-3-4) + C(-3+2)(-3+3)$$

$$-7 = 7B$$

$$B = -1$$

Podemos encontrar el valor de C al usar: $$x=4$$

$$9(4)^2+34(4)+14 = A(4+3)(4-4) + B(4+2)(4-4) + C(4+2)(4+3)$$

$$294 = 42C$$

$$C = 7$$

Entonces, las fracciones parciales son:

$$\frac{9x^2+34x+14}{(x+2)(x+3)(x-4)} = \frac{3}{x+2} - \frac{1}{x+3} + \frac{7}{x-4}$$

