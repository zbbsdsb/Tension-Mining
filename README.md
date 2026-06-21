<p align="center">
  <img src="./social-preview.png" alt="Tension Mining" width="800">
</p>

<p align="center">
  <a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="MIT License"></a>
  <a href="./SKILL.md"><img src="https://img.shields.io/badge/skill-v2.0-blue?style=flat-square" alt="Skill v2.0"></a>
  <a href="./references/tension-atlas.md"><img src="https://img.shields.io/badge/atlas-19_tensions-4a6fa5?style=flat-square" alt="Tensions"></a>
  <a href="./references/invariant-atlas.md"><img src="https://img.shields.io/badge/atlas-12_invariants-4a6fa5?style=flat-square" alt="Invariants"></a>
  <a href="./examples/"><img src="https://img.shields.io/badge/cases-8_studies-6b7280?style=flat-square" alt="Case Studies"></a>
</p>

---

> Most people search for solutions. Great researchers search for tensions.

A research methodology for discovering invariants hidden inside complex systems. Works as an AI-executable Skill across Claude Code, TRAE, Cursor, Windsurf, and any tool that supports Markdown-based skill files.

---

## Quick Start

### 1. Install

Clone this repository into your AI tool's skill directory:

```bash
# Claude Code — project-level (recommended)
git clone https://github.com/CeaserZhao/Tension-Mining.git .claude/skills/tension-mining

# Claude Code — user-level (all projects)
git clone https://github.com/CeaserZhao/Tension-Mining.git ~/.claude/skills/tension-mining

# TRAE
git clone https://github.com/CeaserZhao/Tension-Mining.git .trae/skills/tension-mining

# Cursor / Windsurf / other
# Place the repo anywhere accessible. Reference SKILL.md in your project instructions.
```

### 2. Use

**Automatic trigger** — describe a complex system problem in natural language:

> "I want to design a decentralized identity system for a P2P marketplace."

The AI detects the trigger and activates Tension Mining automatically.

**Manual trigger** — invoke the skill directly:

| Tool | Command |
|------|---------|
| Claude Code | `/tension-mining` |
| TRAE | AI auto-activates based on SKILL.md description |
| Cursor / Windsurf | Reference `SKILL.md` in your `.cursorrules` or project instructions |

### 3. Follow the 7 Phases

The AI will guide you through 7 phases, asking one question at a time:

```
1. Phenomenon Mining  →  Collect 5-10 real-world examples from 3+ domains
2. Tension Mining      →  Identify 5+ ineliminable tradeoffs
3. Invariant Mining    →  Extract 3+ cross-domain principles
4. Mechanism Mining    →  Study how reality resolves these tensions
5. System Synthesis    →  Combine into a coherent model
6. Algorithm Synthesis →  Derive algorithms from mechanisms (only now)
7. Destruction Phase   →  Attack your own model
```

**Core principle:** Do not start from solutions. Start from reality.

---

## How It Works

### Design Patterns

Tension Mining uses a **Pipeline + Inversion + Generator** hybrid pattern:

- **Pipeline** — 7 phases execute in strict order. Each phase has a gate condition; you cannot proceed until it is met.
- **Inversion** — The AI interviews you phase-by-phase, asking one question at a time. You drive the content; the AI enforces the methodology.
- **Generator** — Output follows a structured template with defined sections, ensuring completeness.

### Anti-Cheat Mechanisms

- **Common Rationalizations table** — counters AI's tendency to skip steps ("I already know the tensions, let's skip to the algorithm")
- **Red Flags** — observable behaviors that indicate the methodology is being violated
- **Quality Rubric** — 5-dimension self-evaluation (D1-D5, score 0-15) appended to every output

### Progressive Disclosure

`SKILL.md` is a concise activation skeleton (~80 lines). Detailed phase instructions, atlases, and templates are loaded on demand, keeping initial context minimal.

---

## Why Tensions?

Most innovation workflows start too late.

They begin with algorithms, architectures, implementations, optimizations. But the most influential systems rarely emerge from optimization.

- **PageRank** began with a question about importance.
- **Bitcoin** began with a tension between decentralization and trust.
- **Wikipedia** began with a tension between openness and reliability.
- **Transformer** began with a question about whether recurrence was necessary at all.

The breakthrough often appears long before the algorithm. It appears when a hidden tension is finally made visible.

---

## Core Idea

Every persistent system is shaped by a set of unresolved tensions.

| Domain | Tension |
|--------|---------|
| Organization | Freedom ↔ Efficiency |
| Society | Order ↔ Innovation |
| AI Agents | Autonomy ↔ Control |
| NPC Worlds | Survival ↔ Exploration |
| Products | Simplicity ↔ Capability |
| Markets | Competition ↔ Cooperation |

Most people focus on behavior. Tension Mining focuses on the forces underneath behavior.

---

## The Seven Phases

### 1. Phenomenon Mining

> What systems already exhibit this behavior?

Observe reality before building abstractions. Build a phenomenon library from ant colonies, companies, cities, ecosystems, online communities, open source projects.

### 2. Tension Mining

> What tradeoff can never be completely eliminated?

Identify forces pulling the system in different directions. Build a tension map.

### 3. Invariant Mining

> What remains true regardless of domain?

Search for patterns that appear across unrelated systems. Extract invariants.

### 4. Mechanism Mining

> What mechanisms already exist in nature, society, or technology?

Study how reality resolves tensions. Build a mechanism library.

### 5. System Synthesis

> What is the smallest model that explains the system?

Combine tensions, invariants, and mechanisms into a coherent model. Identify which tensions are primary, which mechanisms are essential, and what failure modes exist.

### 6. Algorithm Synthesis

> If the mechanism is real, how should it be implemented?

Only now design algorithms. Allow them to emerge naturally from mechanisms.

### 7. Destruction Phase

> What assumptions fail? What edge cases break the system?

Attack the model. Assume it is wrong. Identify weak assumptions, missing tensions, and possible redesigns.

---

## What This Is Not

- **Not** a prompt collection
- **Not** a brainstorming template
- **Not** a productivity framework
- **Not** a guaranteed path to innovation
- **Not** a visual design system

Tension Mining is a lens. Its purpose is simple: help researchers discover the forces shaping a system before attempting to design the system itself.

---

## Repository Navigation

| Path | Purpose |
|------|---------|
| [`SKILL.md`](./SKILL.md) | Activation skeleton — the AI entry point (~80 lines) |
| [`references/execution-protocol.md`](./references/execution-protocol.md) | Detailed 7-phase instructions (Goal / Interview / Output / Gate) |
| [`references/interface-contract.md`](./references/interface-contract.md) | Input/output specification and error handling |
| [`references/quality-rubric.md`](./references/quality-rubric.md) | 5-dimension scoring rubric (D1-D5, 0-15 scale) |
| [`references/tension-atlas.md`](./references/tension-atlas.md) | Catalog of 19 persistent tensions across domains |
| [`references/invariant-atlas.md`](./references/invariant-atlas.md) | Catalog of 12 cross-domain invariants |
| [`references/methodology-primer.md`](./references/methodology-primer.md) | Extended methodology reference |
| [`examples/dialogue-example.md`](./examples/dialogue-example.md) | Full user-AI dialogue walkthrough (recommended first read) |
| [`examples/`](./examples/) | 7 additional case studies |
| [`templates/_core-template.md`](./templates/_core-template.md) | Shared 7-phase workflow skeleton |
| [`templates/`](./templates/) | 5 domain-specific templates (Algorithm, AI Agent, NPC Society, Organization, Protocol) |
| [`PROJECT_STRUCTURE.md`](./PROJECT_STRUCTURE.md) | Directory layout, dependency graph, governance rules |

---

## One Question

Before designing anything, ask:

> What tension am I actually looking at?

The answer is often more valuable than the algorithm.

---

## License

MIT License - Copyright (c) 2026 CeaserZhao
