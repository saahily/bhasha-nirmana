
---
## I. Overview

Verbal cases mark how **upa-vr̥ttis** (non-finite verb forms) depend on head-nouns. This page specifies the morphological inventory and geometric definitions. For clause formation patterns, see [[Clause Structure]].

Verbal cases are **field operators** that fall into two geometrically distinct types:
1. **Inverse cases (K⁻¹):** projection operators that externalize a specific internal role
2. **Propositive (PROP):** norm operator that links the entire vr̥tti-field to a head-noun

---

## II. Inverse Verbal Cases (K⁻¹)

### A. Geometric Definition

Inverse cases are **projection operators** that parallel the five core nominal cases (C1, C2, ABL, DAT, SUB). They externalize a specific internal participant while preserving all other arguments.

```
vr̥tti-field: {role₁(C1), role₂(C2), role₃(ABL), role₄(DAT), role₅(SUB)}
           ↓ apply K⁻¹ (K = one of {C1, C2, ABL, DAT, SUB})
externalized: roleₖ becomes head-noun
internal: {all other roles remain with their cases}
```

_In linear algebra, a projection operator extracts one component of a vector. K⁻¹ projects one role out of the vr̥tti's multi-dimensional field._

### B. Inventory

| Case | Projects | Geometric Essence |
|------|----------|-------------------|
| **C1⁻¹** | Primary pole | Structural anchor of the vr̥tti |
| **C2⁻¹** | Secondary pole | Dyadic complement (requires dyadic verb) |
| **ABL⁻¹** | Source-vector | Origin, instrument, or cause participant |
| **DAT⁻¹** | Goal-vector | Recipient, beneficiary, or destination |
| **SUB⁻¹** | Substrate | Locative, temporal, or manner participant |

### C. Selection Principle

The choice of K⁻¹ depends on **which role** the head-noun plays internally:
- Head-noun = internal C1 role → C1⁻¹
- Head-noun = internal C2 role → C2⁻¹
- Head-noun = internal ABL role → ABL⁻¹
- Head-noun = internal DAT role → DAT⁻¹
- Head-noun = internal SUB role → SUB⁻¹

The head-noun's **matrix case** is independent—determined by its role in the main clause.

### D. Key Properties

- All internal arguments retain their nominal cases
- K⁻¹ marks which role is externalized
- Head-noun receives only its matrix case (no double-marking)
- The head-noun *is* the extracted participant

---

## III. Propositive (PROP)

### A. Geometric Definition

PROP is a **norm operator** that collapses the entire vr̥tti-field into a scalar-like entity, binding it to a head-noun.

```
vr̥tti-field: {role₁(C1), role₂(C2), ...}
           ↓ apply PROP
bounded entity: [whole vr̥tti] linked to head-noun
           ↓ nominal case on head-noun
matrix position: determined by head-noun's case
```

_If inverse cases are vector projections, PROP computes the norm—collapsing the field to a scalar that then occupies a coordinate in the matrix field._

### B. Key Properties

- Nothing is externalized; the whole vr̥tti is linked
- All internal arguments retain their nominal cases
- The head-noun *contains* the entire event (not a participant)
- The **nominal case** on the head-noun determines its geometric position in the matrix

### C. Head-Noun Classes

PROP attaches to head-nouns denoting events, facts, states, or circumstances:

| Head-Noun Class | Nominal Case | Function |
|-----------------|--------------|----------|
| Event/fact/content (*fact*, *report*, *belief*) | C1, C2 | Argument of matrix verb |
| Source circumstance (*cause*, *reason*, *concession*) | ABL | Adjunct (causal/contrastive) |
| Substrate circumstance (*time*, *place*, *manner*, *condition*) | SUB | Adjunct (circumstantial) |
| Goal circumstance (*purpose*, *goal*) | DAT | Adjunct (telic) |

---

## IV. Comparison

| Feature | K⁻¹ | PROP |
|---------|-----|------|
| **Operation** | Projection | Norm |
| **Externalizes** | One specific role | Nothing (whole vr̥tti) |
| **Head-noun identity** | *Is* the extracted participant | *Contains* the entire event |
| **What determines flavor** | Which role K is extracted | Head-noun semantics + nominal case |

---

## V. Summary

| Case | Type | Operation | What Head-Noun Represents |
|------|------|-----------|---------------------------|
| **C1⁻¹** | Inverse | Project primary pole | The C1 participant |
| **C2⁻¹** | Inverse | Project secondary pole | The C2 participant |
| **ABL⁻¹** | Inverse | Project source-vector | The ABL participant |
| **DAT⁻¹** | Inverse | Project goal-vector | The DAT participant |
| **SUB⁻¹** | Inverse | Project substrate | The SUB participant |
| **PROP** | Propositive | Collapse entire field | The event-as-totality |
