# 🛡️ ModelRefiner Pro v3.5 — Multilingual QA Framework
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![GitHub stars](https://img.shields.io/github/stars/hideyuki001/model-refiner-pro-v3.5?style=social)
![Release](https://img.shields.io/github/v/release/hideyuki001/model-refiner-pro-v3.5)

**Intended audience**: Translation QA specialists, LLM data quality managers, researchers  

This repository provides the design documentation for a **multilingual translation quality evaluation framework**, integrating:  
- **EUQS (7-dimension scoring)**  
- **RoPE (SVO retention / tone / rhythm + emotion / aesthetics / causality)**  

---

## 📖 Documentation
- [System Instructions (8000 chars)](docs/system_instructions.md)  
  → Full specification (published in full for transparency and research reproducibility)  
- [Translation Matrix](docs/translation_matrix.md)  
  → Language pair thresholds (BLEU/ROUGE, RoPE priorities, cultural weights)  
- [RoPE Metrics](docs/rope_metrics.md)  
  → Definitions of SVO retention, tone consistency, rhythm, aesthetics, causality  
- [Examples](docs/examples.md)  
  → Practical QA examples and scorecard samples  

---

## 🧪 Examples
- [EN→JA Translation QA](examples/en-ja_sample.md)  
- [EN→DE Translation QA](examples/en-de_sample.md)  
- [Creative text evaluation](examples/creative_eval.md)  

---

## ⚠️ Notes
- This repository is intended as a **reference for translation QA and LLM data quality improvement**.  
- Exact reproduction of system behavior is **not guaranteed**, as results may vary depending on model and environment.  
- The focus is on **framework transparency and applicability**, not strict reproducibility.  

---

## 📜 License
MIT License or Apache License 2.0 recommended.
