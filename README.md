## Abstract ##
Here we develop a robust machine vision pipeline for cell and organelle segmentation of volume EM datasets. The pipeline consists of a single lightweight Jupyter notebook that can be run on a consumer-grade desktop. We leverage the near-symmetric voxel shape of a Focused Ion Beam Scanning Electron Microscopy data to capture 3D correlations using 2D neural networks. We segment and analyze hundreds of platelets, and report quantitative morphological measurements consistent with published data. Our study paves the way for large-scale platelet studies, lending unique insight into thrombi formation and heart disease.

## Pipeline ##
![image](https://github.com/user-attachments/assets/a80caee9-71d3-43f1-bea1-c2cc7808269b)

## How to Use ##
Neural network initiation, training, and testing are contained within the Jupyter notebook.

#### Requirements ####
-NVIDIA GPU

-CUDA

-Python

-VSCode (recommended)

For setting up Cuda, visit:
https://www.youtube.com/watch?v=r7Am-ZGMef8

## Input Data ##
Input data should be in the .tif format. We recommend performing extensive augmentation, from which we generated our raw and labeled training datasets, along with small validation datasets. 

Raw data and training labels can be found at https://osf.io/mpysc/.

![Raw+LabeledTrainingImage](https://github.com/user-attachments/assets/094c190e-a195-435c-8ea7-6d02d96a2f80)

## Example Analysis ##
#### Cell and Organelle Predictions ####
Segmentation of platelet cell membrane, mitochondria, and a-granules. 

![segmentation-results](https://github.com/user-attachments/assets/c1a3b009-ecb3-4dfe-be07-de4fa6e42ded)

#### 3D Rendering and Volume Quantification in Amira ####
Rendering of platelet cell membrane, mitochondria, and a-granules for quantification of cell morphology.

![3d-rendering](https://github.com/user-attachments/assets/63681faa-24ca-4129-9349-ac2c618e099e)
