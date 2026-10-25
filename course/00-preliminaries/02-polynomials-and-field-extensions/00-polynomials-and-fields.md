# Polynomials and Field Extensions

Este capítulo desarrolla las herramientas básicas sobre anillos de polinomios y extensiones de cuerpos que se utilizarán durante todo el curso.

El objetivo principal es comprender cómo un elemento algebraico determina una extensión de cuerpos mediante su polinomio minimal.

---

## Learning objectives

Al finalizar este capítulo, el estudiante debería poder:

- utilizar el algoritmo de división en anillos de polinomios;
- comprender por qué $F[x]$ es un dominio euclídeo cuando $F$ es un cuerpo;
- definir elementos algebraicos y trascendentes;
- trabajar con extensiones de cuerpos;
- calcular el grado de una extensión;
- encontrar polinomios minimales;
- describir extensiones simples;
- utilizar la fórmula de la torre;
- construir extensiones generadas por varios elementos algebraicos.

---

## Prerequisites

Antes de estudiar este capítulo se recomienda conocer:

- dominios integrales;
- unidades;
- ideales;
- dominios euclídeos;
- dominios de ideales principales;
- dominios de factorización única;
- irreducibilidad de polinomios;
- espacios vectoriales.

---

# 1. Polynomial Rings

Sea $R$ un anillo.

El anillo de polinomios con coeficientes en $R$ se denota por

$$
R[x].
$$

Un polinomio no nulo

$$
f(x)=a_0+a_1x+\cdots+a_Nx^N,
\qquad
a_N\neq 0,
$$

tiene grado

$$
\deg(f)=N.
$$

El coeficiente $a_N$ se denomina **coeficiente principal**.

Decimos que $f$ es **mónico** si

$$
a_N=1.
$$

---

## 1.1 Polynomial division

Sean $f,g\in R[x]$.

Si el coeficiente principal de $g$ es una unidad de $R$, entonces existen

$$
q,r\in R[x]
$$

tales que

$$
f=qg+r,
$$

donde

$$
r=0
$$

o bien

$$
\deg(r)<\deg(g).
$$

Este resultado generaliza el algoritmo de división usual.

---

## 1.2 The case of a field

Si $F$ es un cuerpo, entonces todo elemento no nulo de $F$ es una unidad.

Por tanto, para todo

$$
f,g\in F[x],
\qquad
g\neq 0,
$$

existen $q,r\in F[x]$ tales que

$$
f=qg+r
$$

con

$$
r=0
$$

o

$$
\deg(r)<\deg(g).
$$

En consecuencia,

$$
(F[x],\deg)
$$

es un dominio euclídeo.

Por tanto:

$$
F[x]
\text{ es DE}
\Longrightarrow
F[x]
\text{ es DIP}
\Longrightarrow
F[x]
\text{ es DFU}.
$$

---

# 2. Algebraic Elements

Sea $E/F$ una extensión de cuerpos.

Un elemento

$$
\alpha\in E
$$

se dice **algebraico sobre $F$** si existe un polinomio no nulo

$$
f\in F[x]
$$

tal que

$$
f(\alpha)=0.
$$

Si no existe tal polinomio, $\alpha$ se denomina **trascendente sobre $F$**.

---

## Examples

El número

$$
i
$$

es algebraico sobre $\mathbb Q$, pues

$$
i^2+1=0.
$$

También

$$
\sqrt{2}
$$

es algebraico sobre $\mathbb Q$, ya que

$$
(\sqrt 2)^2-2=0.
$$

---

# 3. Field Extensions

Sean $F$ y $E$ cuerpos.

Decimos que

$$
E/F
$$

es una **extensión de cuerpos** si

$$
F\subseteq E.
$$

En este caso, $E$ puede considerarse como espacio vectorial sobre $F$.

---

## 3.1 Degree of an extension

Si $E$ es un espacio vectorial de dimensión finita sobre $F$, decimos que $E/F$ es una **extensión finita**.

Su grado se define mediante

$$
[E:F]
=
\dim_F E.
$$

---

## Example

Consideremos

$$
\mathbb Q(\sqrt 2).
$$

Todo elemento puede escribirse como

$$
a+b\sqrt 2,
\qquad
a,b\in\mathbb Q.
$$

Por tanto,

$$
\{1,\sqrt 2\}
$$

es una base sobre $\mathbb Q$ y

$$
[\mathbb Q(\sqrt 2):\mathbb Q]=2.
$$

---

# 4. Finite Extensions are Algebraic

## Theorem

Toda extensión finita es algebraica.

Es decir, si

$$
[E:F]<\infty,
$$

entonces todo

$$
\alpha\in E
$$

es algebraico sobre $F$.

### Idea of the proof

Sea

$$
[E:F]=n.
$$

Entonces los $n+1$ elementos

$$
1,\alpha,\alpha^2,\ldots,\alpha^n
$$

pertenecen al espacio vectorial $E$, que tiene dimensión $n$ sobre $F$.

Por tanto son linealmente dependientes.

Existen

$$
a_0,\ldots,a_n\in F,
$$

no todos nulos, tales que

$$
a_0+a_1\alpha+\cdots+a_n\alpha^n=0.
$$

