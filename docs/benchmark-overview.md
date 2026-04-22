# SML-CML Benchmark Overview

## Purpose

This document outlines the purpose, scope, and basic design of **SML-CML-based benchmark materials** for AI-assisted ethical and clinical inquiry.

The benchmark is designed to evaluate not only whether an AI output is superficially coherent, but also whether it preserves or distorts important layers of human meaning.

In particular, it distinguishes between:

- **SML (Semantic Meaning Layer)**: interpretive structure, framing, coherence, and explanatory logic
- **CML (Cosmological Meaning Layer)**: values, worldview, meaning orientation, ethical salience, and context-sensitive adequacy

The benchmark is intended for use in domains where human reasoning cannot be reduced to simple factual correctness, especially:

- healthcare
- ethics
- philosophy
- cross-cultural dialogue
- worldview-sensitive explanation

---

## Why this benchmark is needed

Many current AI evaluations focus on accuracy, agreement with labeled outputs, or general helpfulness.  
These approaches are useful in some settings, but they are often insufficient in domains where the core issue is not only **what answer is produced**, but also:

- how the case is framed
- what kind of meaning is preserved or erased
- which worldview the answer assumes
- whether important ethical or existential dimensions are flattened
- whether the response remains respectful across value pluralism

A response may appear clear, helpful, and internally consistent while still failing to engage with the worldview-sensitive dimensions of a case.

The SML-CML benchmark is intended to make this difference more visible.

---

## Core idea

The benchmark does **not** treat AI evaluation as a single scale of “good” versus “bad.”

Instead, it asks:

1. **Is the output semantically structured and interpretable?**  
   This is mainly an SML question.

2. **Is the output adequate to the value-laden, worldview-sensitive, or ethically charged dimensions of the case?**  
   This is mainly a CML question.

3. **Do these two layers diverge?**  
   Some outputs may score relatively high on SML while remaining weak on CML.

This layered design allows evaluators to identify cases in which AI produces language that is coherent but existentially thin, ethically shallow, or worldview-insensitive.

---

## Main use cases

### 1. AI-assisted ethical inquiry
The benchmark can be used to assess how AI systems handle morally complex cases, especially when the task involves:

- explaining a dilemma
- comparing interpretive frames
- articulating competing considerations
- generating ethically sensitive responses
- responding across value pluralism

### 2. Clinical communication
The benchmark can be used to compare AI-generated explanation drafts for cases in which patient trust depends not only on medical clarity, but also on whether the patient’s worldview is respected.

This is especially relevant in:

- acupuncture clinics
- integrative care
- chronic symptom care
- culturally complex communication
- cases where illness meaning matters to the patient

### 3. Benchmark design for anonymized cases
The framework can also be used to develop reusable benchmark cases derived from anonymized clinical or ethical scenarios, without uploading raw personal materials.

---

## What this benchmark evaluates

The benchmark is designed to evaluate outputs in relation to the following broad dimensions.

### SML-related dimensions
Examples include:

- clarity of framing
- interpretive coherence
- ability to distinguish possible explanations
- quality of explanatory comparison
- awareness of ambiguity
- consistency between the question and the response
- ability to preserve the structure of the case

### CML-related dimensions
Examples include:

- recognition of worldview-sensitive meaning
- awareness of value assumptions
- respect for religious, spiritual, familial, or philosophical commitments
- sensitivity to lived experience
- ethical salience
- contextual adequacy
- avoidance of flattening or dismissing meaning structures important to the person involved

The exact scoring scheme may evolve, but the benchmark is built on the principle that **semantic adequacy and cosmological adequacy should not be collapsed into a single measure**.

---

## What this benchmark does not evaluate

This benchmark is **not** intended to do the following:

- determine which worldview is objectively correct
- rank persons or patients
- diagnose religious belief
- replace clinical judgment
- replace ethical judgment
- automate trust
- reduce moral reasoning to a final score
- authorize AI as an ethics expert

It is also **not** intended to reward outputs merely for sounding empathic or culturally polite.

An output may sound respectful while still failing to engage with the actual worldview structure of the case.

---

## Benchmark inputs

The benchmark is designed to work with **anonymized, AI-safe case summaries**, not raw personal records.

Inputs may be derived from:

- structured ethical scenarios
- anonymized clinical communication cases
- worldview-sensitive questionnaire responses transformed into generalized summaries
- educational comparison cases
- synthetic or hybrid cases created for evaluation

These inputs should preserve meaning structure while removing identifying details.

---

## Relationship to clinical questionnaire materials

In clinical settings, the benchmark may be linked to a worldview-sensitive questionnaire used to better understand how a patient interprets illness, recovery, trust, explanation, and meaning.

However:

- the original patient form is not the benchmark itself
- raw patient responses are not uploaded to AI
- benchmark cases are created only after anonymization and generalization
- religious or spiritual references are transformed into meaning-preserving but non-identifying descriptors

For example:

- a named religious affiliation should usually be transformed into a broader description of what kind of belief or practice matters to the person
- location, occupation, institutions, and personal identifiers should be generalized or removed
- free text should be summarized rather than copied directly when necessary for privacy

---

## Public/private boundary

This benchmark project follows a strict distinction between **public methods** and **protected cases**.

### Public
The following may be shared publicly:

- benchmark design principles
- questionnaires
- anonymization rules
- case templates
- prompt templates
- scoring sheets
- implementation notes
- clinic notices and policy documents

### Protected
The following should not be uploaded publicly:

- raw patient questionnaires
- identifiable free-text responses
- non-anonymized clinical notes
- directly identifying religious or community details
- materials that could reasonably allow re-identification

This project follows the principle:

**Methods are public. Cases are protected.**

---

## Benchmark orientation

This benchmark is not primarily a leaderboard.

Its main goal is not simply to produce statements such as:

- “Model A is better than Model B”
- “Model X scored 82 and Model Y scored 76”

Those comparisons may sometimes be useful, but they are not the central purpose.

The deeper goal is to examine:

- where AI performs relatively well at semantic organization
- where worldview-sensitive reasoning remains shallow
- where ethical adequacy and surface coherence diverge
- where evaluation depends on human interpretive stance
- where AI may assist inquiry without being allowed to displace judgment

In this sense, the benchmark is both:

- a comparative tool
- a reflective tool
- a boundary-setting tool for responsible AI use

---

## Human evaluation

Human evaluation remains central to the benchmark.

This is necessary because the benchmark does not treat human meaning as fully recoverable from text structure alone.

Evaluators may be asked to assess outputs using layered criteria, and in some versions of the benchmark, evaluators may also complete a short profile about their own interpretive or value orientation.

This can help examine:

- whether SML judgments are more stable than CML judgments
- whether different evaluators notice different worldview-sensitive features
- whether disagreement reflects noise or genuine pluralism
- whether AI outputs are semantically strong but cosmologically weak

---

## Planned benchmark workflow

A typical workflow may include the following steps:

1. **Create or select a case**
   - clinical, ethical, educational, or synthetic

2. **Ensure anonymization**
   - remove or generalize identifying details

3. **Prepare a standardized AI input**
   - preserve meaning structure while making the case AI-safe

4. **Generate AI outputs**
   - compare one or more systems using the same input

5. **Evaluate using SML-CML criteria**
   - assess semantic and cosmological layers separately

6. **Document interpretation**
   - note where the output is strong, thin, flattening, or misleading

7. **Use findings responsibly**
   - for reflection, comparison, explanation design, or implementation research

---

## Clinical implementation note

In small clinical settings such as acupuncture clinics, this benchmark can support a practical workflow for testing how AI-generated explanations respond to different patient orientations.

Examples include patients who:

- want highly scientific explanations
- want both scientific explanation and recognition of lived experience
- understand illness in relational, spiritual, or existential terms
- want their worldview respected without non-scientific overstatement
- do not want moral, religious, or spiritual assumptions imposed on them

This makes the benchmark relevant not only to AI evaluation in the abstract, but also to real clinical communication.

---

## Ethical caution

The SML-CML benchmark should be used with restraint.

It should not be used to:

- infer sensitive identity categories from sparse data
- sort patients into rigid ideological types
- treat worldview as a fixed label
- justify opaque AI use
- override individual conversation and clinical judgment

Worldviews are often layered, shifting, and partially articulated.  
The benchmark should therefore be treated as an aid to comparison and reflection, not as a total map of a person.

---

## Ongoing development

This benchmark is still developing.

Future materials may include:

- case templates
- anonymized benchmark examples
- prompt sets
- scoring sheets
- evaluator guidance
- worldview-sensitive questionnaire tools
- examples from acupuncture and integrative care
- ethics-oriented comparison cases

As the project evolves, this repository will aim to support both:

- conceptual discussion of SML-CML
- practical implementation of layered benchmark design

---

## Summary

The SML-CML benchmark is a layered approach to evaluating AI outputs in domains where meaning, value, and worldview matter.

Its central claim is simple:

**An AI output may be semantically coherent without being worldview-sensitive, ethically adequate, or meaning-preserving.**

For that reason, benchmark design in ethics and clinical communication should not stop at correctness or coherence alone.

The SML-CML approach aims to make that deeper difference visible.
