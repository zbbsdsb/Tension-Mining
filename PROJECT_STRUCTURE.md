# Tension Mining — Project Structure

> Governance documentation for the Tension Mining Skill project.
> This file describes the directory layout, file dependency graph, and governance rules.

---

## Directory Tree

```
Tension-Mining/
├── README.md                           # Project overview and entry point
├── LICENSE                             # MIT License
├── SKILL.md                            # Activation skeleton (~80 lines)
├── PROJECT_STRUCTURE.md                # [THIS FILE] Governance docs
├── social-preview.png                  # Social preview image
│
├── references/
│   ├── tension-atlas.md                # 19 cataloged tensions [CORE/EXPERIMENTAL]
│   ├── invariant-atlas.md              # 12 cataloged invariants [CORE/EXPERIMENTAL]
│   ├── methodology-primer.md           # Extended methodology reference
│   ├── execution-protocol.md          # Detailed 7-phase instructions
│   ├── interface-contract.md          # Input/Output/Error handling
│   └── quality-rubric.md              # 5-dimension scoring rubric
│
├── examples/
│   ├── dialogue-example.md             # Full user-AI interaction demo
│   ├── page-rank.md                    # Case study: PageRank
│   ├── transformer.md                  # Case study: Transformer
│   ├── bitcoin.md                      # Case study: Bitcoin
│   ├── git.md                          # Case study: Git
│   ├── wikipedia.md                    # Case study: Wikipedia
│   ├── npc-society.md                  # Case study: NPC Society
│   └── agent-organization.md           # Case study: Agent Organization
│
└── templates/
    ├── _core-template.md               # Shared 7-phase workflow skeleton
    ├── algorithm-discovery.md          # Real-world phenomena
    ├── ai-agent.md                     # Domain template: AI Agent
    ├── npc-society.md                  # Domain template: NPC Society
    ├── organization.md                 # Domain template: Organization
    └── protocol-design.md              # Domain template: Protocol Design
```

---

## Dependency Graph

### Loading Hierarchy (Progressive Disclosure)

```
Activation Decision
    │
    ▼
SKILL.md (concise skeleton, ~80 lines)
    │
    ├── When loaded via "Load execution-protocol.md §N"
    │       └── references/execution-protocol.md  (7-phase instructions)
    │
    ├── When interface contract is needed
    │       └── references/interface-contract.md  (I/O spec, error handling)
    │
    ├── When Phase 7 (Destruction) is complete
    │       └── references/quality-rubric.md     (self-evaluation)
    │
    ├── When tension reference is needed
    │       └── references/tension-atlas.md
    │
    ├── When invariant reference is needed
    │       └── references/invariant-atlas.md
    │
    ├── When methodology context is needed
    │       └── references/methodology-primer.md
    │
    ├── When examples are needed
    │       └── examples/ (8 .md files)
    │
    └── When templates are needed
            └── templates/ (6 .md files)
                └── _core-template.md (shared skeleton)
                    └── domain templates reference this
```

### Case Study → Atlas Cross-References

Each case study in `examples/` references specific tensions and invariants in the atlases. The current coverage:

| Case Study | Tensions Covered | Invariants Covered |
|-----------|-----------------|-------------------|
| PageRank | T-LOC-004, T-FRE-006 | I-LCG-001, I-GDM-001 |
| Transformer | T-SYN-010, T-COM-003, T-LOC-004, T-SPE-002 | I-CRS-001, I-GDM-001 |
| Bitcoin | T-CEN-011, T-COP-015 | I-IDC-001, I-TAE-001 |
| Git | T-CON-012, T-LOC-004 | I-LCG-001, I-IDC-001 |
| Wikipedia | T-FRE-006, T-IND-007 | I-IDC-001, I-CRS-001 |
| NPC Society | T-SUR-014, T-IND-007, T-FRE-006 | I-LCG-001, I-GDM-001, I-IDC-001 |
| Agent Organization | T-AUT-005, T-CEN-011 | I-IDC-001, I-FLS-001 |

---

## Governance Rules

### 1. ID Naming Convention

- **Tensions:** `T-{DOMAIN}-{NNN}` where DOMAIN is 3 letters derived from the tension name (e.g., EXP = Exploration, LOC = Local).
- **Invariants:** `I-{DOMAIN}-{NNN}` where DOMAIN is 3 letters (e.g., LCG = Local Creates Global, CRS = Compression Reveals Structure).
- **IDs are permanent.** Once assigned, never reassign or delete. Deprecated IDs should be marked `[DEPRECATED]` rather than reused.

### 2. ID Validation Rules

- No two entries may share the same ID.
- All cross-references in one file must resolve to entries in the other atlas file.
- Before adding a new entry, verify no existing entry covers the same concept.
- When a new entry references an existing entry by ID, verify the target ID exists.

### 3. [CORE] Labeling Rules

| Label | Criteria | Action on Downgrade |
|-------|----------|---------------------|
| `[CORE]` | Validated in 3+ case studies | Required: cross-reference to 3+ supporting examples |
| `[EXPERIMENTAL]` | Theoretical grounding, limited validation | Required: at least 2 distinct domain examples |
| Unmarked | Well-defined but not validated | Acceptable as placeholder; upgrade path to EXPERIMENTAL |

### 4. Versioning

- The active version number is tracked in `SKILL.md` frontmatter (`metadata.version`).
- Major version increment: structural change to phases or design patterns.
- Minor version increment: additions to atlases, templates, or examples.
- Patch version increment: fixes, documentation clarifications, path corrections.

### 5. File Governance

| File | Owner | Update Authority | Review Required |
|------|-------|-----------------|-----------------|
| SKILL.md | Methodology author | Author only | Yes |
| tension-atlas.md | Domain researchers | PR/review | Yes (for [CORE] changes) |
| invariant-atlas.md | Domain researchers | PR/review | Yes (for [CORE] changes) |
| execution-protocol.md | Methodology author | Author only | Yes |
| interface-contract.md | Methodology author | Author only | Yes |
| quality-rubric.md | Methodology author | Author only | Yes |
| methodology-primer.md | Knowledge base | Anyone | No |
| examples/ | Contributors | Anyone | Light review |
| templates/ | Domain experts | Contributors | Light review |

### 6. Pipeline Pattern Compliance

This project follows a **Pipeline + Inversion + Generator** hybrid design pattern:

- **Pipeline:** The 7 phases must execute in strict order. No phase may be skipped.
- **Inversion:** The executor interviews the user phase-by-phase, asking one question at a time, rather than presenting all questions upfront.
- **Generator:** Output is produced using structured templates with defined sections.
- **Gate Conditions:** Each phase has a gate condition that must be met before proceeding.
- **Anti-Rationalization:** The Common Rationalizations table in SKILL.md serves as a defense against AI tendencies to skip steps.

### 7. File Loading Rules (Progressive Disclosure)

- SKILL.md is the **only file loaded at activation time**.
- Sub-files (`references/`, `examples/`, `templates/`) are loaded **on demand** based on the phase table in SKILL.md.
- Do not load multiple sections of `execution-protocol.md` at once — load only the section corresponding to the current phase.
- Load `quality-rubric.md` only after Phase 7 (Destruction) is complete.