Definiendo

$$
f(x)
=
a_0+a_1x+\cdots+a_nx^n,
$$

obtenemos

$$
f(\alpha)=0.
$$

Por tanto, $\alpha$ es algebraico sobre $F$.

---

# 5. Evaluation Homomorphism

Sea $\alpha$ algebraico sobre $F$.

Consideramos el homomorfismo de evaluación

$$
\operatorname{ev}_\alpha:F[x]\longrightarrow E
$$

definido por

$$
f\longmapsto f(\alpha).
$$

Su núcleo es

$$
\ker(\operatorname{ev}_\alpha)
=
\{f\in F[x]:f(\alpha)=0\}.
$$

Como $F[x]$ es un dominio de ideales principales, este ideal es principal.

---

# 6. Minimal Polynomial

Sea $\alpha$ algebraico sobre $F$.

El **polinomio minimal de $\alpha$ sobre $F$**, denotado por

$$
m_{F,\alpha},
$$

es el único polinomio mónico tal que

$$
\ker(\operatorname{ev}_\alpha)
=
(m_{F,\alpha}).
$$

El polinomio minimal es irreducible en $F[x]$.

Además, si

$$
h(\alpha)=0
$$

para algún $h\in F[x]$, entonces

$$
m_{F,\alpha}\mid h.
$$

---

## Examples

$$
m_{\mathbb Q,i}(x)=x^2+1,
$$

$$
m_{\mathbb Q,\sqrt 2}(x)=x^2-2,
$$

$$
m_{\mathbb Q,3/2}(x)=x-\frac32.
$$

---

# 7. Simple Extensions

Para $\alpha$ algebraico sobre $F$, definimos

$$
F[\alpha]
=
\{g(\alpha):g\in F[x]\}.
$$

Como $m_{F,\alpha}$ es irreducible,

$$
(m_{F,\alpha})
$$

es un ideal maximal de $F[x]$.

Por el primer teorema de isomorfismo,

$$
F[\alpha]
\cong
\frac{F[x]}{(m_{F,\alpha})}.
$$

Por tanto, $F[\alpha]$ es un cuerpo.

En particular,

$$
F[\alpha]=F(\alpha).
$$

---

# 8. Degree and Minimal Polynomial

Si

$$
n=\deg(m_{F,\alpha}),
$$

entonces

$$
1,\alpha,\alpha^2,\ldots,\alpha^{n-1}
$$

es una base de $F(\alpha)$ sobre $F$.

Por tanto,

$$
\boxed{
[F(\alpha):F]
=
\deg(m_{F,\alpha})
}.
$$

Este resultado será utilizado constantemente durante todo el curso.

---

# 9. Tower Law

Sean

$$
F\subseteq E\subseteq L
$$

extensiones de cuerpos.

Si

$$
L/E
$$

y

$$
E/F
$$

son finitas, entonces $L/F$ también es finita y

$$
\boxed{
[L:F]
=
[L:E]\,[E:F]
}.
$$

Esta identidad se conoce como **fórmula de la torre**.

---

## Example

Consideremos

$$
\mathbb Q
\subset
\mathbb Q(\sqrt2)
\subset
\mathbb Q(\sqrt2,\sqrt3).
$$

Tenemos

$$
[\mathbb Q(\sqrt2):\mathbb Q]=2
$$

y

$$
[\mathbb Q(\sqrt2,\sqrt3):\mathbb Q(\sqrt2)]=2.
$$

Por tanto,

$$
[\mathbb Q(\sqrt2,\sqrt3):\mathbb Q]=4.
$$

Una base sobre $\mathbb Q$ es

$$
\{1,\sqrt2,\sqrt3,\sqrt6\}.
$$

---

# 10. Extensions Generated by Several Elements

Dados elementos algebraicos

$$
\alpha_1,\ldots,\alpha_r
$$

sobre $F$, podemos considerar

$$
F(\alpha_1,\ldots,\alpha_r).
$$

Para un número finito de elementos algebraicos se tiene

$$
F(\alpha_1,\ldots,\alpha_r)
=
F[\alpha_1,\ldots,\alpha_r].
$$

Además, toda extensión finita puede generarse por un número finito de elementos algebraicos.

---

# 11. Conceptual Summary

```mermaid
flowchart TD
    A[Polynomial Rings] --> B[Division Algorithm]
    B --> C[F[x] is Euclidean]
    C --> D[Algebraic Elements]
    D --> E[Field Extensions]
    E --> F[Finite Extensions]
    F --> G[Minimal Polynomial]
    G --> H[Simple Extensions]
    H --> I[Degree Formula]
    I --> J[Tower Law]
    J --> K[Finitely Generated Extensions]
    K --> L[Embeddings]
```

El siguiente capítulo desarrolla precisamente el último nodo:

[`01-embeddings-and-automorphisms.md`](01-embeddings-and-automorphisms.md)

---

# Exercises

Los ejercicios de este capítulo se organizarán posteriormente en:

`exercises/00-preliminaries/02-polynomials-and-field-extensions/`

---

# Source

Este capítulo está basado en las notas originales de la segunda parte del curso, reorganizadas para seguir una progresión conceptual.
