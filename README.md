
# BraTS 2024 — Brain Tumor Segmentation & Analysis

End‑to‑end pipeline for the BraTS 2024 (post‑treatment glioma) challenge:
- ✅ Data preparation & sanity checks
- ✅ Baseline models (U‑Net / nnU‑Net or your custom)
- ✅ Training & experiment tracking
- ✅ Evaluation (Dice, HD95) + visualizations
- ✅ Reproducible configs & scripts

> **Status:** WIP — migrating notebooks & adding first baseline.

---

## 🔧 Environment

Choose one:

**Conda**
```bash
conda create -n brats24 python=3.10 -y
conda activate brats24
pip install -r requirements.txt
