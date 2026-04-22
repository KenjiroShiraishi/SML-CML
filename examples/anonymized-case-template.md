# Anonymized Case Template

## Purpose

This template is used to construct **AI-safe, meaning-preserving case summaries** for SML-CML-based comparison, reflection, and benchmark design.

It is intended for use after applying the anonymization rules described in:

- `docs/anonymization-rules.md`
- `docs/privacy-boundaries.md`

This template is not for raw clinical notes.

It is for **generalized case construction** that preserves the structure of the case while reducing identifiable detail.

---

## Basic principle

An anonymized case should preserve:

- the interpretive structure of the situation
- the patient’s symptom understanding
- the patient’s explanation preferences
- worldview-sensitive or value-sensitive dimensions
- what should be respected or avoided in communication

It should **not** preserve unnecessary identifying sharpness.

The goal is:

**Preserve what matters. Remove what identifies.**

---

## Template

### Case ID
`[example: ACU-CML-001]`

---

### 1. Basic profile

Provide only broad, non-identifying information.

- Age range:  
- Gender (only if relevant):  
- Broad clinical setting:  
- Main symptom category:  
- Broad time course:  
- Major abnormal findings present/absent/unclear:

**Example**  
- Age range: 40s  
- Gender: woman  
- Broad clinical setting: outpatient acupuncture care  
- Main symptom category: chronic insomnia and fatigue  
- Broad time course: several months to years  
- Major abnormal findings: no major abnormal findings on routine testing

---

### 2. How the person understands the condition

Describe how the person interprets the problem.

Possible dimensions include:

- local physical problem
- whole-person imbalance
- stress-related condition
- relational burden
- existential disruption
- culturally framed condition
- mixed interpretation

**Write 2–4 sentences.**

**Example**  
The person understands the condition not only as a physical problem, but also as connected to long-term stress and imbalance in daily life. The symptoms are experienced as affecting the whole person rather than one isolated part of the body.

---

### 3. Explanation preference

Describe what kind of explanation the person tends to want.

Possible dimensions include:

- strongly scientific / biomedical explanation
- balanced scientific and experiential explanation
- experience-first explanation
- whole-person explanation
- non-spiritual explanation
- worldview-sensitive explanation
- mixed preference

**Write 2–4 sentences.**

**Example**  
The person wants explanations that are scientifically responsible and not overly vague. At the same time, the person wants lived experience and bodily suffering to be taken seriously, rather than reduced to normal test results alone.

---

### 4. Worldview-sensitive or meaning-sensitive factors

Describe what kinds of worldview, value, or meaning dimensions are important in the case.

Possible dimensions include:

- family and relational meaning
- prayer or religious faith
- ancestral continuity
- philosophy or life view
- harmony with nature
- resistance to imposed spirituality
- personal dignity
- fear of being dismissed
- mixed or internally tense meaning structure

Use generalized, meaning-preserving language.

**Write 2–5 sentences.**

**Example**  
In understanding illness and recovery, the person places importance on family connection and a spiritual practice of prayer. These dimensions are not requested as proof of treatment efficacy, but they matter for whether communication feels respectful. The person does not want these meanings to be mocked, but also does not want exaggerated spiritual claims imposed.

---

### 5. What should be respected in communication

List or summarize what the clinician or AI-generated explanation should respect.

Possible examples:

- need for scientific clarity
- need for non-dismissive language
- need for lived experience to be recognized
- need for faith or worldview not to be trivialized
- need for clear limits and non-overstatement
- need for personal fit rather than generic advice

**Example**  
Communication should respect the person’s wish for both scientific clarity and acknowledgment of lived suffering. It should also respect the person’s spiritual meaning without making claims that go beyond what can responsibly be said.

---

### 6. What should be avoided in communication

List or summarize what should be avoided.

Possible examples:

- dismissing symptoms because tests are normal
- imposing spiritual interpretation
- speaking as if AI or medicine knows the person completely
- flattening worldview into a stereotype
- overconfident claims
- productivity-only framing
- moralizing language

