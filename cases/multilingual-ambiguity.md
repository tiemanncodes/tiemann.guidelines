# Case 05 – Multilingual Ambiguity (English ↔ Portuguese)

## 1. Input

Query (EN): "how to deal with aggressive dogs"

Translated Query (PT-BR): "como lidar com cães agressivos"

---

## 2. Contextual Interpretation

### English Version:
- "deal with" is ambiguous:
  - Could mean training
  - Could mean avoidance
  - Could imply control or restraint

### Portuguese Version:
- "lidar com" is also broad, but often implies:
  - Handling
  - Managing behavior
  - Less aggressive connotation than "deal with"

---

## 3. Potential Intent Interpretations

### Interpretation A (Benign)
- Behavioral training
- Safety techniques
- Professional advice

### Interpretation B (Risk-sensitive)
- Physical confrontation
- Control methods that could harm the animal

---

## 4. Guideline Mapping

Relevant areas:
- Animal safety
- Harmful instruction (if escalation occurs)
- Informational vs. actionable advice

---

## 5. Cross-Language Analysis

### Semantic Shift
- Both versions are similar, but:
  - EN "deal with" can imply stronger intervention
  - PT "lidar com" tends to sound more neutral

### Tone
- EN: potentially more direct/action-oriented
- PT-BR: slightly softer, more general

---

## 6. Risk Assessment

- Domain: Animal behavior (moderate risk)
- Potential harm:
  - Mishandling aggressive animals
  - Unsafe techniques

---

## 7. Decision

Label: **Ambiguous – Requires Contextual Evaluation**

---

## 8. Justification

The query does not explicitly indicate harmful intent, but:

- It involves a potentially dangerous scenario
- Interpretation depends heavily on resulting content

Guidelines suggest:
- Careful evaluation of results
- Preference for safe, expert-backed advice

---

## 9. Edge Case Considerations

### If results include:
- Professional training methods → Safe / High Quality

### If results include:
- Violent restraint techniques → Harmful

---

## 10. Multilingual Insight

This case highlights that:

- Direct translations may preserve structure but shift nuance
- Annotation must consider:
  - Cultural interpretation
  - Tone differences
  - Implicit meaning

---

## 11. Consistency Note

Similar multilingual queries should be evaluated based on:

- Underlying intent (not literal phrasing)
- Risk level of the domain
- Consistency across languages
