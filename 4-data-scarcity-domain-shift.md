# 4. Data Scarcity & Domain Shift

## Multiple Choice Questions (MCQs)

### 1. What is a major reason why rare infrastructure classes (e.g., small airports) are difficult to model in GeoAI?

- Geographic regions often lack such structures entirely.
- Labeled datasets often exclude rare classes intentionally.
- -✅ These classes are overwhelmed by dominant classes due to geographic sparsity.
- They have well-defined patterns and are easy to generalize.

---

### 2. Why might a coastal erosion model fail when applied inland?

- Coastal models are more accurate by design.
- Soil moisture levels are ignored in inland areas.
- Inland regions have higher elevation, affecting prediction.
- -✅ Soil composition and spectral characteristics differ significantly.

---

### 3. What technique helps identify novel land-cover types not seen during training?

- Semantic segmentation
- Transfer learning
- -✅ Open-set recognition with meta-learning
- Cross-validation

---

### 4. Why is manual annotation particularly problematic in geospatial data modeling?

- Labels are always inaccurate.
- Manual annotation adds temporal noise.
- -✅ It slows training and depends heavily on costly field visits.
- Annotators often mislabel radar data.

---

### 5. Which of the following is a solution to privacy constraints in sensitive geospatial data?

- Cloud data augmentation
- Active learning
- -✅ Federated learning
- Sensor simulation

---

### 6. A model trained in summer fails in winter due to:

- Low-resolution imagery
- Cloud obstructions
- -✅ Seasonal domain shifts and changes like snow cover
- Data corruption during transmission

---

### 7. How does discriminative learning rate help in domain adaptation?

- It regularizes the training error globally.
- -✅ It assigns smaller learning rates to general layers and larger to task-specific ones.
- It avoids data leakage.
- It ensures maximum accuracy on training data.

---

### 8. Why are lightweight models like MobileNet preferred in scarce label settings?

- They produce richer representations.
- -✅ They perform well without overfitting on small datasets.
- They are more explainable.
- They support larger input sizes.

---

### 9. How do GANs assist in addressing rare-class imbalance?

- By amplifying frequent class features.
- -✅ By generating synthetic samples of rare classes.
- Through compressing labels.
- By removing label noise from datasets.

---

### 10. What is the role of AutoAugment in geospatial modeling?

- It encodes spectral bands automatically.
- -✅ It learns optimal augmentation strategies using reinforcement learning.
- It discards irrelevant augmentations.
- It fine-tunes pretrained language models.

---

## ✅ Tricky True/False Questions

### 1. Stratified splits by geography or time can help simulate domain shifts during validation.

- ✅ True

---

### 2. Foundation models like ImageNet-pretrained weights are always superior for geospatial tasks.

- ❌ False — Domain-specific pretraining (e.g., BigEarthNet) is more effective.

---

### 3. Sensor calibration drift is a non-issue in modern satellite systems.

- ❌ False — Sensor degradation still contributes to domain shifts.

---

### 4. Open-set learning helps classify known categories with higher precision.

- ❌ False — It helps detect **unknown** categories not seen during training.

---

### 5. Parameter-efficient fine-tuning reduces overfitting by freezing all model layers.

- ❌ False — It adapts specific layers while using fewer parameters, not freezing all.

---
