# 05_LEVEL_MODEL_COLON_DEPTH.md
# Schloemer::Notation / SGP-7/X
## Level Model of Colon Depth 2026
### Depth Model of the `::`, `:::`, `::::` and `:::::` Levels

**Version:** 1.1.0  
**Status:** Canonical Working Specification  
**Date:** 2026-05-13  
**Author:** Joost H. Schloemer  
**License:** CC BY 4.0 Joost H. Schloemer  
**Attribution required:** yes  

---

# 1. Purpose of this File

This file documents the colon-depth model of the Schloemer::Notation.

The Schloemer::Notation does not work only with individual `::markers`. It distinguishes multiple levels of semantic control:

```text
::        marker / operational semantic unit
:::       effect or review chain
::::      mode / work control
:::::     meta-mode / system stance / validity frame
```

These levels must not be misunderstood as typographic variation.

Colon depth marks a functional shift: from the individual marker to the chain, from the work-mode to the meta-mode.

---

# 2. Canonical Short Form

```text
:: designates.
::: connects.
:::: controls.
::::: establishes.
```

More explicitly:

```text
::        designates a semantic function.
:::       connects functions into an effect or review chain.
::::      controls the concrete work-mode.
:::::     establishes the overarching system stance.
```

This creates a multi-level semantic depth architecture.

---

# 3. Why the Depth Model Is Required

Without the depth model, the Schloemer::Notation may appear as a collection of individual markers:

```text
::root
::boot
::init
::semantic
::admissibility
```

With the depth model, it becomes visible that SGP-7/X distinguishes levels:

```text
:::::modus   = overarching system stance
::::modus    = concrete work control
:::sequence  = effect or review chain
::marker     = operational semantic unit
```

Colon depth is therefore part of the effect architecture.

---

# 4. Level Model

## 4.1 Level `::` — Marker / Operational Semantic Unit

The `::` level designates an individual semantic marker.

Examples:

```text
::root
::boot
::init
::semantic
::admissibility
::decision_logic
::output_gate
::on
```

Canonical formula:

```text
:: = semantic unit
```

A `::marker` names a function. Its operational effect arises through definition, rule binding and sequence position.

---

## 4.2 Level `:::` — Effect or Review Chain

The `:::` level designates a chain, inner order or composed effect structure.

Examples:

```text
:::minimal_effect_sequence
:::extended_minimal_sequence
:::governance_chain
:::privacy_gate_sequence
:::cyber_review_chain
```

Canonical formula:

```text
::: = connection / chain / effect order
```

A `:::chain` makes visible that multiple markers operate together.

---

## 4.3 Level `::::` — Mode / Work Control

The `::::` level designates the concrete work-mode.

Examples:

```text
::::analysis
::::review
::::refactoring
::::audit
::::publication
::::instruction_check
::::semantic_review
::::risk_review
```

Canonical formula:

```text
:::: = work control
```

The `::::modus` determines which kind of work is performed inside the overarching frame.

---

## 4.4 Level `:::::` — Meta-Mode / System Stance

The `:::::` level designates the overarching system stance or meta-mode.

Examples:

```text
:::::governance
:::::privacy
:::::cyber
:::::publication
:::::research
:::::compliance
:::::semantic_governance
```

Canonical formula:

```text
::::: = validity and system frame
```

The `:::::modus` establishes the overarching effect and validity frame of the sequence.

---

# 5. Relation of the Levels

The levels form a stepped order:

```text
:::::Meta-Mode
→ ::::Work-Mode
→ :::Effect or Review Chain
→ ::Marker
```

Reading:

```text
The meta-mode establishes.
The work-mode controls.
The chain connects.
The marker designates.
```

---

# 6. Application to the Minimal Effect Sequence

```text
:::::modus
→ ::::modus
→ ::root
→ ::boot
→ ::init
→ ::semantic
→ ::admissibility
→ ::decision_logic
→ ::output_gate
→ ::on
```

The sequence contains three visible levels:

```text
:::::modus = meta-mode
::::modus  = work-mode
::marker   = operational marker order
```

The `:::` level is present in the designation of the entire sequence as:

```text
:::minimal_effect_sequence
```

---

# 7. Attribution

```text
Schloemer::Notation / SGP-7/X · Level Model of Colon Depth 2026
Joost H. Schloemer · CC BY 4.0
Attribution required.
```
