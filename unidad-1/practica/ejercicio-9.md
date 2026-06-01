---
layout: default
title: Ejercicio 9
parent: Práctica — Unidad 1
grand_parent: Unidad 1 — Funciones
nav_order: 9
permalink: /unidad-1/practica/ejercicio-9
---

# Ejercicio 9 — Dominio natural

Hallar el dominio natural de las siguientes funciones.

## 9a

{: .enunciado }
> $y=-\sqrt{2}\,x^4-3x+\dfrac17\,x^2-2$.

{: .resolucion }
> La expresión es un polinomio de grado $4$ (suma de potencias enteras no negativas de $x$ con coeficientes reales). Los polinomios están definidos para todo número real.
>
> **Resultado:** $D=\mathbb{R}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 9b

{: .enunciado }
> $y=(x^2-3)^{-4}$.

{: .resolucion }
> Por la definición de exponente negativo:
>
> $$y=(x^2-3)^{-4}=\dfrac{1}{(x^2-3)^4}$$
>
> El denominador no puede anularse:
>
> $$(x^2-3)^4\neq 0\iff x^2-3\neq 0\iff x\neq\pm\sqrt{3}$$
>
> **Resultado:** $D=\mathbb{R}-\{-\sqrt{3},\sqrt{3}\}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 9c

{: .enunciado }
> $y=\dfrac{x^5-2x+5}{x^2-3x+2}$.

{: .resolucion }
> Cociente de polinomios. Los polinomios están definidos en $\mathbb{R}$, así que la única restricción viene del denominador no nulo. Factorizamos:
>
> $$x^2-3x+2=(x-1)(x-2)$$
>
> Las raíces son $x=1$ y $x=2$. Hay que excluirlas.
>
> **Resultado:** $D=\mathbb{R}-\{1,2\}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 9d

{: .enunciado }
> $y=\dfrac{\lvert x-1\rvert}{x+2}$.

{: .resolucion }
> El numerador $\lvert x-1\rvert$ está definido para todo $x$. El denominador no debe anularse:
>
> $$x+2\neq 0\iff x\neq-2$$
>
> **Resultado:** $D=\mathbb{R}-\{-2\}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 9e

{: .enunciado }
> $y=\sqrt{x+2}$.

{: .resolucion }
> La raíz cuadrada real exige radicando no negativo:
>
> $$x+2\geq 0\iff x\geq -2$$
>
> **Resultado:** $D=[-2,+\infty)$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 9f

{: .enunciado }
> $y=\sqrt{\dfrac{1}{2x+1}-2}$.

{: .resolucion }
> La raíz cuadrada exige radicando no negativo y, además, el denominador interno no se debe anular:
>
> $$\dfrac{1}{2x+1}-2\geq 0,\qquad 2x+1\neq 0$$
>
> La segunda condición da $x\neq -\dfrac12$. Para la primera, llevamos todo a una sola fracción:
>
> $$\dfrac{1-2(2x+1)}{2x+1}\geq 0$$
>
> $$\dfrac{-4x-1}{2x+1}\geq 0$$
>
> Multiplicamos por $-1$ (invierte la desigualdad):
>
> $$\dfrac{4x+1}{2x+1}\leq 0$$
>
> Estudiamos el signo del cociente. El numerador $4x+1$ se anula en $x=-\dfrac14$; el denominador $2x+1$ en $x=-\dfrac12$.
>
> - Para $x<-\dfrac12$: numerador y denominador ambos negativos, cociente positivo.
> - Para $-\dfrac12<x<-\dfrac14$: denominador positivo y numerador negativo, cociente negativo.
> - Para $x>-\dfrac14$: ambos positivos, cociente positivo.
>
> El cociente es $\leq 0$ en $\left(-\dfrac12,-\dfrac14\right]$. El extremo $-\dfrac14$ se incluye porque allí el numerador es $0$; el extremo $-\dfrac12$ se excluye porque anula el denominador.
>
> **Resultado:** $D=\left(-\dfrac12,-\dfrac14\right]$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 9g

{: .enunciado }
> $y=\dfrac{2x}{\sqrt{x^2-4}}$.

{: .resolucion }
> La raíz cuadrada está en el denominador, así que el radicando debe ser **estrictamente positivo**:
>
> $$x^2-4>0$$
>
> $$x^2>4$$
>
> $$x<-2\ \text{o}\ x>2$$
>
> **Resultado:** $D=(-\infty,-2)\cup(2,+\infty)$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 9h

{: .enunciado }
> $y=\dfrac{x+3}{\lvert 3x+2\rvert}+\dfrac{1}{\sqrt[4]{x+1}}$.

