# CAS-Net

This is the official repository for “CAS-Net: Comparison-Based Attention Siamese Network for Change Detection with an Open High Resolution UAV Image Dataset”. The repo is based on Pytorch.

## Abstract

Change detection (CD) is a process of extracting changes on the Earth's surface from bitemporal images. When high-resolution remote sensing images are used, current CD methods require extensive computational resources and are susceptible to irrelevant noises embedded in the images. In addressing these challenges, a comparison-based attention Siamese network (CAS-Net) is proposed. The network utilizes the contrastive attention modules (CAMs) for feature fusion and employs a classifier to determine similarities and differences of bitemporal image patches. It simplifies pixel-level CD by comparing image patches. As such, influences of image background noises on change predictions are reduced. Along with the CAS-Net, an unmanned aerial vehicle (UAV) similarity detection (UAV-SD) dataset is built from high-resolution remote sensing images. This dataset, serving as a benchmark for CD, comprises 10,000 pairs of UAV images with a size of 256×256. Experiments of the CAS-Net on the UAV-SD dataset demonstrate that the CAS-Net is superior to other baseline CD networks. The CAS-Net detection accuracy is 93.1% on the UAV-SD dataset. The code and the dataset can be found at https://github.com/WenbaLi/CAS-Net.

![framework](./CAS-Net.jpg)

## Requirements
- Ubuntu 18.04
- Python 3.8
- pytorch 1.13.0
  

## UAV-SD dataset

UAV-SD dataset is available. [GoogleDrive](https://drive.google.com/file/d/1-9JVM9VgRd9pEwy4cnmpNMwh8SuSyZVc/view?usp=drive_link)


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
