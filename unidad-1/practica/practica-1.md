---
layout: default
title: Práctica — Unidad 1
parent: Unidad 1 — Funciones
permalink: /unidad-1/practica/practica-1
nav_order: 2
---

# Práctica 1 — Funciones

Resolución completa y paso a paso de la **Práctica 1: Funciones**. 

Cada ejercicio incluye el enunciado resumido, el desarrollo con explicaciones, el resultado final en negrita y la comparación con la respuesta oficial. Los gráficos se sugiere verificarlos en **GeoGebra**; aquí se determinan analíticamente dominio, imagen, ceros, asíntotas y transformaciones.

## Ejercicio 1 — Graficar, indicar dominio e imagen

### `1a`

{: .enunciado }
> La función lineal que pasa por $P(-3,4)$ y $Q(2,-3)$.

{: .resolucion }
> La pendiente es
>
> $$m=\dfrac{y_Q-y_P}{x_Q-x_P}=\dfrac{-3-4}{2-(-3)}=\dfrac{-7}{5}=-\dfrac75.$$
>
> Usando la forma punto-pendiente con $Q(2,-3)$:
>
> $$y-(-3)=-\dfrac75(x-2)\ \Rightarrow\ y=-\dfrac75 x+\dfrac{14}{5}-3=-\dfrac75 x-\dfrac15.$$
>
> Una recta no constante tiene dominio e imagen $\mathbb{R}$.
>
> **Resultado:** $m(x)=-\dfrac75 x-\dfrac15$, con $D=I=\mathbb{R}$. ✓ Coincide con la respuesta oficial.

### `1b`

{: .enunciado }
> La función lineal que representa una recta paralela a $2x-3y+9=0$ y corta al eje $x$ en el punto de abscisa $x=-\dfrac12$.

{: .resolucion }
> Dos rectas son paralelas cuando tienen la misma pendiente. Empezamos escribiendo la recta dada en forma explícita para identificar su pendiente.
>
> Partimos de:
>
> $$2x-3y+9=0.$$
>
> Despejamos $y$:
>
> $$3y=2x+9.$$
>
> $$y=\dfrac23 x+3.$$
>
> La pendiente de la recta dada es $\dfrac23$. Por lo tanto, la recta buscada tiene la misma pendiente:
>
> $$m=\dfrac23.$$
>
> Como corta al eje $x$ en $x=-\dfrac12$, pasa por el punto $\left(-\dfrac12,0\right)$. Planteamos la forma explícita:
>
> $$f(x)=\dfrac23 x+b.$$
>
> Imponemos $f\left(-\dfrac12\right)=0$:
>
> $$0=\dfrac23\left(-\dfrac12\right)+b.$$
>
> $$0=-\dfrac13+b.$$
>
> $$b=\dfrac13.$$
>
> Entonces:
>
> $$f(x)=\dfrac23 x+\dfrac13.$$
>
> Por tratarse de una función lineal no constante, su dominio e imagen son todos los reales.
>
> **Resultado:** $f(x)=\dfrac23 x+\dfrac13$, con $D_f=\mathbb{R}$ e $I_f=\mathbb{R}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### 1c

{: .enunciado }
> La función cuadrática cuya representación gráfica es una parábola que tiene vértice en $V\left(-\dfrac12,5\right)$ y corta al eje de ordenadas en $(0,4)$.

{: .resolucion }
> Toda función cuadrática puede escribirse en forma canónica como
>
> $$f(x)=a(x-h)^2+k,$$
>
> donde $(h,k)$ es el vértice de la parábola y $a\neq 0$ determina la orientación y abertura.
>
> Como el vértice es $V\left(-\dfrac12,5\right)$, entonces:
>
> $$h=-\dfrac12,\qquad k=5.$$
>
> Por lo tanto:
>
> $$f(x)=a\left(x+\dfrac12\right)^2+5.$$
>
> Como corta al eje de ordenadas en $(0,4)$, se cumple que $f(0)=4$:
>
> $$4=a\left(0+\dfrac12\right)^2+5.$$
>
> $$4=\dfrac{a}{4}+5.$$
>
> $$-1=\dfrac{a}{4}.$$
>
> $$a=-4.$$
>
> Entonces:
>
> $$f(x)=-4\left(x+\dfrac12\right)^2+5.$$
>
> Como $a<0$, la parábola abre hacia abajo, por lo que su valor máximo está en el vértice y la imagen es $(-\infty,5]$.
>
> **Resultado:** $p(x)=-4\left(x+\dfrac12\right)^2+5$, con $D=\mathbb{R}$ e $I=(-\infty,5]$.

### `1d`

{: .enunciado }
> La función cuadrática cuya representación gráfica es una parábola que tiene raíces $x_1=-1$, $x_2=\dfrac57$ y pasa por $P\left(1,\dfrac87\right)$.

{: .resolucion }
> Si una función cuadrática tiene raíces $x_1$ y $x_2$, puede escribirse en forma factorizada como
>
> $$f(x)=a(x-x_1)(x-x_2),$$
>
> donde $a\neq 0$ determina la orientación y abertura de la parábola.
>
> Como las raíces son $x_1=-1$ y $x_2=\dfrac57$, resulta:
>
> $$f(x)=a(x+1)\left(x-\dfrac57\right).$$
>
> Además, la parábola pasa por $P\left(1,\dfrac87\right)$, por lo tanto:
>
> $$f(1)=\dfrac87.$$
>
> Reemplazamos:
>
> $$\dfrac87=a(1+1)\left(1-\dfrac57\right).$$
>
> $$\dfrac87=a\cdot 2\cdot \dfrac27.$$
>
> $$\dfrac87=\dfrac{4a}{7}.$$
>
> $$8=4a.$$
>
> $$a=2.$$
>
> Entonces:
>
> $$f(x)=2(x+1)\left(x-\dfrac57\right).$$
>
> Como $a>0$, la parábola abre hacia arriba. Para hallar la imagen, usamos que el vértice está en el punto medio entre las raíces:
>
> $$x_v=\dfrac{x_1+x_2}{2}.$$
>
> Reemplazamos:
>
> $$x_v=\dfrac{-1+\dfrac57}{2}=\dfrac{-\dfrac27}{2}=-\dfrac17.$$
>
> Evaluamos la función en ese valor:
>
> $$f\left(-\dfrac17\right)=2\left(-\dfrac17+1\right)\left(-\dfrac17-\dfrac57\right).$$
>
> $$f\left(-\dfrac17\right)=2\cdot\dfrac67\cdot\left(-\dfrac67\right).$$
>
> $$f\left(-\dfrac17\right)=-\dfrac{72}{49}.$$
>
> Como la parábola abre hacia arriba, ese valor es el mínimo.
>
> **Resultado:** $h(x)=2(x+1)\left(x-\dfrac57\right)$, con $D=\mathbb{R}$ e $I=\left[-\dfrac{72}{49},+\infty\right)$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `1e`

{: .enunciado }
> $f:D_f\to I_f \,/\, f(x)=\lvert x\rvert$.

{: .resolucion }
> La función valor absoluto se define como
>
> $$\lvert x\rvert=\begin{cases} x & \text{si } x\geq 0, \\ -x & \text{si } x<0. \end{cases}$$
>
> Esta función está definida para todo número real, porque se puede calcular el valor absoluto de cualquier $x\in\mathbb{R}$.
>
> Por lo tanto:
>
> $$D_f=\mathbb{R}.$$
>
> Además, el valor absoluto nunca toma valores negativos:
>
> $$\lvert x\rvert\geq 0.$$
>
> Su menor valor es $0$, que ocurre cuando $x=0$:
>
> $$f(0)=\lvert 0\rvert=0.$$
>
> Por eso, su imagen es:
>
> $$I_f=[0,+\infty).$$
>
> Gráficamente, es una función con forma de “V”, con vértice en $(0,0)$.
>
> **Resultado:** $D_f=\mathbb{R}$ e $I_f=[0,+\infty)$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `1f`

{: .enunciado }
> $g:D_g\to \mathbb{R} \,/\, g(x)=\sqrt{x}$.

{: .resolucion }
> La función raíz cuadrada real
>
> $$g(x)=\sqrt{x}$$
>
> sólo está definida cuando el radicando es mayor o igual que cero:
>
> $$x\geq 0.$$
>
> Por lo tanto:
>
> $$D_g=[0,+\infty).$$
>
> Además, la raíz cuadrada principal nunca toma valores negativos:
>
> $$\sqrt{x}\geq 0.$$
>
> Su menor valor es $0$, que ocurre cuando $x=0$:
>
> $$g(0)=\sqrt{0}=0.$$
>
> Entonces:
>
> $$I_g=[0,+\infty).$$
>
> Gráficamente, comienza en $(0,0)$ y crece hacia la derecha.
>
> **Resultado:** $D_g=[0,+\infty)$ e $I_g=[0,+\infty)$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `1g`

{: .enunciado }
> $h:D_h\to I_h \,/\, h(x)=\dfrac1x$.

{: .resolucion }
> La función racional
>
> $$h(x)=\dfrac1x$$
>
> está definida para todos los valores reales excepto aquellos que anulan el denominador.
>
> En general, una fracción no está definida cuando su denominador vale cero. En este caso:
>
> $$x\neq 0.$$
>
> Por lo tanto:
>
> $$D_h=\mathbb{R}-\{0\}.$$
>
> Para hallar la imagen, observamos que
>
> $$\dfrac1x$$
>
> nunca puede valer $0$, porque ninguna división de la forma $\dfrac1x$ da como resultado cero.
>
> Entonces:
>
> $$I_h=\mathbb{R}-\{0\}.$$
>
> Gráficamente, es una hipérbola con asíntota vertical $x=0$ y asíntota horizontal $y=0$.
>
> **Resultado:** $D_h=\mathbb{R}-\{0\}$ e $I_h=\mathbb{R}-\{0\}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

---

## Ejercicio 2 — Celsius y Fahrenheit

Obtener la ecuación de la recta que relaciona la temperatura $C$ en grados Celsius con la temperatura $F$ en grados Fahrenheit, sabiendo que el agua se hiela a $0^\circ C\,(32^\circ F)$ y hierve a $100^\circ C\,(212^\circ F)$.

### `2a`

{: .enunciado }
> Hallar la función (terna) que modela la situación planteada.

{: .resolucion }
> La relación entre $C$ y $F$ es lineal, por lo que puede escribirse como
>
> $$F(C)=mC+b.$$
>
> Los datos del enunciado nos dan dos puntos en el plano $(C,F)$:
>
> $$(0,32)\quad\text{y}\quad(100,212).$$
>
> Calculamos la pendiente como el cociente de variaciones:
>
> $$m=\dfrac{F_2-F_1}{C_2-C_1}.$$
>
> Reemplazamos:
>
> $$m=\dfrac{212-32}{100-0}=\dfrac{180}{100}=\dfrac95.$$
>
> Para la ordenada al origen, usamos el primer punto $(0,32)$:
>
> $$32=\dfrac95\cdot 0+b.$$
>
> $$b=32.$$
>
> Entonces:
>
> $$F(C)=\dfrac95 C+32.$$
>
> La temperatura en Celsius puede tomar cualquier valor real, y la imagen también recorre todos los reales, por lo que la terna es:
>
> $$F:\mathbb{R}\to\mathbb{R}\,/\,F(C)=\dfrac95 C+32.$$
>
> **Resultado:** $F:\mathbb{R}\to\mathbb{R}\,/\,F(C)=\dfrac95 C+32$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `2b`

{: .enunciado }
> ¿Cuántos grados Fahrenheit son $-10^\circ C$?

{: .resolucion }
> Para convertir una temperatura de Celsius a Fahrenheit, evaluamos la función hallada en `2a`:
>
> $$F(C)=\dfrac95 C+32.$$
>
> Reemplazamos $C=-10$:
>
> $$F(-10)=\dfrac95\cdot(-10)+32.$$
>
> $$F(-10)=-\dfrac{90}{5}+32.$$
>
> $$F(-10)=-18+32.$$
>
> $$F(-10)=14.$$
>
> **Resultado:** $-10^\circ C$ equivalen a $14^\circ F$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `2c`

{: .enunciado }
> ¿Cuántos grados Celsius se corresponden con $0^\circ F$?

{: .resolucion }
> Ahora queremos despejar $C$ en función de $F$. Partimos de:
>
> $$F=\dfrac95 C+32.$$
>
> Restamos $32$ a ambos miembros:
>
> $$F-32=\dfrac95 C.$$
>
> Multiplicamos ambos miembros por $\dfrac59$:
>
> $$C=\dfrac59(F-32).$$
>
> Reemplazamos $F=0$:
>
> $$C=\dfrac59(0-32).$$
>
> $$C=\dfrac59\cdot(-32).$$
>
> $$C=-\dfrac{160}{9}.$$
>
> En forma decimal aproximada:
>
> $$C\approx-17{,}78.$$
>
> **Resultado:** $0^\circ F$ equivalen a $-\dfrac{160}{9}^\circ C\approx-17{,}78^\circ C$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `2d`

