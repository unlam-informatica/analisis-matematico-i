---
layout: default
title: Ejercicio 13
parent: Práctica — Unidad 1
grand_parent: Unidad 1 — Funciones
nav_order: 13
permalink: /unidad-1/practica/ejercicio-13
---

# Ejercicio 13 — Paridad

Indicar si las siguientes funciones son pares, impares o ninguna de las dos.

**Recordatorio.** Una función $f$ es:

- **Par** si $f(-x)=f(x)$ para todo $x$ del dominio (simétrica respecto al eje $y$).
- **Impar** si $f(-x)=-f(x)$ para todo $x$ del dominio (simétrica respecto al origen).
- **Ninguna** en otro caso.

En todos los incisos calculamos $f(-x)$ reemplazando $x$ por $-x$ en la regla y comparamos con $f(x)$ y $-f(x)$.

## 13a

{: .enunciado }
> $f(x)=x^2-4$.

{: .resolucion }
> Reemplazamos:
>
> $$f(-x)=(-x)^2-4=x^2-4=f(x).$$
>
> Coincide con $f(x)$.
>
> **Resultado:** $f$ es **par**.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 13b

{: .enunciado }
> $g(x)=x^2+x-2$.

{: .resolucion }
> Reemplazamos:
>
> $$g(-x)=(-x)^2+(-x)-2=x^2-x-2.$$
>
> Comparamos:
>
> $$g(x)=x^2+x-2,\qquad -g(x)=-x^2-x+2.$$
>
> $g(-x)$ no coincide con $g(x)$ ni con $-g(x)$ (por el término lineal).
>
> **Resultado:** $g$ no es ni par ni impar (**ninguna**).
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 13c

{: .enunciado }
> $f(x)=\lvert x+1\rvert-\lvert x-1\rvert$.

{: .resolucion }
> Reemplazamos:
>
> $$f(-x)=\lvert -x+1\rvert-\lvert -x-1\rvert.$$
>
> Usamos la propiedad $\lvert -a\rvert=\lvert a\rvert$:
>
> $$f(-x)=\lvert x-1\rvert-\lvert x+1\rvert.$$
>
> Reordenando:
>
> $$f(-x)=-\bigl(\lvert x+1\rvert-\lvert x-1\rvert\bigr)=-f(x).$$
>
> **Resultado:** $f$ es **impar**.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 13d

{: .enunciado }
> $h(x)=x+1$.

{: .resolucion }
> Reemplazamos:
>
> $$h(-x)=-x+1.$$
>
> Comparamos:
>
> $$h(x)=x+1,\qquad -h(x)=-x-1.$$
>
> $h(-x)=-x+1$ no coincide con ninguna de las dos.
>
> **Resultado:** $h$ no es ni par ni impar (**ninguna**).
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 13e

{: .enunciado }
> $g(x)=\sqrt[3]{x}$.

{: .resolucion }
> Usamos la propiedad de la raíz cúbica $\sqrt[3]{-a}=-\sqrt[3]{a}$:
>
> $$g(-x)=\sqrt[3]{-x}=-\sqrt[3]{x}=-g(x).$$
>
> **Resultado:** $g$ es **impar**.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 13f*

{: .enunciado }
> $h(x)=\sqrt[3]{x^2}$.

{: .resolucion }
> Reemplazamos:
>
> $$h(-x)=\sqrt[3]{(-x)^2}=\sqrt[3]{x^2}=h(x).$$
>
> El cuadrado neutraliza el signo, y la raíz cúbica conserva la igualdad.
>
> **Resultado:** $h$ es **par**.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 13g*

{: .enunciado }
> $m(x)=x-3x^3$.

{: .resolucion }
> Reemplazamos:
>
> $$m(-x)=(-x)-3(-x)^3=-x-3\cdot(-x^3)=-x+3x^3.$$
>
> Factorizamos un $-1$:
>
> $$m(-x)=-(x-3x^3)=-m(x).$$
>
> **Resultado:** $m$ es **impar**.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 13h*

{: .enunciado }
> $y=\dfrac{1-x}{1+x}$.

{: .resolucion }
> Llamamos $f(x)=\dfrac{1-x}{1+x}$. Reemplazamos:
>
> $$f(-x)=\dfrac{1-(-x)}{1+(-x)}=\dfrac{1+x}{1-x}.$$
>
> Comparamos. Notar que $\dfrac{1+x}{1-x}$ es el **inverso** multiplicativo de $f(x)$, no su opuesto:
>
> $$f(x)\cdot f(-x)=\dfrac{1-x}{1+x}\cdot\dfrac{1+x}{1-x}=1.$$
>
> Por lo tanto $f(-x)\neq f(x)$ y $f(-x)\neq -f(x)$ en general.
>
> **Resultado:** $f$ no es ni par ni impar (**ninguna**).
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 13i

{: .enunciado }
> $g(x)=\dfrac{1}{\lvert x\rvert}$.

{: .resolucion }
> Reemplazamos y usamos $\lvert -x\rvert=\lvert x\rvert$:
>
> $$g(-x)=\dfrac{1}{\lvert -x\rvert}=\dfrac{1}{\lvert x\rvert}=g(x).$$
>
> **Resultado:** $g$ es **par**.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

## 13j

{: .enunciado }
> $f(x)=2^x+2^{-x}$.

{: .resolucion }
> Reemplazamos:
>
> $$f(-x)=2^{-x}+2^{-(-x)}=2^{-x}+2^x.$$
>
> La suma es conmutativa, así que:
>
> $$f(-x)=2^x+2^{-x}=f(x).$$
>
> **Resultado:** $f$ es **par**.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

---

## Resumen

- **Pares:** $\{a,\,f,\,i,\,j\}$.
- **Impares:** $\{c,\,e,\,g\}$.
- **Ninguna:** $\{b,\,d,\,h\}$.
