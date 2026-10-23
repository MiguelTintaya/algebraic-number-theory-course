# Course Syllabus

## Teoría Algebraica de Números

Este documento organiza el contenido académico que da origen al repositorio.

El proyecto se desarrolla inicialmente a partir del sílabo del curso **CM062 — Teoría Algebraica de Números**, de la Escuela Profesional de Matemática de la Universidad Nacional de Ingeniería.

> Este repositorio es un proyecto educativo independiente y no constituye una publicación oficial de la Universidad Nacional de Ingeniería.

---

## Course description

El curso constituye una introducción a la teoría de números con especial énfasis en técnicas algebraicas.

Entre sus motivaciones principales se encuentran:

- problemas de divisibilidad;
- ecuaciones diofánticas;
- estructuras algebraicas asociadas a cuerpos numéricos;
- aplicaciones posteriores a áreas como la criptografía avanzada.

Los principales prerrequisitos son familiaridad con:

- grupos;
- anillos;
- espacios vectoriales.

---

# 0. Algebraic Preliminaries

## Preliminares Algebraicos

### 0.1 Factorización en dominios integrales

Estudio de divisibilidad y factorización en dominios integrales.

### 0.2 Dominios de ideales principales y dominios de factorización única

- Dominios de ideales principales.
- Dominios de factorización única.

### 0.3 Anillos de polinomios sobre un cuerpo

- Polinomios sobre cuerpos.
- Irreducibilidad.

### 0.4 Extensiones finitas de cuerpos

Estudio de extensiones finitas y sus propiedades fundamentales.

### 0.5 Extensiones de Galois

- Extensiones de Galois.
- Correspondencia de Galois.

---

# 1. Quadratic Forms

## Formas Cuadráticas

### 1.1 El problema \(p=X^2+nY^2\)

Estudio de la representación de números primos mediante formas cuadráticas.

### 1.2 Clasificación modular y discriminantes

- Clasificación modular.
- Discriminantes.

### 1.3 Símbolos de Legendre y reciprocidad cuadrática

- Símbolo de Legendre.
- Ley de reciprocidad cuadrática.

### 1.4 Composición y géneros

- Composición de formas cuadráticas.
- Géneros.

### 1.5 Grupo de clases de formas cuadráticas

Introducción al grupo de clases asociado a formas cuadráticas.

---

# 2. Rings of Integers

## Anillos de Enteros

### 2.1 Dominios de ideales principales y factorización única

Revisión y aplicación de:

- dominios de ideales principales;
- dominios de factorización única.

### 2.2 Inmersiones, normas y trazas

- Inmersiones de cuerpos numéricos.
- Norma.
- Traza.

### 2.3 Dependencia entera

- Elementos enteros.
- Dependencia entera.
- Dominios integralmente cerrados.

### 2.4 Cuerpos numéricos y anillos de enteros

- Cuerpos numéricos.
- Anillos de enteros.

### 2.5 Discriminantes y bases integrales

- Discriminantes.
- Bases integrales.

### 2.6 Dominios de Dedekind

Introducción y propiedades fundamentales de los dominios de Dedekind.

### 2.7 Teoría de ideales de Dedekind

- Ideales en dominios de Dedekind.
- Factorización de ideales.

### 2.8 Grupo de clases

Construcción y estudio del grupo de clases.

---

# 3. Geometry of Numbers

## Geometría de los Números

### 3.1 Grupos abelianos finitamente generados y retículos

- Grupos abelianos finitamente generados.
- Retículos.

### 3.2 Volúmenes de retículos

Estudio geométrico del volumen y dominios fundamentales.

### 3.3 Teorema de Minkowski

Estudio del teorema fundamental de Minkowski.

### 3.4 Cotas de Minkowski

Aplicación de las cotas de Minkowski a problemas aritméticos.

### 3.5 Finitud del grupo de clases

Aplicación de la geometría de números para demostrar la finitud del grupo de clases.

### 3.6 Grupo de unidades

Estudio de las unidades del anillo de enteros.

### 3.7 Teorema de Dirichlet

Teorema de unidades de Dirichlet.

---

# 4. Ramification

## Ramificación

### 4.1 Índices y grados de ramificación

- Índices de ramificación.
- Grados asociados a la descomposición de primos.

### 4.2 Extensiones no ramificadas

Estudio de extensiones no ramificadas.

### 4.3 Ramificación total y moderada

- Ramificación total.
- Ramificación moderada.

### 4.4 Teoría de ramificación de Hilbert

Introducción a la teoría de ramificación de Hilbert.

### 4.5 Símbolos de Artin

Introducción a los símbolos de Artin.

### 4.6 Extensiones abelianas

Estudio de grupos de clases asociados a extensiones abelianas.

---

# References

La bibliografía inicial indicada para el curso incluye:

1. David Cox, *Primes of the Form \(X^2+nY^2\)*.
2. Ireland and Rosen, *A Classical Introduction to Modern Number Theory*.
3. Serge Lang, *Algebraic Number Theory*.
4. Raghavan Narasimhan, *Algebraic Number Theory*.
5. Jürgen Neukirch, *Algebraic Number Theory*.
6. Pierre Samuel, *Théorie algébrique des nombres*.
7. J.-P. Serre, *A Course in Arithmetic*.
8. J.-P. Serre, *Local Fields*.
9. Joseph H. Silverman, *The Arithmetic of Elliptic Curves*.
10. Ian Stewart and David Tall, *Algebraic Number Theory*.

Una guía de lectura comentada será desarrollada posteriormente en:

```text
references/reading-guide.md
```

---

# Repository organization

El contenido de este sílabo se desarrollará principalmente dentro de:

```text
course/
├── 00-preliminaries/
├── 01-quadratic-forms/
├── 02-rings-of-integers/
├── 03-geometry-of-numbers/
└── 04-ramification/
```

Cada unidad podrá contener:

- teoría;
- definiciones;
- teoremas;
- demostraciones;
- ejemplos;
- ejercicios;
- referencias adicionales.

Los ejercicios y las soluciones se mantendrán en directorios separados.

---

# Progress

- [ ] Preliminares algebraicos
- [ ] Formas cuadráticas
- [ ] Anillos de enteros
- [ ] Geometría de los números
- [ ] Ramificación
