# Contributing

Gracias por tu interés en contribuir a este proyecto.

El objetivo del repositorio es mantener material matemático riguroso, organizado, legible y útil para estudiantes de Teoría Algebraica de Números.

---

## Types of contributions

Son especialmente bienvenidas:

- correcciones de erratas;
- mejoras en demostraciones;
- ejemplos adicionales;
- ejercicios originales;
- soluciones alternativas;
- diagramas matemáticos;
- referencias bibliográficas;
- mejoras en la organización del curso.

---

## Mathematical standards

Toda contribución matemática debe procurar:

1. declarar claramente las hipótesis;
2. definir la notación antes de utilizarla;
3. distinguir definiciones, proposiciones, teoremas y corolarios;
4. justificar los pasos no triviales;
5. citar una referencia cuando corresponda;
6. evitar copiar material protegido por derechos de autor.

---

## File naming

Los nombres de archivos deberán escribirse preferentemente en inglés, en minúsculas y separados mediante guiones.

Ejemplos:

```text
algebraic-integers.md
norm-and-trace.md
integral-bases.md
dedekind-domains.md
minkowski-theorem.md
```

Evitar nombres como:

```text
Clase1.md
apuntes-nuevos.md
final.md
final-final.md
ahora-si-final.md
```

---

## Mathematical notation

Se utilizará notación estándar siempre que sea posible.

Ejemplos:

$$
\mathbb Z,\qquad
\mathbb Q,\qquad
\mathbb R,\qquad
\mathbb C.
$$

Para un cuerpo numérico $K$,

$$
\mathcal O_K
$$

denotará su anillo de enteros.

La norma y la traza se escribirán como:

$$
N_{K/\mathbb Q}(\alpha),
\qquad
\mathrm{Tr}_{K/\mathbb Q}(\alpha).
$$

Para expresiones cortas dentro del texto se utilizará notación matemática en línea. Por ejemplo:

```markdown
Sea $K/\mathbb Q$ una extensión finita.
```

Para expresiones destacadas se utilizarán bloques matemáticos:

```markdown
$$
[K:\mathbb Q]=n.
$$
```

---

## Exercises

Los ejercicios deberán incluir, cuando sea posible:

- tema;
- dificultad;
- prerrequisitos;
- fuente;
- enunciado.

Escala recomendada:

```text
★☆☆☆☆  Direct computation
★★☆☆☆  Basic application
★★★☆☆  Standard problem
★★★★☆  Difficult problem
★★★★★  Challenge
```

---

## Sources

Si un ejercicio o resultado proviene de un libro, artículo o curso, debe indicarse claramente la referencia.

No deben subirse copias completas de libros, artículos o material protegido sin permiso.

---

## Commit messages

Se recomienda utilizar mensajes descriptivos.

Ejemplos:

```text
docs: add algebraic integer definition

proof: add norm multiplicativity proof

exercise: add quadratic reciprocity problems

fix: correct discriminant computation

bib: add Neukirch reference

fig: add Minkowski lattice diagram
```

Evitar mensajes como:

```text
changes

update

stuff

final
```

El historial de Git también es documentación.

---

## Pull Requests

Toda contribución significativa podrá realizarse mediante una rama separada y un Pull Request.

Antes de solicitar la incorporación de cambios:

- revisa la notación;
- comprueba las referencias;
- revisa errores tipográficos;
- verifica las demostraciones;
- confirma que no se haya incluido material protegido.

---

## Philosophy

El objetivo no es simplemente acumular apuntes.

El repositorio busca construir un recurso educativo donde cada tema pueda entenderse dentro de una estructura matemática clara:

```text
definitions
    ↓
examples
    ↓
theorems
    ↓
proofs
    ↓
exercises
    ↓
connections
```
