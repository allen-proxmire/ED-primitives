# Event Density — Constitution

**Version 1.0**
**Status: ratified, primitives frozen.**

---

## 1. What ED Is

Event Density (ED) is an **ontology**. It describes the world as a structured
substrate of discrete commitment events organised by relational primitives,
participation amplitudes, and gradient-driven dynamics on those events.

ED is *not* a physical theory in the textbook sense. It does not, by itself,
predict particle masses, coupling constants, or numerical observables. Instead,
ED specifies the **structural slots** that any physical theory built on top of
it must fill, and the **forms** that any consistent dynamics over the
substrate must take.

The ED-primitives repository (this repository) is the **constitution-level
layer** of the framework. It contains the ontology, the primitives, the
philosophical grounding, and the methodological commitments that govern every
downstream construction. All physics-sector work — quantum mechanics, QFT,
gravitational extensions, kernel architecture, retrodictions, simulations —
lives in the companion `event-density` repository and is built on top of, but
not part of, the constitution.

---

## 2. The Thirteen Primitives

The primitives are the irreducible vocabulary of ED. They are frozen at v1.0
and may only be revised through a numbered amendment to this constitution.

| # | Name |
|---|---|
| 01 | Micro-event |
| 02 | Chain |
| 03 | Participation |
| 04 | Participation bandwidth |
| 05 | Event density |
| 06 | ED gradient |
| 07 | Channel |
| 08 | Multiplicity |
| 09 | Tension / polarity |
| 10 | Individuation |
| 11 | Commitment |
| 12 | Thickening |
| 13 | Relational timing |

Full memos for each primitive live in `primitives/`.

---

## 3. The Form-FORCED / Value-INHERITED Commitment

ED makes one disciplined methodological commitment that runs through every
layer:

> **Forms are FORCED. Values are INHERITED.**

- A claim that a structural object (an equation, a kernel class, a symmetry,
  a classification) is **FORCED** means it follows from the primitives plus
  the constitution and admits no alternative within the ontology.
- A claim that a numerical content (a mass, a coupling, a magnitude, a count)
  is **INHERITED** means ED does not produce it; it is supplied empirically
  by the Dimensional Atlas (see `foundations/dimensional_atlas.md`).

This rule is not a hedge. It is the constitutional boundary between what ED
is responsible for and what it explicitly is not. Violating it — claiming
that the primitives produce a numerical constant, or claiming that an
empirical input forces an equation form — breaks the ontology.

See `foundations/form_forced_value_inherited.md`.

---

## 4. Structural Ceiling — Explicit Non-Claims

ED does not claim, and the constitution explicitly forbids claiming, any of
the following:

- Einstein field equations from the primitives
- The Standard Model gauge group `SU(3) × SU(2) × U(1)`
- The number of fermion generations
- The Higgs mechanism or the electroweak scale
- The magnitude of the cosmological constant Λ
- A Newtonian limit derived from primitives alone
- The fine-structure constant α or any other dimensionless coupling
- Any numerical prediction of any observable

Items in this list may appear as *form-level* structural results elsewhere
in the framework (for example, a kernel integral that has the form of a
Λ-like term, with magnitude inherited). They never appear as primitive-level
numerical predictions.

See `foundations/structural_ceiling.md`.

---

## 5. Relationship to the `event-density` Repository

ED splits cleanly into two repositories:

- **`ed-primitives`** (this repo) — constitution, primitives, ontology,
  philosophical foundations, interpretive positioning. Slow-changing,
  amendment-governed.
- **`event-density`** — physics-sector work built on the constitution: the
  Phase-1/2/3 arcs, Arc N kernel work, FORCED theorems with proofs,
  retrodictions, simulations, papers, diagrams. Fast-changing, normal
  research velocity.

A document belongs in this repository if and only if it is either (a) one
of the thirteen primitives, (b) ontology-level architecture or
interpretation, (c) foundational philosophical grounding, or (d) a
constitutional governance document (this file, the changelog, the license).
Everything else lives in `event-density`.

---

## 6. Versioning Policy

The primitives and constitutional commitments change rarely and only through
formal amendment.

- **Major version (v1, v2, …)** — change to the primitive set, to the
  form-FORCED / value-INHERITED commitment, or to the structural ceiling.
  Requires a numbered amendment recorded in `CHANGELOG.md` and a stated
  rationale.
- **Minor version (v1.1, v1.2, …)** — clarifications, glossary additions,
  new foundational memos that do not alter the primitives or the
  commitments.
- **Patch (v1.0.1, …)** — typographical or expository corrections only.

The current version (v1.0) freezes primitives 01–13 as listed in §2.

---

## 7. How to Read This Constitution

A reader entering ED for the first time should proceed in this order:

1. **`README.md`** — orientation and repository map.
2. **This document** — what ED is and what it commits to.
3. **`primitives/`** — the thirteen primitive memos, in numerical order.
4. **`foundations/`** — the philosophical grounding (why event-based, why
   geometry-first, why gradients, etc.) and the three constitutional memos
   (`dimensional_atlas.md`, `form_forced_value_inherited.md`,
   `structural_ceiling.md`).
5. **`architecture/`** — how the primitives compose, with `derived/`
   covering higher-order architectural concepts.
6. **`interpretations/`** — ED's ontological positioning relative to
   neighbouring frameworks.

A reader interested in the physics-sector consequences of the ontology
should then move to the `event-density` repository.

---

*This document is the constitutional charter of the ED ontology. It is
binding on every document in this repository.*
