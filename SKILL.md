---
name: tension-mining
description: >
  Discover invariants hidden inside complex systems by mining tensions across reality, phenomena, and mechanisms.
  Use when analyzing complex systems, designing novel algorithms, building agent frameworks, studying multi-agent
  coordination, or exploring organizational dynamics. Not for simple optimization tasks or known-solution problems.
user-invocable: true
version: "2.0"
# --- Extended metadata (not parsed by skill loaders, kept for documentation) ---
# author: zbbsdsb
# domain: complex-systems-research
# methodology: tension-driven-discovery
# phases: 7
# patterns: [pipeline, inversion, generator]
# quality_rubric: references/quality-rubric.md
# interface_contract: references/interface-contract.md
---

# Tension Mining — Activation Protocol

## Core Principle

Do not start from solutions. Do not start from architectures. Do not start from algorithms.
Start from reality. Move through the layers: Reality → Phenomena → Tensions → Invariants → Mechanisms → System → Algorithm.

## When to Use

- User asks about "fundamental forces", "tradeoffs", or "tensions" in a system
- User begins designing a protocol, algorithm, or multi-agent system from scratch
- User is exploring "why" a system behaves as it does, not just "how"
- User mentions a complex system with observable opposing forces
- Research question involves cross-domain pattern recognition

## When NOT to Use

- User needs simple implementation or code review
- Problem has a well-defined known optimal solution
- User needs incremental optimization of an existing system
- Time constraints prevent deep exploration (< 1 hour expected)

## Common Rationalizations

| Rationalization | Reality |
|----------------|---------|
| "I already know the tensions, let's skip to the algorithm" | Algorithms discovered without tension analysis are solutions to the wrong problem. Follow the phases. |
| "This system is simple, I don't need 7 phases" | Simple systems reveal the same tensions as complex ones. A lightweight 3-phase analysis (Phases 1-3) is acceptable but must be explicit. |
| "I can identify tensions while designing the algorithm" | Tension identification requires a separate, focused phase. Attempting both simultaneously biases the tension discovery. |
| "The atlas covers all tensions, I just need to pick from it" | The atlas is a reference, not a substitute for original analysis. Each system has unique tensions. |

## Red Flags

If any of these occur during execution, the skill is not being followed correctly:
- Phase 1 output contains algorithm ideas or implementation details
- Phase 2 tensions are merely "pros vs cons" rather than ineliminable tradeoffs
- Phase 3 invariants are domain-specific (only from the target domain)
- Phase 6 executed before Phase 5 is complete
- Phase 7 omitted entirely

## 7-Phase Structure (Pipeline)

Execute strictly in order. Do not skip phases. Do not proceed past a phase until the user confirms.

| # | Phase | Load | Gate Condition |
|---|-------|------|----------------|
| 1 | **Phenomenon Mining** | Load execution-protocol.md §1 | 5-10 phenomena from 3+ domains collected |
| 2 | **Tension Mining** | Load execution-protocol.md §2 | 5+ tensions with Force A/B identified |
| 3 | **Invariant Mining** | Load execution-protocol.md §3 | 3+ cross-domain principles extracted |
| 4 | **Mechanism Mining** | Load execution-protocol.md §4 | 3+ mechanisms mapped |
| 5 | **System Synthesis** | Load execution-protocol.md §5 | Coherent system model built |
| 6 | **Algorithm Synthesis** | Load execution-protocol.md §6 | Algorithm candidates derived from mechanisms |
| 7 | **Destruction Phase** | Load execution-protocol.md §7 + quality-rubric.md | Failure analysis + self-evaluation complete |

## Quick Reference

- **Interface Contract:** `references/interface-contract.md`
- **Execution Protocol (detailed phase instructions):** `references/execution-protocol.md`
- **Quality Rubric (self-evaluation):** `references/quality-rubric.md`
- **Tension Atlas:** `references/tension-atlas.md`
- **Invariant Atlas:** `references/invariant-atlas.md`
- **Examples:** `examples/` (10 case studies + 1 dialogue example)
- **Templates:** `templates/` (9 domain templates)

## Tool Activation

Each AI platform activates this skill differently. Choose your platform below:

| Platform | Mechanism | Command / Setup |
|----------|-----------|-----------------|
| Claude Code | Auto-detect via SKILL.md description; explicit `/tension-mining` | `git clone ... .claude/skills/tension-mining` |
| TRAE | Auto-discover from `.trae/skills/` | `git clone ... .trae/skills/tension-mining` |
| Cursor | Reference SKILL.md in `.cursorrules` | Add: *"When analyzing complex systems... follow ./path/to/SKILL.md"* |
| Windsurf | Reference SKILL.md in `.windsurfrules` | Same as Cursor |
| Statuz | `statuz unite skill` | `statuz unite skill https://github.com/zbbsdsb/Tension-Mining.git` |

### Platform-Specific Notes

- **Claude Code**: Best for deep 7-phase analysis. Supports interruption and phase confirmation.
- **TRAE**: Best for multi-file research with Explore agent. Use `general_purpose_task` sub-agent for Phase 6-7 execution.
- **Cursor / Windsurf**: Best for Phase 4-5-6 (mechanism → system → algorithm). Read `tension-atlas.md` and `invariant-atlas.md` first.
- **Statuz**: Auto-activates on matching system descriptions. Supports partial phase execution.