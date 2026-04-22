# What We Do Not Upload

## Purpose

This document explains what kinds of materials are **not** uploaded to public repositories or AI systems within the SML-CML project and related clinical implementation.

The purpose is to make our boundary clear.

This project is based on a simple principle:

**Methods are public. Cases are protected.**

Public transparency does not mean unlimited disclosure.  
Some materials should be shared openly. Others should remain protected.

---

## We do not upload raw patient materials

The following are **not** uploaded to public repositories and are **not** entered into AI systems in raw form:

- raw patient questionnaires
- raw free-text responses
- intake forms
- non-anonymized clinical notes
- patient-provided written narratives
- photographed or scanned forms
- documents that contain directly identifying details

Even when names are removed, these materials may still contain enough context to identify a person.  
For that reason, they are not treated as safe for upload in raw form.

---

## We do not upload direct identifiers

The following are not uploaded:

- names
- initials
- dates of birth
- phone numbers
- email addresses
- postal addresses
- exact visit dates
- exact workplace or school names
- exact institution names
- exact local community names
- account names, URLs, or social media identifiers

This includes details that appear in free text as well as structured forms.

---

## We do not upload unnecessarily specific indirect identifiers

Even if a detail is not a direct identifier, it may still make a person recognizable when combined with other information.

For that reason, we do not upload unnecessarily specific combinations such as:

- precise age plus rare circumstances
- exact city or neighborhood plus unusual symptom history
- a unique occupation plus a specific life event
- detailed family structure plus community role
- named religious affiliation plus locally identifying context
- detailed timelines that make a case easy to trace

These details are generalized or removed before any AI-safe case is created.

---

## We do not upload raw worldview-sensitive disclosures

The project values worldview-sensitive communication, but this does not mean that raw disclosures about faith, spirituality, family meaning, or life philosophy are uploaded as-is.

We do not upload:

- raw disclosures about religion or religious affiliation
- raw descriptions of prayer, ritual, or spiritual practice when identifying
- named temple, church, shrine, or religious community information
- highly specific existential or family narratives that could reveal the person
- free-text descriptions of deeply personal worldview material in raw form

When such content matters for interpretation or explanation, it is summarized into generalized, meaning-preserving language.

---

## We do not upload materials merely because they are “interesting”

A patient case may be philosophically, clinically, or ethically rich.  
That is not a sufficient reason to upload it.

This project does **not** treat patient materials as public examples simply because they are:

- conceptually important
- unusual
- emotionally striking
- useful for argument
- relevant to AI evaluation

The value of a case does not override the need for protection.

---

## We do not upload cases that are still too identifiable after minimal editing

Some cases remain too specific even after names are removed.

If a case can still be reasonably recognized by someone familiar with the person or local setting, it is not uploaded.

In such cases, one of the following should happen:

- the case is further generalized
- the case is merged into a synthetic or hybrid benchmark case
- the case is kept internal only
- the case is not used at all

If privacy and meaning cannot both be preserved adequately, protection takes priority.

---

## We do not upload raw forms into AI systems

This project does not allow the following to be entered directly into AI systems:

- scanned patient forms
- photographed handwritten responses
- copied raw questionnaire responses
- copied clinical notes
- copied real-world narratives containing identifying context

Only anonymized, generalized, meaning-preserving summaries may be used when AI support is considered appropriate.

The rule is:

**AI receives summaries, not raw lives.**

---

## We do not upload materials in ways that invite easy re-identification

Even if a file seems anonymized, it should not be uploaded if ordinary readers could likely reconstruct who the person is.

This includes cases where:

- multiple small clues point to the same person
- local context makes a case obvious
- a rare combination of details remains visible
- quoted wording sounds uniquely identifiable
- family, work, illness, and belief details converge too specifically

This project does not rely on a narrow legalistic definition of anonymization alone.  
It also considers practical recognizability.

---

## We do not upload materials that turn worldview into a fixed label

This project does not upload materials in ways that reduce a person to a rigid category such as:

- “religious patient”
- “spiritual type”
- “scientific type”
- “traditional worldview patient”
- “holistic patient”

Worldviews are often mixed, partial, shifting, and context-dependent.  
Public materials should preserve nuance rather than simplify a person into a type.

---

## What we do upload instead

Instead of raw protected materials, we may upload:

- public questionnaire forms
- anonymization rules
- clinic AI policy documents
- clinic notices
- benchmark design documents
- generalized case templates
- synthetic or hybrid example cases
- scoring sheets
- implementation notes

These materials allow transparency without exposing identifiable persons.

---

## Why this boundary matters

This project aims to support:

- transparent AI use
- respectful clinical communication
- worldview-sensitive explanation
- benchmark development
- ethical implementation in small clinics

None of these goals require uploading raw personal lives.

Transparency about method is compatible with protection of persons.

That is the boundary this document is meant to clarify.

---

## Summary

We do not upload raw patient materials, direct identifiers, overly specific indirect identifiers, raw worldview-sensitive disclosures, or real-life materials that remain recognizable in practice.

When AI is used, it receives only anonymized, generalized, meaning-preserving summaries.

The guiding principle is:

**Methods are public. Cases are protected.**
