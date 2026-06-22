<p align="center">
  <img src="./social-preview.jpg" alt="Tension Mining" width="100%">
</p>

<p align="center">
  <a href="https://github.com/CeaserZhao/Tension-Mining/stargazers"><img src="https://img.shields.io/github/stars/CeaserZhao/Tension-Mining?style=flat-square&color=e63946" alt="GitHub Stars"></a>
  <a href="https://github.com/CeaserZhao/Tension-Mining/network/members"><img src="https://img.shields.io/github/forks/CeaserZhao/Tension-Mining?style=flat-square&color=f4a261" alt="GitHub Forks"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square&color=2a9d8f" alt="MIT License"></a>
  <a href="./SKILL.md"><img src="https://img.shields.io/badge/skill-v2.0-blue?style=flat-square&color=4a6fa5" alt="Skill v2.0"></a>
  <a href="./references/tension-atlas.md"><img src="https://img.shields.io/badge/tensions-19-4a6fa5?style=flat-square" alt="19 Tensions"></a>
  <a href="./references/invariant-atlas.md"><img src="https://img.shields.io/badge/invariants-12-4a6fa5?style=flat-square" alt="12 Invariants"></a>
  <a href="./examples/"><img src="https://img.shields.io/badge/cases-8_studies-6b7280?style=flat-square" alt="8 Case Studies"></a>
  <a href="https://github.com/CeaserZhao/Tension-Mining/actions"><img src="https://img.shields.io/github/actions/workflow/status/CeaserZhao/Tension-Mining/ci.yml?style=flat-square&color=2a9d8f" alt="CI Status"></a>
</p>

---

> **Most people search for solutions. Great researchers search for tensions.**

A research methodology for discovering invariants hidden inside complex systems. Works as an **AI-executable Skill** across Claude Code, TRAE, Cursor, Windsurf, and any tool that supports Markdown-based skill files.

