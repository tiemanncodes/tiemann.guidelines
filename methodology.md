# Annotation Methodology

This methodology reflects a guideline-driven annotation workflow designed for consistency, interpretability, and scalability.

---

## 1. Guideline Decomposition

Before annotating, guidelines are broken down into:

- Core rules (mandatory constraints)
- Conditional rules (context-dependent)
- Exceptions and edge cases

This step ensures correct rule prioritization.

---

## 2. Query & Content Interpretation

Each input is analyzed based on:

- User intent (informational, transactional, navigational)
- Clarity (clear vs. ambiguous vs. underspecified)
- Risk level (safe vs. sensitive vs. potentially harmful)

---

## 3. Ambiguity Resolution

When multiple interpretations are possible:

- Identify dominant intent
- Consider plausible alternative intents
- Apply conservative judgment in sensitive domains

---

## 4. Guideline Mapping

Relevant rules are explicitly mapped to the case:

- Which rule applies?
- Why this rule over others?
- Are there conflicting rules?

---

## 5. Decision Framework

Decisions are made based on:

- Alignment with guideline rules
- Consistency with similar cases
- Risk minimization (especially for sensitive topics)

---

## 6. Justification Protocol

Every decision must:

- Be explicit and structured
- Reference guideline logic (not personal opinion)
- Address ambiguity where applicable

---

## 7. Consistency Check

Before finalizing:

- Compare with previous similar cases
- Ensure no contradiction in reasoning
- Validate classification stability

---

## Key Principle

> In high-quality annotation, the reasoning must be reproducible, not just the label.
