# Image Cleaning Project
---

Last Updated: June 5, 2025

Author(s): Max Freitas, Dylan Marray

---
### **Project Goal**: Use ML methods to clean datasets before production
  - Brightness (too bright, or dim)
  - Orientation (this is quite trivial, but we can do this anyway)
  - Dims (this is quite trivial, but necessary)
  - Duplicates (remove images that are too similar)
  - Outliers (remove images off-topic)
  - Blurriness (deal with images out of focus, we can sharpen)
  - Too-similar augments (augments should be different enough, or not worth including in training)
---
### **Potential ML Modesl to Use**:
- **Clustering**
  - *KNN*
  - *SNN*: https://github.com/AngusNicolson/soft_nearest_neighbors
  - *Contrastive Clustering*
  - *BNN*
