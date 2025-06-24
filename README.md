# DiverseHeadNet - Semi-supervised Semantic Segmentation for Road Extraction

**A PyTorch implementation of DiverseHeadNet for semi-supervised segmentation on road extraction benchmarks (e.g. DeepGlobe, Massachusetts, DFC2020, DiverseRoad).**
## 📝 References

- DiverseHeadNet paper:  
  [Decision Diversified Semi-supervised Semantic Segmentation Networks for Remote Sensing Imagery (CVPR 2023)](https://arxiv.org/abs/2311.13716)
- DiverseRoad Dataset:  
  [https://github.com/XihGaiTihQai/DiverseRoad](https://github.com/XihGaiTihQai/DiverseRoad)

## ⭐️ Features

- Multi-head DeepLabV3 backbone (DiverseHeadNet) for semi-supervised segmentation.
- Dynamic freezing, voting pseudo-label, confidence filtering.
- Support for custom and public remote sensing road extraction datasets.
- Training & inference scripts included.

---

## 📂 Dataset Structure

**Organize your dataset as follows** (example for DeepGlobe/DiverseRoad):

