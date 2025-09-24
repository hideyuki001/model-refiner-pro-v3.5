# Example: Creative Text Evaluation (Multilingual)

## Source Text (Marketing Copy)
"Unlock the future of communication — where every voice matters."

---

## Translation Output (JA)
「すべての声が価値を持つ、未来のコミュニケーションを解き放とう。」

## Translation Output (ES)
"Desbloquea el futuro de la comunicación — donde cada voz importa."

## Translation Output (DE)
"Entfalte die Zukunft der Kommunikation — in der jede Stimme zählt."

---

## Evaluation Scorecard (JA)

```yaml
scorecard:
  euqs_composite: 0.89
  rope_integration: 0.91
  gate_decision: "ship"
  srank_status: "pass"
  rope_metrics:
    core: { svo_retention: 0.92, tone_consistency: 0.90, token_rhythm: 0.89 }
    extended: { emotional_alignment: 0.91, structural_aesthetic: 0.93, causal_chain_fidelity: 0.90 }
