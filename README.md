# CAS-Net

This is the official repository for “SAS-Net: Similarity-Based Attention Siamese Network for Building Change Detection with an Open High Resolution UAV Image Dataset”. The repo is based on Pytorch.

## Abstract

Change detection (CD) is a process of extracting changes on the Earth’s surface from bitemporal images. However, when high-resolution remote sensing images are used, current CD methods require extensive computational resources and are susceptible to irrelevant noises embedded in the images. In addressing these challenges, a similarity-based attention Siamese network (SAS-Net) was proposed. The network utilizes the similarity attention modules (SAMs) for feature fusion and employs a classifier to determine similarities of bitemporal image patches. It simplifies pixel-level CDs by classifying patch similarities. As such, influences of image background noises on change predictions are reduced. Furthermore, there is a lack of high-resolution remote sensing image datasets captured by unmanned aerial vehicles (UAVs) for CD. Therefore, an UAV Similarity Detection (UAV-SD) dataset was built from high-resolution remote sensing images. This dataset serves as a benchmark for patch similarity comparison, comprising UAV 10,000 pairs of aerial images with a size of 256×256. Experiments of the SAS-Net on the UAV-SD dataset demonstrate that the SAS-Net is superior to other baseline CD networks. The SAS-Net detection accuracy is 93.1% on the UAV-SD dataset.

![framework](./framework.jpg)

## Requirements
- Ubuntu 18.04
- Python 3.8
- pytorch 1.13.0

## Installation


## Getting Started

### Train with a single GPU. 
```shell

```

### Test
```shell

```

### Evaluation



## UAV-SD dataset

UAV-SD dataset is available. [GoogleDrive](https://drive.google.com/file/d/1499SYQm1WklKdF1vGfVa6zQN-m_zId_N/view?usp=drive_link)


## Citation

Please cite this if you want to use it in your work.

```
@ARTICLE{WenbaLi,
  title={SAS-Net: Similarity-Based Attention Siamese Network for Building Change Detection with an Open High Resolution UAV Image Dataset}, 
  author={Yikui Zhai, Wenba Li, Tingfeng Xian, Xudong Jia, Zijun Tan, Jianhong Zhou, Junying Zeng and C. L. P. Chen},
  journal={}, 
  year={},
  volume={},
  number={},
  pages={},
  doi={}
}
```
