# Tension Mining — Graduate Workshop Module

## Overview

**Duration:** 90 minutes
**Target Audience:** Graduate students in computer science, information science, or related fields
**Prerequisites:** Basic systems thinking concepts; no prior Tension Mining experience required.

**Learning Objectives**
By the end of this workshop, students will be able to:
1. Collect real-world phenomena from multiple domains related to a chosen complex system.
2. Identify underlying tensions (Force A vs Force B) from observed phenomena.
3. Extract cross-domain invariants — principles that persist across seemingly unrelated domains.
4. Self-evaluate analysis quality using the D1–D5 rubric.

**Core Methodology Reference**
This workshop covers Phases 1–3 (Reality, Phenomena, Tensions) and evaluation rubric (Phase 7) of the 7-phase Tension Mining methodology. Full reference: `references/methodology-primer.md` and `references/quality-rubric.md`.

---

## Session Plan

| Time | Activity | Format |
|------|----------|--------|
| 0–10 min | **Introduction:** Tension Mining overview, 7-phase method, key concepts (phenomena, tensions, invariants), historical motivation (PageRank, Bitcoin, Transformer). | Lecture |
| 10–25 min | **Exercise 1: Phenomenon Collection.** Groups select a topic, collect 5–7 phenomena from 3+ domains. | Group work (3–4 students) |
| 25–40 min | **Exercise 2: Tension Identification.** Groups identify 3–5 tensions as "Force A vs Force B," prepare 2-min verbal brief. | Group work + brief report |
| 40–55 min | **Exercise 3: Invariant Extraction.** Groups extract recurring cross-domain principles with supporting evidence. | Group work + brief report |
| 55–70 min | **Exercise 4: Self-Evaluation.** Individuals score their group's output using D1–D5 rubric; class discussion on disagreements. | Individual + class discussion |
| 70–80 min | **Discussion: Cross-Domain Patterns.** Facilitated conversation comparing invariants across topics. | Facilitated |
| 80–90 min | **Wrap-Up and Further Reading.** Summary, reading list distribution, connection to full methodology (Phases 4–7 for independent study). | Summary |

---

## Exercise Templates

### Exercise 1: Phenomenon Collection

**Goal:** Gather 5–7 observable real-world phenomena from at least 3 distinct domains, all related to a chosen topic.

**Instructions**
1. Your group receives one of the three topics below.
2. Brainstorm observable patterns, behaviors, or outcomes related to the topic.
3. Ensure phenomena span **at least 3 domains** (e.g., technology, economics, psychology, biology, sociology).
4. Record each phenomenon with a one-sentence description and its domain label.
5. Include at least one surprising or counterintuitive phenomenon.

*Template:*
```
Phenomenon 1: [one-sentence description]
Domain: [...]

Phenomenon 2: [...]
...
```

**Topic A: Social Media Algorithms**
*Guiding questions:* What observable patterns exist in content recommendation? How do users behave differently across platforms? What economic or psychological effects are visible? Are there analogies in non-digital systems (gossip networks, ancient marketplaces)?

**Topic B: Urban Transportation**
*Guiding questions:* What recurring traffic patterns exist in cities? How do transportation modes interact? What economic or environmental side effects are visible? Are there analogies in data routing or blood circulation?

**Topic C: Academic Publishing**
*Guiding questions:* What patterns exist in research production, review, and dissemination? How do incentive structures shape researcher behavior? What inequalities or inefficiencies are observable? Are there analogies in fashion trends or patent systems?

---

### Exercise 2: Tension Identification

**Goal:** From your collected phenomena, identify 3–5 productive tensions — tradeoffs between two forces (Force A vs Force B) that cannot be permanently eliminated.

**Instructions**
1. Review your phenomena. Look for recurring tradeoffs or situations where improving one aspect worsens another.
2. For each tension, name **Force A** and **Force B**, explain *why* it is ineliminable, and list supporting phenomena.
3. Prepare a 2-min verbal brief: state your top 2–3 tensions with one supporting phenomenon each.

*Guiding questions:* When optimizing for Force A, what negative consequences appear? When optimizing for Force B, what degrades? Have attempted solutions historically failed? Is this tension present in more than one domain?

*Template:*
```
Tension 1:
  Force A: [description]
  Force B: [description]
  Why ineliminable: [explanation]
  Supporting phenomena: [IDs]
Tension 2: ...
```

*Example format:*
```
Tension: Personalization vs Diversity
  Force A: Algorithms optimized for individual preferences maximize engagement.
  Force B: Excessive personalization creates filter bubbles, reduces serendipity.
  Why ineliminable: Relevance and discovery cannot be simultaneously maximized with finite attention.
  Supporting phenomena: P1, P3, P5
```

---

### Exercise 3: Invariant Extraction

**Goal:** Extract **cross-domain invariants** — principles that appear valid across multiple domains.

**Instructions**
1. Examine your tensions and phenomena for recurring patterns.
2. State each invariant as a general principle (e.g., "In any system with X, Y inevitably emerges").
3. List at least 2 supporting phenomena from **distinct domains** per invariant.
4. Note a boundary condition: when might this invariant *not* apply?
5. Prepare a 2-min verbal brief: state your top 1–2 invariants and cross-domain evidence.

*Guiding questions:* What principle connects phenomena from different domains? If you removed domain-specific details, what abstract statement remains? Can you think of a counterexample? Would this principle hold 100 years ago and 100 years from now?

