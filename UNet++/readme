## Multi-Class Image Segmentation with UNet++

This project is focused on solving a multi-class image segmentation problem using the UNet++ architecture with attention mechanisms. It leverages a custom dataset and applies deep learning techniques to predict and segment images into distinct classes.


You can explore the detailed implementation and results in the following Kaggle notebook:  
[UNet++ Multi-Class Image Segmentation](https://www.kaggle.com/code/igorjankowski/notebookac0379a87b)


### Dataset Source

This project uses the dataset from [Mendeley Data](https://data.mendeley.com/datasets/zbf6b4pttk/2), which contains raw label images and ground truth label images of axial view slices of lumbar spine MRI. The dataset is used to train a segmentation model (UNet++) to detect lumbar spinal stenosis.

#### Dataset Description

The dataset includes the following labeled Regions of Interest (ROIs) from T1-weighted axial-view MRI slices of the last three intervertebral discs (IVDs) in the lumbar spine:

1. **Intervertebral Disc (IVD)**
2. **Posterior Element (PE)**
3. **Thecal Sac (TS)**
4. **Area between Anterior and Posterior vertebral elements (AAP)**

The labeling process was performed by five labellers under the supervision of an expert radiologist. The task focused on accurately segmenting these anatomical structures to aid in the detection of lumbar spinal stenosis.



### Project Overview

The project includes:

- Data preprocessing and augmentation
- Training of the UNet++ model on a multi-class segmentation task
- Model evaluation using metrics such as Dice Score
- Visualization of segmentation results and training metrics


### Folder Structure

- **`models/`**: Contains saved model checkpoints during training.
- **`testResults/`**: Results of the model on the test dataset.
- **`treningMetrics/`**: Training-related metrics like loss and Dice score for each epoch.
- **`treningResults/`**: Training results, including model evaluation on the training set.

Additionally, the folder includes visualizations of training progress, such as:
- **`dice_score_heatmap.png`**: A heatmap showing Dice scores across different epochs.
- **`segmentation_results.png`**: A visualization of the segmentation results on sample test images, showing how accurately the model predicts and segments each class.



