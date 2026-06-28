# Master Context

## Project Summary

AIFlow OS Engineering Handbook is a documentation-first repository for designing an AI-native workflow automation platform. It will guide future work across workflow authoring, execution, scheduling, integrations, plugin development, AI runtime services, MCP capabilities, enterprise governance, cloud operations, and marketplace distribution.

## Repository Purpose

The repository exists to be the single source of truth for the future AIFlow OS platform. It defines architecture, terminology, governance, documentation standards, review workflows, release discipline, and implementation sequencing before application code is introduced.

## Current Version

`v0.2.0`

## Current Sprint

Sprint 002: Handbook Governance and Documentation Framework.

## Completed Milestones

- Sprint 001 initialized the documentation-first repository foundation.
- Sprint 002 established constitution-level governance, documentation lifecycle, review process, ADR process, expanded standards, Mermaid diagrams, GitHub community templates, and Volume 1 part structure.

## Current Volume

Volume 1: Foundation.

## Current Repository Structure

```text
.
|-- README.md
|-- AGENTS.md
|-- CHANGELOG.md
|-- CODE_OF_CONDUCT.md
|-- CONTRIBUTING.md
|-- LICENSE
|-- SECURITY.md
|-- docs/
|-- volumes/
|-- adr/
|-- templates/
|-- prompts/
|-- diagrams/
|-- assets/
|-- examples/
`-- .github/
```

## Current Architecture Summary

The handbook uses a documentation-first architecture. Project-wide governance lives in `docs/`; handbook content lives in `volumes/`; material decisions live in `adr/`; diagrams live in `diagrams/`; reusable structures live in `templates/`; AI workflow prompts live in `prompts/`; collaboration templates live in `.github/`.

Future implementation must be driven by approved handbook material, ADRs, diagrams, glossary terms, and roadmap exit criteria.

## Technology Decisions

- Markdown is the primary documentation format.
- Mermaid is the default text-based diagram format.
- Draw.io and PlantUML may be introduced when the standards in [docs/STANDARDS.md](STANDARDS.md) are followed.
- Semantic versioning governs handbook releases.
- ADRs govern material architecture and governance decisions.
- GitHub issue and pull request templates guide public collaboration.

## Documentation Decisions

- The handbook remains documentation-only through Sprint 002.
- Volume 1 is structured before full chapter authoring.
- New implementation details require roadmap support and, when material, ADR approval.
- Master context and changelog must be updated after every completed sprint.
- Diagrams are source files in the repository and must be referenced from relevant documents.

## Completed Documents

- [README.md](../README.md)
- [AGENTS.md](../AGENTS.md)
- [CHANGELOG.md](../CHANGELOG.md)
- [docs/CONSTITUTION.md](CONSTITUTION.md)
- [docs/MASTER_CONTEXT.md](MASTER_CONTEXT.md)
- [docs/ROADMAP.md](ROADMAP.md)
- [docs/ARCHITECTURE.md](ARCHITECTURE.md)
- [docs/DECISIONS.md](DECISIONS.md)
- [docs/STANDARDS.md](STANDARDS.md)
- [docs/DOCUMENTATION_LIFECYCLE.md](DOCUMENTATION_LIFECYCLE.md)
- [docs/REVIEW_PROCESS.md](REVIEW_PROCESS.md)
- [docs/GLOSSARY.md](GLOSSARY.md)
- [adr/ADR-0000-architecture-decision-record-process.md](../adr/ADR-0000-architecture-decision-record-process.md)

## Pending Documents

- Full Volume 1 chapters.
- Additional ADRs for implementation boundary, diagram governance, and release publishing policy when required.
- Detailed bibliography and external reference policy examples.
- Future volume READMEs after Volume 1 completion criteria are met.

## Known Risks

- The handbook may become inconsistent if glossary terms are not actively maintained.
- Future implementation pressure may attempt to bypass documentation-first governance.
- Diagrams may drift from written architecture unless review checks enforce synchronization.
- ADRs may be skipped for material decisions unless maintainers enforce the threshold.

## Current Priorities

1. Preserve governance established in Sprint 002.
2. Complete Volume 1 chapters in a controlled sequence.
3. Keep roadmap, master context, changelog, and diagrams synchronized.
4. Maintain publication-quality writing and review standards.

## Upcoming Milestones

- Sprint 003: Expand Volume 1 Chapter 1, Project Vision.
- Sprint 004: Expand product requirements and non-goals.
- Sprint 005: Develop market and competitor analysis.
- Sprint 006: Complete feature matrix and Volume 1 review.

## Glossary References

The current glossary defines workflow, node, edge, execution, scheduler, worker, AI agent, LLM, prompt, memory, MCP, connector, plugin, integration, workspace, organization, tenant, execution engine, vector database, knowledge base, trigger, action, credential, and runbook.

## Architecture Status

Architecture governance is active. No platform implementation architecture has been approved beyond high-level future platform relationship. No application code is authorized.

## Repository Statistics

- Current version: `v0.2.0`.
- Active volume: Volume 1.
- Planned volumes: 10.
- Active ADRs: 1.
- Mermaid diagrams added in Sprint 002: 7.
- Application code directories: 0.

## Next Sprint Preview

The next sprint should expand Volume 1 Chapter 1: Project Vision. It should define problem statement, audience, platform thesis, goals, non-goals, success criteria, and relationship to the roadmap. It should not start implementation.