*Template:*
```
Invariant 1:
  Statement: [general principle]
  Supporting phenomena: [P1 (domain X), P3 (domain Y), ...]
  Boundary condition: [when it might not hold]
Invariant 2: ...
```

*Example format:*
```
Invariant: Relevance-Diversity Tradeoff
  Statement: Any system mediating information between producers and consumers faces a fundamental tradeoff between individual relevance and content diversity.
  Supporting phenomena: Social media filter bubbles (technology); academic citation preferences (sociology); retail shelf allocation (economics).
  Boundary condition: May not apply when the information space is small enough for exhaustive exploration.
```

---

### Exercise 4: Self-Evaluation (D1–D5)

**Goal:** Individually evaluate your group's output using the D1–D5 rubric, then discuss scoring disagreements as a class.

**Instructions**
1. Score your group's output for D1 (Phenomenon Quality), D2 (Tension Depth), and D3 (Invariant Validity). D4 and D5 are reference only.
2. Write a 1–2 sentence justification for each score.
3. Share scores with the class. When disagreements arise, discuss: what would it take to reach consensus?
4. Identify one concrete improvement if given another 15 minutes.

**D1–D5 Scoring Rubric**

| Dimension | Score | Criteria |
|-----------|-------|----------|
| **D1: Phenomenon Quality** | 0 | No phenomena or only 1 domain |
| | 1 | 3–5 phenomena from 2 domains |
| | 2 | 5–10 phenomena from 3+ domains |
| | 3 | 10+ phenomena from 4+ domains, including surprising cross-domain analogy |
| **D2: Tension Depth** | 0 | Fewer than 3 tensions, or merely "pros vs cons" |
| | 1 | 3–4 tensions with Force A/B clearly distinguished |
| | 2 | 5+ tensions with cross-domain examples and over-optimization consequences |
| | 3 | Tensions include "why ineliminable" reasoning and mapping to invariants |
| **D3: Invariant Validity** | 0 | No invariants, or domain-specific only |
| | 1 | 1–2 invariants with supporting phenomena from 2 domains |
| | 2 | 3+ invariants each from 3+ distinct domains |
| | 3 | Invariants include boundary conditions and falsifiable claims |

*Note: D4 (Mechanism Map) and D5 (Destruction Depth) are not covered in this workshop. See `references/quality-rubric.md` for full criteria.*

*Self-evaluation template:*
```
D1: [0–3] — Justification: [...]
D2: [0–3] — Justification: [...]
D3: [0–3] — Justification: [...]
Improvement if given 15 more minutes: [...]
```

**Overall Interpretation (D1–D3)**

| Total | Rating |
|-------|--------|
| 7–9 | Strong for a 90-min session |
| 4–6 | Solid start; more cross-domain work needed |
| 0–3 | Revisit phenomena collection |

---

## Instructor Notes

### Preparation Tips
1. **Pre-reading:** Assign glossary terms (phenomenon, tension, invariant) from `references/methodology-primer.md` before the session.
2. **Groups:** 3–4 students per group. Distribute the three topics evenly so cross-topic discussion has diverse material.
3. **Timing:** Each segment is tight. Use a visible timer; give 2-min warnings before transitions.
4. **Materials:** Provide printed/digital copies of exercise templates. Whiteboards or shared documents work best.

### Common Pitfalls to Watch For
- **Narrow phenomena:** Students may list from only one domain. Intervene: "Can you find analogous patterns in biology or economics?"
- **Tensions as "problems":** Remind students that tensions are tradeoffs, not problems. "Engagement drops when content is diverse" should be reframed as a *personalization vs diversity* tension.
- **Vague invariants:** "Everything is connected" is not useful. Push for specificity: "Connected in what way? What pattern repeats?"
- **Confusing invariants with mechanisms:** Invariants are *what always happens*; mechanisms are *how* it is achieved. This workshop covers only invariants.

### Discussion Guiding Questions (70–80 min)
- "Did any two groups on different topics discover a similar invariant?"
- "Which tension felt most universal? Which most domain-specific?"
- "If you had to defend one invariant to a skeptical researcher, which would you choose?"
- "What phenomenon surprised your group most?"
- "How would D1–D3 scores differ if we required 10 phenomena from 4 domains?"

### Adapting for Class Size
- **Small (6–10):** Run as a single plenary group with whole-class participation.
- **Large (30+):** Add a 5-min "gallery walk" between Exercise 2 and 3 where groups post tensions and read others' work.

---

## Further Reading

1. Tension Mining methodology primer — `references/methodology-primer.md` in this repository.
2. Tension Mining quality rubric — `references/quality-rubric.md` in this repository.
3. Meadows, D. H. (2008). *Thinking in Systems: A Primer*. Chelsea Green Publishing.
4. Page, S. E. (2018). *The Model Thinker: What You Need to Know to Make Data Work for You*. Basic Books.
5. Holland, J. H. (1995). *Hidden Order: How Adaptation Builds Complexity*. Addison-Wesley.
6. Simon, H. A. (1962). "The Architecture of Complexity." *Proceedings of the American Philosophical Society*, 106(6), 467–482.
7. Axelrod, R. (1997). *The Complexity of Cooperation*. Princeton University Press.
8. Norman, D. A. (2013). *The Design of Everyday Things: Revised and Expanded Edition*. Basic Books.
9. Kuhn, T. S. (1962). *The Structure of Scientific Revolutions*. University of Chicago Press.
10. Arthur, W. B. (2015). *Complexity and the Economy*. Oxford University Press.

---

*Document version: 1.0 — Last updated: 2026-06-23*