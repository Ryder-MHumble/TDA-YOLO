# TDA-YOLO

This repository contains the experimental data used for validating the results presented in our research paper on the TDA-YOLO model. The data is organized to facilitate easy access and verification of the results by storing training and validation outputs for different YOLO-based models. In addition to this, we provide you with download links to the open-source datasets used in this repository.
## Abstract
Unmanned Aerial Vehicle (UAV) remote sensing imagery (RSI) has been widely recognized across various industries for its effectiveness in target detection. However, existing methods that enhance spatial sensing fields using large kernel convolutions or dilated convolutional backbones often fall short of effectively capturing fine-grained features, leading to suboptimal performance in complex environments with varying object scales and densities. In this study, we introduce TDA-YOLO, an advanced adaptive detection model uniquely designed with optimized sampling and dynamic sensing head modules. To address spatial redundancy and loss of critical feature information during downsampling, we propose a Light Adaptive Weight DownSampling (LAWDS) technique that adaptively adjusts feature importance, ensuring selective retention of valuable spatial information while minimizing computational complexity. Additionally, we incorporate the Dynamic UpSampling (DUS) method to reduce computational overhead by selectively upsampling relevant points. We further enhance the model's adaptability with Deformable Dynamic Detect (TD Detect), a novel detection head that employs dynamic offsets for non-regular sampling, significantly improving generalization across diverse image distortions. Moreover, we introduce InnerDimension-IoU (ID-IoU), a novel bounding box regression loss function tailored to minimize the influence of varying bounding box sizes on regression accuracy. Extensive experiments on the VisDrone and DOTAv2 datasets demonstrate the superior performance of TDA-YOLO, achieving higher precision and mAP compared to other models, thereby confirming its effectiveness and robustness in diverse real-world scenarios.
![Overview of the structure of TDA-YOLO](/images/TDA-YOLO.png)

## Repository Structure

The repository is structured into two main directories, each containing data from different phases of model evaluation:

### 1. Train

This directory contains the results from the training phase of the models. It is subdivided into three specific subdirectories:

- **YOLO**: Contains training result images and logs for the standard YOLO models and other YOLO models during the research.
  
- **TDA-YOLO**: Stores training results specific to our proposed TDA-YOLO model, including visual outputs and log files.

### 2. Value

This directory includes validation data from the testing phase of the models. The structure is similar to the "Train" directory:

- **YOLO**: Contains validation result images and logs for the standard YOLO models and other YOLO models during the research.
  
- **TDA-YOLO**: Stores validation results for the TDA-YOLO model.

## How to Use This Repository

1. **Navigate**: Use the above directory structure to navigate to the specific model and phase you are interested in.
   
2. **Access Data**: Each subdirectory contains graphical outputs (such as training and validation accuracy plots) that reflect the performance of the respective model.

3. **Verification**: These results can be used to verify the findings presented in our research paper.

4. **DataSets**：The experimental datasets we used are two open source datasets:
   - **VisDrone2019**: https://github.com/VisDrone/VisDrone-Dataset
   - **Dotav2**: https://github.com/ultralytics/yolov5/releases/download/v1.0/DOTAv2.zip

## Citation

If you find this repository useful in your research, please consider citing our paper:

