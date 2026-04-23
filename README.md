# SML-CML
A structured model grounded in human cognition—including worldview, phenomenology, hermeneutics, and abductive reasoning. Usable with LLMs and AI systems.

# 📘 SML-CML Framework

**SML-CML** is a two-layered reasoning framework designed to structure both **semantic interpretation** and **value-based evaluation**.

It aims to explicitly represent how humans generate meaning (**SML**) and assess it within a worldview (**CML**).  
This allows AI systems to move beyond surface-level correctness and engage with contextually valid reasoning.

---

## 1. Layer Definitions

### 🔹 SML (Semantic Meaning Layer)

Describes how a phenomenon is interpreted — the frame, perspective, or lens through which it is understood.

- Example: “Is this fatigue a sign of *Qi deficiency* or *dampness obstructing the spleen*?”
- SML structures abductive reasoning, interpretive framing, and explanatory comparison.

### 🔹 CML (Cosmological Meaning Layer)

Encodes the value system or worldview underpinning a given interpretation.

- Example: “Should health prioritize *harmony with nature* or *removal of pain*?”
- CML enables normative evaluation grounded in ethics, culture, religion, spirituality, or philosophy.

---

## 2. Functional Differences

| Layer | Function | Focus |
|-------|----------|-------|
| SML | Structures the question | Meaning, interpretation, framing |
| CML | Evaluates the framing | Values, worldview, ethical alignment |

---

## 3. Application to AI and LLMs

SML-CML provides a framework for LLMs to generate and evaluate responses beyond simple pattern matching.

- **SML** enables LLMs to construct questions or explanations based on coherent interpretive structures.
- **CML** provides criteria to assess whether those structures align with specific value systems, worldviews, or ethical priorities.

### Example: Comparing AI-generated diagnoses

| Output | SML-based Interpretation | CML Evaluation |
|--------|---------------------------|----------------|
| A: “Cold sensitivity is caused by blood deficiency.” | East Asian medicine lens | Aligned with a harmony-oriented worldview |
| B: “Cold sensitivity is due to lack of exercise.” | Western biomedical lens | Aligned with a productivity-oriented worldview |

---

## 4. Use Cases

- **AI Diagnosis**: Evaluate interpretive validity, not just surface-level accuracy
- **Cross-cultural Education**: Teach how worldviews shape reasoning
- **Ethical Reasoning**: Make value assumptions behind moral judgments explicit
- **Dialogue Systems**: Support negotiation across value pluralism
- **Clinical Communication**: Improve explanation and trust-building in worldview-sensitive care
- **Benchmark Design**: Compare AI outputs using layered interpretive and normative criteria

---

## 5. Why This Framework Matters

Most AI evaluation relies on “correctness” as defined by training data or tagged labels.  
But in domains like healthcare, ethics, and philosophy, **truth** depends on:

- how something is *framed*
- which *worldview* or *value system* it appeals to
- whether the response fits a lived human context
- whether important meanings are preserved rather than flattened

**SML-CML** offers a way to:

- make these layers explicit
- enable pluralistic and context-sensitive reasoning
- distinguish semantic coherence from worldview-sensitive adequacy
- guide AI systems toward more meaningful interaction with human thought

---

## 6. Clinical and Benchmark Implementation

This repository also includes practical materials for using SML-CML in real-world clinical communication and AI benchmarking.

These materials are designed for:

- acupuncture and integrative care settings
- worldview-sensitive patient communication
- anonymized benchmark case generation for AI evaluation
- transparent and ethically bounded use of AI-assisted explanation

The aim is not only to describe SML-CML as a concept, but also to show how it can be used in practice.

---

## 7. Implementation Principles

The practical materials in this repository follow three principles:

### 1. Respect for worldview
Patients may hold religious, spiritual, familial, philosophical, or culturally grounded views of illness and recovery.  
These should not be dismissed simply because they do not fit one explanatory model.

### 2. Privacy by design
Raw patient forms are not uploaded to AI systems.  
Only anonymized, generalized case summaries are used for benchmark or explanation-support purposes.

### 3. Auditability and transparency
The aim is not opaque AI use, but explicit and reviewable support for explanation, comparison, and reflection.

---

## 8. Public/Private Boundary

This repository shares **methods, templates, and rules**, but does **not** upload identifiable patient materials.

### Public
- questionnaires
- anonymization rules
- benchmark templates
- clinic notices
- scoring sheets
- implementation guidance

### Not public
- raw patient responses
- identifiable free-text descriptions
- internal case notes
- non-anonymized clinical records

This project follows the principle:

**Methods are public. Cases are protected.**

---

## 9. Repository Structure

### `docs/`
Policy documents, public-facing materials, and implementation guidance.

Current contents include:

- `docs/questionnaire-public.md`
- `docs/questionnaire-public-en.md`
- `docs/anonymization-rules.md`
- `docs/clinic-ai-policy.md`
- `docs/clinic-notice-ja.md`
- `docs/clinic-notice-en.md`
- `docs/benchmark-overview.md`
- `docs/purpose-and-scope.md`
- `docs/what-we-do-not-upload.md`
- `docs/privacy-boundaries.md`

### `examples/`
Example benchmark cases, anonymized input formats, and scoring logic.

