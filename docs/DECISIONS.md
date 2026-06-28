# Architecture Decision Records

## Purpose

Architecture Decision Records preserve the reasoning behind material technical, architectural, governance, and documentation decisions. ADRs make decisions discoverable and prevent future contributors from repeating settled debates without new evidence.

## ADR Numbering Strategy

ADRs use sequential four-digit identifiers:

```text
ADR-0000-architecture-decision-record-process.md
ADR-0001-title.md
ADR-0002-title.md
```

Numbers are never reused. Superseded ADRs remain in the repository and link to the replacing decision.

## ADR Lifecycle

1. Identify a material decision.
2. Draft an ADR using [../templates/adr-template.md](../templates/adr-template.md).
3. Review context, alternatives, consequences, and affected documents.
4. Approve, reject, or request revision.
5. Update this index, master context, changelog, and related documents.
6. Revisit the ADR when its review trigger occurs.

## ADR Status Values

- `Proposed`: The decision is under discussion.
- `Accepted`: The decision governs future work.
- `Rejected`: The decision was considered but not adopted.
- `Superseded`: A later ADR replaces the decision.
- `Deprecated`: The decision remains historically useful but should not guide new work.

## ADR Naming Convention

ADR files must use this format:

```text
ADR-0000-short-title.md
```

Use lowercase words separated by hyphens after the number.

## ADR Template

The canonical ADR structure is stored in [../templates/adr-template.md](../templates/adr-template.md). Each ADR must include status, context, decision, alternatives considered, consequences, and review trigger.

## ADR Review Workflow

ADR review should evaluate whether the decision is material enough for an ADR, whether the context is complete, whether realistic alternatives are considered, whether consequences include risks and follow-up work, and whether affected roadmap, standards, diagrams, glossary, and master context files are identified.

## ADR Approval Workflow

An ADR is accepted when maintainers agree that it is necessary, consistent with the constitution, aligned with the roadmap, and sufficiently reviewed. Accepted ADRs must be added to the ADR index.

## ADR Index

| ADR | Title | Status | Summary |
| --- | --- | --- | --- |
| [ADR-0000](../adr/ADR-0000-architecture-decision-record-process.md) | Architecture Decision Record Process | Accepted | Establishes ADR numbering, lifecycle, status values, review, and approval process. |
