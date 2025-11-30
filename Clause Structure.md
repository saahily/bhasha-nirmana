
---
## I. Overview

This grammar treats all linguistic structure as arising from **vr̥ttis**—modulations of semantic fields (see [[Vr̥tti Ontology]]). A clause consists of:
- a single **finite vr̥tti** (the clause‑head), and
- zero or more **dependent vr̥ttis** modifying nouns.

All dependent clauses are structurally uniform. There are no special syntactic types beyond what follows from vr̥tti relations.

---

## II. Architectural Principles

### 1. Single Clause Head (Vr̥tti Monism)

- The **finite verb (V‑FIN)** is the **sole head** of its clause—the mahā‑vr̥tti.
- V‑FIN is **obligatorily final** within its clause.
- All other elements depend directly or indirectly on this single pulse.

### 2. Unified Dependent Clause Shell

All dependent clauses share one structural shell:

```
[ (internal dependents…) vr̥tti-PART-VERBAL-CASE ] head-noun(NOMINAL-CASE)
```

Where:
- the **vr̥tti** is a non‑finite derivation (upa-vr̥tti),
- **VERBAL-CASE** is either K⁻¹ or PROP (see [[Verb Cases]]),
- the **head-noun** carries only the nominal case assigned by the main clause,
- the unit behaves as a **compound** with the head-noun final.

**Key principle**: All upa-vr̥ttis modify **nouns** (lexical or abstract). There is no verb‑to‑verb subordination.

### 3. Valency Preservation

**No gaps, deletions, or traces.** All roles present in the vr̥tti-field manifest syntactically:
- K⁻¹ **relocates** one argument to head position but never deletes it.
- PROP embeds the entire vr̥tti with all its arguments intact.

### 4. Pure Dependency Structure

- No phrase-structure categories or projections (NP, VP, etc.).
- All relations are head–dependent.
- Linear order is determined by head-finality constraints, not hierarchical constituency.

---

## III. Clause Inventory

### A. Main Clause

```
noun(case) … V-FIN
```
- V‑FIN is clause-final and the dependency root.

### B. Dependent Clause 

```
[ (internal dependents…) vr̥tti-PART-VERBAL-CASE ] head-noun(NOMINAL-CASE)
```
- Head-noun is final within the unit.
- The whole unit behaves as a morphological compound.

---

## IV. Functional Differentiation

The function of a dependent clause is determined by three factors:

| Factor | Options | Determines |
|--------|---------|------------|
| **Verbal case** | K⁻¹ vs. PROP | Participant extraction vs. event linkage |
| **Head-noun semantics** | Lexical, event/fact, circumstantial | What the head-noun represents |
| **Nominal case on head** | C1, C2, ABL, DAT, SUB | Geometric position in matrix |

These factors combine to yield the following clause typology:

| Verbal Case | Head-Noun Type | Nominal Case | Clause Type |
|-------------|----------------|--------------|-------------|
| K⁻¹ | Lexical (participant) | Any | Relative |
| PROP | Event/fact/content | C1, C2 | Complement |
| PROP | *cause*, *reason*, *concession* | ABL | Adverbial (causal/contrastive) |
| PROP | *time*, *place*, *manner*, *condition* | SUB | Adverbial (circumstantial) |
| PROP | *purpose*, *goal* | DAT | Adverbial (telic) |
| PROP | *state*, *case* (light) | ABL, SUB | Absolute |

---

## V. Relative Clauses

Relative clauses use **K⁻¹** to mark that the head-noun *is* a participant extracted from the dependent vr̥tti.

### Formation

1. Derive a participial vr̥tti.
2. Apply **K⁻¹** matching the head-noun's internal role.
3. Retain all other arguments with their nominal cases.
4. Place the vr̥tti before the head-noun.
5. Head-noun receives only its matrix case.

### Template
```
[ … Arg_i(case_i) … V-PART-K⁻¹ ] head-noun(matrix-case)
```

### Examples

**C1⁻¹ — Subject relativization:**
```
[enemy(C2) defeat-PFV-C1⁻¹] warrior(C1)
"the warrior [who defeated the enemy]"
```

**C2⁻¹ — Object relativization:**
```
[speaker(C1) praise-PFV-C2⁻¹] listener(C1)
"the listener [whom the speaker praised]"
```

**ABL⁻¹ — Instrument relativization:**
```
[warrior(C1) enemy(C2) strike-PFV-ABL⁻¹] sword(C1)
"the sword [with which the warrior struck the enemy]"
```

**DAT⁻¹ — Recipient relativization:**
```
[sage(C1) wisdom(C2) teach-PFV-DAT⁻¹] student(C2)
"the student [to whom the sage taught wisdom]"
```

**SUB⁻¹ — Locative relativization:**
```
[king(C1) sit-PFV-SUB⁻¹] throne(C1)
"the throne [on which the king sat]"
```

---

## VI. Adverbial Clauses

Adverbial clauses use **PROP** to link the entire dependent vr̥tti to a circumstantial head-noun. The **nominal case** determines the geometric relationship:
- **ABL**: The dependent event is the **source** of the matrix event
- **SUB**: The dependent event is the **substrate** of the matrix event
- **DAT**: The dependent event is the **goal** of the matrix event

