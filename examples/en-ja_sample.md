# Example: EN → JA Translation QA

## Source Text
"The rapid adoption of AI in healthcare brings both opportunities and ethical challenges."

## Translation Output (JA)
「医療におけるAIの急速な導入は、機会と倫理的課題の両方をもたらしている。」

---

## Evaluation Scorecard

```yaml
scorecard:
  euqs_composite: 0.91
  rope_integration: 0.92
  gate_decision: "ship"
  srank_status: "pass"
  rope_metrics:
    core: { svo_retention: 0.96, tone_consistency: 0.93, token_rhythm: 0.91 }
    extended: { emotional_alignment: 0.90, structural_aesthetic: 0.92, causal_chain_fidelity: 0.93 }
