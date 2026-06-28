# Architecture Overview

## Documentation First Philosophy

AIFlow OS Engineering Handbook uses a documentation-first architecture. The handbook defines system purpose, domain vocabulary, governance, decision process, diagrams, review workflow, and implementation sequencing before code exists.

## Repository Architecture

The repository is organized as an engineering knowledge system: root files provide project orientation and community governance; `docs/` contains project-wide governance, architecture, lifecycle, standards, roadmap, decisions, and glossary; `volumes/` contains the book content; `adr/` contains Architecture Decision Records; `diagrams/` contains diagram sources; `templates/` contains reusable document structures; `prompts/` contains AI-assisted authoring and review prompts; `.github/` contains collaboration templates.

See [../diagrams/repository-structure.mmd](../diagrams/repository-structure.mmd).

## Future Platform Relationship

The future platform will include workflow authoring, graph execution, scheduling, workers, integrations, plugins, AI runtime, MCP mediation, enterprise governance, cloud operations, and marketplace distribution. The handbook describes these systems before they are implemented.

See [../diagrams/future-platform-relationship.mmd](../diagrams/future-platform-relationship.mmd).

## Architecture Governance

Architecture governance is enforced through the constitution, roadmap, ADRs, standards, review process, glossary, diagrams, changelog, and master context. Material decisions require ADRs.

## Versioning Strategy

The handbook uses semantic versioning. Every release should explain what changed and whether the change affects governance, roadmap, architecture, standards, diagrams, glossary, or future implementation.

## Folder Organization

- `docs/` for repository-wide rules and architectural context.
- `volumes/` for book chapters and parts.
- `adr/` for decisions.
- `diagrams/` for architecture and workflow views.
- `templates/` for repeatable structures.
- `prompts/` for AI workflow guidance.
- `assets/` for supporting publication material.
- `examples/` for future reference examples.

## Documentation Lifecycle

Documents move through planning, writing, review, approval, publishing, maintenance, deprecation, and archiving. See [docs/DOCUMENTATION_LIFECYCLE.md](DOCUMENTATION_LIFECYCLE.md) and [../diagrams/documentation-lifecycle.mmd](../diagrams/documentation-lifecycle.mmd).

## Review Workflow

Review includes architecture, technical, editorial, consistency, quality, final approval, and publishing approval. See [docs/REVIEW_PROCESS.md](REVIEW_PROCESS.md) and [../diagrams/documentation-review-workflow.mmd](../diagrams/documentation-review-workflow.mmd).

## Publishing Workflow

Publishing requires approved scope, reviewed content, updated version metadata, synchronized changelog and master context, validated diagrams, and release approval. See [../diagrams/publishing-workflow.mmd](../diagrams/publishing-workflow.mmd).

## Future Codebase Relationship

Future code must follow approved handbook architecture. If implementation reveals a missing or incorrect architecture assumption, documentation must be updated through review before the behavior becomes precedent.

## How Handbook Drives Implementation

Implementation should trace to roadmap volume and exit criteria, approved chapters and diagrams, ADRs, standards, glossary terms, and review process requirements.

## Diagram Strategy

Mermaid is the default diagram format in Sprint 002. Diagrams should be source-controlled, referenced by related documents, and reviewed alongside text. C4, sequence, ERD, and deployment-specific diagrams should use their dedicated folders when the view requires them.

## Cross Referencing Strategy

Documents should use relative links to connect governance, roadmap, standards, diagrams, ADRs, and volume content. Cross-references must be updated when files move, names change, or decisions are superseded.
