# Documentation Lifecycle

## Purpose

This document defines how AIFlow OS Engineering Handbook content moves from idea to maintained publication. It applies to governance files, roadmap documents, standards, ADRs, diagrams, volume parts, chapters, templates, prompts, and GitHub community files.

See [../diagrams/documentation-lifecycle.mmd](../diagrams/documentation-lifecycle.mmd) and [../diagrams/handbook-lifecycle.mmd](../diagrams/handbook-lifecycle.mmd).

## Planning

Planning identifies the document purpose, audience, scope, dependencies, owner, required diagrams, glossary impact, and review path. Planning should confirm that the work fits the current sprint and roadmap.

## Writing

Writing should follow [docs/STANDARDS.md](STANDARDS.md). Authors must avoid placeholders, filler, unsupported claims, and implementation detail that the roadmap has not authorized.

## Review

Review includes architecture, technical, editorial, consistency, and quality checks. See [docs/REVIEW_PROCESS.md](REVIEW_PROCESS.md).

## Approval

Approval confirms that the document satisfies scope, quality, governance, terminology, cross-reference, and publication requirements. Material decisions require accepted ADRs.

## Publishing

Publishing requires updated version metadata, changelog, master context, diagram references, and release notes when applicable. See [../diagrams/publishing-workflow.mmd](../diagrams/publishing-workflow.mmd).

## Versioning

Documents participate in repository semantic versioning. Notable changes must be recorded in [../CHANGELOG.md](../CHANGELOG.md). Current status must be reflected in [docs/MASTER_CONTEXT.md](MASTER_CONTEXT.md).

## Deprecation

Deprecation marks content as no longer recommended while preserving historical context. Deprecated content should link to replacement material when available.

## Archiving

Archived content remains available for history but should not guide new work. Archiving requires review because broken links or stale references can damage handbook quality.

## Maintenance

Maintenance includes link checks, terminology review, diagram synchronization, ADR status review, roadmap alignment, and release metadata updates.

## Relationship With Implementation

Implementation must not outrun the handbook. When implementation work becomes authorized, it must trace back to approved documentation, ADRs, diagrams, and review criteria. If implementation exposes a gap, the handbook lifecycle must handle the documentation change before the behavior is treated as standard.
