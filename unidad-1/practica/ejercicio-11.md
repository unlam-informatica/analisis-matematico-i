---
layout: default
title: Ejercicio 11
parent: Práctica — Unidad 1
grand_parent: Unidad 1 — Funciones
nav_order: 11
permalink: /unidad-1/practica/ejercicio-11
---

# Ejercicio 11 — Funciones por tramos

### `11a` - $f(x)=x+2\,(x\le-1);\ -x\,(-1<x\le1);\ 3x-4\,(1<x\le3);\ 2\,(x>3)$

- **Dominio:** los tramos cubren todo, $D=\mathbb{R}$.
- **Imagen:** tramo 1 ($x\le-1$): $x+2\le1$, da $(-\infty,1]$. Tramo 2 ($-1<x\le1$): $-x\in[-1,1)$. Tramo 3 ($1<x\le3$): $3x-4\in(-1,5]$. Tramo 4: $\{2\}$. La unión es $(-\infty,5]$.
- **Ceros:** $x+2=0\Rightarrow x=-2$ (válido); $-x=0\Rightarrow x=0$ (válido); $3x-4=0\Rightarrow x=\tfrac43$ (válido, está en $(1,3]$); el tramo $=2$ no se anula. Ceros $\{-2,0,\tfrac43\}$.

**Resultado: $D=\mathbb{R}$, $I=(-\infty,5]$, ceros $\{-2,0,\tfrac43\}$.** ✓ Coincide.

### `11b`* - $f(x)=\dfrac{x^2-6x+9}{x-3}\ (x\neq3);\ 4\ (x=3)$

Simplificamos: $\dfrac{(x-3)^2}{x-3}=x-3$ para $x\neq3$. Es la recta $y=x-3$ con un punto desplazado: en $x=3$ vale $4$ en vez de $0$.

- $D=\mathbb{R}$.
- **Imagen:** la recta $x-3$ cubre todo $\mathbb{R}$ salvo el valor en $x=3$ (que sería $0$, pero queda excluido porque allí $f=4$). El valor $4$ ya lo aporta la recta en $x=7$. Entonces $I=\mathbb{R}-\{0\}$.
- **Ceros:** $x-3=0\Rightarrow x=3$, pero en $x=3$ la función vale $4\neq0$. No hay ceros.

**Resultado: $D=\mathbb{R}$, $I=\mathbb{R}-\{0\}$, sin ceros.** ✓ Coincide.

### `11c` - $f(x)=\lvert x+\tfrac12\rvert\,(x\le2);\ \lvert x-4\rvert\,(x>2)$

- $D=\mathbb{R}$.
- **Imagen:** tramo 1 ($x\le2$): $\lvert x+\tfrac12\rvert$ tiene mínimo $0$ en $x=-\tfrac12$ y crece; en $x=2$ vale $2{,}5$, da $[0,2{,}5]$. Tramo 2 ($x>2$): $\lvert x-4\rvert$, mínimo $0$ en $x=4$; en $x\to2^+$ vale $2$ y crece sin cota, da $[0,+\infty)$. Unión: $[0,+\infty)$.
- **Ceros:** $\lvert x+\tfrac12\rvert=0\Rightarrow x=-\tfrac12$ (válido, $\le2$); $\lvert x-4\rvert=0\Rightarrow x=4$ (válido, $>2$). Ceros $\{-\tfrac12,4\}$.

**Resultado: $D=\mathbb{R}$, $I=[0,+\infty)$, ceros $\{-\tfrac12,4\}$.** ✓ Coincide.

### `11d` - Interpretado como $f(x)=\sqrt{x+4}\,(x\ge-3);\ x+3\,(-4\le x<-3);\ \sqrt[3]{x}+3\,(x<-4)$

- $D=\mathbb{R}$ (los tramos cubren $x<-4$, $-4\le x<-3$ y $x\ge-3$).
- **Imagen:** tramo $x\ge-3$: $\sqrt{x+4}\ge\sqrt1=1$, da $[1,+\infty)$. Tramo $-4\le x<-3$: $x+3\in[-1,0)$. Tramo $x<-4$: $\sqrt[3]{x}+3$, con $x<-4$ se tiene $\sqrt[3]{x}<\sqrt[3]{-4}\approx-1{,}59$, da $(-\infty,\,3+\sqrt[3]{-4})=(-\infty,\approx1{,}41)$. La unión cubre $\mathbb{R}$.
- **Ceros:** $\sqrt{x+4}=0\Rightarrow x=-4$, pero $-4\notin[-3,+\infty)$: no aplica. $x+3=0\Rightarrow x=-3$, pero $-3\notin[-4,-3)$: no aplica. $\sqrt[3]{x}+3=0\Rightarrow\sqrt[3]{x}=-3\Rightarrow x=-27$ (válido, $<-4$). Cero $\{-27\}$.

**Resultado: $D=\mathbb{R}$, $I=\mathbb{R}$, cero $\{-27\}$.** ✓ Coincide.

