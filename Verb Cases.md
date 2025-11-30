
---
## I. Overview

Verbal cases mark how **upa-vr̥ttis** (non-finite verb forms) depend on head-nouns. This page specifies the morphological inventory and usage patterns. For the geometric and philosophical foundations of the case system, see [[Case System]].

Verbal cases are **field operators** that:
1. **Inverse cases (K⁻¹):** externalize a specific internal role of the vr̥tti as the head-noun
2. **Propositive (PROP):** link the entire vr̥tti-field to an event/fact noun

All verbal cases are marked on participial verb forms and create dependent clause structures as specified in [[Clause Structure]].

---

## II. Inverse Verbal Cases (K⁻¹)

Inverse cases are **projection operators** that parallel the five core nominal cases (C1, C2, ABL, DAT, SUB). They externalize a specific internal participant while preserving all other arguments.

### A. Inventory

#### 1. C1⁻¹ (Primary Inverse)
- Promotes the vr̥tti's **structural anchor** to head position
- Most common inverse case; creates typical relative clauses

**Geometric essence:** *Projects the primary pole out of the vr̥tti-field*

**Usage:**
```
[ Arg₂(C2) Arg₃(ABL/DAT/SUB) V-PART-C1⁻¹ ] Arg₁(matrix-case)
```

**Example:**
```
[ speaker(C2) praise-PFV-C1⁻¹ ] listener(C1)
"the listener [who was praised by the speaker]"
```

#### 2. C2⁻¹ (Secondary Inverse)
- Promotes the **secondary pole** of dyadic vr̥ttis
- Only applicable to verbs with dyadic valency

**Geometric essence:** *Projects the secondary pole out of the vr̥tti-field*

**Usage:**
```
[ Arg₁(C1) Arg₃(ABL/DAT/SUB) V-PART-C2⁻¹ ] Arg₂(matrix-case)
```

**Example:**
```
[ speaker(C1) praise-PFV-C2⁻¹ ] listener(C1)
"the listener [whom the speaker praised]"
```

#### 3. ABL⁻¹ (Ablative Inverse)
- Promotes the **source/origin** participant
- Common for instrument relativization, causal clauses

**Geometric essence:** *Projects the source-vector out of the vr̥tti-field*

**Usage:**
```
[ Arg₁(C1) Arg₂(C2) V-PART-ABL⁻¹ ] source-noun(matrix-case)
```

**Example:**
```
[ warrior(C1) enemy(C2) strike-PFV-ABL⁻¹ ] sword(C1)
"the sword [with which the warrior struck the enemy]"
```

#### 4. DAT⁻¹ (Dative Inverse)
- Promotes the **goal/recipient** participant
- Common for beneficiary and destination relativization

**Geometric essence:** *Projects the goal-vector out of the vr̥tti-field*

**Usage:**
```
[ Arg₁(C1) Arg₂(C2) V-PART-DAT⁻¹ ] goal-noun(matrix-case)
```

**Example:**
```
[ sage(C1) wisdom(C2) teach-PFV-DAT⁻¹ ] student(C1)
"the student [to whom the sage taught wisdom]"
```

#### 5. SUB⁻¹ (Substrative Inverse)
- Promotes the **substrate/ambient** participant
- Primary mechanism for adverbial clauses (time, place, manner, condition)

**Geometric essence:** *Projects the substrate field out of the vr̥tti-field*

**Usage:**
```
[ Arg₁(C1) Arg₂(C2) V-PART-SUB⁻¹ ] abstract-noun(matrix-case)
```

**Example:**
```
[ Krishna(C1) arrive-PFV-SUB⁻¹ ] time(SUB)
"at the time [when Krishna arrived]"
```

### B. Inverse Case Selection

The choice of inverse case (K⁻¹) depends on **which role** the head-noun plays internally within the vr̥tti:
- Head-noun = internal C1 role → use C1⁻¹
- Head-noun = internal C2 role → use C2⁻¹
- Head-noun = internal ABL role → use ABL⁻¹
- Head-noun = internal DAT role → use DAT⁻¹
- Head-noun = internal SUB role → use SUB⁻¹