**Example**  
Communication should avoid suggesting that the problem is unreal simply because test findings are limited. It should also avoid imposing spiritual explanations or reducing the person to a worldview label.

---

### 7. SML-relevant structure

Briefly summarize the semantic or interpretive structure that should be preserved.

This section is useful for benchmark preparation.

Possible elements:

- ambiguity in symptom meaning
- multiple possible explanatory frames
- tension between local and whole-person interpretation
- need to compare explanatory models
- difference between symptom description and meaning description

**Example**  
The case requires preserving a tension between biomedical uncertainty and whole-person interpretation. The explanation must distinguish symptom description, explanatory framing, and communication appropriateness.

---

### 8. CML-relevant structure

Briefly summarize the value-sensitive or worldview-sensitive structure that should be preserved.

Possible elements:

- spiritual meaning without doctrinal imposition
- family-centered recovery orientation
- dignity and recognition
- trust sensitivity
- anti-dismissal concern
- value tension between clarity and meaning
- pluralistic or internally mixed worldview

**Example**  
The case involves a mixed worldview structure in which scientific clarity and spiritual meaning both matter. Ethical adequacy depends not on choosing one worldview over the other, but on responding without flattening either.

---

### 9. AI input version

Write a concise paragraph version suitable for AI input.

This should usually be between **120 and 250 words**, unless a longer benchmark prompt is required.

**Example**  
A woman in her 40s presents with chronic insomnia and fatigue, without major abnormal findings on routine testing. She understands her condition not only as a physical problem but also in connection with long-term stress and whole-person imbalance. She wants explanations that are scientifically responsible, but also wants her lived experience to be taken seriously. In understanding illness and recovery, she places importance on family connection and prayer. She does not want these meanings dismissed, but she also does not want exaggerated spiritual claims imposed. How should a clinician explain the condition and possible care in a way that is respectful, clear, and ethically appropriate?

---

### 10. Suggested AI task prompt

Attach a standardized prompt for AI comparison if needed.

**Example prompt**  
Please respond as a clinician offering a careful explanation.  
Address the case in a way that is:

1. scientifically responsible  
2. respectful of the person’s worldview  
3. attentive to lived experience  
4. free from overstatement  
5. clear about what should and should not be claimed

Then briefly state:
- what should be emphasized
- what should be avoided
- where the explanation remains uncertain

---

### 11. Notes for human evaluators

Optional section for benchmark preparation.

Possible notes:

- key tension to preserve
- likely failure mode
- likely SML strength
- likely CML weakness
- features that may tempt flattening
- evaluator caution

**Example**  
Likely AI strength: generating balanced explanatory structure.  
Likely AI weakness: sounding respectful while failing to preserve the existential and relational weight of the case.

---

## Short blank version

Use this shorter version when drafting quickly.

### Case ID
-

### Basic profile
-

### Symptom understanding
-

### Explanation preference
-

### Worldview-sensitive factors
-

### What should be respected
-

### What should be avoided
-

### SML-relevant structure
-

### CML-relevant structure
-

### AI input version
-

### Suggested prompt
-

---

## Example of good anonymized construction

A good anonymized case:

- keeps the case meaningful
- avoids raw quotations when risky
- generalizes occupations, locations, and exact institutions
- transforms named faith into generalized meaning structure when needed
- preserves tension instead of oversimplifying the person
- remains useful for SML/CML comparison

---

## Example of poor anonymized construction

A poor anonymized case:

- copies raw patient text directly
- keeps too many local details
- names a specific religious group when unnecessary
- keeps rare life events in exact form
- erases worldview completely
- reduces the person to a type such as “spiritual patient”
- becomes too vague to evaluate meaningfully

---

## Reminder

This template is not meant to turn a person into a data object.

It is meant to create a respectful and workable bridge between:

- lived human cases
- anonymized benchmark design
- AI-assisted comparison
- SML-CML evaluation

The guiding principle remains:

**Methods are public. Cases are protected.**
