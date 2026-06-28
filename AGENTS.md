# AI Agent Instructions

AI coding agents working in this repository must treat the handbook as the single source of truth. The repository is documentation-first. Agents must not introduce application code, backend code, frontend code, APIs, database schemas, or implementation documentation until the roadmap explicitly authorizes that work.

## Required Reading Before Work

Every agent must read these documents before making changes:

1. [docs/MASTER_CONTEXT.md](docs/MASTER_CONTEXT.md)
2. [docs/ROADMAP.md](docs/ROADMAP.md)
3. [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md)
4. [docs/CONSTITUTION.md](docs/CONSTITUTION.md)
5. [docs/STANDARDS.md](docs/STANDARDS.md)
6. [docs/DECISIONS.md](docs/DECISIONS.md)
7. The affected volume, part, chapter, ADR, template, diagram, or glossary files

## Core Operating Rules

- Follow the constitution.
- Follow the roadmap.
- Follow the architecture overview.
- Follow documentation standards.
- Preserve existing architectural decisions.
- Never rewrite completed chapters unless the task explicitly authorizes a revision.
- Never remove documentation without a documented reason and review path.
- Never violate architecture governance.
- Never add placeholder documentation, lorem ipsum, filler, or unsupported claims.
- Maintain terminology consistency with [docs/GLOSSARY.md](docs/GLOSSARY.md).
- Use internal links when referring to repository documents.
- Keep changes inside the current sprint scope.
- Stop when the sprint scope is complete.

## Required Updates After Work

Agents must update these files when their work changes project status or scope:

- [CHANGELOG.md](CHANGELOG.md)
- [docs/MASTER_CONTEXT.md](docs/MASTER_CONTEXT.md)
- [docs/ROADMAP.md](docs/ROADMAP.md), when roadmap scope, sequencing, or exit criteria change
- [docs/DECISIONS.md](docs/DECISIONS.md), when ADR state changes
- [docs/GLOSSARY.md](docs/GLOSSARY.md), when terminology changes
- Relevant diagram files under [diagrams/](diagrams/), when architecture or workflow relationships change

## Documentation Quality Rules

Agents must ensure every document has a clear purpose, audience, scope, deliverables, dependencies, and review path when those attributes are relevant. Documents should read like professional engineering handbook material, not generated notes.

## ADR Rules

Create or update ADRs when a change affects governance, architecture, documentation lifecycle, future implementation boundaries, or material technical direction. Follow [docs/DECISIONS.md](docs/DECISIONS.md) and [templates/adr-template.md](templates/adr-template.md).

## Review Rules

Before completing a task, verify that changed files align with the current sprint and roadmap, master context is current, changelog includes notable changes, cross-references are valid, diagrams are referenced where relevant, no completed chapter was overwritten accidentally, and no unsupported implementation detail was introduced.

## Completion Standard

Agent output should state what changed, how it was verified, and whether any work remains. If the sprint request says to stop at completion, do not proceed to the next sprint.
