---
layout: default
title: Ejercicio 14
parent: Práctica — Unidad 2
grand_parent: Unidad 2 — Límite y Continuidad
nav_order: 14
permalink: /unidad-2/practica/ejercicio-14
---

# Ejercicio 14 — Límites trigonométricos

Usamos $\operatorname{sen}u\sim u$, $1-\cos u\sim \tfrac{u^2}{2}$, $\tan u\sim u$ cuando $u\to0$.

## 14a
$\lim_{x\to0}\dfrac{\operatorname{sen}4x}{3x}$

$$\dfrac{\operatorname{sen}4x}{3x}=\dfrac{4}{3}\cdot\dfrac{\operatorname{sen}4x}{4x}\to\dfrac{4}{3}\cdot 1=\mathbf{\dfrac{4}{3}}$$

✓ Coincide con la respuesta oficial.

## 14b
$\lim_{x\to0}\dfrac{\operatorname{sen}4x}{\operatorname{sen}5x}$

$\operatorname{sen}4x\sim 4x$, $\operatorname{sen}5x\sim 5x$:

$$\dfrac{4x}{5x}=\dfrac{4}{5}=\mathbf{\dfrac{4}{5}}$$

✓ Coincide con la respuesta oficial.

## 14c
$\lim_{x\to0}\dfrac{\operatorname{sen}^2 3x}{4x^2}$

$\operatorname{sen}^2 3x\sim (3x)^2=9x^2$:

$$\dfrac{9x^2}{4x^2}=\dfrac{9}{4}=\mathbf{\dfrac{9}{4}}$$

✓ Coincide con la respuesta oficial.

## 14d
$\lim_{x\to0}\dfrac{x\operatorname{sen}x}{1-\cos x}$

Numerador $\sim x\cdot x=x^2$; denominador $1-\cos x\sim \tfrac{x^2}{2}$:

$$\dfrac{x^2}{x^2/2}=2=\mathbf{2}$$

✓ Coincide con la respuesta oficial.

## 14e
* $\lim_{z\to0}\dfrac{1-\cos 3z}{z^2}$

$1-\cos 3z\sim \tfrac{(3z)^2}{2}=\tfrac{9z^2}{2}$:

$$\dfrac{9z^2/2}{z^2}=\dfrac{9}{2}=\mathbf{\dfrac{9}{2}}$$

✓ Coincide con la respuesta oficial.

## 14f
$\lim_{x\to a}\dfrac{\operatorname{sen}(x-a)}{x-a}$

Sustituyendo $u=x-a\to0$: $\lim_{u\to0}\dfrac{\operatorname{sen}u}{u}=\mathbf{1}.$

✓ Coincide con la respuesta oficial.

## 14g
$\lim_{x\to0^+}\left(\dfrac{\operatorname{sen}2x}{x}\right)^{\tan 3x/x}$

Base: $\dfrac{\operatorname{sen}2x}{x}\to 2$. Exponente: $\dfrac{\tan 3x}{x}\to 3$ (pues $\tan 3x\sim 3x$). La base tiende a $2\neq 1$, por lo que no hay indeterminación $1^\infty$:

$$\to 2^{3}=8=\mathbf{8}$$

✓ Coincide con la respuesta oficial.

## 14h
* $\lim_{x\to0}\dfrac{2\operatorname{sen}x+3x\cos x}{3\operatorname{sen}x-x\cos x}$

Dividimos numerador y denominador por $x$ y usamos $\dfrac{\operatorname{sen}x}{x}\to1$, $\cos x\to1$:

$$\dfrac{2\frac{\operatorname{sen}x}{x}+3\cos x}{3\frac{\operatorname{sen}x}{x}-\cos x}\to\dfrac{2\cdot 1+3\cdot 1}{3\cdot 1-1}=\dfrac{5}{2}=\mathbf{\dfrac{5}{2}}$$

✓ Coincide con la respuesta oficial.

## 14i
$\lim_{x\to3}\dfrac{\operatorname{sen}(x^2-10x+21)}{x-3}$

Factorizamos el argumento: $x^2-10x+21=(x-3)(x-7)$. Con $u=(x-3)(x-7)\to0$:

$$\dfrac{\operatorname{sen}\big((x-3)(x-7)\big)}{x-3}=\dfrac{\operatorname{sen}\big((x-3)(x-7)\big)}{(x-3)(x-7)}\cdot(x-7)$$

El primer factor $\to1$ y $(x-7)\to-4$:

$$\to 1\cdot(-4)=-4=\mathbf{-4}$$

✓ Coincide con la respuesta oficial.