[Quick Start](#quick-start) · [How It Works](#how-it-works) · [Case Studies](#case-studies) · [Documentation](#documentation) · [Contribute](./CONTRIBUTING.md)

---

## Table of Contents

- [Why Tension Mining?](#why-tension-mining)
- [Quick Start](#quick-start)
- [How It Works](#how-it-works)
- [The Seven Phases](#the-seven-phases)
- [Case Studies](#case-studies)
- [What This Is Not](#what-this-is-not)
- [Documentation](#documentation)
- [Roadmap](#roadmap)
- [License](#license)

---

## Why Tension Mining?

Most innovation workflows start too late.

They begin with algorithms, architectures, implementations, optimizations. But the most influential systems rarely emerge from optimization.

- **PageRank** began with a question about importance — not a matrix equation.
- **Bitcoin** began with a tension between decentralization and trust — not a blockchain data structure.
- **Wikipedia** began with a tension between openness and reliability — not a revision control system.
- **Transformer** began with a question about whether recurrence was necessary at all — not an attention mechanism.

The breakthrough appears long before the algorithm. It appears when a hidden tension is finally made visible.

**Tension Mining is a lens.** Its purpose is simple: help researchers discover the forces shaping a system before attempting to design the system itself.

### The Core Idea

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

## Case Studies

Each case study walks through the full 7-phase pipeline:

| Case Study | Domain | Key Tensions | Key Invariants |
|-----------|--------|-------------|----------------|
| [PageRank](./examples/page-rank.md) | Information Retrieval | Local vs Global, Freedom vs Efficiency | Local Rules Create Global Order, Gradients Drive Movement |
| [Transformer](./examples/transformer.md) | Deep Learning | Synchronicity vs Asynchronicity, Compression vs Fidelity | Compression Reveals Structure, Gradients Drive Movement |
| [Bitcoin](./examples/bitcoin.md) | Cryptocurrency | Centralization vs Decentralization, Competition vs Cooperation | Identity Drives Cooperation, Tradeoffs Are Inescapable |
| [Git](./examples/git.md) | Version Control | Consistency vs Availability, Local vs Global | Local Rules Create Global Order, Identity Drives Cooperation |
| [Wikipedia](./examples/wikipedia.md) | Collaborative Knowledge | Freedom vs Efficiency, Individual vs Collective | Identity Drives Cooperation, Compression Reveals Structure |
| [NPC Society](./examples/npc-society.md) | Multi-Agent Systems | Survival vs Exploration, Individual vs Collective | Local Rules Create Global Order, Variation Enables Selection |
| [Agent Organization](./examples/agent-organization.md) | AI Coordination | Autonomy vs Control, Centralization vs Decentralization | Identity Drives Cooperation, Feedback Loops Stabilize |
| [Dialogue Walkthrough](./examples/dialogue-example.md) | Decentralized Identity | *Full 7-phase interaction demo* | *Recommended first read* |

---

## What This Is Not

- **Not** a prompt collection
- **Not** a brainstorming template
- **Not** a productivity framework
- **Not** a guaranteed path to innovation
- **Not** a visual design system

Tension Mining is a lens. Its purpose is simple: help researchers discover the forces shaping a system before attempting to design the system itself.

---

## Documentation

| Path | Purpose |
|------|---------|
| [`SKILL.md`](./SKILL.md) | Activation skeleton — the AI entry point (~80 lines) |
| [`references/execution-protocol.md`](./references/execution-protocol.md) | Detailed 7-phase instructions (Goal / Interview / Output / Gate) |
| [`references/interface-contract.md`](./references/interface-contract.md) | Input/output specification and error handling |
| [`references/quality-rubric.md`](./references/quality-rubric.md) | 5-dimension scoring rubric (D1-D5, 0-15 scale) |
| [`references/tension-atlas.md`](./references/tension-atlas.md) | Catalog of 19 persistent tensions across 5 domains |
| [`references/invariant-atlas.md`](./references/invariant-atlas.md) | Catalog of 12 cross-domain invariants across 4 layers |
| [`references/methodology-primer.md`](./references/methodology-primer.md) | Extended methodology reference & FAQ |
| [`examples/dialogue-example.md`](./examples/dialogue-example.md) | Full user-AI dialogue walkthrough (**recommended first read**) |
| [`examples/`](./examples/) | 7 additional case studies |
| [`templates/_core-template.md`](./templates/_core-template.md) | Shared 7-phase workflow skeleton |
| [`templates/`](./templates/) | 5 domain-specific templates (Algorithm, AI Agent, NPC Society, Organization, Protocol) |
| [`PROJECT_STRUCTURE.md`](./PROJECT_STRUCTURE.md) | Directory layout, dependency graph, governance rules |
| [`CONTRIBUTING.md`](./CONTRIBUTING.md) | How to contribute tensions, invariants, cases, and templates |
| [`CHANGELOG.md`](./CHANGELOG.md) | Version history |

---

## Roadmap

### v2.0 (Current)
- [x] 7-phase pipeline with gate conditions
- [x] Progressive Disclosure architecture
- [x] Atlas with [CORE]/[EXPERIMENTAL] labeling
- [x] 5 domain-specific templates
- [x] 8 case studies
- [x] Quality rubric (D1-D5)
- [x] CI/CD with automated atlas validation
- [x] Anti-Rationalization defense mechanisms

### v2.1 (Planned)
- [ ] Interactive web demo
- [ ] Additional case studies (Distributed Systems, Biological Systems, Economics)
- [ ] Template expansion (API Design, Consensus Protocols, Game Design)
- [ ] Community-contributed tensions and invariants
- [ ] Multi-language support (Chinese, Japanese)

---

## One Question

Before designing anything, ask:

> What tension am I actually looking at?

The answer is often more valuable than the algorithm.

---

## License

MIT License — Copyright (c) 2026 CeaserZhao

See [LICENSE](./LICENSE) for details.
