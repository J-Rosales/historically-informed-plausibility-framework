# NAMING CONVENTIONS FRAMEWORK
## Purpose

This document defines the naming conventions used to distinguish **framework-level guidance**, **authoritative policy**, **authoring scaffolds**, **examples**, and **world-specific content** within the historically informed plausibility ecosystem.

The goal is to prevent accidental canonization, hidden world-specific assumptions, and conceptual drift, while keeping the repository navigable and extensible.

---

## Core Principle

> **File names must communicate the role a document plays, not the content it happens to describe.**

If a reader can infer whether a document is:
- binding or illustrative,
- abstract or instantiating,
- reusable or world-specific,

*from the filename alone*, the convention is working.

---

## Primary Document Classes

### 1. FRAMEWORK documents

**Suffix:** `_FRAMEWORK.md`

**Role:**
- Define *how to construct* authoritative or policy documents.
- Specify structure, constraints, interfaces, and stopping rules.
- Do **not** enumerate world-specific rules, entities, or values.

**Characteristics:**
- Normative at the meta level.
- World-agnostic.
- Reusable across implementations.

**Examples:**
- `CONSEQUENCE_LATTICE_FRAMEWORK.md`
- `ANALYTICAL_LENS_FRAMEWORK.md`
- `BELIEF_REGIME_FRAMEWORK.md`
- `PERIODIZATION_FRAMEWORK.md`
- `CORPUS_AUTHORSHIP_FRAMEWORK.md`

**Rule:**  
If a document answers *“how should one define X?”*, it must be a FRAMEWORK.

---

### 2. CONSTITUTION documents

**Suffix:** `_CONSTITUTION.md`

**Role:**
- Establish binding principles and non-negotiable constraints.
- Define authority, scope, and interpretive precedence.

**Characteristics:**
- Normative and authoritative.
- Not world-specific, but not optional.
- Few in number.

**Examples:**
- `NARRATIVE_CONSTITUTION.md`

**Rule:**  
Constitutions define *what cannot be violated*, not how to construct content.

---

### 3. CONTRACT documents

**Suffix:** `_CONTRACT.md`

**Role:**
- Define explicit obligations, modes, or interfaces for agents or processes.
- Function as behavioral or operational agreements.

**Characteristics:**
- Binding within their scope.
- Procedural rather than descriptive.

**Examples:**
- `AGENT_MODE_CONTRACT.md`

---

### 4. TEMPLATE documents

**Suffix:** `_TEMPLATE.md`

**Role:**
- Provide structured scaffolding for authors to create valid documents.
- Mirror framework concepts in a fill-in form.

**Characteristics:**
- Non-authoritative.
- Incomplete by design.
- Intended to be copied and instantiated elsewhere.

**Examples:**
- `CONSEQUENCE_LATTICE_TEMPLATE.md`
- `ANALYTICAL_LENS_TEMPLATE.md`

**Rule:**  
Templates show *how to write one*, not *what exists*.

---

### 5. EXAMPLE documents

**Prefix or directory:** `EXAMPLE_` or `examples/`

**Role:**
- Demonstrate correct usage of frameworks and templates.
- Provide concrete, readable instantiations.

**Characteristics:**
- Explicitly non-canonical.
- May be simplified or artificial.
- Should never be treated as defaults.

**Examples:**
- `EXAMPLE_CONSEQUENCE_LATTICE_ADMINISTRATIVE_CAPACITY.md`
- `EXAMPLE_ANALYTICAL_LENS_CULTURAL_COMPLIANCE_PRESSURE.md`

**Rule:**  
Examples explain by demonstration, not by authority.

---

### 6. WORLD / IMPLEMENTATION documents

**No framework suffix; world-scoped directories**

**Role:**
- Enumerate actual lattices, lenses, beliefs, periods, institutions, and corpus material.
- Instantiate frameworks for a specific setting.

**Characteristics:**
- Canonical *within that world only*.
- Historically or fictionally contingent.
- Not reusable without reinterpretation.

**Examples (world-side):**
- `CONSEQUENCE_LATTICES_<WORLD>.md`
- `PERIODS_MAJOR.md`
- `beliefs/`
- `corpus/`

**Rule:**  
If a document answers *“what exists in this world?”*, it belongs here.

---

## Lattices vs. Lenses (Naming Implication)

- **Lattices** are structural, gating constructs → defined via FRAMEWORK + TEMPLATE.
- **Lenses** are interpretive modifiers → defined via FRAMEWORK + TEMPLATE.
- Neither should be enumerated in the framework repository as a canonical list.

Concrete selections belong only to implementations.

---

## Anti-Patterns (Explicitly Prohibited)

- Naming a framework document after a specific world.
- Enumerating canonical lists inside a `_FRAMEWORK.md`.
- Using `_MODEL.md` or `_GUIDE.md` where `_FRAMEWORK.md` is intended.
- Allowing examples to live outside an `examples/` namespace.
- Letting templates accumulate world-specific assumptions.

---

## Summary Rule (Enforceable)

> **If a document defines “what exists,” it does not belong in the framework.  
> If a document defines “how to define what exists,” it must be named as a framework.**

This convention is mandatory for long-term coherence and reuse.

---
