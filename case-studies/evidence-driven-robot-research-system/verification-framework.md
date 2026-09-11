# Evidence Classification & Verification Framework

## Purpose

This framework was designed to prevent AI-assisted research from collapsing documented fact, repeated claims, community observations, and unverified assumptions into a single category of "information."

The system assigns an evidence status to each meaningful research claim and defines what must happen before that claim can be treated as verified.

The underlying principle is simple:

> A plausible claim is not the same thing as a verified claim.

---

## Evidence Classification Model

### 1. Official

**Definition:**  
The claim is supported directly by authoritative primary documentation.

Examples of qualifying evidence may include:

- official manuals
- manufacturer documentation
- technical specifications
- official packaging
- first-party archival material

**Use:**  
May be treated as established within the limitations of the source.

---

### 2. Multi-Source Confirmed

**Definition:**  
The claim is supported by two or more independent credible sources but has not yet been located in authoritative primary documentation.

**Requirements:**

- sources must be meaningfully independent
- sources should describe substantially the same behavior or fact
- contradictory credible evidence must be documented
- source quality should be considered, not merely source count

**Use:**  
May be used with appropriate attribution or qualification depending on context.

---

### 3. Community Discovery

**Definition:**  
The claim is reported by users, collectors, enthusiasts, archived discussions, or other community sources but has not been sufficiently verified.

Community observations can be extremely useful for discovering undocumented behavior, but repetition alone does not convert a claim into fact.

**Use:**  
Treat as a lead, observation, or testing candidate.

---

### 4. Needs Testing

**Definition:**  
Available research cannot reliably settle the claim.

The item requires one or more of the following:

- physical testing
- direct observation
- stronger primary documentation
- repeat testing
- additional source verification

**Use:**  
Do not present as established fact.

---

## Claim Lifecycle

A research claim moves through the system rather than receiving a permanent label at discovery.

```text
Claim Discovered
      ↓
Source Identified
      ↓
Evidence Classified
      ↓
Corroborating Sources Checked
      ↓
Conflict Assessment
      ↓
┌─────────────────────┐
│ Evidence Sufficient │──→ Verified / Qualified
└─────────────────────┘

          OR

┌─────────────────────┐
│ Evidence Incomplete │──→ Needs Testing
└─────────────────────┘
                               ↓
                         Test Protocol
                               ↓
                       Repeat Observation
                               ↓
                       Evidence Reclassified
