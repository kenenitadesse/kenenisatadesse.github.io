---
layout: single
title: "Software & Reproducibility"
permalink: /software/
author_profile: true
---

I am committed to open science and reproducible research. Below are software packages and code repositories I have developed to support pharmacovigilance and drug safety research.

> **Note:** The original pharmacovigilance data used in these projects are owned by regional pharmacovigilance centers (CRPV Bordeaux, CRFV Veneto) and cannot be publicly shared due to regulatory restrictions. The code and methodology are fully provided for reproducibility with similar data structures.

---

## GitHub Repositories

### zGPS-AO-PSI
[github.com/kenenitadesse/zGPS-AO-PSI](https://github.com/kenenitadesse/zGPS-AO-PSI)

Integrates zero-inflated GPS modeling with an adverse-event ontology to enhance drug safety signal detection.

**Features:**
- Stratified, random, and thinned data splitting
- Validation-based MSE and ROC metrics
- Post-selection inference for model robustness assessment

**Languages:** R

---

### Finetuned_MedDRA_Coding
[github.com/kenenitadesse/Finetuned_MedDRA_coding](https://github.com/kenenitadesse/Finetuned_MedDRA_coding)

Fine-tuned transformer models (CamemBERT-bio) for MedDRA coding verification in pharmacovigilance.

**Focus:**
- Fine-tuning transformer-based models for medical text classification
- Binary classification under extreme class imbalance
- Text-only vs. multimodal model comparison

**Languages:** Python, PyTorch

---

## Tools & Technologies

| Category | Tools |
|----------|-------|
| **Programming** | R, Python, PyTorch, Hugging Face Transformers |
| **Statistical methods** | ZINB, Empirical Bayes, GPS, data thinning, permutation testing |
| **NLP** | CamemBERT-bio, text classification, regex, rule-based extraction |
| **Version control** | Git, GitHub |

---

## Research Software Philosophy

I believe in:
- **Open Source:** Making code freely available to advance research
- **Reproducibility:** Providing complete workflows so others can replicate results
- **Documentation:** Clear instructions and examples for users
- **Collaboration:** Contributing to and building upon community tools

---

## Citation

If you use any of these tools in your research, please cite the corresponding publications. For questions or contributions, feel free to open an issue on GitHub or contact me directly.
