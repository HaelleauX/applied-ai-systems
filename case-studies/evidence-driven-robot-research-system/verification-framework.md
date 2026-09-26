# Evidence Classification & Verification Framework

## Public Portfolio Summary

This artifact shows the **architecture** of an evidence-classification system used to prevent AI-assisted research from collapsing documented fact, repeated claims, community observations, and unresolved assumptions into one undifferentiated category of “information.”

The complete operational framework, decision rules, schemas, and implementation logic are intentionally private.

> **A plausible claim is not the same thing as a verified claim.**

---

## Evidence States

The system separates claims into distinct evidence states so uncertainty remains visible.

### Official

Supported directly by authoritative primary material.

Typical examples include first-party documentation, manufacturer materials, specifications, or other primary records.

### Corroborated

Supported by multiple credible sources but not yet established through authoritative primary documentation.

Corroboration increases confidence, but source independence, source quality, and contradictory evidence still matter.

### Community / Observational

Reported through users, collectors, archived discussions, practitioner communities, or direct observations that have not yet met the project's verification standard.

These findings are useful as research leads, not automatic facts.

### Needs Verification

Available evidence is insufficient or conflicting.

The claim remains unresolved until stronger documentation, direct observation, or controlled testing provides enough evidence to reclassify it.

---

## Evidence Movement

Evidence status is **revisable**.

At a high level, claims move through a process such as:

```text
Discovery
   ↓
Source Review
   ↓
Evidence Classification
   ↓
Corroboration / Conflict Check
   ↓
Human Review or Verification
   ↓
Evidence Status Updated
```

The exact promotion thresholds and decision logic are part of the private implementation system.

---

## Design Principles

### Preserve Uncertainty

An unresolved claim should remain unresolved rather than being converted into confident prose.

### Prefer Provenance Over Fluency

A well-written answer is not necessarily a well-supported answer.

### Separate Discovery From Verification

Community knowledge and AI-generated hypotheses may identify useful leads without qualifying as verified evidence.

### Make Contradictions Visible

Conflicting evidence should be preserved for review instead of silently reconciled.

### Keep Human Judgment in the Loop

AI may organize, compare, and surface evidence. Human review determines whether the evidence is strong enough to change what the system treats as known.

---

## Why This Matters

This architecture is useful anywhere AI is being asked to synthesize information from sources of uneven quality.

Potential applications include:

- research operations
- knowledge management
- AI-assisted documentation
- product research
- customer implementation QA
- policy analysis
- AI-agent evaluation
- support troubleshooting

---

## Portfolio Boundary

This public version demonstrates the reasoning model without publishing:

- exact scoring or promotion rules
- database schemas
- decision tables
- reusable implementation templates
- project-specific claims or source collections
- automation logic

Those elements remain part of the private methodology.
