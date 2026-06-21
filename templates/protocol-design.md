# Tension Mining Template: Protocol Design

> Use this template when designing distributed protocols, consensus mechanisms, or communication systems.

---

## When to Use This Template

- Designing a new distributed protocol
- Evaluating existing consensus mechanisms
- Building peer-to-peer systems
- Designing inter-agent communication
- Analyzing protocol security and robustness

---

## Pre-Filled Phenomenon Library

Select relevant phenomena for your protocol:

- [ ] **TCP/IP** (reliable transmission over unreliable networks)
- [ ] **Byzantine Consensus** (agreement despite malicious actors)
- [ ] **CAP Theorem** (consistency, availability, partition tolerance tradeoffs)
- [ ] **Gossip Protocols** (epidemic information dissemination)
- [ ] **Blockchain Consensus** (proof-of-work, proof-of-stake)
- [ ] **DNS** (distributed naming system)
- [ ] **BGP** (border gateway protocol, path vector routing)
- [ ] **Raft/Paxos** (leader-based consensus)
- [ ] **BitTorrent** (peer-to-peer file sharing)
- [ ] **Other:** ___________________

For each selected phenomenon, describe:
- **Relevant behavior:** What does this phenomenon do that relates to your protocol?
- **Why it matters:** What insight does this phenomenon provide?

---

## Pre-Filled Tension Checklist

Identify tensions shaping your protocol:

### Core Tensions (select all that apply)

- [ ] **Consistency vs Availability** (`T-CON-012`)
  - What consistency guarantees does your protocol provide?
  - What availability guarantees does it provide?
  - How does it behave under network partition?

- [ ] **Security vs Performance** (`T-CMP-013`)
  - What security properties are required?
  - What performance costs do they impose?
  - What attacks are you defending against?

- [ ] **Complexity vs Usability** (`T-SIM-017`)
  - How complex is the protocol?
  - What is the cost of implementation?
  - What errors do implementers typically make?

- [ ] **Centralization vs Decentralization** (`T-CEN-011`)
  - Does the protocol require central coordination?
  - What are the single points of failure?
  - How does the protocol scale?

- [ ] **Synchronicity vs Asynchronicity** (`T-SYN-010`)
  - Does the protocol require synchronous communication?
  - What happens under latency and message loss?
  - How are timeouts handled?

- [ ] **Trust vs Verification** (`T-TRA-008`)
  - What trust assumptions does the protocol make?
  - What is cryptographically verified?
  - What are the adversarial models?

### Additional Tensions

- [ ] **Local vs Global** (`T-LOC-004`)
- [ ] **Short-term vs Long-term** (`T-SHO-019`)
- [ ] **Specialization vs Resilience** (`T-SPR-016`)
- [ ] **Other:** ___________________

---

## Pre-Filled Invariant Checklist

Identify invariants relevant to your protocol:

- [ ] **Consensus Requires Cost** (`I-TAE-001`)
  - What resource does your protocol consume for consensus?
  - What is the cost of attack?
  - How does cost scale with participants?

- [ ] **Boundaries Shape Behavior** (`I-BSB-001`)
  - What are the protocol's trust boundaries?
  - How do boundaries partition the system?
  - What happens at boundary crossings?

- [ ] **Feedback Loops Stabilize** (`I-FLS-001`)
  - What feedback mechanisms ensure protocol convergence?
  - What prevents runaway behavior?
  - How does the protocol recover from faults?

- [ ] **Local Rules Create Global Order** (`I-LCG-001`)
  - What local rules do participants follow?
  - What global properties emerge?
  - How do you prove global properties from local rules?

- [ ] **Tradeoffs Are Inescapable** (`I-TAE-001`)
  - What tradeoffs has the protocol explicitly accepted?
  - What tradeoffs are implicit?
  - How do you communicate tradeoffs to users?

- [ ] **Other:** ___________________

---

## Pre-Filled Mechanism Library

Select mechanisms relevant to your protocol:

- [ ] **Leader Election** (coordinator selection)
- [ ] **Quorum Consensus** (majority agreement)
- [ ] **Cryptographic Verification** (signature checking, hash chains)
- [ ] **Timeout and Retry** (failure detection and recovery)
- [ ] **State Machine Replication** (deterministic execution)
- [ ] **Merkle Trees** (efficient verification of large datasets)
- [ ] **Vector Clocks** (causality tracking)
- [ ] **CRDTs** (conflict-free replicated data types)
- [ ] **Zero-Knowledge Proofs** (privacy-preserving verification)
- [ ] **Other:** ___________________

For each selected mechanism:
- **Function:** What does this mechanism do?
- **Related tensions:** Which tensions does this mechanism address?
- **Related invariants:** Which invariants does this mechanism embody?

---

## 7-Phase Workflow

### Phase 1: Phenomenon Mining

**Selected phenomena:** (from above)

**Phenomenon Library:**

| Name | Domain | Relevant Behavior | Why It Matters |
|------|--------|-------------------|----------------|
| | | | |
| | | | |
| | | | |

### Phase 2: Tension Mining

**Selected tensions:** (from above)

**Tension Map:**

| Tension ID | Force A | Force B | Why Both Matter | Over-optimize A | Over-optimize B |
|------------|---------|---------|-----------------|-----------------|-----------------|
| | | | | | |
| | | | | | |
| | | | | | |

### Phase 3: Invariant Mining

**Selected invariants:** (from above)

**Invariant Library:**

| Invariant ID | Statement | Supporting Phenomena | Explanation |
|--------------|-----------|----------------------|-------------|
| | | | |
| | | | |
| | | | |

### Phase 4: Mechanism Mining

**Selected mechanisms:** (from above)

**Mechanism Library:**

| Mechanism | Function | Related Tensions | Related Invariants |
|-----------|----------|------------------|--------------------|
| | | | |
| | | | |
| | | | |

### Phase 5: System Synthesis

**System Model:**

**Core Tensions:**
- (List primary tensions)

**Core Invariants:**
- (List primary invariants)

**Core Mechanisms:**
- (List primary mechanisms)

**Expected Behaviors:**
- (What should the protocol do?)

**Failure Modes:**
- (What could go wrong?)

### Phase 6: Algorithm Synthesis

**Algorithm Candidates:**

| Name | Core Idea | Mathematical Representation | Advantages | Limitations |
|------|-----------|----------------------------|------------|-------------|
| | | | | |
| | | | | |

### Phase 7: Destruction Phase

**Failure Analysis:**

**Weak Assumptions:**
- (What assumptions might fail?)

**Missing Tensions:**
- (What tensions were overlooked?)

**Missing Invariants:**
- (What principles were ignored?)

**Missing Mechanisms:**
- (What mechanisms are absent?)

**Possible Redesigns:**
- (How would you redesign if the model is wrong?)

---

## Output Template

### Final Deliverable

```
## Phenomenon Library
[Summary]

## Tension Map
[Summary]

## Invariant Library
[Summary]

## Mechanism Library
[Summary]

## System Model
[Summary]

## Algorithm Candidates
[Summary]

## Failure Analysis
[Summary]

## Key Insight
[One sentence capturing the core insight]
```