{: .enunciado }
> Calcular el cambio de temperatura $\Delta F$ en los intervalos $[0,10]$, $[10,20]$ (en grados Celsius). Interpretar gráficamente.

{: .resolucion }
> En una función lineal $F(C)=mC+b$, el cambio en $F$ entre dos valores $C_1$ y $C_2$ es:
>
> $$\Delta F=F(C_2)-F(C_1)=m\,(C_2-C_1)=m\,\Delta C.$$
>
> Es decir, $\Delta F$ depende solo de la pendiente y de la longitud del intervalo, no de dónde está ubicado.
>
> **Intervalo $[0,10]$:** acá $\Delta C=10-0=10$, entonces
>
> $$\Delta F=\dfrac95\cdot 10=18.$$
>
> **Intervalo $[10,20]$:** acá también $\Delta C=20-10=10$, entonces
>
> $$\Delta F=\dfrac95\cdot 10=18.$$
>
> En ambos casos se obtiene el mismo cambio porque la pendiente $m=\dfrac95$ es constante: la razón de cambio de una función lineal es la misma en todo el dominio. Gráficamente, a incrementos iguales en el eje $C$ les corresponden incrementos iguales en el eje $F$, y la pendiente representa la inclinación de la recta (por cada $1^\circ C$ que sube la temperatura Celsius, la Fahrenheit sube $\dfrac95^\circ F$).
>
> **Resultado:** $\Delta F=18^\circ F$ en ambos intervalos.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

---

## Ejercicio 3 — Vaciado de un tanque

El siguiente gráfico muestra el vaciado de un tanque de agua. Sólo mirando el gráfico respondan las siguientes preguntas. Del gráfico se lee que la cantidad de agua decrece linealmente desde $4000$ L en $t=0$ hasta $0$ L en $t=16$ min.

![Vaciado de un tanque](3.png){: .img-center}

### `3a`

{: .enunciado }
> ¿Cuánta agua había en el tanque y en cuánto tiempo tardó en vaciarse?

{: .resolucion }
> Leyendo el gráfico:
>
> - La recta cruza el eje vertical (cantidad de agua) en el valor $4000$, que corresponde al instante inicial $t=0$.
> - La recta cruza el eje horizontal (tiempo) en $t=16$, momento en el que la cantidad de agua vale $0$.
>
> Por lo tanto, la cantidad inicial de agua era $4000$ L y el tanque tardó $16$ minutos en vaciarse.
>
> **Resultado:** había $4000$ L y tardó $16$ minutos en vaciarse.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `3b`

{: .enunciado }
> ¿Cuántos litros por minuto salían del tanque cuando se vaciaba?

{: .resolucion }
> La cantidad de litros por minuto que salen del tanque es el valor absoluto de la razón de cambio del volumen respecto al tiempo, es decir, la pendiente de la recta del gráfico.
>
> Tomamos los dos puntos extremos $(0,4000)$ y $(16,0)$:
>
> $$m=\dfrac{V_2-V_1}{t_2-t_1}.$$
>
> Reemplazamos:
>
> $$m=\dfrac{0-4000}{16-0}=\dfrac{-4000}{16}=-250\ \dfrac{\text{L}}{\text{min}}.$$
>
> El signo negativo indica que el volumen disminuye con el tiempo. La cantidad de litros que salen por minuto es el módulo de esa razón.
>
> **Resultado:** salían $250$ L/min del tanque.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `3c`

{: .enunciado }
> Marquen en el gráfico el momento en el que en el tanque había $1000$ litros. ¿Cuánto tiempo había transcurrido desde que se comenzó a vaciar?

{: .resolucion }
> Necesitamos el instante $t$ para el cual el volumen es $V(t)=1000$. Usamos la fórmula que describe la recta (deducida en el bloque analítico):
>
> $$V(t)=4000-250\,t.$$
>
> Imponemos $V(t)=1000$:
>
> $$1000=4000-250\,t.$$
>
> Despejamos $t$:
>
> $$250\,t=4000-1000.$$
>
> $$250\,t=3000.$$
>
> $$t=\dfrac{3000}{250}=12.$$
>
> En el gráfico se marca el punto $(12,1000)$ sobre la recta.
>
> **Resultado:** habían transcurrido $12$ minutos.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `3` — Trabajando analíticamente

{: .enunciado }
> - Si queremos relacionar el tiempo de vaciado con la cantidad de agua en el tanque ¿cuál sería la variable independiente y cuál la dependiente?
> - Definirlas con simbología adecuada y unidades correspondientes. ¿Cuál es el dominio e imagen en contexto?
> - Escriban una fórmula que calcule la cantidad de agua a los $t$ minutos.
> - ¿Cuál es la razón de cambio de volumen respecto al tiempo en un intervalo de $5$ minutos? ¿Y en uno de $10$ minutos?

{: .resolucion }
> **Variables.** La cantidad de agua en el tanque depende del tiempo transcurrido desde que comenzó el vaciado, por lo que:
>
> - Variable independiente: $t$, el tiempo, medido en minutos.
> - Variable dependiente: $V$, el volumen de agua, medido en litros.
>
> **Dominio e imagen en contexto.** El tiempo arranca en $0$ (instante en que empieza a vaciarse) y termina en $16$ (instante en que el tanque queda vacío). El volumen va desde los $4000$ L iniciales hasta los $0$ L finales. Por lo tanto:
>
> $$D=[0,16]\ \text{min},\qquad I=[0,4000]\ \text{L}.$$
>
> **Fórmula.** Buscamos la recta que pasa por $(0,4000)$ y $(16,0)$. La ordenada al origen es $4000$ y la pendiente, calculada en `3b`, es $-250$. Entonces:
>
> $$V(t)=4000-250\,t.$$
>
> **Razón de cambio en distintos intervalos.** La razón de cambio media del volumen respecto al tiempo en un intervalo $[t_1,t_2]$ es:
>
> $$\dfrac{\Delta V}{\Delta t}=\dfrac{V(t_2)-V(t_1)}{t_2-t_1}.$$
>
> Como $V$ es una función lineal con pendiente $-250$, esa razón es constante e igual a la pendiente para cualquier intervalo, sin importar su longitud:
>
> $$\dfrac{\Delta V}{\Delta t}=-250\ \dfrac{\text{L}}{\text{min}}.$$
>
> En particular:
>
> - En un intervalo de $5$ minutos: $\Delta V=-250\cdot 5=-1250$ L, con razón de cambio $-250$ L/min.
> - En un intervalo de $10$ minutos: $\Delta V=-250\cdot 10=-2500$ L, con razón de cambio $-250$ L/min.
>
> El signo negativo refleja que en cualquier intervalo el volumen disminuye.
>
> **Resultado:** $V:[0,16]\to[0,4000]\,/\,V(t)=4000-250\,t$, con razón de cambio constante igual a $-250$ L/min (equivalente a $-1250$ L cada $5$ min y $-2500$ L cada $10$ min).
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

---

## Ejercicio 4 — Resorte

Para diseñar un vehículo es necesario crear un modelo que permita determinar la respuesta de un resorte con diferentes cargas. Se realizó un experimento para medir el estiramiento ($y$) de un resorte, en pulgadas, como una función del número ($x$) de unidades de masa colocadas como carga en él y se obtuvieron los siguientes resultados:

| $x$ | $0$ | $1$ | $2$ | $3$ | $4$ | $5$ | $6$ | $7$ | $8$ |
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| $y$ | $0$ | $0{,}875$ | $1{,}721$ | $2{,}641$ | $3{,}531$ | $4{,}391$ | $5{,}241$ | $6{,}120$ | $6{,}992$ |
{: .table-tight }

### `4a`

{: .enunciado }
> ¿Cuál es la variable independiente y dependiente del problema? (con sus unidades).

{: .resolucion }
> El experimento consiste en colocar distintas cargas en el resorte y medir cuánto se estira. La causa es la masa que colgamos, y el efecto es el estiramiento que provoca. Entonces:
>
> - Variable independiente: $x$, el número de unidades de masa colocadas como carga (adimensional, "unidades de masa").
> - Variable dependiente: $y$, el estiramiento del resorte, medido en pulgadas.
>
> **Resultado:** $x$ (unidades de masa) es la independiente; $y$ (pulgadas) es la dependiente.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `4b`

{: .enunciado }
> Usar **Tabla** en GeoGebra para graficar los puntos en un par de ejes cartesianos y comprobar la hipótesis de que el estiramiento "y" es proporcional a la masa "x" que se cuelga del resorte.

{: .resolucion }
> Dos cantidades $x$ e $y$ son proporcionales cuando existe una constante $k$ tal que
>
> $$y=k\,x,$$
>
> es decir, el cociente $\dfrac{y}{x}$ se mantiene aproximadamente constante para todos los valores observados (excluyendo $x=0$). Verificamos esa condición con la tabla:
>
> | $x$ | $1$ | $2$ | $3$ | $4$ | $5$ | $6$ | $7$ | $8$ |
> |-----|-----|-----|-----|-----|-----|-----|-----|-----|
> | $y/x$ | $0{,}875$ | $0{,}861$ | $0{,}880$ | $0{,}883$ | $0{,}878$ | $0{,}874$ | $0{,}874$ | $0{,}874$ |
>
> Todos los cocientes están muy próximos a $0{,}875$, con pequeñas variaciones atribuibles al error de medición. Esto confirma la hipótesis de proporcionalidad directa.
>
> Al graficar los puntos en GeoGebra (comando **Tabla**), los $9$ puntos quedan prácticamente alineados sobre una recta que pasa por el origen, lo que es consistente con $y=k\,x$.
>
> **Resultado:** los cocientes $y/x$ son aproximadamente constantes ($\approx 0{,}875$) y los puntos se alinean sobre una recta por el origen, por lo que la hipótesis de proporcionalidad se verifica.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `4c`

{: .enunciado }
> Estimar la constante de proporcionalidad con GeoGebra utilizando el comando **Regresión** (se puede encontrar en los "tres puntitos" en la tabla) y armar la función obtenida. O hacerlo manualmente.

{: .resolucion }
> Para estimar la constante de proporcionalidad $k$ de la relación $y=k\,x$, podemos:
>
> - **Usar GeoGebra:** seleccionar la tabla, elegir **Regresión** $\to$ **Lineal** y obtener la ecuación $y\approx 0{,}875\,x$.
> - **Hacerlo manualmente:** promediar los cocientes $y/x$ calculados en `4b`:
>
> $$\bar{k}=\dfrac{0{,}875+0{,}861+0{,}880+0{,}883+0{,}878+0{,}874+0{,}874+0{,}874}{8}.$$
>
> $$\bar{k}\approx 0{,}875.$$
>
> Ambos caminos llevan al mismo valor:
>
> $$k\approx 0{,}875.$$
>
> La función obtenida es:
>
> $$f(x)=0{,}875\,x.$$
>
> **Resultado:** $k\approx 0{,}875$ pulgadas por unidad de masa, y la función es $f(x)=0{,}875\,x$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `4d`

{: .enunciado }
> Identificar dominio e imagen de la función definida en el ítem c) bajo el contexto del problema.

{: .resolucion }
> En el contexto del experimento, la variable $x$ representa la cantidad de unidades de masa colocadas como carga, y se midió para los valores enteros entre $0$ y $8$. Considerando el rango medido como dominio del modelo:
>
> $$D_f=[0,8].$$
>
> Como $f(x)=0{,}875\,x$ es una función lineal creciente, los valores mínimo y máximo de la imagen se alcanzan en los extremos del dominio:
>
> $$f(0)=0{,}875\cdot 0=0.$$
>
> $$f(8)=0{,}875\cdot 8=7.$$
>
> Por lo tanto:
>
> $$I_f=[0,7].$$
>
> La función expresada como terna queda:
>
> $$f:[0,8]\to[0,7]\,/\,f(x)=0{,}875\,x.$$
>
> **Resultado:** $f:[0,8]\to[0,7]\,/\,f(x)=0{,}875\,x$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `4e`

{: .enunciado }
> Predecir el estiramiento del resorte si se le carga una masa de $10$ unidades de masa.

{: .resolucion }
> Para predecir el estiramiento con $10$ unidades de masa, evaluamos la función obtenida en `4c`:
>
> $$f(x)=0{,}875\,x.$$
>
> Reemplazamos $x=10$:
>
> $$f(10)=0{,}875\cdot 10.$$
>
> $$f(10)=8{,}75.$$
>
> Observación: el valor $x=10$ queda fuera del dominio en contexto $[0,8]$, por lo que es una **extrapolación** del modelo. La predicción asume que la relación de proporcionalidad sigue siendo válida fuera del rango medido, lo que físicamente solo se cumple mientras no se supere el límite elástico del resorte.
>
> **Resultado:** se predice un estiramiento de $8{,}75$ pulgadas.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `4f`

{: .enunciado }
> ¿Cuál es la razón de cambio del estiramiento del resorte respecto a la carga colgada? Interpretar gráficamente.

