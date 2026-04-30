# Case 04 – Relevance and User Intent Mismatch

## 1. Input
Query: "how to train a puppy"

Result snippet:
"Top 10 luxury dog accessories you must buy in 2025"

---

## 2. Contextual Interpretation

The query is clearly informational:
- The user is seeking guidance on puppy training

The result is commercial and product-focused.

---

## 3. Guideline Mapping

Relevant guideline areas:

- Relevance to user intent
- Content usefulness
- Informational vs. commercial mismatch

Guidelines emphasize:
- Direct alignment with user needs
- Practical usefulness of results

---

## 4. Intent Classification

- Query intent: Informational
- Result type: Commercial / promotional

Mismatch identified.

---

## 5. Decision

Label: **Not Relevant**

---

## 6. Justification

The result does not address the user's need for training guidance.

Instead, it:
- Promotes products
- Provides no instructional value
- Fails to deliver actionable information

Guidelines prioritize usefulness and intent alignment, both of which are absent here.

---

## 7. Edge Case Considerations

- If the result included:
  - Training tools with explanation (e.g., clickers, leashes)
  → It could be partially relevant

However, pure product lists without instructional context remain irrelevant.

---

## 8. Consistency Note

Similar mismatches should be flagged:
- Informational query → commercial-only results
- Educational intent → entertainment content

Consistency in intent matching is critical.