{: .resolucion }
> Analizamos cada término por separado e intersectamos las condiciones.
>
> **Primer término:** $\dfrac{x+3}{\lvert 3x+2\rvert}$ requiere $\lvert 3x+2\rvert\neq 0$, es decir:
>
> $$3x+2\neq 0\iff x\neq-\dfrac{2}{3}$$
>
> **Segundo término:** $\dfrac{1}{\sqrt[4]{x+1}}$ tiene raíz cuarta (índice par) en el denominador, por lo que el radicando debe ser estrictamente positivo:
>
> $$x+1>0\iff x>-1$$
>
> Intersecamos: $x>-1$ y $x\neq-\dfrac23$.
>
> **Resultado:** $D=(-1,+\infty)-\left\{-\dfrac23\right\}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 9i

{: .enunciado }
> $y=\dfrac{x^3+5x^2-6x}{x\,\sqrt[3]{x^2-1}}$.

{: .resolucion }
> El numerador es un polinomio (definido en todo $\mathbb{R}$). El denominador es un producto que no se debe anular:
>
> $$x\cdot\sqrt[3]{x^2-1}\neq 0$$
>
> La raíz cúbica (índice impar) está definida para todo real, así que no hay restricción de signo. Hay que excluir:
>
> $$x=0\quad\text{y}\quad \sqrt[3]{x^2-1}=0\iff x^2-1=0\iff x=\pm 1$$
>
> **Resultado:** $D=\mathbb{R}-\{-1,0,1\}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 9j

{: .enunciado }
> $y=\sqrt{\dfrac{3x-4}{x+1}}$.

