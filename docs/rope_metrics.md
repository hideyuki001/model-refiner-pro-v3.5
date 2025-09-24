# RoPE Metrics (Role-based Pattern Evaluation)

This document defines the **RoPE evaluation metrics** used in ModelRefiner Pro v3.5.  
They are grouped into **Core Metrics** (applied to all languages) and **Extended Metrics** (applied to high-context languages).

---

## Core Metrics (all language pairs)

- **SVO Retention**  
  Measures how well the Subject-Verb-Object structure is preserved.  
  *Target: ≥ 0.94*

- **Tone Consistency**  
  Evaluates consistency in register, sentiment, and politeness.  
  *Target: ≥ 0.90*

- **Token Rhythm**  
  Assesses pacing and natural rhythm of sentences.  
  *Target: ≥ 0.88*

---

## Extended Metrics (high-context languages only)

- **Emotional Alignment (HeartVision)**  
  Checks if the emotional tone of the source is faithfully carried into the target.  
  *Target: ≥ 0.86*

- **Structural Aesthetics (ArtVision)**  
  Evaluates clarity, stylistic balance, and elegance of phrasing.  
  *Target: ≥ 0.92*

- **Causal Chain Fidelity (Synapse)**  
  Ensures logical progression and cause-effect relationships are intact.  
  *Target: ≥ 0.90*
