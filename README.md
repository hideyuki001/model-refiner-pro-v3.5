# 🛡️ ModelRefiner Pro v3.5 — Multilingual QA Framework

![License](https://img.shields.io/badge/License-MIT-green.svg) 
![Stars](https://img.shields.io/github/stars/hideyuki001/model-refiner-pro-v3.5?style=social) 
![Release](https://img.shields.io/github/v/release/hideyuki001/model-refiner-pro-v3.5)

---

## 🎯 Intended Audience
Translation QA specialists, LLM data quality managers, researchers

This repository provides the design documentation for a **multilingual translation quality evaluation framework**, integrating:

- **EUQS** (7-dimension scoring)  
- **RoPE** (SVO retention / tone / rhythm + emotion / aesthetics / causality)

---

## 📖 Documentation
- [docs/system_instructions.md](docs/system_instructions.md) → Full specification (8000 chars, transparency & reproducibility)  
- [docs/translation_matrix.md](docs/translation_matrix.md) → Language pair thresholds (BLEU/ROUGE, RoPE priorities, cultural weights)  
- [docs/rope_metrics.md](docs/rope_metrics.md) → Definitions of SVO retention, tone consistency, rhythm, aesthetics, causality  
- [docs/examples.md](docs/examples.md) → Practical QA case guide  

---

## 🧪 Examples
- [examples/en-ja_sample.md](examples/en-ja_sample.md) → Japanese high-context QA example  
- [examples/en-de_sample.md](examples/en-de_sample.md) → German technical translation QA  
- [examples/creative_eval.md](examples/creative_eval.md) → Creative marketing copy evaluation (JA / ES / DE)  

---

## ⚠️ Notes
- This repository is intended as a **reference for translation QA and LLM data quality improvement**.  
- Exact reproduction of system behavior is **not guaranteed**, as results may vary depending on model and environment.  
- The focus is on **framework transparency and applicability**, not strict reproducibility.  

---

## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  

---

## 🚀 Usage
Browse the **examples/** folder to see how ModelRefiner Pro v3.5 can be applied to multilingual translation QA:  

- `en-ja_sample.md` → Japanese QA example  
- `en-de_sample.md` → German QA example  
- `creative_eval.md` → Creative text evaluation  

For detailed scoring dimensions and evaluation metrics, check the **docs/** folder.  
