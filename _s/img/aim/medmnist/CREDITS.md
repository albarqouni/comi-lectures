# MedMNIST+ extracts

Sprite sheets (first 12 test images per class) extracted from MedMNIST+ v3.0, Zenodo doi:10.5281/zenodo.10519652.
Licence CC BY 4.0 (DermaMNIST: CC BY-NC 4.0). Not for clinical use.

Cite: Yang J, et al. MedMNIST v2 – a large-scale lightweight benchmark for 2D and 3D biomedical image classification. Sci Data 2023;10:41.
Yang J, Shi R, Ni B. MedMNIST Classification Decathlon. IEEE ISBI 2021:191–5. Plus the source datasets of each subset.

## Derived audits (our own, for teaching)

- `audit.png/json` — corner-feature audit of all 624 PneumoniaMNIST test X-rays (source data: Kermany DS, et al. Cell 2018;172:1122–31). Simple detector for burned-in letters and black borders in the top corners; flagged images 31 % pneumonia vs 75 % unflagged; corners-only AUC 0.72.
- `ita.png/json` — skin-tone (ITA) audit of all 2,005 DermaMNIST test images (source data: HAM10000, Tschandl P, et al. Sci Data 2018;5:180161). Rough colour proxy; images in darker categories were checked visually and are mostly reddened skin or frame-filling lesions.
