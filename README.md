# Lumbar Spine MRI Segmentation Project

This project focuses on the segmentation of lumbar spine MRI images to identify key anatomical structures related to lumbar spinal stenosis. The work was conducted in collaboration with **Aleksandra Borowska (Ola2808-Boro)**, where two different state-of-the-art segmentation models were implemented and compared:

- **UNet++**: Implemented by Igor Jankowski, designed for detailed and accurate segmentation with a focus on refining boundaries and hierarchical learning.
- **DeepLab**: Implemented by Aleksandra Borowska, utilizing atrous convolutions for semantic segmentation with high contextual understanding.

### Project Goals

- **Develop Robust Segmentation Models**: Train and evaluate DeepLab and UNet++ models on the dataset to achieve high accuracy in identifying lumbar spine regions.
- **Analyze Performance**: Compare the performance of the two models using metrics like Dice scores and visualizations of segmentation results.
- **Support Medical Diagnosis**: Facilitate the detection of lumbar spinal stenosis through precise anatomical segmentation.

### Dataset

The dataset was sourced from [Mendeley Data](https://data.mendeley.com/datasets/zbf6b4pttk/2) and includes T1-weighted axial-view MRI slices of the last three intervertebral discs (IVDs). Key regions of interest (ROIs) labeled in the dataset are:

1. Intervertebral Disc (IVD)
2. Posterior Element (PE)
3. Thecal Sac (TS)
4. Area between Anterior and Posterior vertebral elements (AAP)

Labeling was performed by multiple experts under the supervision of a radiologist to ensure quality and consistency.

### Key Features of the Project

- **Model Comparison**: Implementation and evaluation of UNet++ and DeepLab models to determine strengths and limitations of each approach.
- **Custom Preprocessing and Augmentation**: Use of Albumentations for data augmentation to enhance the robustness of the models.
- **Detailed Metrics**: Evaluation using multi-class Dice scores to quantify model performance.

### Results and Outputs

- **Segmentation Results**: Visualizations highlighting model predictions versus ground truth labels.
- **Performance Metrics**: Metrics, such as Dice scores for each region of interest, to demonstrate model effectiveness.
- **Model Artifacts**: Best-performing models and training artifacts stored in the output directory.

### Collaborative Contributions

- **Aleksandra Borowska (Ola2808-Boro)**: Developed the DeepLab model implementation, focusing on contextual segmentation and overall architecture design.
- **Igor Jankowski (elprofesoriqo)**: Focused on the UNet++ architecture, emphasizing detailed boundary refinement and multi-scale feature learning.

This collaborative effort combined different strengths and perspectives, resulting in a comprehensive exploration of segmentation techniques for lumbar spine MRI images.

### Acknowledgments

This project was conducted as part of a collaborative effort within the **MILab** initiative led by Daniel Cieślak. The aim of the case study was to develop segmentation solutions for a dataset available at [Mendeley Data](https://data.mendeley.com/datasets/k57fr854j2/2). 
