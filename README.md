# ED-primitives
**The Axiomatic Core of Event Density**

This repository is the constitutional core of Event Density (ED).
All physics, simulations, retrodictions, and execution-level work
live in the separate `event-density` repository.

This repo contains only the **minimal, stable ontology** of the framework:
the primitives, their internal architecture, and the conceptual
foundations that justify them. It is intentionally **small**,
**slow-changing**, and **physics-free**.

---

## Purpose

The goal of `ED-primitives` is to:

- **Define the primitives** of Event Density (ED-01 through ED-13).
- **Describe how they relate** and compose into higher structures.
- **Clarify the conceptual and philosophical foundations** of the ontology.
- **Provide a stable constitutional reference** that other ED work can
  build on without being entangled with ongoing physics development.

If you want to understand *what ED is* at the level of ontology and
structure, you are in the right place. If you want equations,
experiments, or platform-specific predictions, see the `event-density`
repository.

---

## Repository structure

```text
ED-primitives/
├── README.md                ← this file
├── CONSTITUTION.md          ← ratified constitutional charter
├── CHANGELOG.md             ← versioned amendment log
├── LICENSE
├── .gitignore
│
├── primitives/              ← the 13 primitives (ED-01 through ED-13)
│   ├── 01_micro_event.md
│   ├── 02_chain.md
│   ├── 03_participation.md
│   ├── 04_participation_bandwidth.md
│   ├── 05_event_density.md
│   ├── 06_ed_gradient.md
│   ├── 07_channel.md
│   ├── 08_multiplicity.md
│   ├── 09_tension_polarity.md
│   ├── 10_individuation.md
│   ├── 11_commitment.md
│   ├── 12_thickening.md
│   ├── 13_relational_timing.md
│   └── README.md
│
├── architecture/            ← ontology-level architecture
│   ├── architecture_overview.md
│   ├── architecture_faq.md
│   ├── architecture_flowcharts.md
│   ├── architecture_glossary.md
│   ├── architecture_minimal_examples.md
│   ├── primitive_interactions.md
│   ├── README.md
│   └── derived/             ← higher-order architectural concepts
│       ├── gradient_sign_flip.md
│       ├── motif_formation.md
│       └── saddle_boundary_horizon.md
│
├── foundations/             ← philosophical grounding + constitutional memos
│   ├── philosophical_basis.md
│   ├── philosophical_background.md
│   ├── conceptual_background.md
│   ├── why_event_based.md
│   ├── why_geometry_first.md
│   ├── why_gradients.md
│   ├── why_multiplicity.md
│   ├── why_primitives.md
│   ├── why_relational_timing.md
│   ├── dimensional_atlas.md
│   ├── form_forced_value_inherited.md
│   ├── structural_ceiling.md
│   ├── forced_theorems_inventory.md
│   └── README.md
│
└── interpretations/         ← ontology-level interpretive memos
    ├── ED-interpretation.md
    ├── ED_as_substrate_theory.md
    ├── ED_vs_process.md
    ├── ED_vs_relational.md
    ├── ED_vs_other_quantum_foundations.md
    ├── conceptual_minimalism.md
    ├── event_based_ontology.md
    ├── geometry_first.md
    ├── how_to_read_ED.md
    ├── interpretive_principles.md
    ├── structural_realism_in_ED.md
    ├── why_ED_is_not_field_theory.md
    ├── why_ED_is_not_wavefunction_theory.md
    └── README.md
```

---

## The four-folder structure

### 1. `primitives/`
The 13 ED primitives (ED-01 through ED-13). These are the axioms of the
framework. They change rarely, and only through a numbered amendment
recorded in `CHANGELOG.md`.

### 2. `architecture/`
Ontology-level architecture: how the primitives relate to one another,
their interaction patterns, and the structural scaffolding that binds
them. The `derived/` subfolder houses higher-order architectural
concepts that follow from primitive composition (gradient sign flip,
motif formation, saddle/boundary/horizon).

### 3. `foundations/`
Philosophical grounding, motivations, and the conceptual background
that led to the primitive set. Also home to the constitutional memos:
the Dimensional Atlas, the form-FORCED / value-INHERITED commitment,
the structural ceiling, and the FORCED-theorems inventory.

### 4. `interpretations/`
Ontology-level interpretive positioning of ED, including comparison
to neighbouring frameworks. No physics equations; only conceptual
positioning.

---

## Relationship to the `event-density` repository

ED splits cleanly into two repositories:

- **`ed-primitives`** (this repo) — constitution, primitives, ontology,
  philosophical foundations, interpretive positioning. Slow-changing,
  amendment-governed.
- **`event-density`** — physics-sector work built on the constitution:
  Phase-1/2/3 arcs, Arc N kernel work, FORCED theorems with proofs,
  retrodictions, simulations, papers, diagrams. Fast-changing, normal
  research velocity.

A document belongs in *this* repository if and only if it is one of:
the thirteen primitives, ontology-level architecture or interpretation,
foundational philosophical grounding, or a constitutional governance
document. Everything else lives in `event-density`.

---

## What this repo does NOT contain

- No PDEs
- No quantum mechanics or QFT derivations
- No general relativity
- No platform-bridge derivations
- No retrodictions or predictions
- No experiments
- No code
- No numerical data

---

## How to read this repo

1. **`CONSTITUTION.md`** — what ED is and what it commits to.
2. **`primitives/`** — the 13 primitive memos in numerical order.
3. **`foundations/`** — philosophical grounding and constitutional memos.
4. **`architecture/`** — how the primitives compose; `derived/` for
   higher-order concepts.
5. **`interpretations/`** — ED's positioning relative to other ontologies.

This repo is intentionally minimal. It is the seed from which the full
ED theory grows.
