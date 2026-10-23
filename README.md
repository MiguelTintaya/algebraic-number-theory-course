# Algebraic Number Theory

> A structured open course on Algebraic Number Theory: theory, proofs, examples, exercises and lecture notes.

Curso abierto y estructurado de **Teoría Algebraica de Números**, desarrollado inicialmente a partir del contenido del curso CM074 de la Escuela Profesional de Matemática de la Universidad Nacional de Ingeniería.

> **Nota:** Este repositorio es un proyecto educativo independiente y no constituye una publicación oficial de la Universidad Nacional de Ingeniería.

---

## About this project

El objetivo de este repositorio es construir progresivamente un curso riguroso y autocontenido de **Teoría Algebraica de Números**.

El proyecto reunirá:

- teoría y definiciones;
- teoremas y demostraciones;
- ejemplos desarrollados;
- ejercicios clasificados por dificultad;
- soluciones separadas;
- notas de clase;
- material en LaTeX;
- diagramas y recursos visuales;
- referencias bibliográficas;
- rutas de aprendizaje.

La intención es que el repositorio pueda ser utilizado tanto para seguir el curso como para estudiar el área de manera autodidacta.

---

## Prerequisites

Se recomienda familiaridad con:

- teoría de grupos;
- anillos e ideales;
- dominios integrales;
- espacios vectoriales;
- anillos de polinomios;
- extensiones de cuerpos;
- teoría básica de Galois.

Los prerrequisitos necesarios se desarrollarán también en la unidad `00-preliminaries`.

---

## Course structure

El curso está organizado en cinco grandes bloques.

### 0. Algebraic Preliminaries

- Factorización en dominios integrales
- Dominios de ideales principales
- Dominios de factorización única
- Anillos de polinomios
- Irreducibilidad
- Extensiones finitas de cuerpos
- Extensiones de Galois
- Correspondencia de Galois

### 1. Quadratic Forms

- El problema \(p=X^2+nY^2\)
- Clasificación modular
- Discriminantes
- Símbolo de Legendre
- Reciprocidad cuadrática
- Composición de formas
- Géneros
- Grupo de clases de formas cuadráticas

### 2. Rings of Integers

- Inmersiones
- Norma y traza
- Dependencia entera
- Dominios integralmente cerrados
- Cuerpos numéricos
- Anillos de enteros
- Discriminantes
- Bases integrales
- Dominios de Dedekind
- Factorización de ideales
- Grupo de clases

### 3. Geometry of Numbers

- Grupos abelianos finitamente generados
- Retículos
- Volúmenes de retículos
- Teorema de Minkowski
- Cotas de Minkowski
- Finitud del grupo de clases
- Grupo de unidades
- Teorema de unidades de Dirichlet

### 4. Ramification

- Índices de ramificación
- Grados residuales
- Extensiones no ramificadas
- Ramificación total
- Ramificación moderada
- Teoría de ramificación de Hilbert
- Símbolos de Artin
- Extensiones abelianas

---

## Learning path

La dependencia conceptual principal del curso será:

\[
\text{Álgebra}
\longrightarrow
\text{Extensiones de cuerpos}
\longrightarrow
\text{Teoría de Galois}
\]

\[
\downarrow
\]

\[
\text{Cuerpos numéricos}
\longrightarrow
\text{Enteros algebraicos}
\longrightarrow
\text{Norma, traza y discriminante}
\]

\[
\downarrow
\]

\[
\text{Dominios de Dedekind}
\longrightarrow
\text{Factorización de ideales}
\longrightarrow
\text{Grupo de clases}
\]

\[
\downarrow
\]

\[
\text{Geometría de números}
\longrightarrow
\text{Minkowski}
\longrightarrow
\text{Unidades}
\]

\[
\downarrow
\]

\[
\text{Ramificación}.
\]

Un mapa más detallado estará disponible en `ROADMAP.md`.

---

## Repository structure

```text
algebraic-number-theory-course/
│
├── course/          # teoría organizada por temas
├── exercises/       # listas de ejercicios
├── solutions/       # soluciones
├── lectures/        # material correspondiente a clases
├── notes/           # apuntes en LaTeX
├── figures/         # diagramas y figuras
├── references/      # bibliografía y guía de lectura
├── docs/            # documentación general
│
├── README.md
├── ROADMAP.md
├── SYLLABUS.md
├── CONTRIBUTING.md
└── CITATION.cff
```

---

## How to use this repository

Para estudiar una unidad:

1. Revisa sus prerrequisitos.
2. Lee las definiciones principales.
3. Estudia los ejemplos.
4. Reconstruye las demostraciones.
5. Resuelve los ejercicios sin consultar las soluciones.
6. Compara después con las soluciones propuestas.
7. Consulta las referencias para profundizar.

---

## Exercises

Los ejercicios estarán separados del contenido teórico.

Se utilizará aproximadamente la siguiente escala:

| Nivel | Dificultad |
|---|---|
| ★☆☆☆☆ | Definición o cálculo directo |
| ★★☆☆☆ | Aplicación básica |
| ★★★☆☆ | Problema estándar |
| ★★★★☆ | Problema difícil |
| ★★★★★ | Challenge |

También podrán clasificarse como:

`Theory` · `Proof` · `Computation` · `Exam` · `Challenge`

---

## References

Entre las referencias principales del curso se encuentran:

- David A. Cox — *Primes of the Form \(x^2+ny^2\)*
- Ireland & Rosen — *A Classical Introduction to Modern Number Theory*
- Serge Lang — *Algebraic Number Theory*
- Jürgen Neukirch — *Algebraic Number Theory*
- J.-P. Serre — *A Course in Arithmetic*
- J.-P. Serre — *Local Fields*
- Ian Stewart & David Tall — *Algebraic Number Theory*
- Joseph Silverman — *The Arithmetic of Elliptic Curves*

Una guía bibliográfica detallada estará disponible en `references/`.

---

## Project status

**Current version:** `v0.1.0-dev`

El repositorio se encuentra actualmente en desarrollo.

### Progress

- [ ] Algebraic Preliminaries
- [ ] Quadratic Forms
- [ ] Rings of Integers
- [ ] Geometry of Numbers
- [ ] Ramification
- [ ] Complete exercise sets
- [ ] Complete solutions
- [ ] LaTeX lecture notes
- [ ] GitHub Pages website

---

## Contributing

Las correcciones y contribuciones son bienvenidas, especialmente:

- erratas;
- mejoras de demostraciones;
- nuevos ejemplos;
- ejercicios;
- soluciones alternativas;
- referencias;
- diagramas matemáticos.

Las reglas de contribución estarán descritas en `CONTRIBUTING.md`.

---

## Author

**Miguel Angel Tintaya Condori**

Mathematics  
Universidad Nacional de Ingeniería

---

## License

El contenido original de este proyecto se distribuirá bajo una licencia abierta.

Los materiales pertenecientes a terceros conservan sus respectivos derechos de autor y no se redistribuyen mediante este repositorio.
