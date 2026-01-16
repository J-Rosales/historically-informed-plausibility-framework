# CONSEQUENCE LATTICE FRAMEWORK

## Purpose and Scope

This document defines what a **consequence lattice** is, how it is constructed, and how it is used within a historically informed plausibility framework.

It does **not** enumerate specific lattices.
It does **not** prescribe which lattices an implementation must use.

Instead, it provides a **normative framework** by which authors may define, evaluate, and compose their own consequence lattices for a particular world, corpus, or historical model.

---

## Definition: Consequence Lattice

A **consequence lattice** is a structured analytical construct that constrains plausible outcomes by modeling how stress, change, or shock propagates through a specific systemic domain.

A lattice:

* Is **domain-bounded** (e.g., administration, legitimacy, demography).
* Evolves over time under pressure.
* Produces **downstream constraints** on what actions, behaviors, or outcomes remain plausible.
* Gates or modulates narrative developments independently of authorial intent.

A lattice is **not**:

* A narrative device.
* A plot driver.
* A moral judgment.
* A catalog of events.
* A world-specific rulebook.

---

## Role in Plausibility Analysis

Consequence lattices exist to answer questions of the form:

* *Why did this outcome become likely or inevitable?*
* *Why did apparently rational alternatives fail?*
* *Why did a system collapse slowly, suddenly, or not at all?*

They function as **structural brakes** on implausible developments rather than as generators of story.

---

## Required Properties of a Lattice

For a construct to qualify as a consequence lattice, it **must** satisfy all of the following:

1. **Distinct Domain**

   * It governs a clearly delimited systemic domain.
   * Its effects are not fully subsumable under another lattice.

2. **Stress Responsiveness**

   * It changes state in response to identifiable pressures or shocks.

3. **Directional Constraint**

   * Its state meaningfully restricts future plausible actions or outcomes.

4. **Non-Intentionality**

   * It operates regardless of whether actors recognize it.

5. **Temporal Extension**

   * It unfolds across time rather than instantaneously.

---

## Recommended Lattice Interface

Implementations should document each lattice using a consistent structure.
The following sections are recommended but not mandatory:

### 1. Scope

What systemic domain this lattice governs and what it explicitly excludes.

### 2. Trigger Variables

Events, conditions, or pressures that cause the lattice to change state.

### 3. State Levels

A small number of ordinal states (e.g., stable → strained → saturated), not fine-grained metrics.

### 4. Propagation Rules

How and why transitions between states occur.

### 5. Outputs

What narrative, institutional, or behavioral constraints follow from each state.

### 6. Failure Modes

What becomes impossible, unstable, or self-defeating when the lattice saturates.

### 7. Typical Evidence

What kinds of in-world documents, actions, or absences would indicate the lattice’s state.

### 8. Overlap Analysis

A justification for why this lattice is not reducible to existing ones.

---

## Lattices vs. Lenses

The framework distinguishes between **lattices** and **lenses**.

### Consequence Lattices

* Few in number.
* World-agnostic in form.
* Gate plausibility.
* Introduce distinct failure or stabilization modes.

### Lenses

* Numerous and optional.
* Contextual (cultural, species-based, technological).
* Modify how lattices manifest.
* Do **not** independently gate plausibility.

If a construct explains *how* a lattice expresses itself, rather than *whether* outcomes remain plausible, it should be treated as a **lens**, not a lattice.

---

## Orthogonality and Redundancy Test

A proposed lattice must pass the following test:

> If the effects of the proposed lattice can be fully reconstructed as a combination of existing lattices **without introducing a new downstream constraint**, it is redundant.

Redundant constructs should be:

* Reclassified as lenses, or
* Merged into an existing lattice.

---

## Diminishing Returns and Stopping Rule

The framework explicitly rejects exhaustive enumeration.

Implementations should stop adding lattices when:

* All major domains of systemic constraint are covered.
* Additional lattices refine description without changing conclusions.
* New lattices alter narrative texture but not plausibility boundaries.

As a rule of thumb:

* Most implementations converge between **5 and 9 lattices**.
* Beyond this, explanatory power increases slowly while complexity increases sharply.

---

## Composition and Interaction

Lattices may interact, but interactions should be treated as **informal coupling**, not as composite lattices.

Avoid:

* Defining lattices whose sole purpose is to mediate between other lattices.
* Encoding full causal graphs.

The goal is **constraint**, not simulation.

---

## Implementation Responsibility

This framework does not define any canonical lattice set.

Each world, corpus, or historical model **must**:

* Declare which lattices it uses.
* Justify their selection.
* Document any lenses applied.

Such declarations belong in the **implementation repository**, not in this framework.

---

## Guiding Principle

> A consequence lattice exists to prevent an author from accidentally making the world easier, simpler, or more coherent than it plausibly could be.

Anything that does not serve this function does not belong at the lattice level.
