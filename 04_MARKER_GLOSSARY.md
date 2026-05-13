# 04_MARKER_GLOSSARY.md
# Schloemer::Notation / SGP-7/X
## Marker Glossary 2026
### Semantic Marker Inventory for Minimal-Core, Extensions, Safety, Runtime Governance and Control Layers

**Version:** 1.1.0  
**Status:** Canonical Working Specification  
**Date:** 2026-05-13  
**Author:** Joost H. Schloemer  
**License:** CC BY 4.0 Joost H. Schloemer  
**Attribution required:** yes  

---

# 1. Purpose of this File

This file documents the **::marker::glossar** of the Schloemer::Notation / SGP-7/X.

The glossary defines markers, marker classes, use contexts and distinctions. It is explicitly **not a sequence**.

Central distinction:

```text
::sequence        = operational effect order
::marker::glossar = semantic inventory
::ruleset         = validity and limitation order
```

A marker may be defined in the glossary without being part of the Minimal-Core.

---

# 2. Relation to the Minimal Effect Sequence

The smallest effective SGP-7/X sequence remains:

```text
SGP::7/X::MINIMAL_EFFECT_SEQUENCE::2026

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

These markers form the **Minimal-Core**.

All additional markers in this glossary are extension, review, protection, domain, runtime, provenance, privacy, audit, safety, retention or status markers.

Anti-drift rule:

```text
Not every strong marker belongs in the smallest chain.
But every strong marker belongs in the ::marker::glossar.
```

---

# 3. Colon-Depth Model

The Schloemer::Notation uses multiple colon-depth levels:

```text
::        marker / operational semantic unit
:::       effect or review chain
::::      mode / work control
:::::     meta-mode / system stance / validity frame
```

Short form:

```text
:: designates.
::: connects.
:::: controls.
::::: establishes.
```

---

# 4. Marker Classes

```text
A. Minimal-Core Markers
B. Extended-Minimal Markers
C. Semantic and Context Markers
D. Reflection and Clarity Markers
E. Admissibility, Decision and Reception Markers
F. Provenance, License and Attribution Markers
G. Privacy and Protection Markers
H. Cyber, Risk and Security Markers
I. Semantic Safety & Runtime Control Markers
J. Audit, Evidence and Traceability Markers
K. Status and Gate Markers
L. Runtime and Control Markers
M. Domain and Specialist Markers
```

---

# A. Minimal-Core Markers

## `:::::modus`

**Class:** Minimal-Core / Meta-Mode  
**Sequence status:** part of the Minimal Effect Sequence  
**Function:** set overarching system stance

```text
:::::modus = meta-frame / system stance / validity direction
```

## `::::modus`

**Class:** Minimal-Core / Work-Mode  
**Sequence status:** part of the Minimal Effect Sequence  
**Function:** set concrete work mode

```text
::::modus = work frame / processing mode / operative direction
```

## `::root`

**Class:** Minimal-Core / Origin  
**Sequence status:** part of the Minimal Effect Sequence  
**Function:** set origin and validity frame

```text
::root = origin / identity / validity frame / reference point
```

## `::boot`

**Class:** Minimal-Core / Activation  
**Sequence status:** part of the Minimal Effect Sequence  
**Function:** start semantic runtime

```text
::boot = start / activation / runtime beginning
```

## `::init`

**Class:** Minimal-Core / Initialization  
**Sequence status:** part of the Minimal Effect Sequence  
**Function:** initialize role, rules, boundaries and terms

```text
::init = initialization / role binding / rule binding / operational readiness
```

## `::semantic`

**Class:** Minimal-Core / Semantics  
**Sequence status:** part of the Minimal Effect Sequence  
**Function:** clarify meaning before formulation

```text
::semantic = semantic clarification / deep structure / meaning before style
```

## `::admissibility`

**Class:** Minimal-Core / Admissibility  
**Sequence status:** part of the Minimal Effect Sequence  
**Function:** review permissibility before execution or output

```text
::admissibility = admissibility review / pre-execution gate / responsibility review
```

## `::decision_logic`

**Class:** Minimal-Core / Decision  
**Sequence status:** part of the Minimal Effect Sequence  
**Function:** transform review into decision

```text
::decision_logic = decision logic / prioritization / PASS-WARN-FAIL order
```

## `::output_gate`

**Class:** Minimal-Core / Output Gate  
**Sequence status:** part of the Minimal Effect Sequence  
**Function:** final output barrier before release

```text
::output_gate = output barrier / final gate / release review
```

## `::on`

**Class:** Minimal-Core / Release State  
**Sequence status:** part of the Minimal Effect Sequence  
**Function:** mark released operational state

```text
::on = active / released / output-capable state
```

---

# B. Extended-Minimal Markers

## `::provenance`

**Class:** Extended Minimal / Origin / Traceability  
**Sequence status:** part of the Extended Minimal Sequence  
**Function:** secure origin, version, license and attribution

```text
::provenance = origin / attribution / version / license / reference frame
```

## `::runtime_enforcer`

**Class:** Extended Minimal / Runtime Control  
**Sequence status:** part of the Extended Minimal Sequence  
**Function:** secure rule binding during processing

```text
::runtime_enforcer = runtime enforcement / drift limitation / rule binding
```

---

# C. Semantic and Context Markers

## `::context`

```text
::context = case reference / purpose / data situation / scope
```

## `::ontology`

```text
::ontology = entities / roles / relations / classes / dependencies
```

## `::scope`

```text
::scope = range / limitation / area of application
```

## `::frame`

```text
::frame = interpretive frame / perspective / reference logic
```

## `::frame_bundle`

```text
::frame_bundle = bundle of frames / perspective alignment
```

---

# D. Reflection and Clarity Markers

## `::denk`

```text
::denk = reflection phase / review phase / deliberation
```

## `::clarity`

```text
::clarity = term clarity / goal clarity / anti-false-clarity
```

## `::ambiguity`

```text
::ambiguity = ambiguity review / ambiguity control
```

---

# E. Admissibility, Decision and Reception Markers

## `::reception`

```text
::reception = perception / interpretation / public effect
```

## `::validation`

```text
::validation = review / validation / release preparation
```

## `::consistency`

```text
::consistency = contradiction-free structure / coherence review
```

---

# F. Provenance, License and Attribution Markers

## `::license`

```text
::license = license / usage frame / rights binding
```

## `::attribution`

```text
::attribution = attribution / authorship notice / license notice
```

---

# G. Privacy and Protection Markers

## `::privacy`

```text
::privacy = privacy / personal data / protection need
```

## `::data_protection`

```text
::data_protection = GDPR / data protection review / personal data protection
```

---

# H. Cyber, Risk and Security Markers

## `::risk`

```text
::risk = risk / threat / need for assessment
```

## `::cyber`

```text
::cyber = cybersecurity / IT security / digital threat
```

## `::drift_control`

```text
::drift_control = drift limitation / semantic stabilization
```

---

# I. Semantic Safety & Runtime Control Markers

## `::safety`

**Class:** Semantic Safety / Runtime Governance  
**Sequence status:** optional, recommended for professional, agentic or safety-relevant systems  
**Function:** semantic safety and risk review before output, execution or runtime action

`::safety` checks whether outputs, actions, automations, code generation, agentic actions or recommendations may create harm, misuse, loss of control or operational risks.

```text
::safety = semantic safety / risk control / controlled execution
```

Review areas:

```text
harm potential
misuse potential
privacy exposure
operational risk
unsafe automation
infrastructural risk
loss of control
```

Canonical formula:

```text
::admissibility determines whether something is permissible.
::safety determines whether it remains safely controllable.
```

## `::stability`

**Class:** Runtime Stability / Governance Continuity  
**Sequence status:** optional  
**Function:** secure semantic coherence and runtime stability

```text
::stability = semantic coherence / runtime continuity / architectural non-drift
```

Canonical formula:

```text
::stability preserves semantic coherence over time.
```

## `::retention`

**Class:** Semantic Retention / Governance Persistence  
**Sequence status:** optional  
**Function:** protect against semantic loss or silent forgetting

```text
::retention = semantic persistence / non-forgetting / governance continuity
```

Canonical formula:

```text
::retention prevents semantic loss.
```

## `::wirkung`

**Class:** Semantic Effect / Runtime Semantics  
**Sequence status:** optional  
**Function:** make semantic effects of the sequence visible

```text
::wirkung = semantic effect / governance effect / runtime semantic influence
```

Canonical formula:

```text
::wirkung describes the operative effect of semantic order.
```

## `::risk_control`

**Class:** Runtime Risk Governance  
**Sequence status:** optional  
**Function:** operational risk and escalation control

```text
::risk_control = operational risk limitation / escalation control
```

Canonical formula:

```text
::risk_control limits operational escalation.
```

## `::hallucination`

```text
::hallucination = hallucination control / protection against unsupported fabrication
```

## `::probability`

```text
::probability = probability awareness / uncertainty marking
```

## `::bias`

```text
::bias = bias review / distortion control
```

---

# J. Audit, Evidence and Traceability Markers

## `::audit`

```text
::audit = audit trail / traceability / auditability
```

## `::evidence`

```text
::evidence = evidence / proof / evidentiary basis
```

---

# K. Status and Gate Markers

## `::pass`

```text
::pass = passed / releasable
```

## `::warn`

```text
::warn = restricted / warning required / review needed
```

## `::fail`

```text
::fail = not releasable / blocked
```

---

# L. Runtime and Control Markers

## `::runtime`

```text
::runtime = runtime / active operational state
```

## `::control`

```text
::control = control / steering / limitation
```

---

# M. Domain and Specialist Markers

## `::bim`

```text
::bim = planned and documented building model
```

## `::owl`

```text
::owl = Ontology Web Language / formal meaning logic
```

## `::digital_twin`

```text
::digital_twin = current digital state twin
```

---

# 5. Extended Runtime Short Form

```text
::stability preserves.
::retention retains.
::safety limits.
::wirkung describes effect.
::risk_control limits escalation.
```

---

# 6. Extended Anti-Drift Rule

```text
New runtime markers deepen the governance architecture.
They do not replace the Minimal-Core.
```

---

# 7. Attribution

```text
Schloemer::Notation / SGP-7/X · Marker Glossary 2026
Joost H. Schloemer · CC BY 4.0
Attribution required.
```
