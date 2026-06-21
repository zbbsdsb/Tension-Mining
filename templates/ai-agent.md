# Tension Mining Template: AI Agent Design

> Use this template when designing AI agent systems, agent frameworks, or multi-agent architectures.

---

## When to Use This Template

- Designing a new AI agent from scratch
- Evaluating an existing agent architecture
- Building a multi-agent system
- Choosing between agent design patterns
- Investigating agent failure modes

---

## Pre-Filled Phenomenon Library

Select relevant phenomena for your agent system:

- [ ] **Human assistants** (executive assistants, personal assistants)
- [ ] **Expert systems** (medical diagnosis, legal reasoning)
- [ ] **Autonomous vehicles** (self-driving cars, drones)
- [ ] **Game AI** (NPCs, strategy game opponents)
- [ ] **Robotics** (manipulation, navigation, human-robot interaction)
- [ ] **Customer service** (chatbots, call center agents)
- [ ] **Scientific research** (automated hypothesis generation, experiment design)
- [ ] **Trading systems** (algorithmic trading, market making)
- [ ] **Creative tools** (AI writing, art generation, music composition)
- [ ] **Other:** ___________________

For each selected phenomenon, describe:
- **Relevant behavior:** What does this phenomenon do that relates to your agent?
- **Why it matters:** What insight does this phenomenon provide?

---

## Pre-Filled Tension Checklist

Identify tensions shaping your agent system:

### Core Tensions (select all that apply)

- [ ] **Autonomy vs Control** (`T-AUT-005`)
  - How much freedom should the agent have?
  - What human oversight is required?
  - What are the consequences of too much or too little autonomy?

- [ ] **Capability vs Alignment** (`T-SPE-002`)
  - What can the agent do vs what should it do?
  - How do you prevent capability misalignment?
  - What happens when capability exceeds understanding?

- [ ] **Latency vs Quality** (`T-COM-003`)
  - How fast must the agent respond?
  - What quality tradeoffs are acceptable for speed?
  - When is it better to be slow and correct vs fast and approximate?

- [ ] **General vs Specialized** (`T-SPR-016`)
  - Should the agent be a generalist or specialist?
  - What is the cost of specialization?
  - Can the agent adapt to out-of-distribution tasks?

- [ ] **Exploration vs Exploitation** (`T-EXP-001`)
  - How should the agent balance trying new strategies vs using known ones?
  - What is the cost of exploration in your domain?
  - When should the agent be conservative vs adventurous?

- [ ] **Transparency vs Performance** (`T-TRA-008`)
  - How explainable must the agent's decisions be?
  - What performance is sacrificed for explainability?
  - Who needs to understand the agent's reasoning?

### Additional Tensions

- [ ] **Memory vs Computation** (`T-CMP-013`)
- [ ] **Short-term vs Long-term** (`T-SHO-019`)
- [ ] **Simplicity vs Capability** (`T-SIM-017`)
- [ ] **Other:** ___________________

---

## Pre-Filled Invariant Checklist

Identify invariants relevant to your agent system:

- [ ] **Relevant Information is Sparse** (`I-CRS-001`)
  - For any decision, only a fraction of available information matters
  - How does your agent identify what is relevant?
  - What mechanisms enable selective attention?

- [ ] **Feedback Loops Stabilize** (`I-FLS-001`)
  - How does your agent learn from outcomes?
  - What feedback mechanisms prevent drift?
  - How do you detect and correct misalignment?

- [ ] **Boundaries Shape Behavior** (`I-BSB-001`)
  - What boundaries define your agent's operating space?
  - How do boundaries enable specialization?
  - What happens when boundaries are crossed?

- [ ] **Gradients Drive Movement** (`I-GDM-001`)
  - What gradients does your agent follow?
  - How does the agent navigate complex decision landscapes?
  - What prevents the agent from getting stuck in local optima?

- [ ] **Tradeoffs Are Inescapable** (`I-TAE-001`)
  - What tradeoffs has your design explicitly accepted?
  - What tradeoffs are implicit and unacknowledged?
  - How do you manage tradeoffs dynamically?

- [ ] **Other:** ___________________

---

## Pre-Filled Mechanism Library

Select mechanisms relevant to your agent:

- [ ] **ReAct** (Reasoning + Acting loops)
- [ ] **Chain-of-Thought** (step-by-step reasoning)
- [ ] **Tool Use / Function Calling** (external capability extension)
- [ ] **Retrieval-Augmented Generation (RAG)** (external memory)
- [ ] **Multi-Agent Debate** (consensus through disagreement)
- [ ] **Reinforcement Learning** (reward-driven behavior optimization)
- [ ] **Hierarchical Planning** (task decomposition)
- [ ] **Memory Systems** (short-term, long-term, episodic)
- [ ] **Reflection / Self-Correction** (meta-cognitive monitoring)
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
- (What should the agent do?)

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