{: .resolucion }
> La razón de cambio media del estiramiento respecto a la carga en un intervalo $[x_1,x_2]$ es:
>
> $$\dfrac{\Delta y}{\Delta x}=\dfrac{f(x_2)-f(x_1)}{x_2-x_1}.$$
>
> Como $f(x)=0{,}875\,x$ es una función lineal, esa razón es constante e igual a la pendiente para cualquier intervalo:
>
> $$\dfrac{\Delta y}{\Delta x}=0{,}875\ \dfrac{\text{pulgadas}}{\text{unidad de masa}}.$$
>
> **Interpretación gráfica:** la razón de cambio es la inclinación de la recta $y=0{,}875\,x$. Al ser constante, a incrementos iguales en el eje $x$ les corresponden incrementos iguales en el eje $y$: por cada unidad de masa adicional que se cuelga del resorte, el estiramiento aumenta $0{,}875$ pulgadas.
>
> **Resultado:** la razón de cambio es constante e igual a $0{,}875$ pulgadas por unidad de masa.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

---

## Ejercicio 5* — Canaleta de desagüe

Se desea construir una canaleta de desagüe a partir de una hoja rectangular de metal de $12$ cm de ancho y $1$ metro de largo. Se dobla la hoja hacia arriba $x$ cm en los dos bordes de $1$ metro de largo.

### `5a`

{: .enunciado }
> Expresar el área de la sección transversal de la canaleta como una función de $x$.

