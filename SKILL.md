---
name: tension-mining
description: >
  Discover invariants hidden inside complex systems by mining tensions across reality,
  phenomena, and mechanisms. Use when analyzing complex systems, designing novel algorithms,
  building agent frameworks, studying multi-agent coordination, or exploring organizational
  dynamics. Not for simple optimization tasks or known-solution problems.
license: MIT
compatibility: Designed for research-oriented AI agents with markdown output capabilities
metadata:
  author: CeaserZhao
  version: "1.0"
  domain: complex-systems-research
  methodology: tension-driven-discovery
---

# Tension Mining Protocol

## Core Principle

Do not start from solutions.
Do not start from architectures.
Do not start from algorithms.

Start from reality.

Move through the layers:

```
Reality -> Phenomena -> Tensions -> Invariants -> Mechanisms -> Algorithms
```

The quality of the result depends on the depth of understanding in the earlier layers.

## When NOT to Use

- The problem has a known optimal solution
- The task is pure implementation or refactoring
- The goal is incremental optimization of an existing system
- Time constraints prevent deep exploration

## 7-Phase Workflow

### Phase 1: Phenomenon Mining

**Goal:** Build a library of relevant real-world phenomena.

**Questions:**
- What existing systems exhibit similar behavior?
- What natural systems solve similar problems?
- What social systems solve similar problems?
- What technological systems solve similar problems?
- What historical systems solve similar problems?

**Output:** Phenomenon Library (5-10 phenomena, each with Name, Domain, Relevant behavior, Why it matters)

**Reference:** See [`tension-atlas.md`](./tension-atlas.md) for domain-specific phenomena.

### Phase 2: Tension Mining

**Goal:** Identify forces that continuously shape the system.

**Definition:** A tension is a tradeoff that cannot be permanently eliminated.

**Questions:**
- What forces are pulling in opposite directions?
- What optimization destroys another optimization?
- What remains difficult regardless of implementation?

**Output:** Tension Map (at least 5 tensions, each with Force A, Force B, Why both matter, Consequences of over-optimizing either side)

**Reference:** See [`tension-atlas.md`](./tension-atlas.md) for a catalog of persistent tensions.

### Phase 3: Invariant Mining

**Goal:** Discover patterns that appear across multiple phenomena.

**Definition:** An invariant is a principle that remains valid across different domains.

**Questions:**
- What repeatedly appears?
- What survives context changes?
- What principle explains multiple phenomena?

**Output:** Invariant Library (principles with Statement, Supporting phenomena, Explanation)

**Reference:** See [`invariant-atlas.md`](./invariant-atlas.md) for cross-domain principles.

### Phase 4: Mechanism Mining

**Goal:** Understand how reality resolves tensions.

**Questions:**
- What mechanisms maintain stability?
- What mechanisms coordinate behavior?
- What mechanisms distribute resources?
- What mechanisms generate adaptation?

**Output:** Mechanism Library (Name, Function, Related tensions, Related invariants)

### Phase 5: System Synthesis

**Goal:** Combine tensions, invariants, and mechanisms into a coherent system model.

**Questions:**
- What is the smallest model explaining the system?
- Which tensions are primary?
- Which mechanisms are essential?
- Which mechanisms are optional?

**Output:** System Model (Core Tensions, Core Invariants, Core Mechanisms, Expected Behaviors, Failure Modes)

### Phase 6: Algorithm Synthesis

**Goal:** Generate implementation candidates.

**IMPORTANT:** Algorithms are not the objective. Algorithms are downstream consequences.

**Questions:**
- How can the mechanism be represented computationally?
- What mathematical structures fit naturally?
- What graph structures exist?
- What flows exist?
- What information propagates?

**Output:** Algorithm Candidates (Name, Core idea, Mathematical representation, Advantages, Limitations)

### Phase 7: Destruction Phase

**Goal:** Attack the model. Assume it is wrong.

**Questions:**
- What assumptions fail?
- What edge cases break the system?
- What adversarial environments exist?
- What phenomena remain unexplained?

**Output:** Failure Analysis (Weak assumptions, Missing tensions, Missing invariants, Missing mechanisms, Possible redesigns)

## Final Deliverable

Produce:

1. Phenomenon Library
2. Tension Map
3. Invariant Library
4. Mechanism Library
5. System Model
6. Algorithm Candidates
7. Failure Analysis

Do not skip layers. Do not jump directly to algorithms.

The objective is not optimization. The objective is understanding.

## File References

| File | Purpose |
|------|---------|
| [`tension-atlas.md`](./tension-atlas.md) | Catalog of persistent tensions with IDs and cross-references |
| [`invariant-atlas.md`](./invariant-atlas.md) | Cross-domain invariants with IDs and cross-references |
| [`examples/`](./examples/) | 7 complete case studies demonstrating the workflow |
| [`templates/`](./templates/) | 5 fill-in-the-blank templates for immediate use |
| [`references/methodology-primer.md`](./references/methodology-primer.md) | Extended methodology reference |
