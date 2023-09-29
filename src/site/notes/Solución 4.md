---
{"dg-publish":true,"permalink":"/Solución 4/","noteIcon":""}
---


**Descomposición en Fracciones Parciales**

El factor cuadrático $x^2+2$ del denominador no puede ser factorizado. Entonces, las fracciones parciales tienen la forma:

$$\frac{6x+7}{(x^2+2)(x+3)} = \frac{Ax+B}{x^2+2} + \frac{C}{x+3}$$

Multiplicando a ambos lados de la expresión por $(x^2+2)(x+3)$, tenemos:

$$6x+7=(Ax+B)(x+3)+C(x^2+2)$$

Podemos encontrar el valor de C al sustituir $x=-3$, de modo que el término $(Ax+B)$ sea igual a cero:

$$6(-3)+7=(A(-3)+B)(-3+3)+C((-3)^2+2)$$

$$-11=11C$$

$$C=-1$$

Ahora, podemos encontrar el valor de A al comparar a los coeficientes de los términos con $x^2$. En la izquierda no tenemos y en la derecha tenemos $Ax^2+Cx^2$. Entonces:

$$0=A+C$$

$$0=A+(-1)$$

$$A=1$$

Podemos encontrar el valor de B al comparar a los coeficientes de los términos constantes:

$$7=3B+2C$$

$$7=3B+2(-1)$$

$$B=3$$

Entonces, las fracciones parciales son:

$$\frac{6x+7}{(x^2+2)(x+3)} = \frac{x+3}{x^2+2} - \frac{1}{x+3}$$
