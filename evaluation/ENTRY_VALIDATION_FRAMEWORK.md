# ENTRY_VALIDATION_FRAMEWORK

## Purpose and Scope

This document defines the **entry validation stage** of plausibility evaluation.

Entry validation determines whether a claim is:
- analytically well-formed,
- category-valid within the framework,
- and admissible given the **baseline world constraints** of the narrative universe.

Claims that fail entry validation are rejected **prior to** lattice analysis, lens application, or corpus consultation.

Entry validation is a **hard gate**, not a gradient assessment.

---

## I. Governing Principle

> **A claim must be structurally admissible before it can be plausibly evaluated.**

No amount of narrative justification, evidentiary support, or thematic coherence can salvage a claim that violates baseline constraints or category rules.

---

## II. Inputs Required for Entry Validation

Entry validation requires only:

1. The **claim** to be evaluated  
2. The applicable **Baseline World Constraints**  
   (as defined by `BASELINE_WORLD_CONSTRAINTS_FRAMEWORK.md` and instantiated via `WORLD_CONSTRAINTS_TEMPLATE.md`)

No consequence lattices, belief regimes, or corpus documents are consulted at this stage.

---

## III. Validation Sequence (Mandatory)

Entry validation proceeds in the following order.  
Failure at any step terminates evaluation.

---

### III.1 Claim Coherence Check

Confirm that the claim:

- asserts a change, occurrence, or state transition,
- is intelligible without narrative embellishment,
- and does not collapse multiple incompatible assertions into a single sentence.

Claims that are purely descriptive, thematic, or rhetorical are invalid.

---

### III.2 Canonical Entry Classification

Determine whether the claim can be instantiated as one or more **Historical Change Entry types** defined in `HISTORICAL_CHANGE_ENTRY_FRAMEWORK.md`.

Valid types:
- Event
- Process
- Structural Transformation
- Condition (derived)
- Crisis (derived)

If the claim cannot be classified, it is invalid.

---

### III.3 Baseline World Constraint Compatibility

Evaluate whether the claim **depends on mechanisms permitted** by the baseline world constraints.

This step asks:

- Does the claim require a kind of physical reach, energy manipulation, ontological access, infrastructure, epistemic capacity, or agency that has *not* been declared possible?
- Does the claim contradict any **explicit exclusions** defined in the world constraints?

If yes, the claim is **category-invalid**.

No mitigation or revision within the existing world is permitted at this stage.

---

### III.4 Undeclared Capability Check

If the claim relies on a capability that is:

- extraordinary,
- systemic,
- or outcome-determinative,

and that capability is **not explicitly declared** in the baseline constraints, the claim is invalid.

Undeclared capability defaults to **non-existence**, not ambiguity.

---

### III.5 Scope and Scale Consistency

Confirm that the claim’s scope and scale:

- do not exceed what the baseline constraints allow in principle,
- do not imply universal or costless access to permitted mechanisms,
- and do not collapse local possibility into global capability.

Claims that implicitly universalize rare or localized mechanisms are invalid.

---

## IV. Special Case: Derived Entries

If the claim is instantiated as a **Condition** or **Crisis**, confirm that:

- the claim references underlying Events or Processes,
- it does not introduce new baseline capabilities,
- and it does not function as a surrogate for undeclared structure.

Derived entries cannot be used to bypass baseline constraints.

---

## V. Outcomes of Entry Validation

Entry validation produces one of the following outcomes:

### V.1 Valid

The claim:
- is category-valid,
- is compatible with baseline world constraints,
- and may proceed to plausibility evaluation.

---

### V.2 Invalid (Category Error)

The claim:
- cannot be instantiated as a historical change entry, or
- collapses incompatible analytical categories.

Evaluation terminates.

---

### V.3 Invalid (Constraint Violation)

The claim:
- requires undeclared or excluded mechanisms, or
- contradicts baseline world constraints.

Evaluation terminates.

Revision is possible **only** by redefining baseline world constraints.

---

## VI. What Entry Validation Does Not Do

Entry validation does **not**:
- assess likelihood,
- weigh evidence,
- consider actor motivation,
- apply consequence lattices,
- or judge narrative quality.

Those belong to subsequent stages.

---

## VII. Illustrative Boundary Case (Non-Normative)

> “The king went to another planet on foot.”

- Cannot be classified as a valid historical change entry.
- Requires undeclared physical reach and energetic capacity.
- Violates baseline world constraints in all terrestrial settings.

Rejected at entry validation.

---

## Guiding Principle

> **If a claim requires redefining the world to be possible, it is invalid within the world as defined.**

Entry validation enforces the boundary between:
- declaring a world, and
- telling a story within it.

No story may cross that boundary unnoticed.
