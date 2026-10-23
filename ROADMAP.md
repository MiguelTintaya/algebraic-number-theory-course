# Learning Roadmap

Este documento describe la ruta conceptual recomendada para estudiar el contenido del repositorio.

El orden no representa únicamente una secuencia de capítulos: las flechas indican **dependencias matemáticas**.

---

# 1. Foundations

Antes de comenzar Teoría Algebraica de Números se recomienda dominar:

```text
Groups
   │
   ├── Subgroups
   ├── Quotient groups
   └── Homomorphisms

Rings
   │
   ├── Ideals
   ├── Quotient rings
   ├── Integral domains
   ├── PID
   └── UFD

Linear Algebra
   │
   ├── Vector spaces
   ├── Linear maps
   └── Determinants
```

Estas herramientas conducen a:

```text
Polynomial Rings
        │
        ▼
Irreducibility
        │
        ▼
Field Extensions
        │
        ▼
Galois Theory
```

---

# 2. Entry into Algebraic Number Theory

Una vez dominados los preliminares:

```text
Field Extensions
        │
        ▼
Number Fields
        │
        ▼
Algebraic Integers
        │
        ▼
Rings of Integers
```

El objeto central será:

\[
\mathcal O_K,
\]

el anillo de enteros de un cuerpo numérico \(K\).

---

# 3. Arithmetic Invariants

A partir de los cuerpos numéricos aparecen tres herramientas fundamentales:

```text
              Number Fields
                    │
          ┌─────────┼─────────┐
          ▼         ▼         ▼
        Norm      Trace   Embeddings
          │         │         │
          └─────────┼─────────┘
                    ▼
              Discriminant
                    │
                    ▼
              Integral Bases
```

Estos conceptos permiten estudiar la estructura aritmética de \(\mathcal O_K\).

---

# 4. Factorization and Ideals

La factorización única de elementos puede fallar en un anillo de enteros.

El remedio fundamental consiste en estudiar ideales:

```text
Failure of unique factorization
             │
             ▼
           Ideals
             │
             ▼
      Dedekind Domains
             │
             ▼
   Unique factorization
        of ideals
             │
             ▼
        Class Group
```

El grupo de clases mide, en cierto sentido, cuánto falla la factorización única de elementos.

---

# 5. Geometry of Numbers

Los embeddings permiten asociar un cuerpo numérico con un espacio euclídeo.

```text
Embeddings
     │
     ▼
Minkowski Embedding
     │
     ▼
  Lattices
     │
     ▼
Minkowski Theorem
     │
     ├───────────────┐
     ▼               ▼
Class Group       Units
Finiteness           │
                     ▼
              Dirichlet Unit
                 Theorem
```

Esta parte conecta álgebra, geometría y teoría de números.

---

# 6. Prime Decomposition and Ramification

Otro problema fundamental consiste en estudiar qué ocurre con un primo racional

\[
p\in\mathbb Z
\]

cuando se considera dentro de un cuerpo numérico.

La estructura general será:

```text
Prime ideals
     │
     ▼
Prime decomposition
     │
     ├── Ramification index
     ├── Residue degree
     └── Number of prime factors
     │
     ▼
Ramification Theory
     │
     ├── Unramified extensions
     ├── Total ramification
     ├── Tame ramification
     └── Hilbert ramification theory
     │
     ▼
Artin Symbol
```

---

# 7. Complete Roadmap

La ruta principal del curso puede resumirse como:

```text
Abstract Algebra
       │
       ▼
Field Extensions
       │
       ▼
Galois Theory
       │
       ▼
Number Fields
       │
       ▼
Algebraic Integers
       │
       ▼
Rings of Integers
       │
       ├───────────────┐
       ▼               ▼
Norm / Trace       Discriminant
       │               │
       └───────┬───────┘
               ▼
        Integral Bases
               │
               ▼
       Dedekind Domains
               │
               ▼
      Ideal Factorization
               │
       ┌───────┴────────┐
       ▼                ▼
   Class Group     Prime Decomposition
       │                │
       ▼                ▼
   Minkowski        Ramification
       │                │
       ▼                ▼
Class Number       Artin Symbol
       │
       ▼
Unit Group
       │
       ▼
Dirichlet Unit Theorem
```

---

# 8. Course Progress

## Phase 0 — Foundations

- [ ] Integral domains
- [ ] PID and UFD
- [ ] Polynomial rings
- [ ] Field extensions
- [ ] Galois theory

## Phase 1 — Quadratic Forms

- [ ] Representation \(p=x^2+ny^2\)
- [ ] Discriminants
- [ ] Legendre symbol
- [ ] Quadratic reciprocity
- [ ] Composition
- [ ] Class groups of forms

## Phase 2 — Rings of Integers

- [ ] Number fields
- [ ] Algebraic integers
- [ ] Embeddings
- [ ] Norm and trace
- [ ] Integral dependence
- [ ] Discriminants
- [ ] Integral bases
- [ ] Dedekind domains
- [ ] Ideal factorization
- [ ] Class group

## Phase 3 — Geometry of Numbers

- [ ] Lattices
- [ ] Lattice volume
- [ ] Minkowski theorem
- [ ] Minkowski bound
- [ ] Finiteness of the class group
- [ ] Unit group
- [ ] Dirichlet unit theorem

## Phase 4 — Ramification

- [ ] Prime decomposition
- [ ] Ramification index
- [ ] Residue degree
- [ ] Unramified extensions
- [ ] Total ramification
- [ ] Tame ramification
- [ ] Hilbert ramification theory
- [ ] Artin symbols

---

# 9. Long-term Extensions

Una vez completado el curso base, el proyecto podrá expandirse hacia:

```text
Algebraic Number Theory
        │
        ├── Local Fields
        │
        ├── Cyclotomic Fields
        │
        ├── Class Field Theory
        │
        ├── Elliptic Curves
        │
        ├── Modular Forms
        │
        └── Arithmetic Cryptography
```

Estas extensiones no forman parte inicialmente del curso base.
