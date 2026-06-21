# Tension Mining Template: Algorithm Discovery

> Use this template when discovering novel algorithms, optimizing existing ones, or understanding algorithmic tradeoffs.

---

## When to Use This Template

- Designing a new algorithm for an unsolved problem
- Optimizing an existing algorithm
- Understanding why an algorithm works (or fails)
- Choosing between algorithmic approaches
- Analyzing algorithmic complexity tradeoffs

---

## Pre-Filled Phenomenon Library

Select relevant phenomena for your algorithm:

- [ ] **Sorting** (comparison-based, non-comparison, adaptive)
- [ ] **Graph Traversal** (BFS, DFS, shortest path, minimum spanning tree)
- [ ] **Optimization** (convex, non-convex, constrained, multi-objective)
- [ ] **Approximation** (when exact solutions are intractable)
- [ ] **Randomized Algorithms** (Monte Carlo, Las Vegas)
- [ ] **Dynamic Programming** (optimal substructure, overlapping subproblems)
- [ ] **Greedy Algorithms** (local optimal choices)
- [ ] **Divide and Conquer** (problem decomposition)
- [ ] **Local Search** (hill climbing, simulated annealing)
- [ ] **Other:** ___________________

For each selected phenomenon, describe:
- **Relevant behavior:** What does this phenomenon do that relates to your algorithm?
- **Why it matters:** What insight does this phenomenon provide?

---

## Pre-Filled Tension Checklist

Identify tensions shaping your algorithm:

### Core Tensions (select all that apply)

- [ ] **Exact vs Approximate** (`T-SPE-002`)
  - Does the problem require exact solutions?
  - What approximation guarantees are acceptable?
  - What is the cost of exactness?

- [ ] **Time vs Space** (`T-CMP-013`)
  - What is the time complexity requirement?
  - What is the space complexity constraint?
  - Can you trade time for space or vice versa?

- [ ] **General vs Specialized** (`T-SPR-016`)
  - Does the algorithm work for all inputs or specific cases?
  - What is the cost of generality?
  - What optimizations are possible for special cases?

- [ ] **Deterministic vs Randomized** (`T-EXP-001`)
  - Does the algorithm need deterministic guarantees?
  - What benefits does randomization provide?
  - What are the failure probabilities?

- [ ] **Offline vs Online** (`T-STA-009`)
  - Is all input available upfront?
  - What decisions must be made without complete information?
  - What is the competitive ratio?

- [ ] **Simplicity vs Optimality** (`T-SIM-017`)
  - Is a simple, good-enough algorithm preferable?
  - What is the cost of the optimal algorithm?
  - Who will implement and maintain this?

### Additional Tensions

- [ ] **Local vs Global** (`T-LOC-004`)
- [ ] **Exploration vs Exploitation** (`T-EXP-001`)
- [ ] **Short-term vs Long-term** (`T-SHO-019`)
- [ ] **Other:** ___________________

---

## Pre-Filled Invariant Checklist

Identify invariants relevant to your algorithm:

- [ ] **Compression Reveals Structure** (`I-CRS-001`)
  - What structure in the input can be exploited?
  - How does the algorithm compress the problem space?
  - What information is preserved vs discarded?

- [ ] **Gradients Drive Movement** (`I-GDM-001`)
  - What is the optimization landscape?
  - How does the algorithm navigate the landscape?
  - What prevents getting stuck in local optima?

- [ ] **Local Rules Create Global Order** (`I-LCG-001`)
  - What local operations does the algorithm perform?
  - What global properties emerge?
  - How do you prove correctness from local rules?

- [ ] **Tradeoffs Are Inescapable** (`I-TAE-001`)
  - What tradeoffs has the algorithm explicitly accepted?
  - What lower bounds constrain the solution?
  - How do you communicate tradeoffs to users?

- [ ] **Variation Enables Selection** (`I-VES-001`)
  - How does the algorithm explore the solution space?
  - What selection mechanism identifies good solutions?
  - How does the algorithm balance exploration and exploitation?

- [ ] **Other:** ___________________

---

## Pre-Filled Mechanism Library

Select mechanisms relevant to your algorithm:

- [ ] **Divide and Conquer** (problem decomposition)
- [ ] **Dynamic Programming** (memoization, tabulation)
- [ ] **Greedy Selection** (local optimal choice)
- [ ] **Local Search** (neighborhood exploration)
- [ ] **Random Sampling** (Monte Carlo estimation)
- [ ] **Pruning** (branch and bound, alpha-beta)
- [ ] **Relaxation** (Lagrangian, linear programming)
- [ ] **Rounding** (integer programming, discretization)
- [ ] **Amortization** (aggregate analysis, potential method)
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
- (What should the algorithm do?)

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
