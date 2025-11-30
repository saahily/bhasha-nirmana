
---
## I. Overview

This grammar treats all linguistic structure as arising from **vr̥ttis**—modulations of semantic fields (see [[Vr̥tti Ontology]] for philosophical foundations). A clause consists of:
- a single **finite vr̥tti** (the clause‑head), and
- zero or more **dependent vr̥ttis** modifying nouns.

All dependent clauses are structurally uniform. There are no special syntactic types beyond what follows from vr̥tti relations.

---

## II. Architectural Principles

### 1. Single Clause Head (Vr̥tti Monism)

- The **finite verb (V‑FIN)** is the **sole head** of its clause—the mahā‑vr̥tti (great modulation).
- V‑FIN is **obligatorily final** within its clause.
- All other elements depend directly or indirectly on this single pulse.

### 2. Unified Dependent Clause Shell

All dependent clauses share one structural shell:

```
[ (internal dependents…) vr̥tti-PART-VERBAL-CASE … ] head-noun(NOMINAL-CASE)
```

Where:
- the **vr̥tti** is a non‑finite derivation (upa-vr̥tti),
- **VERBAL-CASE** is either an **inverse verbal case** (C1⁻¹, C2⁻¹, ABL⁻¹, DAT⁻¹, SUB⁻¹) or **PROP**,
- the **head-noun** carries only the nominal case assigned by its role in the main clause,
- the unit behaves as a **compound** with the head-noun final.

**Key principle**: All upa-vr̥ttis modify **nouns** (lexical or abstract). There is no verb‑to‑verb subordination.

Functional differentiation is determined entirely by the head-noun:
- **Relative**: lexical head-noun + inverse verbal case.
- **Adverbial**: abstract head-noun + inverse verbal case.
- **Complement**: event/fact/content head-noun + PROP.

### 3. Case as Dependency Marker

Case is a unified system encoding geometric topology (see [[Case System]]):
- **Nominal cases** mark how nouns depend on vr̥tti-heads or other nouns.
- **Verbal cases** mark how upa-vr̥ttis depend on head-nouns.
- Inverse cases (K⁻¹) externalize specific internal roles; PROP links the entire vr̥tti.
- GEN⁻¹ is the sole nominal inverse (possessor extraction only).

### 4. Valency Preservation

**No gaps, deletions, or traces.** All roles present in the vr̥tti-field manifest syntactically:
- Externalization (via K⁻¹) **relocates** arguments but never deletes them.
- PROP embeds the entire vr̥tti with all its arguments intact.
- The grammar is informationally lossless.

### 5. Pure Dependency Structure

- No phrase-structure categories or projections (NP, VP, etc.).
- All relations are head–dependent.
- Linear order is determined by head-finality constraints, not hierarchical constituency.

For ontological foundations, see [[Vr̥tti Ontology]].

---

## III. Clause Inventory

### A. Main Clause

```
noun(case) … V-FIN
```
- V‑FIN is clause-final and the dependency root.

### B. Dependent Clause 

```
[ (internal dependents…) vr̥tti-PART-VERBAL-CASE … ] head-noun(NOMINAL-CASE)
```
- **VERBAL-CASE** = inverse verbal case (for relatives/adverbials) or PROP (for complements).
- Head-noun is final within the unit.
- The whole unit behaves as a morphological compound.

---

## IV. Dependent Clause Functions

All dependent clauses share the structural shell described in §II.2. Functional distinctions arise from the semantics of the head-noun and the choice of verbal case.

### 1. Relative Clauses (Lexical Head-Nouns)

Given vr̥tti valency:
```
V( … ArgX(role K) … )
```

To externalize **ArgX** as the head-noun:
1. Derive a participial vr̥tti.    
2. Apply the inverse verbal case **K⁻¹** to mark extraction of role K.
3. Retain all other arguments with their nominal cases.
4. Place the vr̥tti immediately before the head-noun.
5. Head-noun receives only the nominal case assigned by the main clause.

### Template
```
[ … Arg_i(case_i) … V-PART-K⁻¹ … ] head-noun(matrix-case)
```

### Example
```
[Rama(case-C1) kill-PFV-C2⁻¹] Ravana(matrix-case-C1)
```

### 2. Adverbial Clauses (Abstract Head-Nouns)

Abstract head-nouns include **time**, **reason**, **condition**, **manner**, **purpose**, etc. They behave identically to lexical heads but denote circumstantial abstractions.

If an abstract noun A participates in the vr̥tti with role K:
1. Derive the participial vr̥tti.    
2. Apply **K⁻¹**.
3. Place the vr̥tti before A.
4. A receives the nominal case required by its role in the main clause.

### Template
```
[ … V-PART-K⁻¹ … ] abstract-noun(case) … V-FIN
```

### Example
```
[Krishna(case-C1) arrive-PFV-SUB⁻¹] time(case-SUB) Arjuna(case-C1) bowed-FIN
```

The vr̥tti modifies **time**; **time** modifies the main vr̥tti.

### 3. Complement Clauses (Event/Factual Head-Nouns)

Complement head-nouns lexicalize whole events, facts, reports, intentions, or contents. They select the **PROP** verbal case to signal that the vr̥tti as a whole depends on the head-noun.

To form a complement clause:
1. Derive the participial vr̥tti.    
2. Apply **PROP** to the vr̥tti.
3. Retain all internal arguments with their nominal cases.
4. Place the vr̥tti before the event/fact head-noun.
5. Head-noun receives the nominal case determined by the matrix vr̥tti.

### Template
```
[ … V-PART-PROP … ] event-noun(case) … V-FIN
```

### Example
```
[Krishna(case-C1) arrive-PFV-PROP] fact(case-C2) Arjuna(case-C1) know-FIN
```

----

## VI. Word Order Rules

### 1. Clause-Internal

- V‑FIN must be clause-final.

### 2. Dependent Units

- vr̥tti precedes its head-noun.
- Head-noun is final within the unit.    
- Unit behaves as a compound modifier.

### 3. Sentence Level

- Multiple dependent units may appear in any order permitted by dependency relations.
- Each unit retains internal head-finality.

---

## VII. Parsing Specification

To parse a sentence:
1. Identify **V‑FIN**, the clause head.
2. Assign roles to nouns via nominal case.
3. Identify any vr̥tti marked with a **verbal case** (inverse or PROP).
4. The noun immediately following is the **head-noun** of that vr̥tti.
5. Interpret inverse verbal cases as externalizing the marked internal role; interpret **PROP** as linking the entire vr̥tti to the head-noun.
6. Classify the dependent unit by the semantics of its head-noun (lexical → relative, abstract → adverbial, event/fact/content → complement).
7. Attach each dependent unit to V‑FIN according to the head-noun's nominal case.

---

## VIII. Summary
```
- Finite vr̥tti = sole clause head (always final).
- Dependent clauses share one shell: [vr̥tti-PART-VERBAL-CASE …] head-noun(NOMINAL-CASE).
- Nominal cases link nouns to vr̥ttis or other nouns; verbal cases link vr̥ttis to head-nouns.
- Inverse verbal cases externalize internal roles; PROP links whole vr̥ttis to event/fact heads.
- Head-noun (lexical, abstract, or eventive) is final in its unit.
- No gaps, no deletions; valency preserved.
- Dependent units behave as compounds.
```
