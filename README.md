# TDA-YOLO
This repository contains a selection of experimental data used to validate the results presented in our TDA-YOLO modeling research paper. By storing the training and validation outputs of different YOLO-based models, these data are organized for easy access and validation of the results. In addition, we provide you with download links to the open-source datasets used in this repository.
## Abstract
Unmanned Aerial Vehicle (UAV) remote sensing imagery (RSI) has been widely recognized across various industries for its effectiveness in target detection. However, existing methods that enhance spatial sensing fields using large kernel convolutions or dilated convolutional backbones often fall short of effectively capturing fine-grained features, leading to suboptimal performance in complex environments with varying object scales and densities. In this study, we introduce TDA-YOLO, an advanced adaptive detection model uniquely designed with optimized sampling and dynamic sensing head modules. To address spatial redundancy and loss of critical feature information during downsampling, we propose a Light Adaptive Weight DownSampling (LAWDS) technique that adaptively adjusts feature importance, ensuring selective retention of valuable spatial information while minimizing computational complexity. Additionally, we incorporate the Dynamic UpSampling (DUS) method to reduce computational overhead by selectively upsampling relevant points. We further enhance the model's adaptability with Deformable Dynamic Detect (TD Detect), a novel detection head that employs dynamic offsets for non-regular sampling, significantly improving generalization across diverse image distortions. Moreover, we introduce InnerDimension-IoU (ID-IoU), a novel bounding box regression loss function tailored to minimize the influence of varying bounding box sizes on regression accuracy. Extensive experiments on the VisDrone and DOTAv2 datasets demonstrate the superior performance of TDA-YOLO, achieving higher precision and mAP compared to other models, thereby confirming its effectiveness and robustness in diverse real-world scenarios.
![Overview of the structure of TDA-YOLO](/images/TDA-YOLO.png)

## Repository Structure

The repository is structured into two main directories, each containing data from different phases of model evaluation:

### 1. Screenshot of experimental data

This directory contains the results from the training phase of the models. It is subdivided into three specific subdirectories:

- **Train**: This directory is used to store screenshots of training result data for some of the models from the two open-source datasets.
- ***VisDrone***
- ***DOTAv2***
  
- **Val**: This directory is used to store screenshots of value result data for some of the models from the two open-source datasets.
- ***VisDrone***
- ***DOTAv2***

### 2.Code

## Experimental Datasets
 **DataSets**：The experimental datasets we used are two open source datasets:
   - **VisDrone2019**: https://github.com/VisDrone/VisDrone-Dataset
   - **Dotav2**: https://github.com/ultralytics/yolov5/releases/download/v1.0/DOTAv2.zip

## Citation

If you find this repository useful in your research, please consider citing our paper:

