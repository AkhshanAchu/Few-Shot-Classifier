# Few-Shot Ball Bearing Anomaly Detection using Prototypical Networks

This repository presents a lightweight few-shot learning approach for detecting anomalies in ball bearing images.  Prototypical Networks with a ResNet18 backbone, this project demonstrates high classification accuracy even with limited data — making it ideal for industrial inspection tasks with scarce labeled examples.

---

## Project Summary

- **Task**: Anomaly detection in ball bearing images using few-shot learning.
- **Model**: Prototypical Networks with a ResNet18 backbone for feature extraction.
- **Dataset Split**: 10% training, 80% testing, 10% evaluation.
- **Episodes**: Trained over 15,000 few-shot episodes.
- **Class Bias**: Included class imbalance awareness during training.
- **Accuracy**:
  - Training: **99.20%**
  - Testing: **97.92%**

---

## Dependencies

```text
torch
torchvision
tqdm
numpy
pandas
opencv-python
Pillow
easyfsl
```
