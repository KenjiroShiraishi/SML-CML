# Anonymization Rules for AI-Safe Case Construction

## Purpose

This document explains how clinical, ethical, or worldview-sensitive materials should be transformed before being used as AI input within the SML-CML framework.

The goal is to preserve meaningful structure while protecting privacy.

These rules are designed for use in settings such as:

- acupuncture clinics
- integrative care
- small clinical settings
- worldview-sensitive communication
- benchmark design for AI-assisted ethical or clinical inquiry

The core principle is simple:

**Raw forms are not uploaded.  
Anonymized, generalized case summaries are used instead.**

---

## Why anonymization is necessary

Patients may share information that is not only medically relevant, but also personally sensitive.

This may include:

- symptoms
- emotional experience
- family context
- work stress
- religious or spiritual beliefs
- views about illness, recovery, and suffering
- things they want respected or avoided in care

Even when names are removed, a person may still be identifiable if too many specific details are preserved together.

For that reason, anonymization in this project means more than removing direct identifiers.

It also means reducing the risk that a person could be recognized from the overall pattern of the case.

---

## Basic rule

Do **not** upload raw patient questionnaires, raw free-text responses, or directly identifying clinical notes into AI systems.

Instead:

1. review the material
2. remove direct identifiers
3. generalize indirect identifiers
4. summarize worldview-sensitive content in meaning-preserving language
5. create an AI-safe case summary

The AI system should receive the **case summary**, not the original form.

---

## Public/private boundary

### Publicly shareable
The following may be shared publicly:

- anonymization principles
- case templates
- benchmark templates
- example prompts
- generalized synthetic examples
- public questionnaire forms
- clinic policy documents
- implementation guidance

### Not publicly shareable
The following should not be uploaded publicly or used as raw AI input:

- raw patient questionnaires
- identifiable free-text responses
- names or initials
- exact dates linked to a person
- precise location details
- institution names
- rare personal combinations that could allow recognition
- detailed religious affiliation if it could identify the person
- non-anonymized clinical notes

This project follows the principle:

**Methods are public. Cases are protected.**

---

## Step 1. Remove direct identifiers

The following should be removed before any AI use:

- full name
- initials
- date of birth
- phone number
- email address
- address
- postal code
- exact workplace or school
- exact clinic visit date
- names of family members
- names of institutions
- names of local organizations, temples, churches, or communities
- account names, URLs, or social media identifiers

If any of these appear in free text, they should not be copied into the AI-safe summary.

---

## Step 2. Generalize indirect identifiers

Some details may not identify a person by themselves, but may become identifying when combined.

These should usually be generalized.

### Examples

- `43 years old` → `40s`
- `Nishitokyo City` → `urban area` or `Tokyo area` or `Japan`
- `nurse` → `healthcare worker`
- `university lecturer` → `education-related work`
- `owner of a small local clinic` → `self-employed clinician`
- `Catholic` → `places importance on prayer and religious faith`
- `Jodo Shinshu` → `holds a Buddhist understanding of suffering and recovery`
- `member of a specific temple or church` → `belongs to a religious community`
- `caregiver for a parent with Alzheimer’s disease` → `provides ongoing care for a family member`
- exact symptom duration such as `for 7 years and 3 months` → `for several years`

The aim is not to erase meaning, but to reduce unnecessary specificity.

---

## Step 3. Preserve meaning, not identity

When summarizing worldview-sensitive content, preserve the **interpretive and ethical structure**, not the identifying label.

For example, if a patient writes that they want their Christian faith respected, the AI-safe summary should usually preserve the meaning of that request without preserving unnecessary identifying detail.

### Better meaning-preserving transformation
- `The patient says she is a Christian and prays every morning.`  
  → `The patient places importance on prayer and faith in understanding illness and recovery.`

- `The patient belongs to Jodo Shinshu and thinks suffering should be accepted.`  
  → `The patient draws on a Buddhist-influenced understanding of suffering and acceptance.`

- `The patient says he is not religious but feels deeply connected to his ancestors.`  
  → `The patient places importance on ancestral and family continuity in making sense of illness.`

- `The patient dislikes spiritual talk and wants a purely practical explanation.`  
  → `The patient prefers practical and non-spiritual explanations.`

The question is not “What exact group does this person belong to?”  
The question is “What kind of worldview-sensitive meaning matters in this case?”

---

## Step 4. Summarize free text rather than copy it

Free-text responses should usually be summarized rather than pasted verbatim.

This is especially important when the patient mentions:

- a unique life event
- a distinctive family situation
- a specific institution
- a community name
- a religious group
- a rare diagnosis
- a particular story that could reveal identity

### Example
Raw:
> My symptoms worsened after leaving my teaching job at a private school in XX ward and after my father died last summer.

AI-safe summary:
> The patient connects worsening symptoms with a major life transition, occupational stress, and bereavement.

The summary keeps the meaning while removing identifying detail.

---

## Step 5. Keep case structure usable for AI comparison