{: .resolucion }
> La **sección transversal** es la figura plana que se obtiene al cortar la canaleta perpendicularmente a su largo. Como los dos bordes se doblaron hacia arriba $x$ cm, ese corte tiene forma de "U": un fondo horizontal y dos paredes verticales. El área de la sección transversal es el área que ocupa el agua cuando la canaleta está llena hasta el borde, es decir, la del rectángulo encerrado entre el fondo y las paredes.
>
> Las dimensiones de ese rectángulo son:
>
> - Base: $12-2x$ cm (lo que queda del ancho original después de descontar los dos pliegues).
> - Altura: $x$ cm (cuánto se levantaron las paredes al doblarlas).
>
> El área es base por altura:
>
> $$A(x)=(12-2x)\cdot x.$$
>
> Distribuyendo:
>
> $$A(x)=12x-2x^2.$$
>
> Se puede también factorizar como:
>
> $$A(x)=2x\,(6-x).$$
>
> **Resultado:** $A(x)=12x-2x^2=2x(6-x)$, expresada en cm².
>
> **Verificación:** El [documento de respuestas oficiales](https://drive.google.com/file/d/1nJsGgi-k5Zgey-RVAF49SmP-BSGfFFGe/view) publica como respuesta del ejercicio la fórmula del **volumen** $V(x)=200x(6-x)$ (en cm³, ya incluyendo el largo de $100$ cm), mientras que aquí respondemos lo que el enunciado pide literalmente: el **área** de la sección transversal. Ambas expresiones son consistentes entre sí, ya que $V(x)=100\cdot A(x)=100\cdot 2x(6-x)=200x(6-x)$, y se usa más abajo en `5d`.

{: .enunciado }
> ¿Cuál es el dominio de esta función de acuerdo al contexto?

{: .resolucion }
> Para que la canaleta exista físicamente, deben cumplirse simultáneamente dos condiciones de contexto.
>
> **Condición 1.** El pliegue debe tener altura positiva (si no se dobla, no hay canaleta):
>
> $$x>0.$$
>
> **Condición 2.** El fondo debe tener ancho positivo (si se doblara más de la mitad por cada lado, no quedaría base):
>
> $$12-2x>0.$$
>
> $$2x<12.$$
>
> $$x<6.$$
>
> La intersección de ambas condiciones es:
>
> $$0<x<6.$$
>
> **Resultado:** $D_A=(0,6)$, con $x$ medido en cm.
>
> **Verificación:** Coincide con la respuesta indicada en el [documento de respuestas oficiales](https://drive.google.com/file/d/1nJsGgi-k5Zgey-RVAF49SmP-BSGfFFGe/view). El dominio es el mismo para la función área $A(x)$ usada acá y para la función volumen $V(x)=100\cdot A(x)$ con la que trabaja el solucionario, ya que ambas se anulan en los mismos extremos.

### `5c`

{: .enunciado }
> Graficar la función y estimar para qué valor de $x$ el área de la sección transversal de la canaleta es máxima.

{: .resolucion }
> La función $A(x)=-2x^2+12x$ es cuadrática con coeficiente principal $a=-2<0$, por lo que su gráfica es una parábola que abre hacia abajo. Esto garantiza que el vértice corresponde a un **máximo absoluto**.
>
> Buscamos la abscisa del vértice. Como $A$ está factorizada como $A(x)=2x(6-x)$, sus raíces son $x_1=0$ y $x_2=6$. El vértice está en el punto medio entre ambas:
>
> $$x_v=\dfrac{x_1+x_2}{2}=\dfrac{0+6}{2}=3.$$
>
> Evaluamos $A$ en $x_v=3$ para obtener el valor máximo:
>
> $$A(3)=2\cdot 3\cdot(6-3).$$
>
> $$A(3)=2\cdot 3\cdot 3.$$
>
> $$A(3)=18.$$
>
> En el gráfico, la parábola corta al eje $x$ en $x=0$ y $x=6$, sube hasta el vértice $(3,18)$ y luego baja simétricamente.
>
> **Resultado:** el área de la sección transversal es máxima cuando $x=3$ cm, y vale $A_{\max}=18$ cm².
>
> **Verificación:** El valor $x=3$ cm donde se alcanza el máximo coincide con el indicado en el [documento de respuestas oficiales](https://drive.google.com/file/d/1nJsGgi-k5Zgey-RVAF49SmP-BSGfFFGe/view) ("se obtiene mayor volumen cuando se cortan $3$ cm de cada lado"). Como $V(x)=100\cdot A(x)$, los máximos de área y volumen ocurren en el mismo $x$. El valor $A_{\max}=18$ cm² no figura explícito en el solucionario (que reporta el máximo del volumen), pero es consistente con él: $V_{\max}=100\cdot 18=1800$ cm³ $=200\cdot 3\cdot(6-3)$.

### `5d`

{: .enunciado }
> ¿Cuántos cm se deben doblar para que la canaleta tenga la capacidad máxima de transporte de agua?

{: .resolucion }
> La capacidad de transporte de agua de la canaleta es el **volumen** que puede contener. Como la canaleta tiene sección transversal constante a lo largo de toda su longitud, el volumen es el producto del área de la sección por el largo:
>
> $$V(x)=A(x)\cdot L.$$
>
> El largo es $L=1$ m $=100$ cm, por lo que:
>
> $$V(x)=100\cdot A(x)=100\cdot(12x-2x^2)=200x(6-x).$$
>
> Como $100$ es una constante positiva, $V(x)$ alcanza su máximo en el mismo valor de $x$ que $A(x)$. De `5c` ya sabemos que el área es máxima en $x=3$, por lo que también lo es el volumen.
>
> El volumen máximo es:
>
> $$V(3)=100\cdot 18=1800.$$
>
> **Resultado:** se deben doblar $x=3$ cm en cada borde para que la canaleta tenga capacidad máxima, que vale $1800$ cm³.
>
> **Verificación:** Coincide con el [documento de respuestas oficiales](https://drive.google.com/file/d/1nJsGgi-k5Zgey-RVAF49SmP-BSGfFFGe/view): "se obtiene mayor volumen cuando se cortan $3$ cm de cada lado", a partir de la fórmula $V(x)=200x(6-x)$ que coincide con la $V(x)=100\cdot A(x)$ deducida aquí. Evaluando la oficial en $x=3$ se obtiene $V(3)=200\cdot 3\cdot(6-3)=1800$ cm³, igual al valor calculado.

---

## Ejercicio 6 — Caja sin tapa

{: .enunciado }
> Expresar el volumen $V(x)$ de una caja sin tapa que se construye a partir de una pieza de cartón de $24\text{cm}\times 32\text{cm}$ cortando en las esquinas cuadrados de lado $x$. ¿Cuál es el dominio de dicha función de acuerdo al contexto? Con ayuda de GG estimar cuántos centímetros debe tener el cuadrado que se corte para que el volumen de la caja sea máximo.

{: .resolucion }
> **Planteo de la fórmula.** Partimos de una pieza rectangular de cartón de $24\text{ cm}\times 32\text{ cm}$ y cortamos un cuadrado de lado $x$ en cada una de las cuatro esquinas. Al doblar las solapas hacia arriba se forma una caja sin tapa con:
>
> - Base rectangular de dimensiones $(24-2x)$ por $(32-2x)$ cm.
> - Altura igual al lado del cuadrado recortado, es decir, $x$ cm.
>
> El volumen de la caja es el producto de la base por la altura:
>
> $$V(x)=(24-2x)\,(32-2x)\,x.$$
>
> Sacando factor común $2$ en cada paréntesis se obtiene una expresión equivalente más cómoda para analizar:
>
> $$V(x)=4\,x\,(12-x)\,(16-x).$$
>
> **Dominio en contexto.** Para que la caja exista físicamente deben cumplirse simultáneamente tres condiciones:
>
> $$x>0,\qquad 24-2x>0,\qquad 32-2x>0.$$
>
> Despejando las dos últimas:
>
> $$x<12,\qquad x<16.$$
>
> La restricción más fuerte es $x<12$ (la otra se cumple automáticamente). Combinando con $x>0$:
>
> $$D_V=(0,12).$$
>
> **Estimación del máximo con GeoGebra.** Como $V(x)=4x(12-x)(16-x)$ es un polinomio de grado $3$ con coeficiente principal positivo en $-x^3$ (al expandir queda $V(x)=4x^3-112x^2+768x$ con signo principal positivo en $4x^3$, pero al evaluar en el intervalo $(0,12)$ presenta un único máximo local), graficamos $V$ en GeoGebra restringida al dominio $(0,12)$. Con el comando `Extremo[V, 0, 12]` o moviendo el cursor sobre la curva se obtiene:
>
> $$x_{\max}\approx 4{,}53\text{ cm}.$$
>
> Evaluando $V$ en ese valor:
>
> $$V(4{,}53)=4\cdot 4{,}53\cdot(12-4{,}53)\cdot(16-4{,}53).$$
>
> $$V(4{,}53)\approx 4\cdot 4{,}53\cdot 7{,}47\cdot 11{,}47.$$
>
> $$V(4{,}53)\approx 1552{,}5\text{ cm}^3.$$
>
> Observación: el valor exacto se obtiene resolviendo $V'(x)=0$ (Unidad 3), que da $x_{\max}=\dfrac{4(7-\sqrt{13})}{3}\approx 4{,}526\text{ cm}$.
>
> **Resultado:** $V(x)=(24-2x)(32-2x)\,x=4x(12-x)(16-x)$, con $D_V=(0,12)$. El volumen es máximo cuando se cortan cuadrados de $x\approx 4{,}53$ cm de lado, alcanzando $V_{\max}\approx 1552{,}5$ cm³.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

---

## Ejercicio 7 — Fórmula y dominio

Encontrar una fórmula para la función descrita y dar su dominio.

### `7a`*

{: .enunciado }
> El área de un rectángulo cuyo perímetro es $20$ m en función de uno de sus lados.

{: .resolucion }
> Llamamos $x$ a uno de los lados del rectángulo (medido en m) e $y$ al lado contiguo. El perímetro es la suma de los cuatro lados, por lo que:
>
> $$2x+2y=20.$$
>
> Despejamos $y$ en función de $x$:
>
> $$2y=20-2x.$$
>
> $$y=10-x.$$
>
> El área del rectángulo es el producto de los lados:
>
> $$A(x)=x\,(10-x).$$
>
> $$A(x)=10x-x^2.$$
>
> Para que el rectángulo exista físicamente, ambos lados deben ser positivos:
>
> $$x>0,\qquad 10-x>0.$$
>
> La segunda condición da $x<10$. Combinando:
>
> $$0<x<10.$$
>
> **Resultado:** $A:(0,10)\to\mathbb{R}\,/\,A(x)=x(10-x)$, con $D_A=(0,10)$ y $x$ medido en m.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `7b`

{: .enunciado }
> El perímetro de un rectángulo cuya área es $16\text{ m}^2$ en función de uno de sus lados.

{: .resolucion }
> Llamamos $x$ a uno de los lados (medido en m) e $y$ al lado contiguo. El área del rectángulo es:
>
> $$x\cdot y=16.$$
>
> Despejamos $y$ en función de $x$ (con $x\neq 0$):
>
> $$y=\dfrac{16}{x}.$$
>
> El perímetro es la suma de los cuatro lados:
>
> $$P(x)=2x+2y.$$
>
> $$P(x)=2x+2\cdot\dfrac{16}{x}.$$
>
> $$P(x)=2x+\dfrac{32}{x}.$$
>
> Para que el rectángulo exista físicamente, ambos lados deben ser positivos. Como $y=16/x$, basta con pedir $x>0$ (eso garantiza también $y>0$):
>
> $$x>0.$$
>
> **Resultado:** $P:(0,+\infty)\to\mathbb{R}\,/\,P(x)=2x+\dfrac{32}{x}$, con $D_P=(0,+\infty)$ y $x$ medido en m.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `7c`

{: .enunciado }
> El área de un triángulo equilátero en función de la longitud de su lado.

{: .resolucion }
> Llamamos $l$ a la longitud del lado del triángulo equilátero. Para calcular el área necesitamos también la altura.
>
> La altura $h$ se obtiene aplicando el teorema de Pitágoras a uno de los dos triángulos rectángulos en que la altura divide al triángulo equilátero. En ese triángulo rectángulo:
>
> - La hipotenusa es el lado $l$.
> - Un cateto es la mitad de la base, $\dfrac{l}{2}$.
> - El otro cateto es la altura $h$.
>
> Por Pitágoras:
>
> $$l^2=h^2+\left(\dfrac{l}{2}\right)^2.$$
>
> $$h^2=l^2-\dfrac{l^2}{4}=\dfrac{3l^2}{4}.$$
>
> $$h=\dfrac{\sqrt 3}{2}\,l.$$
>
> El área es base por altura sobre dos:
>
> $$A(l)=\dfrac{l\cdot h}{2}=\dfrac{l}{2}\cdot\dfrac{\sqrt 3}{2}\,l.$$
>
> $$A(l)=\dfrac{\sqrt 3}{4}\,l^2.$$
>
> Para que el triángulo exista físicamente, el lado debe ser positivo:
>
> $$l>0.$$
>
> **Resultado:** $A:(0,+\infty)\to\mathbb{R}\,/\,A(l)=\dfrac{\sqrt 3}{4}\,l^2$, con $D_A=(0,+\infty)$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

---

## Ejercicio 8 — Concentración de un calmante

La concentración de un calmante en el torrente sanguíneo de una persona $t$ horas después de haberlo ingerido está dada por $C(t)=-t^2+6t$, donde $C$ es la concentración medida en miligramos por litro.

### `8a`

{: .enunciado }
> Hallar el dominio y la imagen de $C$ bajo contexto. Graficar.

{: .resolucion }
> La función $C(t)=-t^2+6t$ es cuadrática con coeficiente principal $a=-1<0$: su gráfica es una parábola que abre hacia abajo. Factorizándola se observan sus raíces:
>
> $$C(t)=t\,(6-t).$$
>
> Las raíces son $t=0$ y $t=6$. Físicamente:
>
> - En $t=0$ la persona ingiere el calmante y la concentración es $0$.
> - En $t=6$ horas el organismo ya eliminó la sustancia y la concentración vuelve a $0$.
>
> Entre ambos instantes la concentración es positiva. Por lo tanto, el dominio en contexto es:
>
> $$D_C=[0,6]\ \text{(horas)}.$$
>
> Para la imagen, buscamos el valor máximo de $C$. Como la parábola abre hacia abajo, el máximo está en el vértice, en el punto medio de las raíces:
>
> $$t_v=\dfrac{0+6}{2}=3.$$
>
> Evaluamos $C$ en $t=3$:
>
> $$C(3)=-(3)^2+6\cdot 3=-9+18=9.$$
>
> La concentración varía entonces entre $0$ y $9$ mg/l:
>
> $$I_C=[0,9]\ \text{(mg/l)}.$$
>
> Gráficamente, la parábola arranca en el origen $(0,0)$, sube hasta el vértice $(3,9)$ y baja simétricamente hasta $(6,0)$.
>
> **Resultado:** $C:[0,6]\to[0,9]\,/\,C(t)=-t^2+6t$, con $D_C=[0,6]$ h y $I_C=[0,9]$ mg/l.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `8b`

{: .enunciado }
> ¿En qué instantes de tiempo la concentración es mayor a $8$ mg/l?

{: .resolucion }
> Planteamos la inecuación:
>
> $$C(t)>8.$$
>
> $$-t^2+6t>8.$$
>
> Pasamos todo a un solo miembro:
>
> $$-t^2+6t-8>0.$$
>
> Multiplicamos ambos miembros por $-1$ (invierte el sentido de la desigualdad):
>
> $$t^2-6t+8<0.$$
>
> Factorizamos el trinomio. Buscamos dos números que multiplicados den $8$ y sumados $-6$: son $-2$ y $-4$. Por lo tanto:
>
> $$(t-2)(t-4)<0.$$
>
> El producto de dos factores es negativo cuando tienen signos opuestos. Esto ocurre justamente entre las raíces:
>
> $$2<t<4.$$
>
> Como ambos extremos están dentro del dominio $[0,6]$, no hay restricciones adicionales por contexto.
>
> **Resultado:** la concentración supera los $8$ mg/l en el intervalo $(2,4)$, es decir, entre las $2$ y las $4$ horas después de ingerir el calmante.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `8c`

{: .enunciado }
> Calcular la razón de cambio media de la concentración en los intervalos de tiempo $[1,2]$, $[1;1{,}5]$. Interpretar bajo el contexto del problema.

{: .resolucion }
> La razón de cambio media de la concentración en un intervalo $[t_1,t_2]$ se define como:
>
> $$\text{RCM}=\dfrac{C(t_2)-C(t_1)}{t_2-t_1}.$$
>
> **Intervalo $[1,2]$.** Calculamos $C(1)$ y $C(2)$:
>
> $$C(1)=-(1)^2+6\cdot 1=-1+6=5.$$
>
> $$C(2)=-(2)^2+6\cdot 2=-4+12=8.$$
>
> Aplicamos la fórmula:
>
> $$\text{RCM}_{[1,2]}=\dfrac{8-5}{2-1}=\dfrac{3}{1}=3.$$
>
> **Intervalo $[1;1{,}5]$.** Calculamos $C(1{,}5)$:
>
> $$C(1{,}5)=-(1{,}5)^2+6\cdot 1{,}5=-2{,}25+9=6{,}75.$$
>
> Aplicamos la fórmula:
>
> $$\text{RCM}_{[1;1{,}5]}=\dfrac{6{,}75-5}{1{,}5-1}=\dfrac{1{,}75}{0{,}5}=3{,}5.$$
>
> **Interpretación.** Cada razón de cambio media indica cuánto crece la concentración por hora en promedio durante el intervalo considerado. En $[1,2]$ la concentración aumenta a un promedio de $3$ mg/l por hora, mientras que en $[1;1{,}5]$ aumenta a $3{,}5$ mg/l por hora. La razón de cambio más alta en el intervalo más corto indica que cerca de $t=1$ h la concentración crece más rápido que entre $t=1$ y $t=2$: a medida que nos acercamos al vértice $t=3$, la pendiente instantánea va disminuyendo hasta anularse en el máximo.
>
> **Resultado:** $\text{RCM}_{[1,2]}=3$ mg/l por hora y $\text{RCM}_{[1;1{,}5]}=3{,}5$ mg/l por hora.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

---

## Ejercicio 9 — Dominio natural

Hallar el dominio natural de las siguientes funciones.

### `9a`

{: .enunciado }
> $y=-\sqrt{2}\,x^4-3x+\dfrac17\,x^2-2$.

{: .resolucion }
> La expresión es un polinomio de grado $4$ (suma de potencias enteras no negativas de $x$ con coeficientes reales). Los polinomios están definidos para todo número real.
>
> **Resultado:** $D=\mathbb{R}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `9b`

{: .enunciado }
> $y=(x^2-3)^{-4}$.

{: .resolucion }
> Por la definición de exponente negativo:
>
> $$y=(x^2-3)^{-4}=\dfrac{1}{(x^2-3)^4}.$$
>
> El denominador no puede anularse:
>
> $$(x^2-3)^4\neq 0\iff x^2-3\neq 0\iff x\neq\pm\sqrt{3}.$$
>
> **Resultado:** $D=\mathbb{R}-\{-\sqrt{3},\sqrt{3}\}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `9c`

{: .enunciado }
> $y=\dfrac{x^5-2x+5}{x^2-3x+2}$.

{: .resolucion }
> Cociente de polinomios. Los polinomios están definidos en $\mathbb{R}$, así que la única restricción viene del denominador no nulo. Factorizamos:
>
> $$x^2-3x+2=(x-1)(x-2).$$
>
> Las raíces son $x=1$ y $x=2$. Hay que excluirlas.
>
> **Resultado:** $D=\mathbb{R}-\{1,2\}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `9d`

{: .enunciado }
> $y=\dfrac{\lvert x-1\rvert}{x+2}$.

{: .resolucion }
> El numerador $\lvert x-1\rvert$ está definido para todo $x$. El denominador no debe anularse:
>
> $$x+2\neq 0\iff x\neq-2.$$
>
> **Resultado:** $D=\mathbb{R}-\{-2\}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `9e`

{: .enunciado }
> $y=\sqrt{x+2}$.

{: .resolucion }
> La raíz cuadrada real exige radicando no negativo:
>
> $$x+2\geq 0\iff x\geq -2.$$
>
> **Resultado:** $D=[-2,+\infty)$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `9f`

{: .enunciado }
> $y=\sqrt{\dfrac{1}{2x+1}-2}$.

{: .resolucion }
> La raíz cuadrada exige radicando no negativo y, además, el denominador interno no se debe anular:
>
> $$\dfrac{1}{2x+1}-2\geq 0,\qquad 2x+1\neq 0.$$
>
> La segunda condición da $x\neq -\dfrac12$. Para la primera, llevamos todo a una sola fracción:
>
> $$\dfrac{1-2(2x+1)}{2x+1}\geq 0.$$
>
> $$\dfrac{-4x-1}{2x+1}\geq 0.$$
>
> Multiplicamos por $-1$ (invierte la desigualdad):
>
> $$\dfrac{4x+1}{2x+1}\leq 0.$$
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

### `9g`

{: .enunciado }
> $y=\dfrac{2x}{\sqrt{x^2-4}}$.

{: .resolucion }
> La raíz cuadrada está en el denominador, así que el radicando debe ser **estrictamente positivo**:
>
> $$x^2-4>0.$$
>
> $$x^2>4.$$
>
> $$x<-2\ \text{o}\ x>2.$$
>
> **Resultado:** $D=(-\infty,-2)\cup(2,+\infty)$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `9h`

{: .enunciado }
> $y=\dfrac{x+3}{\lvert 3x+2\rvert}+\dfrac{1}{\sqrt[4]{x+1}}$.

{: .resolucion }
> Analizamos cada término por separado e intersectamos las condiciones.
>
> **Primer término:** $\dfrac{x+3}{\lvert 3x+2\rvert}$ requiere $\lvert 3x+2\rvert\neq 0$, es decir:
>
> $$3x+2\neq 0\iff x\neq-\dfrac{2}{3}.$$
>
> **Segundo término:** $\dfrac{1}{\sqrt[4]{x+1}}$ tiene raíz cuarta (índice par) en el denominador, por lo que el radicando debe ser estrictamente positivo:
>
> $$x+1>0\iff x>-1.$$
>
> Intersecamos: $x>-1$ y $x\neq-\dfrac23$.
>
> **Resultado:** $D=(-1,+\infty)-\left\{-\dfrac23\right\}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `9i`

{: .enunciado }
> $y=\dfrac{x^3+5x^2-6x}{x\,\sqrt[3]{x^2-1}}$.

{: .resolucion }
> El numerador es un polinomio (definido en todo $\mathbb{R}$). El denominador es un producto que no se debe anular:
>
> $$x\cdot\sqrt[3]{x^2-1}\neq 0.$$
>
> La raíz cúbica (índice impar) está definida para todo real, así que no hay restricción de signo. Hay que excluir:
>
> $$x=0\quad\text{y}\quad \sqrt[3]{x^2-1}=0\iff x^2-1=0\iff x=\pm 1.$$
>
> **Resultado:** $D=\mathbb{R}-\{-1,0,1\}$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `9j`*

{: .enunciado }
> $y=\sqrt{\dfrac{3x-4}{x+1}}$.

{: .resolucion }
> La raíz cuadrada exige radicando no negativo. Como el radicando es un cociente, pedimos:
>
> $$\dfrac{3x-4}{x+1}\geq 0,\qquad x+1\neq 0.$$
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

### `9k`*

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

### `9l`

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
> $$(-\infty,1]\cup(3,4).$$
>
> **Tramo $x\geq 4$:** $\ln(5-x)$ exige $5-x>0\iff x<5$. Intersecando con $x\geq 4$:
>
> $$[4,5).$$
>
> **Unión:** $(-\infty,1]\cup(3,4)\cup[4,5)=(-\infty,1]\cup(3,5)$.
>
> **Resultado:** $D=(-\infty,1]\cup(3,5)$.
>
> **Verificación:** ⚠️ Discrepa con el [documento de respuestas oficiales](https://drive.google.com/file/d/1nJsGgi-k5Zgey-RVAF49SmP-BSGfFFGe/view), que reporta $D=[1,5)-\{3\}$. La oficial parece haber estudiado mal el signo del cociente $\dfrac{x-1}{x-3}$: para $x<1$ ambos factores $x-1$ y $x-3$ son negativos, su cociente es positivo y la raíz existe. Por lo tanto todo $(-\infty,1]$ pertenece al dominio. **El dominio correcto es** $(-\infty,1]\cup(3,5)$.

### `9m`

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

### `9n`

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

### `9ñ`

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

---

## Ejercicio 10 — Dominio, imagen, intersecciones, positividad/negatividad

Determinar dominio, imagen, intersecciones con los ejes coordenados y los conjuntos de positividad y negatividad de las siguientes funciones. Graficar. Corroborar con GeoGebra.

### `10a`

{: .enunciado }
> $f(x)=x^2+2x-8$.

{: .resolucion }
> Es una función cuadrática con coeficiente principal $a=1>0$: parábola que abre hacia arriba.
>
> **Dominio.** Por ser polinomio:
>
> $$D_f=\mathbb{R}.$$
>
> **Raíces e intersecciones con los ejes.** Factorizamos:
>
> $$x^2+2x-8=(x+4)(x-2).$$
>
> Las raíces son $x=-4$ y $x=2$, por lo que la gráfica corta al eje $x$ en $(-4,0)$ y $(2,0)$. La intersección con el eje $y$ es $f(0)=-8$, punto $(0,-8)$.
>
> **Vértice e imagen.** La abscisa del vértice es el punto medio entre las raíces:
>
> $$x_v=\dfrac{-4+2}{2}=-1.$$
>
> $$f(-1)=(-1)^2+2(-1)-8=1-2-8=-9.$$
>
> Como la parábola abre hacia arriba, el vértice es mínimo absoluto:
>
> $$I_f=[-9,+\infty).$$
>
> **Conjuntos de positividad y negatividad.** Una parábola que abre hacia arriba es positiva fuera del intervalo entre sus raíces y negativa entre ellas:
>
> $$C^+=(-\infty,-4)\cup(2,+\infty),\qquad C^-=(-4,2).$$
>
> **Resultado:** $D_f=\mathbb{R}$, $I_f=[-9,+\infty)$, intersecciones $(0,-8)$, $(-4,0)$, $(2,0)$; $C^+=(-\infty,-4)\cup(2,+\infty)$, $C^-=(-4,2)$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `10b`

{: .enunciado }
> $f(x)=\lvert x-2\rvert$.

{: .resolucion }
> Es un valor absoluto: su gráfica tiene forma de "V" con vértice en $(2,0)$, donde el argumento $x-2$ se anula.
>
> **Dominio.** $\lvert x-2\rvert$ está definido para todo real:
>
> $$D_f=\mathbb{R}.$$
>
> **Imagen.** El valor absoluto nunca es negativo y vale $0$ en $x=2$:
>
> $$I_f=[0,+\infty).$$
>
> **Intersecciones con los ejes.** $f(0)=\lvert-2\rvert=2$ → $(0,2)$. $f(x)=0\iff x=2$ → $(2,0)$.
>
> **Conjuntos de positividad y negatividad.** Como $\lvert x-2\rvert\geq 0$ siempre, y solo se anula en $x=2$:
>
> $$C^+=\mathbb{R}-\{2\},\qquad C^-=\varnothing.$$
>
> **Resultado:** $D_f=\mathbb{R}$, $I_f=[0,+\infty)$, intersecciones $(0,2)$ y $(2,0)$; $C^+=\mathbb{R}-\{2\}$, $C^-=\varnothing$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `10c`

{: .enunciado }
> $f(x)=\dfrac{x}{x-2}$.

{: .resolucion }
> Es una función homográfica (cociente de polinomios de grado $1$).
>
> **Dominio.** Denominador no nulo: $x-2\neq 0$, es decir:
>
> $$D_f=\mathbb{R}-\{2\}.$$
>
> **Asíntotas e imagen.** La asíntota vertical es $x=2$. La horizontal se obtiene del cociente de coeficientes principales:
>
> $$y_{AH}=\dfrac{1}{1}=1.$$
>
> Como la función nunca toma el valor de la AH:
>
> $$I_f=\mathbb{R}-\{1\}.$$
>
> **Intersecciones con los ejes.** $f(x)=0\iff x=0$ → corta a ambos ejes en $(0,0)$.
>
> **Conjuntos de positividad y negatividad.** Estudio de signos del cociente $\dfrac{x}{x-2}$ con raíz en $x=0$ y restricción en $x=2$:
>
> - $x<0$: numerador $<0$, denominador $<0$ → cociente positivo.
> - $0<x<2$: numerador $>0$, denominador $<0$ → cociente negativo.
> - $x>2$: ambos positivos → cociente positivo.
>
> Entonces:
>
> $$C^+=(-\infty,0)\cup(2,+\infty),\qquad C^-=(0,2).$$
>
> **Resultado:** $D_f=\mathbb{R}-\{2\}$, $I_f=\mathbb{R}-\{1\}$, intersección $(0,0)$; $C^+=(-\infty,0)\cup(2,+\infty)$, $C^-=(0,2)$. Asíntotas: $x=2$ (vertical) e $y=1$ (horizontal).
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `10d`*

{: .enunciado }
> $g(x)=\dfrac{-2x+3}{x+4}$.

{: .resolucion }
> Función homográfica.
>
> **Dominio.** $x+4\neq 0$:
>
> $$D_g=\mathbb{R}-\{-4\}.$$
>
> **Asíntotas e imagen.** Asíntota vertical $x=-4$. La horizontal es el cociente de coeficientes principales:
>
> $$y_{AH}=\dfrac{-2}{1}=-2.$$
>
> Imagen:
>
> $$I_g=\mathbb{R}-\{-2\}.$$
>
> **Intersecciones con los ejes.** $g(x)=0\iff -2x+3=0\iff x=\dfrac32$ → $\left(\dfrac32,0\right)$. $g(0)=\dfrac{3}{4}$ → $\left(0,\dfrac34\right)$.
>
> **Conjuntos de positividad y negatividad.** Numerador $-2x+3$ se anula en $x=\dfrac32$; denominador $x+4$ en $x=-4$.
>
> - $x<-4$: numerador $>0$, denominador $<0$ → cociente negativo.
> - $-4<x<\dfrac32$: numerador $>0$, denominador $>0$ → cociente positivo.
> - $x>\dfrac32$: numerador $<0$, denominador $>0$ → cociente negativo.
>
> Entonces:
>
> $$C^+=\left(-4,\dfrac32\right),\qquad C^-=(-\infty,-4)\cup\left(\dfrac32,+\infty\right).$$
>
> **Resultado:** $D_g=\mathbb{R}-\{-4\}$, $I_g=\mathbb{R}-\{-2\}$, intersecciones $\left(\dfrac32,0\right)$ y $\left(0,\dfrac34\right)$; $C^+=\left(-4,\dfrac32\right)$, $C^-=(-\infty,-4)\cup\left(\dfrac32,+\infty\right)$. Asíntotas: $x=-4$ (vertical) e $y=-2$ (horizontal).
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `10e`

{: .enunciado }
> $f(x)=\sqrt{x-2}$.

{: .resolucion }
> **Dominio.** Radicando no negativo:
>
> $$x-2\geq 0\iff x\geq 2.$$
>
> $$D_f=[2,+\infty).$$
>
> **Imagen.** La raíz cuadrada principal nunca es negativa, y toma todos los valores no negativos a partir de $0$:
>
> $$I_f=[0,+\infty).$$
>
> **Intersecciones con los ejes.** $f(2)=0$ → $(2,0)$. No corta el eje $y$ porque $0\notin D_f$.
>
> **Conjuntos de positividad y negatividad.** $\sqrt{x-2}>0$ para todo $x>2$, y solo se anula en $x=2$:
>
> $$C^+=(2,+\infty),\qquad C^-=\varnothing.$$
>
> **Resultado:** $D_f=[2,+\infty)$, $I_f=[0,+\infty)$, intersección $(2,0)$; $C^+=(2,+\infty)$, $C^-=\varnothing$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `10f`

{: .enunciado }
> $f(x)=\ln(x+1)$.

{: .resolucion }
> **Dominio.** El logaritmo natural exige argumento estrictamente positivo:
>
> $$x+1>0\iff x>-1.$$
>
> $$D_f=(-1,+\infty).$$
>
> **Imagen y asíntotas.** La función $\ln$ toma todos los reales, por lo que:
>
> $$I_f=\mathbb{R}.$$
>
> Asíntota vertical en el borde del dominio: $x=-1$.
>
> **Intersecciones con los ejes.** $f(x)=0\iff \ln(x+1)=0\iff x+1=1\iff x=0$ → $(0,0)$ (cruce con ambos ejes).
>
> **Conjuntos de positividad y negatividad.** $\ln(x+1)>0\iff x+1>1\iff x>0$, y $\ln(x+1)<0\iff 0<x+1<1\iff -1<x<0$. Entonces:
>
> $$C^+=(0,+\infty),\qquad C^-=(-1,0).$$
>
> **Resultado:** $D_f=(-1,+\infty)$, $I_f=\mathbb{R}$, intersección $(0,0)$; $C^+=(0,+\infty)$, $C^-=(-1,0)$. Asíntota vertical $x=-1$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

### `10g`

{: .enunciado }
> $f(x)=2^{x+1}$.

{: .resolucion }
> **Dominio.** La exponencial está definida para todo real:
>
> $$D_f=\mathbb{R}.$$
>
> **Imagen y asíntotas.** Toda exponencial con base positiva $\neq 1$ es estrictamente positiva:
>
> $$I_f=(0,+\infty).$$
>
> Asíntota horizontal $y=0$ por izquierda (cuando $x\to-\infty$, $2^{x+1}\to 0$).
>
> **Intersecciones con los ejes.** No corta el eje $x$ porque la exponencial nunca se anula. Con el eje $y$: $f(0)=2^{0+1}=2$ → $(0,2)$.
>
> **Conjuntos de positividad y negatividad.** Por la imagen:
>
> $$C^+=\mathbb{R},\qquad C^-=\varnothing.$$
>
> **Resultado:** $D_f=\mathbb{R}$, $I_f=(0,+\infty)$, intersección $(0,2)$, no corta el eje $x$; $C^+=\mathbb{R}$, $C^-=\varnothing$. Asíntota horizontal $y=0$.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.

---

## Ejercicio 11 — Funciones por tramos

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

---

## Ejercicio 12* — Beneficio (miles de euros)

$B(t)=-t^2+7t\ (0\le t\le5);\ 10\ (5<t\le8)$.

### `12a` - Gráfica

Parábola hacia abajo en $[0,5]$ con vértice, luego constante en $10$ desde $t=5$ a $t=8$ (GeoGebra).

### `12b` - Mayor beneficio

Vértice de $-t^2+7t$ en $t=\dfrac{7}{2}=3{,}5$: $B(3{,}5)=-12{,}25+24{,}5=12{,}25$. La constante $10$ es menor.

**Resultado: máximo $12{,}25$ (miles de euros) a los $3{,}5$ años.** ✓ Coincide.

### `12c` - ¿Cuándo $11{,}250{,}000$ euros = $11{,}25$ miles? (en miles, $B=11{,}25$)

$$-t^2+7t=11{,}25\ \Rightarrow\ t^2-7t+11{,}25=0\ \Rightarrow\ t=\dfrac{7\pm\sqrt{49-45}}{2}=\dfrac{7\pm2}{2}.$$

$t=2{,}5$ o $t=4{,}5$ (ambos en $[0,5]$).

**Resultado: a los $2{,}5$ y $4{,}5$ años.** ✓ Coincide.

### `12d` - ¿Qué pasó tras el $5^\circ$ año?

A partir de $t=5$ el beneficio se mantiene constante en $10$.

**Resultado: el beneficio se estabilizó en $10$ (millones/miles según unidad).** ✓ Coincide.

---

## Ejercicio 13 — Paridad

Recordatorio: **par** si $f(-x)=f(x)$ (simétrica respecto al eje $y$); **impar** si $f(-x)=-f(x)$ (simétrica respecto al origen).

| Inciso | Función | $f(-x)$ | Conclusión |
|--------|---------|---------|-----------|
| a) | $x^2-4$ | $x^2-4=f(x)$ | **Par** |
| b) | $x^2+x-2$ | $x^2-x-2\neq\pm f$ | **Ninguna** |
| c) | $\lvert x+1\rvert-\lvert x-1\rvert$ | $\lvert -x+1\rvert-\lvert -x-1\rvert=\lvert x-1\rvert-\lvert x+1\rvert=-f(x)$ | **Impar** |
| d) | $x+1$ | $-x+1\neq\pm f$ | **Ninguna** |
| e) | $\sqrt[3]{x}$ | $-\sqrt[3]{x}=-f(x)$ | **Impar** |
| f)* | $\sqrt[3]{x^2}$ | $\sqrt[3]{x^2}=f(x)$ | **Par** |
| g)* | $x-3x^3$ | $-x+3x^3=-f(x)$ | **Impar** |
| h)* | $\dfrac{1-x}{1+x}$ | $\dfrac{1+x}{1-x}\neq\pm f$ | **Ninguna** |
| i) | $\dfrac{1}{\lvert x\rvert}$ | $\dfrac{1}{\lvert x\rvert}=f(x)$ | **Par** |
| j) | $2^x+2^{-x}$ | $2^{-x}+2^{x}=f(x)$ | **Par** |
{: .table-tight }

**Resultado: Pares $\{a,f,i,j\}$; Impares $\{c,e,g\}$; Ninguna $\{b,d,h\}$.**

✓ Coincide con la respuesta oficial.

---

## Ejercicio 14 — Efecto de transformaciones (con $c\in\mathbb{R}$)

- **a) $y=f(x)+c$:** desplazamiento **vertical**: hacia arriba si $c>0$, hacia abajo si $c<0$. ($\lvert c\rvert$ unidades.)
- **b) $y=f(x-c)$:** desplazamiento **horizontal**: a la derecha si $c>0$, a la izquierda si $c<0$.
- **c) $y=f(cx)$:** **escalado horizontal** (compresión si $\lvert c\rvert>1$, dilatación si $0<\lvert c\rvert<1$); si $c<0$, además refleja respecto al eje $y$.
- **d) $y=c\,f(x)$:** **escalado vertical** (estiramiento si $\lvert c\rvert>1$, compresión si $0<\lvert c\rvert<1$); si $c<0$, además refleja respecto al eje $x$.

---

## Ejercicio 15 — Reflexiones

- **a) $y=-f(x)$:** reflexión respecto al **eje $x$** (lo de arriba va abajo).
- **b) $y=f(-x)$:** reflexión respecto al **eje $y$** (izquierda y derecha se intercambian).

---

## Ejercicio 16 — Graficar con transformaciones; dominio, imagen, ceros

### `16a` - $f(x)=\lvert x+2\rvert-\tfrac32$

Base $\lvert x\rvert$: traslación **2 a la izquierda** y **$\tfrac32$ abajo**. Vértice en $\left(-2,-\tfrac32\right)$.

- $D=\mathbb{R}$, $I=\left[-\tfrac32,+\infty\right)$.
- **Ceros:** $\lvert x+2\rvert=\tfrac32\Rightarrow x+2=\pm\tfrac32\Rightarrow x=-\tfrac12$ o $x=-\tfrac72$.

**Resultado: $D=\mathbb{R}$, $I=\left[-\tfrac32,+\infty\right)$, ceros $\{-\tfrac72,-\tfrac12\}$.** ✓ Coincide.

### `16b`* - $g(x)=-\sqrt{x-1}+2$

Base $\sqrt{x}$: **1 a la derecha**, **reflexión respecto al eje $x$**, **2 arriba**.

- $D=[1,+\infty)$. Como $-\sqrt{x-1}\le0$, $g(x)\le2$, máximo en $x=1$: $I=(-\infty,2]$.
- **Cero:** $-\sqrt{x-1}+2=0\Rightarrow\sqrt{x-1}=2\Rightarrow x-1=4\Rightarrow x=5$.

**Resultado: $D=[1,+\infty)$, $I=(-\infty,2]$, cero $\{5\}$.** ✓ Coincide.

### `16c` - $m(x)=\dfrac{1}{2-x}$

Reescribimos $\dfrac{1}{2-x}=-\dfrac{1}{x-2}$: base $\tfrac1x$, traslación 2 a la derecha y reflexión.

- $D=\mathbb{R}-\{2\}$. AV $x=2$, AH $y=0$, $I=\mathbb{R}-\{0\}$.
- **Ceros:** el numerador es $1\neq0$: **sin ceros**.

**Resultado: $D=\mathbb{R}-\{2\}$, $I=\mathbb{R}-\{0\}$, sin ceros.** ✓ Coincide.

### `16d` - $k(x)=(x+4)^3-1$

Base $x^3$: **4 a la izquierda**, **1 abajo**.

- $D=I=\mathbb{R}$ (la cúbica es biyectiva).
- **Cero:** $(x+4)^3=1\Rightarrow x+4=1\Rightarrow x=-3$.

**Resultado: $D=I=\mathbb{R}$, cero $\{-3\}$.** ✓ Coincide.

---

## Ejercicio 17* — ¿Existe $f(x)=C\cdot a^x$ por $(-1,6)$ y $(3,\tfrac38)$?

Planteamos el sistema:

$$C\,a^{-1}=6,\qquad C\,a^{3}=\dfrac38.$$

Dividiendo la segunda por la primera:

$$\dfrac{C a^3}{C a^{-1}}=a^4=\dfrac{3/8}{6}=\dfrac{3}{48}=\dfrac{1}{16}\ \Rightarrow\ a=\left(\dfrac{1}{16}\right)^{1/4}=\dfrac12.$$

Entonces $C=6\,a=6\cdot\tfrac12=3$.

**Resultado: $f(x)=3\left(\dfrac12\right)^x$.** Sí existe. ✓ Coincide con la respuesta oficial.

---

## Ejercicio 18* — Presión atmosférica

$p=760\,e^{-0{,}144h}$. La presión al nivel del mar es $760$; buscamos la mitad, $380$:

$$380=760\,e^{-0{,}144h}\ \Rightarrow\ e^{-0{,}144h}=\dfrac12\ \Rightarrow\ -0{,}144h=\ln\tfrac12\ \Rightarrow\ h=\dfrac{\ln2}{0{,}144}\approx\dfrac{0{,}6931}{0{,}144}\approx4{,}81.$$

**Resultado: $h\approx4{,}81$ km.** ✓ Coincide con la respuesta oficial.

---

## Ejercicio 19* — Población de aves

Inicia con $50$ y se triplica cada $2$ años: $A(t)=50\cdot3^{t/2}$.

### `19a` - Tamaño a $6$ años

$$A(6)=50\cdot3^{6/2}=50\cdot3^3=50\cdot27=1350.$$

**Resultado: $1350$ aves.** ✓ Coincide.

### `19b` - $P(t)$

**Resultado: $A:[0,+\infty)\to\mathbb{R}$ (en contexto $[50,+\infty)$), $A(t)=50\cdot3^{t/2}$.** ✓ Coincide.

### `19c` - Tiempo para $1000$ aves

$$50\cdot3^{t/2}=1000\ \Rightarrow\ 3^{t/2}=20\ \Rightarrow\ \dfrac t2=\log_3 20\ \Rightarrow\ t=2\,\dfrac{\ln20}{\ln3}\approx2\cdot2{,}727\approx5{,}45.$$

$0{,}45$ años $\approx0{,}45\cdot365\approx165$ días.

**Resultado: $\approx5$ años y $165$ días.** ✓ Coincide.

---

## Ejercicio 20 — Transformaciones de $\ln x$ y $e^x$

### `20a` - Sobre $\ln x$ (base: $D=(0,+\infty)$, $I=\mathbb{R}$, AV $x=0$, pasa por $(1,0)$)

| Función | Transformación | Dominio |
|---------|----------------|---------|
| $\ln(x-2)$ | 2 a la derecha (AV $x=2$) | $(2,+\infty)$ |
| $\ln x+2$ | 2 arriba | $(0,+\infty)$ |
| $-\ln x$ | reflexión respecto al eje $x$ | $(0,+\infty)$ |
| $\ln(-x)$ | reflexión respecto al eje $y$ | $(-\infty,0)$ |
| $\ln\lvert x\rvert$ | par; suma la rama izquierda reflejada | $\mathbb{R}-\{0\}$ |
| $\lvert\ln x\rvert$ | refleja hacia arriba la parte negativa ($0<x<1$) | $(0,+\infty)$ |
{: .table-tight }

### `20b` - Sobre $e^x$ (base: $D=\mathbb{R}$, $I=(0,+\infty)$, AH $y=0$, pasa por $(0,1)$)

| Función | Transformación | Imagen |
|---------|----------------|--------|
| $e^{x+3}$ | 3 a la izquierda | $(0,+\infty)$ |
| $e^x-1$ | 1 abajo (AH $y=-1$) | $(-1,+\infty)$ |
| $-e^x$ | reflexión respecto al eje $x$ | $(-\infty,0)$ |
| $e^{-x}$ | reflexión respecto al eje $y$ | $(0,+\infty)$ |
| $e^{\lvert x\rvert}$ | par; mínimo $1$ en $x=0$ | $[1,+\infty)$ |
| $-e^{2x+3}+1$ | compresión horiz., refl. eje $x$, 1 arriba (AH $y=1$) | $(-\infty,1)$ |
{: .table-tight }

Todas se verifican en GeoGebra.

---

## Ejercicio 21 — Decibeles

$d=10\log\!\left(\dfrac{P}{P_0}\right)$. Despejamos la potencia.

**Concierto ($110$ dB):** $110=10\log\!\left(\tfrac{P_c}{P_0}\right)\Rightarrow\log\!\left(\tfrac{P_c}{P_0}\right)=11\Rightarrow P_c=10^{11}P_0$.

**Tráfico ($90$ dB):** $\log\!\left(\tfrac{P_t}{P_0}\right)=9\Rightarrow P_t=10^{9}P_0$.

Comparación:

$$\dfrac{P_c}{P_t}=\dfrac{10^{11}P_0}{10^{9}P_0}=10^2=100.$$

**Resultado: el concierto tiene $100$ veces más potencia (intensidad) que el tráfico.** ✓ Coincide.

---

## Ejercicio 22* — Efecto sobre $f(x)=\operatorname{sen}x$

Base: $D=\mathbb{R}$, $I=[-1,1]$, período $2\pi$.

- **a) $c\operatorname{sen}x\ (c>0)$:** cambia la **amplitud** a $c$. Imagen $[-c,c]$. Dominio $\mathbb{R}$.
- **b) $\operatorname{sen}(cx)\ (c>0)$:** cambia el **período** a $\dfrac{2\pi}{c}$ (compresión horizontal si $c>1$). Imagen $[-1,1]$.
- **c) $\operatorname{sen}x+c$:** desplazamiento **vertical** $c$. Imagen $[-1+c,\,1+c]$.
- **d) $\operatorname{sen}(x-c)$:** desfase **horizontal** $c$ a la derecha. Imagen $[-1,1]$.

---

## Ejercicio 23 — Transformaciones de $\operatorname{sen}x$

- **a) +3 arriba:** $y=\operatorname{sen}x+3$, imagen $[2,4]$.
- **b) $\pi/2$ a la derecha:** $y=\operatorname{sen}\!\left(x-\tfrac\pi2\right)=-\cos x$, imagen $[-1,1]$.
- **c) período a la mitad:** período $\pi\Rightarrow y=\operatorname{sen}(2x)$, imagen $[-1,1]$.
- **d) amplitud al doble:** $y=2\operatorname{sen}x$, imagen $[-2,2]$.

**Acotación:** como $-1\le\operatorname{sen}x\le1$ para todo $x$, cualquier $y=a\operatorname{sen}(bx)+c$ está **acotada** entre $c-\lvert a\rvert$ y $c+\lvert a\rvert$. La función es periódica y nunca diverge.

---

## Ejercicio 24* — Profundidad sinusoidal

Ciclo cada $4$ h, mínimo $1$ m, máximo $2$ m. Modelo $p(t)=a\operatorname{sen}(bt)+c$.

### `24a` - Variables

Independiente: tiempo $t$ (h). Dependiente: profundidad $p$ (m).

### `24b` - Parámetros

- **Amplitud:** $a=\dfrac{\max-\min}{2}=\dfrac{2-1}{2}=\dfrac12$.
- **Desplazamiento vertical:** $c=\dfrac{\max+\min}{2}=\dfrac{2+1}{2}=\dfrac32$.
- **Frecuencia:** período $T=4\Rightarrow b=\dfrac{2\pi}{T}=\dfrac{2\pi}{4}=\dfrac\pi2$.

**Resultado: $p(t)=\dfrac12\operatorname{sen}\!\left(\dfrac\pi2 t\right)+\dfrac32$.** ✓ Coincide ($a=\tfrac12,b=\tfrac\pi2,c=\tfrac32$).

### `24c` - Dominio e imagen (terna)

**Resultado: $p:[0,+\infty)\to[1,2]$.** ✓ Coincide.

### `24d` - Profundidad a $6$ h

$$p(6)=\dfrac12\operatorname{sen}\!\left(\dfrac\pi2\cdot6\right)+\dfrac32=\dfrac12\operatorname{sen}(3\pi)+\dfrac32=\dfrac12\cdot0+\dfrac32=1{,}5.$$

**Resultado: $1{,}5$ m.** ✓ Coincide.

### `24e` - Variación entre $3$ y $4$ h

$p(3)=\dfrac12\operatorname{sen}\!\left(\dfrac{3\pi}{2}\right)+\dfrac32=\dfrac12(-1)+\dfrac32=1$.
$p(4)=\dfrac12\operatorname{sen}(2\pi)+\dfrac32=\dfrac32$.
Variación $=1{,}5-1=0{,}5$.

**Resultado: medio metro ($0{,}5$ m).** ✓ Coincide.

---

## Ejercicio 25 — Presión arterial $P(t)=100-20\cos\!\left(\tfrac{8\pi}{3}t\right)$

### `25a` - Variables

Independiente: tiempo $t$ (s). Dependiente: presión $P$ (mmHg).

### `25b` - Dominio e imagen (se mide $1$ minuto $=60$ s)

El coseno varía en $[-1,1]$, entonces $-20\cos(\cdot)\in[-20,20]$ y $P\in[80,120]$.

**Resultado: $D_P=[0,60]$, $I_P=[80,120]$.** ✓ Coincide.

### `25c` - Período

$$T=\dfrac{2\pi}{8\pi/3}=2\pi\cdot\dfrac{3}{8\pi}=\dfrac{6}{8}=\dfrac34\ \text{s}.$$

**Resultado: período $\tfrac34$ s.** ✓ Coincide.

### `25d` - Amplitud

**Resultado: $20$.** ✓ Coincide.

### `25e` - Pulso (latidos por minuto)

Cada período es un latido. En $60$ s caben $\dfrac{60}{3/4}=80$ latidos.

**Resultado: $80$ LPM.** ✓ Coincide.

---

## Ejercicio 26 — Función inversa

Recordatorio: para invertir, $f$ debe ser **biyectiva** (inyectiva + sobreyectiva) en el dominio/codominio dados; se intercambian dominio e imagen.

### `26a` - $f(x)=(x-1)^3+8$

Cúbica trasladada: biyectiva en $\mathbb{R}$. Despejamos:

$$y-8=(x-1)^3\Rightarrow x-1=\sqrt[3]{y-8}\Rightarrow x=\sqrt[3]{y-8}+1.$$

**Resultado: $f^{-1}(x)=\sqrt[3]{x-8}+1$, $\mathbb{R}\to\mathbb{R}$.** ✓ Coincide.

### `26b` - $f(x)=e^{2x}+1$

Inyectiva; imagen $(1,+\infty)$.

$$y-1=e^{2x}\Rightarrow 2x=\ln(y-1)\Rightarrow x=\tfrac12\ln(y-1).$$

**Resultado: $f:\mathbb{R}\to(1,+\infty)$, $f^{-1}(x)=\tfrac12\ln(x-1)$.** ✓ Coincide.

### `26c` - $f(x)=3-\sqrt{x+5}$

$D=[-5,+\infty)$; como $\sqrt{x+5}\ge0$, $f(x)\le3$, imagen $(-\infty,3]$. Inyectiva (decreciente).

$$y-3=-\sqrt{x+5}\Rightarrow\sqrt{x+5}=3-y\Rightarrow x+5=(3-y)^2\Rightarrow x=(3-y)^2-5.$$

**Resultado: $f:[-5,+\infty)\to(-\infty,3]$, $f^{-1}(x)=(3-x)^2-5$.** ✓ Coincide.

### `26d`* - $f(x)=\log_3(2x-4)$

$D:2x-4>0\Rightarrow x>2$, es decir $(2,+\infty)$; imagen $\mathbb{R}$.

$$y=\log_3(2x-4)\Rightarrow 3^y=2x-4\Rightarrow x=\dfrac{3^y+4}{2}.$$

**Resultado: $f:(2,+\infty)\to\mathbb{R}$, $f^{-1}(x)=\dfrac{3^x+4}{2}$.** ✓ Coincide.

### `26e` - $f(x)=2x^2-1$

No es inyectiva en $\mathbb{R}$ (parábola). Restringimos a $[0,+\infty)$ (rama derecha): imagen $[-1,+\infty)$.

$$y+1=2x^2\Rightarrow x^2=\dfrac{y+1}{2}\Rightarrow x=\sqrt{\dfrac{y+1}{2}}\ (x\ge0).$$

**Resultado: $f:[0,+\infty)\to[-1,+\infty)$, $f^{-1}(x)=\sqrt{\dfrac{x+1}{2}}$** (la rama $(-\infty,0]$ da $-\sqrt{\tfrac{x+1}{2}}$). ✓ Coincide.

### `26f`* - $f(x)=2\operatorname{sen}(3x)$

Se restringe a un intervalo donde $3x\in\left[-\tfrac\pi2,\tfrac\pi2\right]$, es decir $x\in\left[-\tfrac\pi6,\tfrac\pi6\right]$; imagen $[-2,2]$.

$$y=2\operatorname{sen}(3x)\Rightarrow\operatorname{sen}(3x)=\dfrac y2\Rightarrow 3x=\arcsin\!\left(\dfrac y2\right)\Rightarrow x=\dfrac13\arcsin\!\left(\dfrac y2\right).$$

**Resultado: $f:\left[-\tfrac\pi6,\tfrac\pi6\right]\to[-2,2]$, $f^{-1}(x)=\tfrac13\arcsin\!\left(\tfrac x2\right)$.** ✓ Coincide.

### `26g` - $f(x)=\dfrac{-x+3}{x-1}$

$D=\mathbb{R}-\{1\}$; AH $y=-1$, imagen $\mathbb{R}-\{-1\}$. Despejamos:

$$y(x-1)=-x+3\Rightarrow yx-y=-x+3\Rightarrow x(y+1)=y+3\Rightarrow x=\dfrac{y+3}{y+1}.$$

**Resultado: $f:\mathbb{R}-\{1\}\to\mathbb{R}-\{-1\}$, $f^{-1}(x)=\dfrac{x+3}{x+1}$.** ✓ Coincide.

---

## Ejercicio 27 — $A(t)=100(1-0{,}9^t)$, $t\in[0,10]$ (mg)

### `27a` - Variables, dominio/imagen

Independiente: tiempo $t$. Dependiente: cantidad $A$ (mg). En $t=0$, $A=0$; en $t=10$, $A=100(1-0{,}9^{10})$.

**Resultado: $D=[0,10]$, $I=\left[0,\,100(1-0{,}9^{10})\right]\approx[0;\,65{,}13]$.** ✓ Coincide.

### `27b` - ¿Qué es $A^{-1}$? Hallarla

$A^{-1}$ da el **tiempo** en función de la cantidad de mg absorbida.

$$A=100(1-0{,}9^t)\Rightarrow 1-0{,}9^t=\dfrac{A}{100}\Rightarrow 0{,}9^t=1-\dfrac{A}{100}\Rightarrow t=\dfrac{\ln\!\left(1-\tfrac{A}{100}\right)}{\ln0{,}9}.$$

**Resultado: $t(A)=\dfrac{\ln\!\left(1-\tfrac{A}{100}\right)}{\ln0{,}9}$.** ✓ Coincide.

### `27c` - Minutos para $50$ mg

$$0{,}9^t=1-\dfrac{50}{100}=0{,}5\Rightarrow t=\dfrac{\ln0{,}5}{\ln0{,}9}\approx\dfrac{-0{,}6931}{-0{,}1054}\approx6{,}58.$$

**Resultado: $\approx6{,}58$ min.** ✓ Coincide.

---

## Ejercicio 28 — Resorte lineal $L(P)$

$7$ cm con $10$ g, $13$ cm con $80$ g.

Pendiente:

$$m=\dfrac{13-7}{80-10}=\dfrac{6}{70}=\dfrac{3}{35}.$$

Ordenada (longitud sin peso): usando $(10,7)$,

$$7=\dfrac{3}{35}\cdot10+b=\dfrac{30}{35}+b=\dfrac67+b\Rightarrow b=7-\dfrac67=\dfrac{49-6}{7}=\dfrac{43}{7}.$$

**Resultado: $L(P)=\dfrac{3}{35}P+\dfrac{43}{7}$.** ✓ Coincide.

### `28a` - Longitud sin peso

$L(0)=\dfrac{43}{7}\approx6{,}14$ cm. ✓ Coincide.

### `28b` - Variación cada $10$ g

$\Delta L=m\cdot10=\dfrac{3}{35}\cdot10=\dfrac{30}{35}=\dfrac67$ cm. ✓ Coincide.

### `28c` - Dominio (se deforma al alargarse $5$ veces la longitud inicial)

Longitud inicial $\dfrac{43}{7}$; el límite es $5\cdot\dfrac{43}{7}=\dfrac{215}{7}$. El peso máximo $P_{\max}$ cumple $L(P_{\max})=\dfrac{215}{7}$:

$$\dfrac{3}{35}P+\dfrac{43}{7}=\dfrac{215}{7}\Rightarrow\dfrac{3}{35}P=\dfrac{172}{7}\Rightarrow P=\dfrac{172}{7}\cdot\dfrac{35}{3}=\dfrac{172\cdot5}{3}=\dfrac{860}{3}.$$

**Resultado: $D=\left[0,\dfrac{860}{3}\right]$, $I=\left[\dfrac{43}{7},\dfrac{215}{7}\right]$.** ✓ Coincide.

### `28d` - Inversa y significado

$$L=\dfrac{3}{35}P+\dfrac{43}{7}\Rightarrow P=\dfrac{35}{3}\left(L-\dfrac{43}{7}\right).$$

$L^{-1}$ da el **peso** necesario para una longitud dada.

---

## Ejercicio 29 — Gas (proporcionalidad inversa)

$V$ inversamente proporcional a $P$: $V=\dfrac kP$. Con $P=1,V=30\Rightarrow k=30$.

### `29a` - Fórmula, dominio/imagen

Datos $P\in[1,12]$; $V(1)=30$, $V(12)=\dfrac{30}{12}=2{,}5$.

**Resultado: $V:[1,12]\to[2{,}5;\,30]$, $V(P)=\dfrac{30}{P}$.** ✓ Coincide.

### `29b` - Volumen a $11$ atm

$$V(11)=\dfrac{30}{11}\approx2{,}72\ \text{litros}.$$

**Resultado: $\approx2{,}72$ litros.** ✓ Coincide.

### `29c` - ¿$P$ en función de $V$?

$$P=\dfrac{30}{V}.$$

**Resultado: $P:[2{,}5;\,30]\to[1,12]$, $P=\dfrac{30}{V}$.** ✓ Coincide.

---

## Ejercicio 30 — Masa de sustancia

$t=0,1,2,5\to$ masa $25,75,225,6075$. Cada paso multiplica por $3$ ($75/25=3$, $225/75=3$, y $6075/225=27=3^3$ ✓). Crecimiento exponencial $M(t)=25\cdot3^t$.

### `30a` - Masa inicial

$M(0)=25$ g. ✓ Coincide.

### `30b` - $M(t)$ (experimento $8$ h)

$M(8)=25\cdot3^8=25\cdot6561=164025$.

**Resultado: $M:[0,8]\to[25,\,164025]$, $M(t)=25\cdot3^t$.** ✓ Coincide.

### `30c` - Inversa y significado

$$M=25\cdot3^t\Rightarrow 3^t=\dfrac{M}{25}\Rightarrow t=\log_3\!\left(\dfrac{M}{25}\right).$$

$M^{-1}$ da el **tiempo** necesario para alcanzar una masa dada. **Resultado: $t=\log_3\!\left(\tfrac{M}{25}\right)$.** ✓ Coincide.

---

## Ejercicio 31* — Marea $y=5+4{,}9\cos\!\left(\tfrac\pi6 t\right)$

### `31a` - Gráfica en $[0,24]$ y terna

Coseno de amplitud $4{,}9$ centrado en $5$; período $\dfrac{2\pi}{\pi/6}=12$ h.

**Resultado: $y:[0,24]\to[0{,}1;\,9{,}9]$** (mín $5-4{,}9=0{,}1$, máx $5+4{,}9=9{,}9$). Verificar en GeoGebra.

### `31b` - Nivel en marea alta

Cuando $\cos=1$ (en $t=0,12,24$): $y=5+4{,}9=9{,}9$.

**Resultado: $9{,}9$ pies.** ✓ Coincide.

### `31c` - Marea baja

Cuando $\cos=-1$: $\dfrac\pi6 t=\pi\Rightarrow t=6$ (y $t=18$). $y=5-4{,}9=0{,}1$.

**Resultado: a las $6$ h y $18$ h, $0{,}1$ pies.** ✓ Coincide.

### `31d` - Período y amplitud

**Resultado: período $12$ h, amplitud $4{,}9$ pies.** ✓ Coincide.

### `31e` - Inversa restringida a las primeras $6$ h

En $[0,6]$ el coseno es inyectivo (decreciente). Despejamos:

$$y-5=4{,}9\cos\!\left(\dfrac\pi6 t\right)\Rightarrow\cos\!\left(\dfrac\pi6 t\right)=\dfrac{y-5}{4{,}9}\Rightarrow\dfrac\pi6 t=\arccos\!\left(\dfrac{y-5}{4{,}9}\right)\Rightarrow t=\dfrac6\pi\arccos\!\left(\dfrac{y-5}{4{,}9}\right).$$

