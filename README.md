# Bit Engineering Notation (BEN)
**Version:** 1.0.0

BEN is a symbolic system for describing the structural logic, cognitive mechanism, and performer status of a comedy bit.

## Model: Captures vs Ignores

| Captures | Ignores |
| :--- | :--- |
| Cognitive "gap" (Mechanism) | Topic / Subject matter |
| Structural delivery (Form) | Exact wording / Phrasing |
| Performer relationship (Status) | Cultural context |
| Logic of the "twist" | Taste / Subjective humor |

## Canonical Syntax

```text
BEN ::= <Form> <Mechanism>+ <Status> [<Modifier>+]
```

Example: `F> M≠ S↓ (C)`

## Symbol Table

### 1. Form (F)
Structural container of the bit.
- `F>`: Linear, setup-punch.
- `F?`: Interrogative, Q&A.
- `F3`: Rule of Three.
- `F~`: Narrative, anecdote.
- `F:`: Comparative, analogy.

### 2. Mechanism (M)
The cognitive operation that creates the laugh.
- `M≠`: **Reversal:** Broken expectation.
- `M*`: **Ambiguity:** Multiple interpretations.
- `M^`: **Exaggeration:** Escalation/Hyperbole.
- `M_`: **Literalism:** Interpreting metaphor literally.
- `M!`: **Recognition:** Articulating unspoken truth.

### 3. Status (S)
The speaker's relative psychological position.
- `S↓`: **Low Status:** Self-deprecating/Powerless.
- `S↑`: **High Status:** Superior/Judgmental.
- `S=`: **Neutral:** Reporter/Observer.

### 4. Modifiers
- `(C)`: Callback.
- `(T)`: Topper.
- `(A)`: Act-out.

## Semantics Rules

- **Mechanism Stacking:** Multiple `M` symbols can be used if a bit relies on several cognitive shifts.
- **Status is First-Class:** Status is essential for the "gap" to function correctly.
- **Diagnosis:** BEN is used to diagnose *why* a bit works or fails structurally.

## Constraints / Invariants

- Every bit must define exactly one Form (`F`) and one Status (`S`).
- Mechanisms (`M`) must be explicitly identified; "just funny" is not a mechanism.
- BEN is content-agnostic; the same BEN string can describe two completely different topics.

## Live Mode (Shorthand)

Optimized for real-time bit tagging.

- Omit prefixes (`F`, `M`, `S`) if using standard ordering.
- Use `!`, `?`, `~`, `:` for forms.

Example: `> ≠ ↓` (Linear, Reversal, Low Status)

---

See [EXAMPLES.md](./EXAMPLES.md) for usage and [CHEATSHEET.md](./CHEATSHEET.md) for a quick reference.
