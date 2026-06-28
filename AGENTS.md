# AI Agent Instructions

AI coding agents working in this repository must treat the handbook as the source of truth.

## Required Reading Order

1. Read [docs/MASTER_CONTEXT.md](docs/MASTER_CONTEXT.md).
2. Read [docs/ROADMAP.md](docs/ROADMAP.md).
3. Read [docs/STANDARDS.md](docs/STANDARDS.md).
4. Read affected volume, chapter, ADR, template, or glossary files.

## Operating Rules

- Never overwrite completed chapters.
- Never violate documented architecture or governance rules.
- Never create placeholder documentation.
- Never introduce lorem ipsum, filler, marketing language, or unsupported claims.
- Maintain consistent terminology from [docs/GLOSSARY.md](docs/GLOSSARY.md).
- Update [CHANGELOG.md](CHANGELOG.md) after completed work.
- Update [docs/MASTER_CONTEXT.md](docs/MASTER_CONTEXT.md) after completed tasks that change status, structure, scope, or next actions.
- Use ADRs for material architecture decisions.
- Preserve documentation-first sequencing; do not add application code until the roadmap authorizes it.

## Review Expectations

Before completing a task, verify:

- The changed files align with the roadmap.
- The master context is still accurate.
- Cross-references are correct.
- Terminology matches the glossary.
- New sections have purpose, scope, and completion criteria.
- Security, performance, and operational implications are not ignored.

## Output Standard

Agent output should be concise, factual, and traceable to repository files. Agents should state what changed, how it was verified, and what remains open.

