# TDA-YOLO
## Introduction

This repository contains the experimental data used for validating the results presented in our research paper on the TDA-YOLO model. The data is organized to facilitate easy access and verification of the results by storing training and validation outputs for different YOLO-based models. In addition to this, we provide you with download links to the open-source datasets used in this repository.
![Overview of the structure of TDA-YOLO](/images/TDA-YOLO.png)

## Repository Structure

The repository is structured into two main directories, each containing data from different phases of model evaluation:

### 1. Train

This directory contains the results from the training phase of the models. It is subdivided into three specific subdirectories:

- **YOLO**: Contains training result images and logs for the standard YOLO model.
  
- **TDA-YOLO**: Stores training results specific to our proposed TDA-YOLO model, including visual outputs and log files.
  
- **Other-YOLO**: Includes training results for other YOLO variants compared in this study.

### 2. Value

This directory includes validation data from the testing phase of the models. The structure is similar to the "Train" directory:

- **YOLO**: Contains validation result images and logs for the standard YOLO model.
  
- **TDA-YOLO**: Stores validation results for the TDA-YOLO model.
  
- **Other-YOLO**: Includes validation data for other YOLO variants evaluated during the research.

## How to Use This Repository

1. **Navigate**: Use the above directory structure to navigate to the specific model and phase you are interested in.
   
2. **Access Data**: Each subdirectory contains graphical outputs (such as training and validation accuracy plots) that reflect the performance of the respective model.

3. **Verification**: These results can be used to verify the findings presented in our research paper.

4. **DataSets**：The experimental dataset we used is an open source dataset:
   - **VisDrone2019**: https://github.com/VisDrone/VisDrone-Dataset
   - **Dotav2**: https://github.com/ultralytics/yolov5/releases/download/v1.0/DOTAv2.zip

## Citation

If you find this repository useful in your research, please consider citing our paper:

