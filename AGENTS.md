# AGENTS.md

This file provides guidance to Codex when working with code in this repository.

## What this repo is

Study notes, guides, and practice exercises for the "Análisis Matemático I" course at UNLaM. Published as a GitHub Pages site using the `just-the-docs` Jekyll theme (`_config.yml`). GitHub Pages builds and deploys automatically on push — no local build step needed.

## Site, layout, and style changes

Before implementing ad hoc changes to **layout, styles, navigation, components, theme configuration, Mermaid, callouts, tables, code blocks, search, or site behavior**, first check whether **Just the Docs** already provides an official way to do it.

- Official documentation: <https://just-the-docs.com/>
- Prefer documented theme configuration, includes, Sass variables, components, and supported extensions.
- Use custom CSS or JavaScript only when the official mechanism does not cover the case, is insufficient, or the change is specific to this site and justified.
- If a custom solution is added, keep it scoped and briefly document why it exists when the reason is not obvious.

## Diagrams, SVG, and images

- Use **Mermaid** when a diagram improves understanding and the model should remain editable in Markdown.
- Mermaid is enabled in `_config.yml`; use fenced blocks:

  ````markdown
  ```mermaid
  flowchart LR
      A[Límite lateral] --> B[Comparar izquierda y derecha]
  ```
  ````

- Prefer Mermaid for flowcharts, conceptual relationships, process steps, and lightweight dependency diagrams.
- If Mermaid is not expressive enough for a mathematical graph, curve, visual construction, or geometric explanation, use an explanatory **SVG** instead.
- Store SVGs close to the content that uses them when they are unit-specific, such as `unidad-N/images/`; use `assets/img/` only for site-wide shared diagrams.
- Keep SVGs simple, legible, lightweight, and with Spanish labels.
- Do not add decorative images. Every diagram or image must clarify a concept, example, calculation, or GeoGebra workflow.

## Repository structure

Each unit follows the same internal layout:

```
unidad-N/
├── index.md         # Unit overview with topic table and links
├── teoria/          # Full unit summary in Markdown
├── guias/           # Focused reference guides on specific topics
├── practica/        # Exercise files (Markdown or plain text)
└── images/          # Images referenced from the Markdown files
```

Units are:
- **Unidad 1:** Funciones
- **Unidad 2:** Límite funcional y Continuidad
- **Unidad 3:** Derivada
- **Unidad 4:** Polinomios de Taylor

There is also a top-level **GeoGebra** section (`geogebra/`) at the same navigation level as the units. It contains a practical guide to GeoGebra in Spanish, organized by unit:

```
geogebra/
├── index.md                  # Overview, install instructions, ToC
├── basico.md                  # Interface, views, commands, sliders
├── funciones.md               # Unidad 1 (graphing, domain, transformations, regression)
├── limites-continuidad.md     # Unidad 2 (Límite, asymptotes, continuity)
├── derivada.md                # Unidad 3 (Derivada, tangent, optimization)
└── taylor.md                  # Unidad 4 (PolinomioTaylor, approximations)
```

The GeoGebra index has `has_children: true` and `has_toc: false` (the manual ToC in the page replaces the auto-generated one).

## Content conventions

- **Language**: All content is written in Spanish.
- **Math notation**: Use LaTeX-style notation inline (e.g., f′(x), lim, ∞) or fenced with `$$…$$` for block equations (just-the-docs supports MathJax if enabled, otherwise use Unicode).
- **Markdown**: GitHub-flavored Markdown. Tables, fenced code blocks with language tags, and heading-based `#` anchors are used throughout.
- **Front matter**: All pages must have at minimum `layout: default`, `title`, `parent` (for subpages), and `permalink`. The root `index.md` uses `layout: home`.
- **Navigation**: The `just-the-docs` theme uses `nav_order`, `has_children: true` (on parent pages), and `parent: <Title>` (on child pages) to build the sidebar.
- **Guides** (`guias/`): self-contained reference documents covering a single specific topic with examples.
- **Teoria files** (`teoria/`): comprehensive unit summaries covering all topics in the syllabus. Include a TOC block at the top.
- **Practica files** (`practica/`): exercises with commented solutions or step-by-step hints. **Each exercise lives in its own file** (`ejercicio-N.md`) as a child page of the practice index (`practica-N.md`), to keep page load fast. The practice index page lists the exercises with links and has `has_children: true` in its front matter. See the format below.

## Practica exercise format

Practice exercises must follow this exact structure so the site stays consistent. The two callouts (`enunciado`, `resolucion`) are configured in `_config.yml` and styled by `_sass/custom/setup.scss` (amber for statement, teal for solution).

**Estructura de archivos.** Una página por ejercicio. Por ejemplo, para Unidad 1, Práctica 1:

```
unidad-1/practica/
├── practica-1.md      # Índice con tabla de links a cada ejercicio
├── ejercicio-1.md     # Un ejercicio (con todos sus incisos a, b, c, …)
├── ejercicio-2.md
├── ...
├── ejercicio-32.md
└── adicionales.md     # Ejercicios extra
```

El front matter de cada `ejercicio-N.md` es:

```yaml
---
layout: default
title: Ejercicio N
parent: Práctica — Unidad 1
grand_parent: Unidad 1 — Funciones
nav_order: N
permalink: /unidad-1/practica/ejercicio-N
---
```

Adentro del archivo, la primera línea de contenido es un H1 con la consigna padre completa (ej. `# Ejercicio N — Descripción de la consigna`). Después siguen los subitems `### \`Na\``, `### \`Nb\``, etc. con sus callouts.

**Per-exercise template:**

```markdown
## 1d

{: .enunciado }
> Enunciado textual del ejercicio, copiado o reescrito de forma natural.

{: .resolucion }
> Texto explicativo introduciendo el primer paso.
>
> $$\text{ecuación o expresión}$$
>
> Conector que explica qué se hizo y qué sigue.
>
> $$\text{siguiente paso}$$
>
> ... (repetir tantos pasos como sea necesario)
>
> **Resultado:** expresión final con dominio e imagen cuando corresponda.
>
> **Verificación:** Coincide con la respuesta indicada en la guía.
```

**Source of truth para enunciados:** la guía oficial está en `reference/practica.pdf`. El enunciado **debe copiarse literalmente** de ese PDF, sin reescribirlo, resumirlo ni "naturalizarlo". Conservar la redacción, signos de puntuación, mayúsculas, paréntesis y notación matemática tal cual aparecen. Solo se permite traducir notación inline a LaTeX (`$…$`) cuando el PDF muestra fórmulas que en Markdown necesitan ese delimitador. Si el enunciado del PDF es ambiguo o contiene un error, no corregir en silencio: dejar el texto original y aclarar la interpretación en la resolución.

🚨 **REGLA CRÍTICA — copia textual estricta del enunciado.** El texto dentro del callout `{: .enunciado }` debe ser una **transcripción literal palabra por palabra** del PDF. Está prohibido:
- Reformular para que "suene mejor", combinar oraciones, dividir oraciones o reordenarlas.
- Cambiar conectores (sustituir "tal que" por "donde" o viceversa, agregar/quitar comas).
- Reemplazar términos por sinónimos (no usar "evaluar" si el PDF dice "calcular", no usar "función" si dice "fórmula").
- Agregar palabras de cortesía, aclaraciones o paréntesis que no estén en el original.
- Cambiar números, símbolos, mayúsculas, o el tipo de delimitadores numéricos (coma decimal vs punto).
- Omitir partes del enunciado por considerarlas redundantes.

La única transformación permitida es **convertir notación matemática inline a LaTeX delimitada por `$…$`** cuando Markdown lo requiera para que renderice (por ejemplo, una raíz que aparece como `√(x+1)` en el PDF se escribe como `$\sqrt{x+1}$`). Esto incluye respetar el formato de números argentino: si el PDF dice `0,5`, escribir `0{,}5` (no `0.5`). Si el PDF tiene typos o errores, **dejarlos tal cual** y aclarar la interpretación en la resolución, nunca en el enunciado.

**Reglas que aplican siempre:**

- 🚨 **REGLA CRÍTICA — NUNCA cerrar con punto el código LaTeX.** Ningún token LaTeX (display `$$…$$`, inline `$…$`, ni el interior de un entorno como `\begin{cases}…\end{cases}`) puede terminar en punto. Esto incluye los tres casos siguientes:
    - **Display:** `$$x\cdot y=16$$` ✓ &nbsp;&nbsp; `$$x\cdot y=16.$$` ✗
    - **Última condición dentro de `cases`:** `…2 & x>3 \end{cases}` ✓ &nbsp;&nbsp; `…2 & x>3. \end{cases}` ✗
    - **Inline al final de la oración:** `$x=1$.` ✓ (el punto queda **afuera** del `$` de cierre) &nbsp;&nbsp; `$x=1.$` ✗
  
  Es la regla que más se viola y es la que más rompe visualmente: el punto renderiza centrado al borde de la ecuación y se confunde con un operador (especialmente cerca de `\cdot` o yuxtaposiciones tipo $xy$, donde luce como un producto $\cdot$). **Coma sí está permitida** al final del display (`$$f(x)=a(x-h)^2+k,$$`) y al separar condiciones intermedias de un `cases`, porque la coma no se confunde con ningún operador. **Antes de cerrar cada edición** correr estas verificaciones:
    - `grep -nE '\.\$\$\s*$' archivo.md` → no debe haber matches (displays terminados en punto).
    - `grep -nE '\.\s*\\end\{cases\}' archivo.md` → no debe haber matches (cases con punto en última condición).
    - `grep -nE '\.\$[^$]' archivo.md` → revisar matches (inline con punto **adentro** del `$`).