{: .resolucion }
> La raíz cuadrada exige radicando no negativo. Como el radicando es un cociente, pedimos:
>
> $$\dfrac{3x-4}{x+1}\geq 0,\qquad x+1\neq 0$$
>
> El numerador se anula en $x=\dfrac43$, el denominador en $x=-1$. Estudiamos el signo del cociente:
>
> - $x<-1$: numerador $3x-4<0$ y denominador $x+1<0$ → cociente **positivo**.
> - $-1<x<\dfrac43$: numerador $<0$ y denominador $>0$ → cociente **negativo**.
> - $x>\dfrac43$: ambos positivos → cociente **positivo**.
>
> El cociente es $\geq 0$ en $(-\infty,-1)\cup\left[\dfrac43,+\infty\right)$. En $x=\dfrac43$ vale $0$ (se incluye); en $x=-1$ no está definido (se excluye).
>
> **Resultado:** $D=(-\infty,-1)\cup\left[\dfrac43,+\infty\right)$.
>
> **Verificación:** ⚠️ Discrepa con el [documento de respuestas oficiales](https://drive.google.com/file/d/1nJsGgi-k5Zgey-RVAF49SmP-BSGfFFGe/view), que reporta $D=\left[\dfrac43,+\infty\right)$. La respuesta oficial omite la rama $(-\infty,-1)$, donde el cociente también es positivo (numerador y denominador ambos negativos) y por lo tanto la raíz existe. **El dominio correcto es** $(-\infty,-1)\cup\left[\dfrac43,+\infty\right)$.

## 9k

{: .enunciado }
> $y=\dfrac{\sqrt{3x-4}}{\sqrt{x+1}}$.

{: .resolucion }
> A diferencia de `9j`, ahora hay **dos raíces separadas**, cada una con su propia condición.
>
> - Numerador $\sqrt{3x-4}$: radicando $\geq 0$, es decir $3x-4\geq 0\iff x\geq\dfrac43$.
> - Denominador $\sqrt{x+1}$: radicando estrictamente positivo (la raíz va abajo), es decir $x+1>0\iff x>-1$.
>
> Intersecando: la condición más fuerte es $x\geq\dfrac43$ (esta ya implica $x>-1$).
>
> **Resultado:** $D=\left[\dfrac43,+\infty\right)$.
>
> **Verificación:** ⚠️ Discrepa con el [documento de respuestas oficiales](https://drive.google.com/file/d/1nJsGgi-k5Zgey-RVAF49SmP-BSGfFFGe/view), que reporta $D=(-\infty,-1)\cup\left[\dfrac43,+\infty\right)$. Aquí no es válido el intervalo $(-\infty,-1)$: para $x<-1$ se tiene $3x-4<0$ y $\sqrt{3x-4}$ no existe en $\mathbb{R}$. La oficial parece haber confundido este caso con `9j`. Notar la diferencia clave: $\sqrt{\dfrac{a}{b}}$ (`9j`) no es lo mismo que $\dfrac{\sqrt{a}}{\sqrt{b}}$ (`9k`) en cuanto a dominio. **El dominio correcto es** $\left[\dfrac43,+\infty\right)$.

## 9l

{: .enunciado }
> $f(x)=\begin{cases} \sqrt{\dfrac{x-1}{x-3}} & \text{si } x<4, \\ \ln(5-x) & \text{si } x\geq 4. \end{cases}$

{: .resolucion }
> Calculamos por separado el dominio admisible en cada tramo y luego unimos.
>
> **Tramo $x<4$:** $\sqrt{\dfrac{x-1}{x-3}}$ exige $\dfrac{x-1}{x-3}\geq 0$ con $x\neq 3$. Estudiamos el signo:
>
> - $x<1$: ambos factores negativos → cociente positivo.
> - $1\leq x<3$: numerador $\geq 0$ y denominador $<0$ → cociente $\leq 0$ (negativo o cero).
> - $x>3$: ambos positivos → cociente positivo.
>
> El cociente es $\geq 0$ en $(-\infty,1]\cup(3,+\infty)$. Intersecando con $x<4$:
>
> $$(-\infty,1]\cup(3,4)$$
>
> **Tramo $x\geq 4$:** $\ln(5-x)$ exige $5-x>0\iff x<5$. Intersecando con $x\geq 4$:
>
> $$[4,5)$$
>
> **Unión:** $(-\infty,1]\cup(3,4)\cup[4,5)=(-\infty,1]\cup(3,5)$.
>
> **Resultado:** $D=(-\infty,1]\cup(3,5)$.
>
> **Verificación:** ⚠️ Discrepa con el [documento de respuestas oficiales](https://drive.google.com/file/d/1nJsGgi-k5Zgey-RVAF49SmP-BSGfFFGe/view), que reporta $D=[1,5)-\{3\}$. La oficial parece haber estudiado mal el signo del cociente $\dfrac{x-1}{x-3}$: para $x<1$ ambos factores $x-1$ y $x-3$ son negativos, su cociente es positivo y la raíz existe. Por lo tanto todo $(-\infty,1]$ pertenece al dominio. **El dominio correcto es** $(-\infty,1]\cup(3,5)$.

## 9m

{: .enunciado }
> $f(x)=\begin{cases} \sqrt{4-x^2} & \text{si } x\leq 2, \\ \dfrac{1}{x-1} & \text{si } x>2. \end{cases}$

{: .resolucion }
> **Tramo $x\leq 2$:** $\sqrt{4-x^2}$ exige $4-x^2\geq 0\iff -2\leq x\leq 2$. Intersecando con $x\leq 2$: $[-2,2]$.
>
> **Tramo $x>2$:** $\dfrac{1}{x-1}$ exige $x\neq 1$, pero $1\notin(2,+\infty)$, por lo que vale todo $(2,+\infty)$.
>
> **Unión:** $[-2,2]\cup(2,+\infty)=[-2,+\infty)$.
>
> **Resultado:** $D=[-2,+\infty)$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 9n

{: .enunciado }
> $f(x)=\begin{cases} \sqrt{x^2-9} & \text{si } x<4, \\ \dfrac{1}{x^2-1} & \text{si } x\geq 4. \end{cases}$

{: .resolucion }
> **Tramo $x<4$:** $\sqrt{x^2-9}$ exige $x^2-9\geq 0\iff x\leq -3$ o $x\geq 3$. Intersecando con $x<4$: $(-\infty,-3]\cup[3,4)$.
>
> **Tramo $x\geq 4$:** $\dfrac{1}{x^2-1}$ exige $x\neq\pm 1$, pero ninguno está en $[4,+\infty)$, por lo que vale todo $[4,+\infty)$.
>
> **Unión:** $(-\infty,-3]\cup[3,4)\cup[4,+\infty)=(-\infty,-3]\cup[3,+\infty)$.
>
> **Resultado:** $D=(-\infty,-3]\cup[3,+\infty)$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 9ñ

{: .enunciado }
> $f(x)=\begin{cases} \dfrac{1}{\sqrt{5-x}} & \text{si } x<3, \\ \sqrt{\ln(x-2)} & \text{si } x\geq 3. \end{cases}$

{: .resolucion }
> **Tramo $x<3$:** $\dfrac{1}{\sqrt{5-x}}$ exige raíz definida y denominador no nulo, es decir $5-x>0\iff x<5$. Intersecando con $x<3$: vale todo $(-\infty,3)$.
>
> **Tramo $x\geq 3$:** $\sqrt{\ln(x-2)}$ exige $\ln(x-2)\geq 0$, lo que equivale a $x-2\geq 1\iff x\geq 3$ (y $x-2>0$ ya se cumple). Intersecando con $x\geq 3$: vale todo $[3,+\infty)$.
>
> **Unión:** $(-\infty,3)\cup[3,+\infty)=\mathbb{R}$.
>
> **Resultado:** $D=\mathbb{R}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