The head-noun's **matrix case** (the case it receives from the main clause) is independent and determined by the main verb.

### C. General Template

```
[ ... internal-args(nominal-cases) ... V-PART-K⁻¹ ] head-noun(matrix-case)
```

**Key properties:**
- All internal arguments retain their nominal cases
- K⁻¹ marks which role is externalized
- Head-noun receives only its matrix case (no double-marking)
- The entire unit behaves as a compound modifier

---

## III. Propositive (PROP)

**PROP** is fundamentally different from inverse cases. It does not extract a single role but links the **entire vr̥tti** to the head-noun.

### A. Function

PROP is a **norm operator** that enables the vr̥tti to depend on a head-noun, creating a bounded entity (proposition-as-totality) that can then become an argument of the matrix verb.

**Geometric essence:** *Collapses the entire vr̥tti-field into a scalar-like entity by binding it to a reifying noun; the noun (not the field itself) then occupies a coordinate in the matrix field*

### B. Complement Clause Formation

PROP constructs complement clauses headed by nouns that lexicalize events, facts, or propositional content:
- _fact_, _event_, _content_, _report_, _plan_, _intention_, _belief_, _rumor_, _knowledge_, etc.

All internal arguments retain their nominal cases—nothing is externalized.

### C. Usage Template

```
[ ... all-args(nominal-cases) ... V-PART-PROP ] event-noun(matrix-case) ... V-FIN
```

**Example:**
```
[sage(C1) secret(C2) reveal-PFV-PROP] report(C2) disciple(C1) trust-FIN
"the disciple trusts the report [that the sage revealed the secret]"
```

### D. PROP vs. Inverse Cases

| Feature                    | Inverse Cases (K⁻¹)           | PROP                      |
| -------------------------- | ----------------------------- | ------------------------- |
| **Externalizes**           | One specific role             | Nothing (whole vr̥tti)    |
| **Head-noun type**         | Lexical or abstract           | Event/fact/content noun   |
| **Internal args**          | All present (one promoted)    | All present (none promoted)|
| **Clause type**            | Relative, adverbial           | Complement                |
| **Geometric interpretation**| Vector projection            | Norm operator             |

---

## IV. Verbal Case and Clause Type

| Verbal Case | Head-Noun Type          | Clause Function    | Example                                 |
| ----------- | ----------------------- | ------------------ | --------------------------------------- |
| **C1⁻¹**    | Lexical noun            | Relative           | "the one who..."                        |
| **C2⁻¹**    | Lexical noun            | Relative           | "the one whom..."                       |
| **ABL⁻¹**   | Lexical/abstract        | Relative/adverbial | "the means by which..." / "because..."  |
| **DAT⁻¹**   | Lexical/abstract        | Relative/adverbial | "the one to whom..." / "in order to..." |
| **SUB⁻¹**   | Lexical/abstract        | Relative/Adverbial | "when...", "where...", "how..."         |
| **PROP**    | Event/fact/content noun | Complement         | "the fact that..."                      |

**Note:** The distinction between relative and adverbial for ABL⁻¹/DAT⁻¹/SUB⁻¹ depends on whether the head-noun is lexical (concrete participant) or abstract (circumstantial concept).

---

## V. Summary Table

| Case      | Type        | Externalizes               | Typical Head-Noun         |
| --------- | ----------- | -------------------------- | ------------------------- |
| **C1⁻¹**  | Inverse     | Primary pole participant   | Lexical (pivot)           |
| **C2⁻¹**  | Inverse     | Secondary pole participant | Lexical (co-core)         |
| **ABL⁻¹** | Inverse     | Source/origin participant  | Lexical or abstract       |
| **DAT⁻¹** | Inverse     | Goal/recipient participant | Lexical or abstract       |
| **SUB⁻¹** | Inverse     | Substrate participant      | Abstract (circumstance)   |
| **PROP**  | Propositive | Nothing (whole vr̥tti)      | Event/fact/content        |

