# DiverseHeadNet - Semi-supervised Semantic Segmentation for Road Extraction

**A PyTorch implementation of DiverseHeadNet for semi-supervised segmentation on road extraction benchmarks (e.g. DeepGlobe, Massachusetts, DFC2020, DiverseRoad).**
## 📝 References

- DiverseHeadNet paper:  
  [Decision Diversified Semi-supervised Semantic Segmentation Networks for Remote Sensing Imagery (CVPR 2023)](https://arxiv.org/abs/2311.13716)

## ⭐️ Features

- Multi-head DeepLabV3 backbone (DiverseHeadNet) for semi-supervised segmentation.
- Dynamic freezing, voting pseudo-label, confidence filtering.
- Support for custom and public remote sensing road extraction datasets.
- Training & inference scripts included.

---

## 📂 Dataset Structure
## 📂 Public Road Datasets

- DiverseRoad (official, CVPR 2023):  
  [https://github.com/XihGaiTihQai/DiverseRoad](https://github.com/XihGaiTihQai/DiverseRoad)

- DeepGlobe Road Extraction (CVPR 2018):  
  [https://competitions.codalab.org/competitions/18467#learn_the_details-datasets](https://competitions.codalab.org/competitions/18467#learn_the_details-datasets)

- Massachusetts Roads Dataset:  
  [https://www.cs.toronto.edu/~vmnih/data/](https://www.cs.toronto.edu/~vmnih/data/)

- DFC2020 (IEEE GRSS):  
  [https://ieee-dataport.org/open-access/dfc2020-data-fusion-contest](https://ieee-dataport.org/open-access/dfc2020-data-fusion-contest)