**Resultado: $t=\dfrac6\pi\arccos\!\left(\dfrac{h-5}{4{,}9}\right)$.** ✓ Coincide.

---

## Ejercicio 32 — Verdadero o Falso (justificar)

**a) Si $f(x)=mx+b$, entonces $\Delta y=m$ en intervalos de longitud $1$.** En una recta $\Delta y=m\,\Delta x$; con $\Delta x=1$, $\Delta y=m$. **Verdadero.** ✓

**b) Si la imagen consta de un solo número, su dominio también.** Una función constante $f(x)=k$ tiene imagen $\{k\}$ pero dominio $\mathbb{R}$. **Falso.** ✓

**c) Si $f$ y $g$ tienen el mismo dominio, $f/g$ también.** Contraejemplo: $f=x+1$, $g=x-2$ (ambas con $D=\mathbb{R}$), pero $\dfrac fg$ excluye $x=2$, $D=\mathbb{R}-\{2\}$. **Falso.** ✓

**d) Si $\cos s=\cos t$ entonces $s=t$.** El coseno no es inyectivo: $\cos0=\cos2\pi=1$ pero $0\neq2\pi$. **Falso.** ✓

**e) Si $f$ es biyectiva, entonces $f^{-1}(x)=\tfrac{1}{f(x)}$.** Confunde inversa con recíproco. Contraejemplo: $f(x)=2x$, $f^{-1}(x)=\tfrac x2\neq\tfrac{1}{2x}$. **Falso.** ✓

**f) Las rectas $ax+y=c$ y $ax-y=c$ son perpendiculares.** Pendientes $-a$ y $a$; son perpendiculares solo si $(-a)(a)=-1\Rightarrow a^2=1\Rightarrow a=\pm1$. No en general. **Falso.** ✓

**g) Si $x>0$, $(\ln x)^6=6\ln x$.** $(\ln x)^6$ es la potencia sexta; $6\ln x=\ln x^6$. Son distintas (p. ej. $x=e$: $1\neq6$). **Falso.** ✓

**h) Si $f(a)=f(b)\Rightarrow a=b$.** Eso solo vale para funciones inyectivas. Contraejemplo: $f(x)=x^2$, $f(-2)=f(2)$ pero $-2\neq2$. **Falso.** ✓

**i) Si $f$ es función, $f(ax)=af(x)$.** Solo vale para lineales homogéneas. Contraejemplo: $f=\operatorname{sen}$, $\operatorname{sen}(2x)\neq2\operatorname{sen}x$. **Falso.** ✓

**j) $f(x)=\sqrt{\dfrac{x+3}{2-5x}}$ y $g(x)=\dfrac{\sqrt{x+3}}{\sqrt{2-5x}}$ son iguales.** Estudiemos dominios. Para $f$: $\dfrac{x+3}{2-5x}\ge0\Rightarrow x\in\left[-3,\tfrac25\right)$. Para $g$: $x+3\ge0$ y $2-5x>0\Rightarrow x\ge-3$ y $x<\tfrac25\Rightarrow\left[-3,\tfrac25\right)$. Coinciden los dominios y, donde existen, los valores son iguales (ambos factores no negativos). **Verdadero.** ✓

**k) $f(x)=4+\ln(3-x)$ surge de $\ln x$ por: traslación 3 a la izquierda, reflexión respecto al eje $y$, traslación 4 arriba.** $\ln(3-x)=\ln(-(x-3))$: reflexión en $y$ y traslación; sumar $4$ desplaza arriba. La descripción es válida. **Verdadero.** ✓

**l) Toda función inyectiva es sobreyectiva.** Contraejemplo: $f:\mathbb{R}\to\mathbb{R}$, $f(x)=e^x$ es inyectiva pero su imagen es $(0,+\infty)\neq\mathbb{R}$. **Falso.** ✓

**Resultado: Verdaderas $\{a,j,k\}$; Falsas $\{b,c,d,e,f,g,h,i,l\}$.** ✓ Coincide con la respuesta oficial.

---

## Ejercicios adicionales

### Adicional 1 — Paridad (V/F)

**a) $h(x)=\dfrac{2x}{x^2+5}$ "no tiene paridad".**

$$h(-x)=\dfrac{2(-x)}{(-x)^2+5}=\dfrac{-2x}{x^2+5}=-h(x).$$

La función es **impar** (sí tiene paridad).

> ⚠️ **Discrepancia:** Resultado calculado: $h$ es **impar** ($h(-x)=-h(x)$). Respuesta del documento: "no tiene paridad".
>
> **Causa probable:** el enunciado afirma erróneamente que no tiene paridad. Como cumple $h(-x)=-h(x)$, es impar. La afirmación del documento es **falsa**.

**b) $h(x)=\dfrac{3x^2}{x-5}$ "es par".**

$$h(-x)=\dfrac{3x^2}{-x-5}=-\dfrac{3x^2}{x+5}.$$

Esto **no** es igual a $h(x)=\dfrac{3x^2}{x-5}$ ni a $-h(x)$. No tiene paridad (ni par ni impar).

> ⚠️ **Discrepancia:** Resultado calculado: $h$ **no es par** (no tiene paridad). Respuesta del documento: "es par".
>
> **Causa probable:** aunque el numerador $3x^2$ es par, el denominador $x-5$ rompe toda simetría; además el dominio $\mathbb{R}-\{5\}$ no es simétrico respecto al origen, condición necesaria para tener paridad. La afirmación del documento es **falsa**.

**c) $k(x)=\dfrac{x^3}{16-x^2}$ "es impar".**

$$k(-x)=\dfrac{(-x)^3}{16-(-x)^2}=\dfrac{-x^3}{16-x^2}=-k(x).$$

Cociente de impar ($x^3$) sobre par ($16-x^2$) = impar; dominio $(-4,4)\setminus$... simétrico. Es **impar**.

**Resultado: impar.** ✓ Coincide con la respuesta oficial.

### Adicional 2 — $N(t)=227\,e^{0{,}007t}$ (millones, $t$ años post-1980)

**a) Variables y función:** independiente $t$ (años desde 1980), dependiente $N$ (millones). $N(t)=227\,e^{0{,}007t}$, con $N(0)=227$.

**b) Variación 1980–1990 ($t:0\to10$):**

$$N(10)=227\,e^{0{,}07}\approx227\cdot1{,}0725\approx243{,}46.$$

Variación $\approx243{,}46-227=16{,}46$ millones. Razón media $\approx1{,}65$ millones/año.

**c) Inversa:**

$$N=227\,e^{0{,}007t}\Rightarrow e^{0{,}007t}=\dfrac{N}{227}\Rightarrow t=\dfrac{1}{0{,}007}\ln\!\left(\dfrac{N}{227}\right)=\dfrac{\ln(N/227)}{0{,}007}.$$

Da el tiempo (años desde 1980) para una población dada.

**d) ¿Cuándo más del doble de 1980?** $N=2\cdot227=454$:

$$e^{0{,}007t}=2\Rightarrow t=\dfrac{\ln2}{0{,}007}\approx\dfrac{0{,}6931}{0{,}007}\approx99{,}0.$$

**Resultado: a los $\approx99$ años (alrededor del año 2079).**

### Adicional 3 — $L(d)=-10\log_2(d)+120$ (dB)

**a) Si $L=90$, hallar la distancia:**

$$90=-10\log_2(d)+120\Rightarrow-10\log_2 d=-30\Rightarrow\log_2 d=3\Rightarrow d=2^3=8\ \text{m}.$$

Terna en contexto: $L:(0,+\infty)\to\mathbb{R}$ (físicamente acotado por la fuente). **Distancia inicial $=8$ m.**

**b) Distancia para $60$ dB:**

$$60=-10\log_2 d+120\Rightarrow\log_2 d=6\Rightarrow d=2^6=64\ \text{m}.$$

**c) Inversa:**

$$L=-10\log_2 d+120\Rightarrow\log_2 d=\dfrac{120-L}{10}\Rightarrow d=2^{(120-L)/10}.$$

**Resultado: $d(L)=2^{(120-L)/10}$.**

### Adicional 4 — $C(q)=10+3\sqrt q$ (costo)

**a) ¿Costo cero si $q=0$?** $C(0)=10+0=10\neq0$. Hay un **costo fijo de $10$** aunque no se produzca nada. (No, no es cero.)

**b) Razón de cambio media de $100$ a $101$:**

$$\dfrac{C(101)-C(100)}{1}=3\left(\sqrt{101}-\sqrt{100}\right)=3(10{,}0499-10)=3\cdot0{,}0499\approx0{,}1496\approx0{,}15.$$

**c) Costo instantáneo (marginal) en $100$ y comparación.** La derivada (Unidad 3) es $C'(q)=\dfrac{3}{2\sqrt q}$; en $q=100$: $C'(100)=\dfrac{3}{2\cdot10}=0{,}15$.

**Resultado: la razón media ($\approx0{,}15$) coincide casi exactamente con el costo marginal instantáneo ($0{,}15$), porque el intervalo es muy pequeño ($\Delta q=1$).**

### Adicional 5 — (opción múltiple) $V(t)=10\left(1-\tfrac{t}{100}\right)^2$, $0\le t\le100$

Dominio $[0,100]$; $V(0)=10$, $V(100)=0$, decreciente en ese tramo, imagen $[0,10]$.

Inversa: $\dfrac{V}{10}=\left(1-\tfrac{t}{100}\right)^2\Rightarrow1-\tfrac{t}{100}=\sqrt{\dfrac{V}{10}}$ (raíz positiva, pues $1-\tfrac t{100}\ge0$) $\Rightarrow t=100\left(1-\sqrt{\dfrac{V}{10}}\right)$.

$V^{-1}:[0,10]\to[0,100]$. **Resultado: la opción correcta es la c) (terna $V^{-1}:[0,10]\to[0,100]$, $t(V)=100\!\left(1-\sqrt{V/10}\right)$).** ✓ Coincide.

### Adicional 6 — (opción múltiple) $g(x)=\dfrac{x^3}{\sqrt{16-x^2}}$

**Dominio:** $16-x^2>0$ (estricto, en denominador) $\Rightarrow-4<x<4$, es decir $(-4,4)$.

**Paridad:**

$$g(-x)=\dfrac{(-x)^3}{\sqrt{16-x^2}}=\dfrac{-x^3}{\sqrt{16-x^2}}=-g(x).$$

Dominio simétrico y $g(-x)=-g(x)$: **impar**.

**Resultado: impar, dominio $(-4,4)$.** ✓ Coincide.

### Adicional 7 — (opción múltiple) $m(x)=3\operatorname{sen}(5x)$

Por convención se restringe $5x\in\left[-\tfrac\pi2,\tfrac\pi2\right]\Rightarrow x\in\left[-\tfrac{\pi}{10},\tfrac{\pi}{10}\right]$; imagen $[-3,3]$.

$$y=3\operatorname{sen}(5x)\Rightarrow\operatorname{sen}(5x)=\dfrac y3\Rightarrow 5x=\arcsin\!\left(\dfrac y3\right)\Rightarrow x=\dfrac15\arcsin\!\left(\dfrac y3\right).$$

**Resultado: $m^{-1}:[-3,3]\to\left[-\tfrac{\pi}{10},\tfrac{\pi}{10}\right]$, $m^{-1}(x)=\tfrac15\arcsin\!\left(\tfrac x3\right)$.** ✓ Coincide.

### Adicional 8 — (opción múltiple) $U(t)=1000(1-e^{-0{,}05t})$

Para $t\ge0$: $U(0)=0$ y $U\to1000$ cuando $t\to+\infty$ (sin alcanzarlo). Imagen $[0,1000)$.

Inversa:

$$U=1000(1-e^{-0{,}05t})\Rightarrow1-e^{-0{,}05t}=\dfrac{U}{1000}\Rightarrow e^{-0{,}05t}=1-\dfrac{U}{1000}\Rightarrow t=-20\ln\!\left(1-\dfrac{U}{1000}\right).$$

El dominio de la inversa es la imagen de $U$.

**Resultado: $t(U)=-20\ln\!\left(1-\tfrac{U}{1000}\right)$, con dominio $[0,1000)$.** ✓ Coincide.

---

## Resumen de discrepancias

Se detectaron discrepancias con la respuesta oficial en:

1. **9j)** — el dominio oficial omite la rama $(-\infty,-1)$, donde el cociente bajo la raíz también es positivo.
2. **9k)** — el dominio oficial agrega indebidamente $(-\infty,-1)$, imposible porque allí $\sqrt{3x-4}$ no existe. (j y k parecen intercambiados.)
3. **9l)** — el dominio oficial $[1,5)-\{3\}$ omite $(-\infty,1)$, donde la raíz existe.
4. **Adicional 1a)** — el enunciado dice "no tiene paridad", pero la función es **impar**.
5. **Adicional 1b)** — el enunciado dice "es par", pero la función **no tiene paridad**.

En todos los demás ejercicios el resultado **coincide** con la respuesta oficial.
