# Example: EN → DE Translation QA

## Source Text
"Data privacy regulations must evolve as technology advances."

## Translation Output (DE)
"Die Datenschutzbestimmungen müssen sich weiterentwickeln, wenn die Technologie fortschreitet."

---

## Evaluation Scorecard

```yaml
scorecard:
  euqs_composite: 0.88
  rope_integration: 0.90
  gate_decision: "refine"
  srank_status: "pass"
  rope_metrics:
    core: { svo_retention: 0.95, tone_consistency: 0.89, token_rhythm: 0.87 }
    extended: { structural_aesthetic: 0.91 }
