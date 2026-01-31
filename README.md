# Factuality & Bias Review

This repository documents **structural, epistemic, and cultural biases** observed in the outputs of large language models (LLMs).

It does **not** focus on political, demographic, or fairness-related bias.  
Instead, it examines how well-aligned, policy-compliant models can still produce **systematic distortions affecting truthfulness, reasoning, and cultural grounding**.

The goal is to analyze **recurring cognitive tendencies** in LLM behavior — not isolated mistakes — through carefully documented prompt → output cases.

---

## 🎯 Scope and focus

This repository explores bias as a **model behavior pattern**, particularly in areas such as:

- Epistemic preferences (plausibility over truth)
- Frequency and majority effects in training data
- Cultural anchoring and implicit contextual assumptions
- Confidence calibration under uncertainty

These biases often appear **even when no explicit hallucination or policy violation occurs**.

---
The categories below are intentionally limited and conceptually distinct, 
focusing on bias as a reasoning tendency rather than a normative or ethical issue.

## 🧩 Bias categories

Current bias categories include:

- **Epistemic Bias**  
  Tendency to favor coherent or plausible answers over verified truth, especially under ambiguity.

- **Majority / Frequency Bias**  
  Preference for the most common, popular, or statistically dominant interpretation rather than the correct or context-specific one.

- **Cultural Anchoring Bias**  
  Implicit assumptions based on anglocentric, mainstream, or dominant cultural frameworks, leading to misinterpretation of local or minority contexts.

- **Confidence Calibration Bias**  
  Mismatch between the certainty expressed by the model and the actual strength of the available evidence.

Each category is documented through a small number of **highly annotated cases**, rather than large datasets.

---

## 📁 Repository structure

```text
factuality-bias-review/
│
├─ epistemic-bias/
├─ majority-bias/
├─ cultural-anchoring-bias/
├─ confidence-calibration-bias/
│
└─ README.md

This repository prioritizes depth, interpretability, and conceptual clarity over coverage or scale.
