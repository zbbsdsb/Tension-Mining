# Contributing to Tension Mining

Contributions are welcome! This project is an open methodology for analyzing
complex systems through the lens of persistent tensions and cross-domain
invariants.

## Quick Start

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/my-contribution`)
3. Run the atlas validation script: `python scripts/validate-atlas.py`
4. Commit your changes and open a [Pull Request](./.github/PULL_REQUEST_TEMPLATE.md)

### Issue Templates

Before starting work, consider opening an issue using the appropriate template:

- [New Tension](https://github.com/zbbsdsb/Tension-Mining/issues/new?template=new-tension.yml) — Submit a new persistent tension
- [New Invariant](https://github.com/zbbsdsb/Tension-Mining/issues/new?template=new-invariant.yml) — Submit a new cross-domain invariant
- [New Case Study](https://github.com/zbbsdsb/Tension-Mining/issues/new?template=new-case-study.yml) — Propose a new case study

## Adding a New Tension

Follow the rules defined in [`PROJECT_STRUCTURE.md`](./PROJECT_STRUCTURE.md)
and the extension guide at the bottom of [`references/tension-atlas.md`](./references/tension-atlas.md).

Key requirements:

- Assign a unique ID matching the format `T-{3-letter-domain}-{3-digit-number}`
- Include all required fields: Force A, Force B, Definition, Why ineliminable,
  Cross-domain examples, Over-optimization consequences, Related invariants
- Mark as `[EXPERIMENTAL]` initially; do not use `[CORE]` unless validated
  in 3+ case studies
- Update related invariant entries with back-references
- Run `python scripts/validate-atlas.py` before committing

## Adding a New Invariant

Follow the extension guide at the bottom of
[`references/invariant-atlas.md`](./references/invariant-atlas.md).

Key requirements:

- Assign a unique ID matching the format `I-{3-letter-domain}-{3-digit-number}`
- Include all required fields: Statement, Supporting phenomena, Mechanism
  explanation, Mathematical intuition, Boundary conditions, Related tensions,
  Related cases
- The invariant must be cross-domain (at least 3 distinct domains)
- Mark as `[EXPERIMENTAL]` initially
- Update related tension entries with back-references
- Run `python scripts/validate-atlas.py` before committing

## Adding a Case Study or Template

- Place case studies in `examples/` following the naming convention
  `examples/{topic-name}.md`
- Place templates in `templates/` following the naming convention
  `templates/{domain-name}.md`
- Use `templates/_core-template.md` as the structural skeleton
- Reference the case study from relevant tension and invariant entries

## [CORE] Promotion Criteria

An entry may be upgraded from `[EXPERIMENTAL]` to `[CORE]` when:

1. It has been applied and validated in **3 or more** distinct case studies
2. The case studies span at least **2 different domains**
3. The validation evidence is documented in the case study files

## PR Checklist

Before submitting a Pull Request, ensure:

- [ ] `python scripts/validate-atlas.py` exits with code 0
- [ ] No redundant atlas files exist in the repository root
- [ ] All new IDs follow the `{T|I}-{3-letters}-{3-digits}` format
- [ ] All cross-references are bidirectional (tension <-> invariant)
- [ ] New entries include the `[EXPERIMENTAL]` marker unless CORE criteria are met
