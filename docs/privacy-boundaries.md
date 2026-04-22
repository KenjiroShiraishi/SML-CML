# Privacy Boundaries

## Purpose

This document explains the privacy boundary structure used in the SML-CML project and related clinical implementation.

Its aim is to clarify how materials are separated across different levels of use, including:

- internal clinical use
- anonymized AI input
- public repository materials

The goal is not only to protect privacy in a narrow technical sense, but also to make the workflow understandable, reviewable, and ethically consistent.

This document follows the principle:

**Methods are public. Cases are protected.**

---

## Why boundaries matter

Privacy protection is not achieved only by deleting names.

In small clinical settings, a person may become identifiable through a combination of details such as:

- age
- occupation
- family context
- symptom history
- local setting
- religious or spiritual disclosures
- unusual life events
- exact timing

For that reason, this project uses **privacy boundaries** rather than a simple public/private distinction.

The central question is not only:

“Is the name removed?”

It is also:

“Could this person still be recognized in practice?”

---

## Three-layer boundary model

This project uses a three-layer model.

### Layer 1. Internal clinical materials
This includes original materials used in care.

Examples:

- raw questionnaires
- raw free-text responses
- intake forms
- internal notes
- direct patient narratives
- non-anonymized case descriptions

These materials are kept internal.

They are not public and are not entered into AI in raw form.

---

### Layer 2. Human-prepared anonymization materials
This includes working materials in which a clinician or project user removes, generalizes, or transforms identifying details.

Examples:

- draft anonymization notes
- generalized summaries
- reduced-detail case drafts
- internal benchmark preparation notes

These materials may still require caution.  
They are not automatically public just because some identifiers have been removed.

Their purpose is to bridge raw materials and AI-safe or public materials.

---

### Layer 3. AI-safe and/or public materials
This includes materials that have been sufficiently generalized and structured so that they can be used for AI input or public repository purposes.

Examples:

- anonymized case templates
- generalized benchmark cases
- public questionnaires
- clinic notices
- anonymization rules
- policy documents
- implementation examples
- scoring sheets

These materials are designed to preserve meaningful structure while avoiding reasonable re-identification risk.

---

## Boundary principle

The main privacy boundary principle is:

**A case should move outward only when identity risk has been sufficiently reduced and meaning has been preserved in a generalized form.**

That means:

- not every internal case should become an AI input
- not every AI input should become a public example
- not every meaningful story should be shared

Movement across boundaries requires judgment.

---

## Boundary table

| Layer | Type of material | AI input allowed? | Public upload allowed? |
|------|------------------|------------------|------------------------|
| Layer 1 | Raw patient materials | No | No |
| Layer 2 | Human anonymization draft | Usually no | Usually no |
| Layer 3 | AI-safe generalized summary or public document | Yes, when appropriate | Yes, when appropriate |

This table is only a guide.  
A material belongs in Layer 3 only when it has been sufficiently generalized and reviewed.

---

## What should remain inside Layer 1

The following should remain in Layer 1 unless fully transformed:

- original questionnaires
- original handwritten responses
- direct free-text narratives
- detailed case notes
- exact dates
- exact locations
- exact institutions
- named communities
- raw religious disclosures
- identifiable family details

These materials are part of direct care and are not benchmark objects in their raw form.

---

## What may enter Layer 2

Layer 2 is a working zone, not a public zone.

It may include:

- rough age-to-age-range conversion
- occupation generalization
- removal of exact names and locations
- simplification of timelines
- transformation of religious labels into worldview-sensitive descriptors
- summary drafts of what should be respected or avoided in communication

Layer 2 still requires review because residual recognizability may remain.

---

## What may enter Layer 3

A case or document may enter Layer 3 when:

- direct identifiers have been removed
- indirect identifiers have been generalized
- the remaining narrative is not reasonably traceable to a specific person by ordinary readers
- worldview-sensitive meaning has been preserved without overexposing the individual
- the material remains useful for explanation, benchmark comparison, or public protocol sharing

Layer 3 is the only layer suitable for routine AI input and public methodological sharing.

---

## AI boundary

The boundary for AI use is strict.

AI should receive:

- anonymized summaries
- generalized benchmark cases
- public-facing templates
- synthetic or hybrid educational examples

AI should not receive:

- raw patient forms
- photographed questionnaires
- copied raw free text
- copied non-anonymized case notes
- directly identifying worldview-sensitive disclosures

The basic rule is:

**AI receives summaries, not raw lives.**

---

## Public repository boundary

A public repository may include:

- methods
- templates
- policies
- notices
- scoring structures
- generalized benchmark cases
- implementation guidance

A public repository should not include:

- real-world raw cases
- identifiable narratives
- direct disclosures that could reveal a person
- local details that make cases recognizable
- materials that were only minimally edited

The repository is for transparency of method, not exposure of persons.

---

## Worldview-sensitive boundary

This project does not remove worldview-sensitive content automatically.

In some cases, faith, spirituality, family meaning, philosophy, or existential interpretation are central to the case.

However, these dimensions should cross the privacy boundary only in transformed form.

### Example transformations
- named religion → generalized meaning orientation
- named ritual → broader practice description
- named community → relation-based descriptor
- exact worldview statement → summarized meaning structure

The goal is to preserve ethical relevance without preserving identifying sharpness.

---

## Boundary test before AI use or public sharing

Before moving material across a boundary, ask:

1. Has direct identifying information been removed?
2. Have indirect identifying details been generalized?
3. Does the summary preserve the case’s meaningful structure?
4. Could an ordinary reader still reasonably identify the person?
5. Is the material necessary for AI input or public sharing?
6. Has worldview-sensitive material been transformed rather than copied?
7. Does the benefit of use justify boundary crossing?

If the answer to any of these is uncertain, the material should remain at the more protected layer.

---

## When to stop moving outward

Not every case should become a benchmark case.

A case should remain internal when:

- it remains recognizable despite editing
- the worldview-sensitive content is too personal to summarize safely
- a rare combination of details remains visible
- the meaning would be destroyed by safe generalization
- the case is clinically important but not safely shareable

In these situations, protection takes priority over public usefulness.

---

## Why this matters for small clinics

In small clinics, the line between “anonymous” and “recognizable” is often thinner than in large datasets.

Local context matters.

A person may be identifiable not because of one obvious detail, but because of a recognizable pattern of:

- illness
- family burden
- local setting
- age
- faith
- profession
- timing

For that reason, small-clinic implementation should be especially careful about boundary movement.

---

## Ethical meaning of boundaries

Privacy boundaries are not merely administrative.

They are also part of how a clinic or project respects the patient as a person rather than treating their story as extractable material.

This is especially important when cases involve:

- suffering
- trust
- meaning-making
- religion or spirituality
- family burden
- existential vulnerability

Boundary discipline is therefore part of ethical care, not only compliance.

---

## Summary

The SML-CML project uses a three-layer boundary model:

- Layer 1: internal raw materials
- Layer 2: human-prepared anonymization drafts
- Layer 3: AI-safe and/or public generalized materials

A case should move outward only when identity risk is sufficiently reduced and meaningful structure is preserved.

The central principles are:

**Methods are public. Cases are protected.**  
**AI receives summaries, not raw lives.**
