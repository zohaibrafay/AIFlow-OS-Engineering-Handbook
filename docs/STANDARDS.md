# Documentation Standards

## Markdown Standards

Use Markdown as the primary source format. Use ATX headings with `#`, relative links for repository references, fenced code blocks with language identifiers, focused paragraphs, and clear lists. Avoid placeholder text, filler, unsupported claims, and marketing language.

## Heading Standards

Use one `#` heading per document. Use title case for major section headings. Do not skip heading levels. Prefer descriptive headings over generic headings.

## Writing Style

Write like an engineering handbook: precise, direct, structured, and evidence-aware. Define terms before relying on them. Separate goals, non-goals, assumptions, constraints, risks, dependencies, and deliverables.

## Naming Conventions

Root governance files use established open source names such as `README.md`, `CONTRIBUTING.md`, and `SECURITY.md`. Project-wide docs in `docs/` use uppercase descriptive names. Volume files use lowercase hyphenated names. ADR files use `ADR-0000-short-title.md`.

## Folder Naming

Use lowercase folder names. Use hyphenated names when a folder represents a volume or named collection. Preserve the established top-level folder structure unless a roadmap or ADR authorizes change.

## File Naming

Use clear names that describe document purpose. Do not encode temporary sprint names into permanent handbook chapter files unless the file is sprint-specific. Use `.md` for Markdown and `.mmd` for Mermaid diagram sources.

## Diagram Standards

Store diagram source files in `diagrams/` or a relevant diagram subfolder. Reference diagrams from related documents. Include diagram titles in Mermaid sources when practical. Keep diagrams aligned with architecture text.

## Mermaid Standards

Use `.mmd` files for Mermaid diagrams. Prefer `flowchart`, `sequenceDiagram`, and `stateDiagram-v2` where appropriate. Use stable node names and readable labels. Avoid diagrams that require hidden context to understand.

## Draw.io Standards

Draw.io files may be added when visual complexity exceeds Mermaid's useful range. Store source `.drawio` files in the appropriate `diagrams/` folder and export reviewed images to `assets/` only when publication requires them.

## PlantUML Standards

PlantUML may be used for formal sequence, component, or deployment diagrams when Mermaid is insufficient. Store source files with clear names and link them from related docs.

## Image Standards

Store source-controlled images in `assets/`. Prefer diagrams as text source when possible. Avoid decorative images that do not support engineering understanding. Include accessible descriptions in surrounding text.

## Table Standards

Use tables for comparison, status, matrices, and structured evaluation. Keep table columns readable in Markdown. Do not use tables when a list or section structure is clearer.

## Reference Standards

References should include source, relevance, and retrieval or publication date when external material is introduced. Do not rely on unnamed authority for material claims.

## Cross Reference Standards

Use relative links. Link to the most specific relevant document. When a document is renamed or moved, update all inbound links in the same change.

## Version Headers

Major release documents should identify their version or release context when status matters. Root release history belongs in [../CHANGELOG.md](../CHANGELOG.md).

## Document Metadata

Long-form chapters may include metadata blocks for status, owner, version, last reviewed date, dependencies, and related ADRs once chapter authoring begins.

## Code Block Standards

Use code blocks only for commands, examples, file trees, configuration examples, or diagram snippets. Do not introduce application code before the roadmap authorizes implementation.

## Callout Standards

Use explicit labels such as `Note`, `Warning`, `Decision`, or `Review Requirement`. Keep callouts short and tied to actionable context.

## Glossary Usage

Use terms from [docs/GLOSSARY.md](GLOSSARY.md). Add or update glossary entries when new platform terminology becomes necessary.

## Bibliography Rules

Long-form chapters that rely on external sources should include a references or bibliography section. References must support the claims made in the chapter.

## Linking Rules

Prefer repository-relative links. Avoid bare URLs when a descriptive link is clearer. Check links during review. Link diagrams from documents that depend on them.

## Consistency Rules

Use the same term for the same concept across the repository. Keep roadmap, master context, changelog, diagrams, and ADR index synchronized. Preserve the distinction between handbook architecture and future implementation.
