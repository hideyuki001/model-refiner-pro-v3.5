# Examples of QA Evaluation

This document shows **practical examples** of how ModelRefiner Pro v3.5 outputs evaluation results.

---

## Example Scorecard

```yaml
scorecard:
  euqs_composite: 0.87
  rope_integration: 0.89
  gate_decision: "ship"
  gate_rationale: "RoPE core met; cultural ≥0.85; CI within tolerance"
  srank_status: "pass"
  euqs_dimensions:
    base_confidence: 0.85
    delta_s: 0.88
    rope_average: 0.89
    refiner_score: 0.87
    multilang_srank: 0.86
    temporal_stability: 0.90
    erdf_alignment: 0.85
    neural_alignment: 0.88
  rope_metrics:
    core: { svo_retention: 0.94, tone_consistency: 0.91, token_rhythm: 0.89 }
    extended: { emotional_alignment: 0.87, structural_aesthetic: 0.93, causal_chain_fidelity: 0.91 }
  cultural_context:
    weight_applied: 1.08
    sensitivity_flags: []
    regional_adaptation: "optimal"
  confidence_interval: "95%: [0.84, 0.90]"
  audit_trace_id: "mrp-v35-2025-09-xx-abc123"
  recommendations:
    - "Enhance token rhythm at sentence endings"
    - "Clarify causal chains in complex sentences"
    - "Maintain emotional alignment quality"
