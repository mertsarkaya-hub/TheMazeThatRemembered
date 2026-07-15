# WRITING_WORKFLOW.md

# The Maze That Remembered

Version: 2.2

Status: Frozen Production Protocol at `spec-v1.0`

---

# Purpose

This document defines the production pipeline for the manuscript.

The project is a concise literary scientific novella with:

- 25,000–35,000 words
- a preferred center of 28,000–32,000 words
- approximately 100–120 printed pages in final design
- 15 chapters plus one short interlude

The total word range is required. Chapter budgets remain flexible within
that total.

Writing and editing are different cognitive tasks. They occur in
sequence, never simultaneously.

---

# Frozen Inputs and Mutable Output

The `spec-v1.0` tag identifies the immutable specification corpus.

After that tag:

- only MANUSCRIPT.md changes in the repository
- architecture never changes during Draft One
- QA and continuity evidence is reported outside the frozen files
- parked ideas remain outside Draft One

If drafting reveals a critical contradiction, stop and report it. Never
repair architecture silently.

---

# Stage 0 — Repository Audit and Freeze

Before drafting:

1. Read every repository document.
2. Audit contradictions, duplication, terminology, and omissions.
3. Obtain approval for genuine corrections.
4. Apply and verify the approved corrections.
5. Tag the corrected specification commit `spec-v1.0`.
6. Treat the tagged specification corpus as immutable.
7. Begin Chapter 1.

---

# Stage 1 — Sequential Chapter Cycle

Complete the following cycle for Chapter 1 through Chapter 15 without
jumping ahead.

## Step 1 — Prepare

- Read the previous two manuscript pages when they exist.
- Read the chapter entry in CHAPTER_BLUEPRINTS.md.
- Review the relevant dependencies and definitions in
  SCIENTIFIC_DEPENDENCY_MAP.md.
- Review one law from EDITOR_CONSTITUTION.md.
- Confirm the incoming reader state, transformation, event, symbols,
  analogy boundary, outgoing question, and working word budget.

## Step 2 — Discovery Draft

- Write only the current chapter.
- Preserve momentum.
- Do not line-edit while drafting.
- Leave a brief external note when a sentence needs later attention.
- Add no concept, plot event, character, location, or symbol outside the
  frozen architecture.
- Stop when the transformation is complete.

## Step 3 — Pause

Do not revise immediately after drafting.

Separate composition from diagnosis. Resume with the chapter as an
editor, not as the writer still inside the first pass.

## Step 4 — Compression Pass

1. Identify the one transformation.
2. Mark every paragraph that directly supports it.
3. Cut repeated explanation.
4. Merge redundant beats.
5. Remove decorative dialogue.
6. Preserve necessary experience, silence, and white space.
7. Confirm that cuts did not create a false scientific intuition.

Compression is concentration, not summary.

## Step 5 — Developmental and Line Review

Developmental review checks:

- fixed narrative event
- pacing
- character movement
- emotional shift
- transition into the outgoing question

Line review checks:

- rhythm
- precision
- natural dialogue
- implication
- restraint
- sentence compression
- paragraph breathing room

Delete before reorganizing. Reorganize before rewriting. Rewrite before
polishing.

## Step 6 — Scientific and Continuity Review

Consult SCIENTIFIC_REVIEW.md and CONTINUITY_GUIDE.md.

Verify:

- canonical definition and terminology
- prerequisite order
- analogy fidelity and retirement
- no future or unlisted scientific concept
- reader-state continuity
- character continuity
- symbol evolution
- callback and foreshadowing continuity

Scientific truth overrides literary elegance.

## Step 7 — Quality Assurance

Run every gate in QUALITY_ASSURANCE.md and produce the required external
QA evidence report.

Failure in any gate returns the chapter to revision and then to the full
QA checklist.

## Step 8 — Lock and Continue

After all gates pass:

- mark the external QA result LOCKED
- record the chapter word count
- update the running manuscript word count
- begin preparation for the next chapter

Do not draft the next chapter before the current chapter is locked.

---

# Interlude Cycle

The interlude occurs after Chapter 8.

It follows Prepare, Discovery Draft, Pause, Compression, Developmental
and Line Review, Continuity Review, and the separate Interlude Acceptance
Checklist.

It introduces no new major concept and receives no ordinary chapter
science gate requiring one.

The interlude must be locked before Chapter 9 begins.

---

# Chapter State Machine

PLANNED

↓

WRITING

↓

DISCOVERY COMPLETE

↓

PAUSED

↓

COMPRESSION PASS

↓

DEVELOPMENTAL REVIEW

↓

LINE REVIEW

↓

SCIENTIFIC AND CONTINUITY REVIEW

↓

QA PASSED

↓

LOCKED

A lock prevents casual backward editing during forward drafting. It is
not an assertion that global manuscript context can never reveal a prose
problem.

---

# Stage 2 — Whole-Manuscript Passes

After Chapter 15 reaches LOCKED, read MANUSCRIPT.md continuously before
claiming completion.

The complete manuscript then receives:

1. Global compression pass.
2. Developmental pass.
3. Line pass.
4. Scientific pass.
5. Continuity and symbol pass.
6. Copy edit.
7. Final manuscript QA.

A verified cross-chapter problem may reopen affected prose. Every
reopened chapter must pass its entire QA checklist again.

The following may never reopen:

- chapter order
- cognitive transformations
- scientific dependency order
- cast
- fixed narrative events
- locations
- symbol architecture
- analogy boundaries

---

# Length Control

Maintain a visible running word count after each locked chapter.

The working architecture totals approximately 29,800 words.

Rules:

1. Never pad a short chapter.
2. Never repeat a definition for reinforcement; reinforce through use.
3. Cut explanation before cutting the experience that earns it.
4. If accuracy requires more words, compress elsewhere.
5. The final manuscript must contain 25,000–35,000 words.

The 100–120-page target is verified during final book design. Layout may
not be manipulated to disguise padding or an out-of-range manuscript.

---

# External Review Boundary

Internal chapter review and final manuscript review are required for
**Manuscript Complete**.

Feedback from general readers, undergraduate students, beginning
graduate students, and domain experts is required for **Publication
Ready**. The user coordinates those readers after manuscript completion.

Never fabricate external feedback.

---

# Definition of Progress

Progress is measured by:

- locked chapters
- preserved scientific accuracy
- reduced unnecessary words
- stronger reader transformation

Raw word count alone is not progress.

---

# Definition of Manuscript Complete

The manuscript is complete when:

- all 15 chapters and the interlude are present in order
- every unit is locked under QUALITY_ASSURANCE.md
- the final word count is 25,000–35,000
- the whole-manuscript passes are complete
- all reopened chapters have passed QA again
- no chapter feels rushed or padded
- every scientific concept is earned
- the ending directs readers toward learning elsewhere

Publication readiness remains a later external-review state.

---

# Final Principle

Reach `THE END` with no unnecessary detours.

The book should feel complete, never exhaustive.