Examples include:

- anonymized case templates
- example AI prompts
- SML-CML scoring examples
- worldview-sensitive ethical reasoning cases

### `assets/`
Printable or visual materials.

Current examples include:

- clinic notices
- workflow diagrams
- QR-linked patient information sheets
- printable questionnaire files
- Japanese PDF questionnaire materials

### Repository root
- `README.md`: English overview
- `overview_ja.md`: Japanese overview
- `clinical_translation_design_checklist.md`: related implementation material

---

## 10. Benchmark Direction

A major direction of this repository is the development of **SML-CML-based benchmark materials** for AI-assisted ethical and clinical inquiry.

This includes:

- worldview-sensitive questionnaires for clinical use
- rules for transforming responses into anonymized AI-safe benchmark cases
- structured prompts for AI comparison
- layered scoring tools for SML and CML assessment

The goal is not merely to rank models, but to examine:

- what kinds of interpretive tasks AI handles relatively well
- where worldview-sensitive reasoning becomes thin, flattened, or misleading
- how semantic adequacy and cosmological adequacy may diverge
- how human evaluators with different interpretive stances assess the same output

---

## 11. Clinical Communication Materials

This repository also supports a practical workflow for small clinical settings, including acupuncture clinics.

The workflow is designed to help clinicians:

- understand how patients interpret illness and recovery
- identify what kinds of explanation feel respectful or dismissive
- preserve worldview-sensitive information while protecting privacy
- use AI only on anonymized and generalized case summaries
- document boundaries for safe and transparent AI use

These materials are intended for real implementation, not only theoretical discussion.

---

## 12. Ethical Scope

The SML-CML framework is not intended to automate moral authority or replace human judgment.

Instead, it helps clarify:

- what layer of meaning an AI output is operating on
- where semantic coherence may mask worldview-insensitive reasoning
- why human interpretation remains necessary in ethics, healthcare, and culturally complex dialogue

In this sense, SML-CML is both:

- a conceptual model of layered meaning
- a practical framework for evaluating assistive versus over-delegated uses of AI

---

## 13. Ongoing Direction

This repository is evolving from a conceptual framework into a practical implementation resource for:

- AI-assisted ethical inquiry
- worldview-sensitive clinical communication
- SML-CML-based benchmark design
- transparent use of AI in small clinical settings
- cross-cultural and pluralistic reasoning support

---

## 🔧 Next Steps

This repository will continue to include and expand:

- conceptual explanations of SML-CML
- Japanese and English overview documents
- benchmark-related materials
- anonymization guidance
- public clinical communication documents
- examples of layered reasoning and evaluation

---

## 📄 Related Materials

### Preprint on OSF
**"Abductive Reasoning from Traditional Chinese Medicine to AI"**  
https://osf.io/p24sa/  
DOI: [10.17605/OSF.IO/P24SA](https://doi.org/10.17605/OSF.IO/P24SA)

### Japanese overview
📄 日本語の解説はこちら → [overview_ja.md](overview_ja.md)

### Example case in Japanese
📄 日本語での社会的対立の事例解説はこちら → [examples/social_conflict_case_horiemon_ja.md](examples/social_conflict_case_horiemon_ja.md)

---

## 📂 Repository Guide

This repository includes both conceptual and practical materials related to the SML-CML framework.

### Core documents
- [Japanese overview](overview_ja.md)
- [Clinical translation design checklist](clinical_translation_design_checklist.md)

### Benchmark and implementation documents
- [SML-CML Benchmark Overview](docs/benchmark-overview.md)
- [Purpose and Scope](docs/purpose-and-scope.md)
- [Public Questionnaire for Clinical Use](docs/questionnaire-public.md)
- [Public Questionnaire for Clinical Use (English)](docs/questionnaire-public-en.md)
- [Anonymization Rules for AI-Safe Case Construction](docs/anonymization-rules.md)
- [Clinic AI Policy](docs/clinic-ai-policy.md)
- [Clinic Notice (Japanese)](docs/clinic-notice-ja.md)
- [Clinic Notice (English)](docs/clinic-notice-en.md)
- [What We Do Not Upload](docs/what-we-do-not-upload.md)
- [Privacy Boundaries](docs/privacy-boundaries.md)

### Benchmark examples
- [Anonymized Case Template](examples/anonymized-case-template.md)
- [Benchmark Case Example 01](examples/benchmark-case-example-01.md)
- [Benchmark Case Example 02](examples/benchmark-case-example-02.md)
- [SML-CML Scoring Example 01](examples/sml-cml-scoring-example.md)
- [SML-CML Scoring Example 02](examples/sml-cml-scoring-example-02.md)

### Templates and scoring materials
- `templates/worldview-questionnaire-template-ja.docx`
- `templates/worldview-questionnaire-template.docx`
- `templates/sml-cml-scoring-sheet.csv`

### Printable materials
- [Worldview Questionnaire Template (Japanese PDF)](assets/worldview-questionnaire-template-ja.pdf)

### Public principle
This repository follows a simple rule:

**Methods are public. Cases are protected.**

It shares frameworks, questionnaires, anonymization rules, notices, benchmark cases, and scoring logic, but does **not** upload raw patient materials or identifiable case records.