- El heading de cada inciso es `## Nx` (H2, solo la numeración sin backticks ni descripción al lado). Como cada `ejercicio-N.md` tiene un H1 con la consigna padre, los incisos van un nivel abajo en H2.
- El enunciado va en un callout `{: .enunciado }` con una sola línea de blockquote `>`, **copiado textual del PDF**. Si el enunciado tiene varios renglones, prefijar cada uno con `>`.
- La resolución va en un callout `{: .resolucion }` y **todas** las líneas (texto, ecuaciones en bloque, líneas vacías de separación) deben empezar con `>` para no romper el blockquote.
- Cada paso del desarrollo se presenta como: oración explicativa → `$$ecuación$$` en bloque. Evitar amontonar varias igualdades en una sola línea; separar en pasos cortos legibles.
- Usar `\dfrac` (no `\frac`) para fracciones que aparezcan en displays.
- Cerrar siempre con dos líneas en negrita: `**Resultado:**` (la respuesta final, dominio e imagen cuando aplique) y `**Verificación:**` (confirmación contra la guía oficial).
- No usar emojis tipo ✓/✗; usar las líneas de verificación en negrita.
- Para definiciones por casos dentro de un callout, `\begin{cases}…\end{cases}` debe ir en **una sola línea** dentro de `$$…$$` (todo el `\begin…\end` en el mismo renglón, separando ramas con `\\`). Saltos de línea reales dentro del entorno rompen el blockquote del callout.
- **Nunca usar `|…|` con pipes crudos en una línea de blockquote** (callout): Kramdown los interpreta como separadores de columna de tabla y rompe el render. Para valor absoluto, normas, etc., usar siempre `\lvert … \rvert` (o `\vert`). Esto vale tanto en el enunciado como en cualquier ecuación inline o display dentro del callout.
- **Nunca usar `\{` o `\}` dentro de un blockquote en math** — usar `\lbrace` y `\rbrace`. En Markdown blockquotes (que es donde viven enunciados y resoluciones), Kramdown consume el `\` de `\{` y `\}` interpretándolos como escapes de llaves literales, así que MathJax termina recibiendo `{` y `}` sin el backslash, lo que rompe con errores tipo "Missing or unrecognized delimiter for \left" cuando van combinados con `\left\{…\right\}`. Patrón correcto: `$\left\lbrace -2,\,0\right\rbrace$`. Patrón **prohibido** en callouts: `$\left\{-2,\,0\right\}$`. Para conjuntos sin `\left/\right` (delimitadores de tamaño fijo), usar también `\lbrace … \rbrace` por consistencia.
- **Definición de una función como terna** (también pedida como "dominio, imagen y regla de asignación"): siempre escribirla en el formato canónico `nombre: Dominio \to Codominio \,/\, regla`. Ejemplo: $h:[0,4]\to[0,45]\,/\,y=h(t)=-5t^2+10t+40$. Cuando el enunciado pide la "terna", el resultado **debe** presentarse en esa forma (no basta con dar solo la fórmula). El separador `\,/\,` (con espacios finos) es el estilo que usa la cátedra para separar el dominio/codominio de la regla.
- **Tablas en la práctica**: aplicar siempre la clase `.table-tight` agregando una línea `{: .table-tight }` inmediatamente debajo de la tabla (sin línea en blanco entre la tabla y el atributo). La clase está definida en `_sass/custom/custom.scss` e impide que la tabla se estire al 100% del contenido cuando el ancho de las celdas no lo justifica. Vale tanto para tablas de datos numéricos (tipo $x/y$) como para tablas explicativas con texto.
- *(La regla del punto al final de displays está al inicio de esta lista por su importancia.)*

**Agrupación por consigna:** los ejercicios de una misma consigna (por ejemplo "Graficar, indicar dominio e imagen") van bajo el H1 del archivo `ejercicio-N.md`, y cada inciso `Na`, `Nb`, … usa el template de arriba.

## Units and syllabus

| Unidad | Topic | Parcial |
|--------|-------|---------|
| 1 | Funciones: definición, dominio, imagen, transformaciones, función inversa | 1er parcial |
| 2 | Límite funcional, infinitésimos, asíntotas, continuidad, discontinuidades | 1er (límites) y 2do (continuidad) |
| 3 | Derivada: definición, reglas, cadena, implícita, derivación logarítmica | 2do parcial |
| 4 | Polinomios de Taylor y Maclaurin, aproximación lineal, resto | 2do parcial |

## GitHub Pages config

- Theme: `just-the-docs/just-the-docs` (via `remote_theme`)
- URL: `https://unlam-informatica.github.io/analisis-matematico-i`
- Color scheme: dark