### Template
```
[ … all-args(nominal-cases) … V-PART-PROP ] circumstance-noun(case) … V-FIN
```

### Causal (ABL)
The dependent event is the origin from which the matrix event emanates.

```
[rain(C1) fall-PFV-PROP] cause(ABL) river(C1) flood-FIN
"Because the rain fell, the river flooded"
```

### Concessive (ABL)
The dependent event is a contrastive source — the origin from which a different outcome was expected.

```
[city(C1) fall-PFV-PROP] concession(ABL) king(C1) fight-FIN
"Although the city fell, the king fights"
```

### Temporal (SUB)
The dependent event is the temporal substrate of the matrix event.

```
[Krishna(C1) arrive-PFV-PROP] time(SUB) Arjuna(C1) bow-FIN
"When Krishna arrived, Arjuna bowed"
```

### Locative (SUB)
The dependent event is the spatial substrate of the matrix event.

```
[battle(C1) occur-PFV-PROP] place(SUB) flowers(C1) grow-FIN
"Where the battle occurred, flowers grow"
```

### Manner (SUB)
The dependent event provides the mode of the matrix event.

```
[father(C1) speak-PFV-PROP] manner(SUB) son(C1) speak-FIN
"As his father spoke, the son speaks"
```

### Conditional (SUB)
The dependent event is a hypothetical substrate for the matrix event.

```
[enemy(C1) attack-IPFV-PROP] condition(SUB) we(C1) fight-FIN
"If the enemy attacks, we fight"
```

### Purpose (DAT)
The dependent event is the goal toward which the matrix event is directed.

```
[peace(C1) prevail-OPT-PROP] purpose(DAT) king(C1) negotiate-FIN
"So that peace prevails, the king negotiates"
```

---

## VII. Complement Clauses

Complement clauses use **PROP** to link the entire dependent vr̥tti to an event/fact head-noun that becomes an **argument** (C1 or C2) of the matrix verb.

### Template
```
[ … all-args(nominal-cases) … V-PART-PROP ] event-noun(C1/C2) … V-FIN
```

### Examples

```
[Krishna(C1) arrive-PFV-PROP] fact(C2) Arjuna(C1) know-FIN
"Arjuna knows the fact [that Krishna arrived]"

[sage(C1) secret(C2) reveal-PFV-PROP] report(C2) disciple(C1) trust-FIN
"The disciple trusts the report [that the sage revealed the secret]"

[enemy(C1) attack-IPFV-PROP] rumor(C1) spread-FIN
"The rumor [that the enemy will attack] spreads"
```

---

## VIII. Absolute Constructions

Absolute constructions use **PROP** with **light abstract-nouns** (*state*, *case*, *event*) that may undergo phonological reduction.

The nominal case disambiguates readings:
- **ABL**: causal reading
- **SUB**: temporal/circumstantial reading

### Template
```
[ … all-args(nominal-cases) … V-PART-PROP ] state/case(ABL/SUB) … V-FIN
```

### Examples

```
[city(C1) capture-PFV-PROP] state(ABL) war(C1) begin-FIN
"The city having been captured, war began" (causal)

[city(C1) capture-PFV-PROP] state(SUB) war(C1) begin-FIN
"The city having been captured, war began" (temporal)

[sun(C1) set-PFV-PROP] case(SUB) travelers(C1) camp(C2) make-FIN
"The sun having set, the travelers made camp"
```

---

## IX. Word Order

### Clause-Internal
- V‑FIN must be clause-final.

### Dependent Units
- Vr̥tti precedes its head-noun.
- Head-noun is final within the unit.
- Unit behaves as a compound modifier.

### Sentence Level
- Multiple dependent units may appear in any order permitted by dependency relations.
- Each unit retains internal head-finality.

---

## X. Parsing Specification

1. Identify **V‑FIN**, the clause head.
2. Assign roles to nouns via nominal case.
3. Identify any vr̥tti marked with a **verbal case** (K⁻¹ or PROP).
4. The noun immediately following is the **head-noun** of that vr̥tti.
5. If **K⁻¹**: the head-noun *is* the extracted participant (role indicated by K).
6. If **PROP**: the head-noun *contains* the entire dependent event.
7. Classify:
   - K⁻¹ → relative clause
   - PROP + C1/C2 → complement clause
   - PROP + ABL/SUB/DAT → adverbial clause
8. Attach each dependent unit to V‑FIN according to the head-noun's nominal case.

---

## XI. Summary

| Principle | Description |
|-----------|-------------|
| **Finite vr̥tti** | Sole clause head (always final) |
| **Dependent shell** | `[vr̥tti-PART-VERBAL-CASE] head-noun(NOMINAL-CASE)` |
| **K⁻¹** | Head-noun *is* extracted participant → relative clause |
| **PROP** | Head-noun *contains* event → complement or adverbial |
| **Nominal case** | Determines matrix position: C1/C2 = argument; ABL/SUB/DAT = adjunct |
| **Head-noun semantics** | Determines flavor: *fact* = complement; *cause* = causal; etc. |
| **No gaps** | Valency preserved; all roles manifest |