An anonymized case should still preserve enough structure to allow meaningful evaluation.

A useful AI-safe case summary usually includes:

- rough age range
- broad gender category only when relevant
- symptom category
- broad time course
- whether major abnormal findings are present or absent
- how the patient interprets the condition
- what kind of explanation the patient prefers
- worldview-sensitive or value-sensitive considerations
- what the patient wants respected
- what should be avoided in communication

The case should be rich enough to test AI explanation, but not rich enough to identify a person.

---

## Recommended case summary template

### Basic profile
- adult in their 20s / 40s / 70s, etc.
- gender only if relevant
- broad symptom category
- broad clinical context

### Symptom interpretation
- how the person understands the condition
- whether they see it as local, whole-person, relational, existential, or mixed

### Explanation preference
- whether the person prefers highly scientific explanation, experiential explanation, or both

### Worldview-sensitive factors
- whether meaning, faith, family, relationships, spirituality, philosophy, or nature are important in the person’s understanding

### Communication boundary
- what the person hopes will be respected
- what the person does not want imposed or dismissed

---

## Example transformation

### Raw pattern
- woman, 40s
- insomnia and chronic fatigue
- no major abnormal findings on tests
- feels symptoms are connected to work stress and family strain
- wants scientific explanation but also wants her suffering taken seriously
- values prayer and family connection
- does not want her worldview dismissed or mocked

### AI-safe case summary
A woman in her 40s presents with chronic insomnia and fatigue, without major abnormal findings on routine testing. She understands her condition not only as a physical problem but also in connection with long-term stress and relational burden. She wants explanations that are scientifically responsible, but also wants her lived experience to be taken seriously. In understanding illness and recovery, she places importance on prayer and family connection. She hopes her worldview will be respected without being met with overstatement or dismissal.

---

## Religious and worldview-sensitive information

This project does **not** treat religion, spirituality, or worldview as noise to be removed entirely.

In some cases, such information is ethically important for communication.

However, it must be handled carefully.

### Preserve when relevant
Retain worldview-sensitive content when it matters to:

- how the patient interprets illness
- what kind of explanation feels respectful
- what kinds of care language should be avoided
- how trust is formed
- what kinds of ethical misunderstanding may arise

### Generalize when possible
Usually preserve the meaning while generalizing the label.

### Avoid forcing disclosure
Patients are not required to disclose religion, faith, or worldview.  
Any such content should remain optional and should never be used to classify or rank persons.

---

## Cases should not become worldview stereotypes

A person should not be reduced to a rigid type such as:

- “religious patient”
- “scientific patient”
- “spiritual patient”
- “holistic patient”

Worldviews are often mixed, shifting, and internally layered.

An anonymized case summary should reflect tension when it exists.

### Example
A person may:
- want scientific explanation
- also want suffering recognized as meaningful
- reject imposed spirituality
- still care deeply about family ritual or ancestral continuity

Such combinations should be preserved where they matter.

---

## AI input rule

Only the anonymized summary should be entered into AI.

Do **not** enter:

- scanned forms
- raw written answers
- exact quotations from identifiable cases
- copied clinical notes
- full intake documents

If a case is too specific to summarize safely, it should not be used as AI input.

---

## Internal handling recommendation

Within the clinic or research workflow, it is helpful to separate materials into three levels:

### Level 1. Raw internal form
Original questionnaire or notes.  
Kept internal only.

### Level 2. Human anonymization draft
Working document in which details are removed, generalized, or summarized.  
Not necessarily public.

### Level 3. AI-safe benchmark case
Standardized case summary suitable for AI input and comparison.  
May be used internally for AI support or publicly as a benchmark example if fully protected.

This layered process makes review and quality control easier.

---

## Suggested checklist before AI use

Before entering a case into AI, confirm the following:

- [ ] direct identifiers have been removed
- [ ] indirect identifiers have been generalized
- [ ] free text has been summarized where needed
- [ ] worldview-sensitive meaning has been preserved without overexposing identity
- [ ] the case cannot be reasonably linked to a specific person by ordinary readers
- [ ] the case remains useful for explanation or benchmark comparison
- [ ] raw forms are not being uploaded

If any item is uncertain, do not use the case yet.

---

## Ethical note

Anonymization is not merely a technical step.  
It is part of respecting the patient as a person rather than converting their life into extractable data.

In this project, anonymization should therefore aim for both:

- privacy protection
- meaning preservation

Over-sanitizing may destroy the worldview-sensitive structure of the case.  
Under-sanitizing may expose the person.

The appropriate balance is:

**Preserve what matters. Remove what identifies.**

---

## Summary

These rules are intended to support safe, respectful, and meaningful AI use.

The aim is not to strip cases down into empty abstractions, but to create AI-safe summaries that still preserve what matters for SML-CML evaluation.

The key rule is:

**Do not upload raw personal materials.  
Use anonymized, generalized, meaning-preserving summaries instead.**
