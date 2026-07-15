# SPECIFICATION_FREEZE.md

# The Maze That Remembered

Version: 1.0

Status: Frozen Control Document at `spec-v1.0`

---

# Purpose

This document defines the immutable boundary used during manuscript
production.

The Git tag `spec-v1.0` identifies the exact corrected specification
commit approved before Draft One.

---

# Frozen Specification Corpus

The following files are immutable after `spec-v1.0`:

- README.md
- AGENT.md
- BOOK_BIBLE.md
- EDITOR_CONSTITUTION.md
- STYLE_GUIDE.md
- WORLD_BIBLE.md
- CHARACTER_BIBLE.md
- SYMBOL_BIBLE.md
- SCIENTIFIC_DEPENDENCY_MAP.md
- CHAPTER_BLUEPRINTS.md
- CONTINUITY_GUIDE.md
- QUALITY_ASSURANCE.md
- WRITING_WORKFLOW.md
- SCIENTIFIC_REVIEW.md
- PARKING_LOT.md
- MANIFESTO.md
- SPECIFICATION_FREEZE.md

All of these Markdown files remain project specifications. Their tagged
content governs every manuscript revision.

---

# Mutable Production Artifact

MANUSCRIPT.md is the sole mutable repository file during Draft One and
subsequent manuscript revision.

Chapter QA reports, continuity evidence, running word counts, and parked
ideas are maintained outside the frozen repository files.

---

# Prohibited Changes During Drafting

Do not change:

- chapter order
- narrative architecture
- scientific concepts or dependency order
- cast
- world locations
- symbol roles
- literary point of view or tense
- target length
- QA gates

Do not add another repository file during drafting.

---

# Critical Contradiction Protocol

If the manuscript exposes a critical contradiction:

1. Stop drafting.
2. Identify the exact conflicting rules.
3. Report the effect on the manuscript.
4. Wait for explicit user authorization.
5. Never alter the frozen specification silently.

A future authorized specification revision requires a new version and a
new tag. It may not rewrite `spec-v1.0`.

---

# Final Principle

The specification is immutable.

The prose may improve within it.
