# Documentation Standards

## Markdown Standards

- Use ATX headings with `#`.
- Use descriptive headings that match the content.
- Prefer short paragraphs and clear lists.
- Use fenced code blocks with language identifiers when applicable.
- Keep links relative within the repository.

## Naming Conventions

- Root governance files use uppercase names where common open source convention expects them.
- Documentation files in `docs/` use uppercase descriptive names.
- Volume files use lowercase, hyphenated names.
- ADR files use `ADR-0000-short-title.md`.

## Folder Conventions

- `docs/` stores project-wide documentation.
- `volumes/` stores handbook content.
- `adr/` stores decision records.
- `templates/` stores reusable document structures.
- `prompts/` stores AI workflow prompts grouped by role.
- `diagrams/` stores diagram sources by view.
- `assets/` stores supporting non-code media.
- `examples/` stores future reference examples.

## Diagram Conventions

- Use Mermaid for diagrams that need to remain close to Markdown.
- Use C4 terminology for system context, container, component, and code views.
- Store diagram sources in the matching `diagrams/` subfolder.
- Diagrams must include titles, scope notes, and ownership context when practical.

## Commit Message Conventions

Use concise conventional commit style:

```text
docs: expand workflow engine roadmap
adr: accept documentation governance decision
chore: update github labels
```

## Versioning Conventions

- Use semantic versioning.
- Record notable changes in `CHANGELOG.md`.
- Update `docs/MASTER_CONTEXT.md` when current status changes.
- Avoid version increments for purely local draft changes until they are accepted.

## Writing Style

- Write as an engineering handbook.
- Avoid marketing language, filler, repetition, and unsupported claims.
- Explain trade-offs rather than presenting choices as obvious.
- Define terms before relying on them.
- Separate goals, non-goals, constraints, risks, and deliverables.

## References

References should identify the source, relevance, and date when external materials are introduced. Do not rely on unnamed industry consensus for material claims.

