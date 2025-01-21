# Bone Fracture Detection System using CNNs

## Overview
This project was developed as part of a group project for our **Soft Computing Lab** in the final year of undergraduate studies. The primary objective of this project was to construct a classification system capable of detecting bone fractures from X-ray images, while also identifying the corresponding bone region within the body. 

Using the **MURA dataset** (a comprehensive dataset of musculoskeletal X-ray images), we implemented and evaluated several deep learning models, including **InceptionV3**, **ResNet50**, **DenseNet**, and **VGG-19**. This project integrates concepts of Convolutional Neural Networks (CNNs) to tackle the challenges of medical imaging and fracture detection.

## Dataset: MURA
- **MURA** (Musculoskeletal Radiographs) dataset contains:
  - **40,561 multi-view radiographic images**
  - Collected from **14,863 studies** conducted on **12,173 patients**.
- The dataset includes X-ray images of multiple bone regions, making it a valuable resource for medical imaging research.
- Dataset Link: - https://stanfordmlgroup.github.io/competitions/mura/

## Approach
1. **Research and Literature Review**: 
   - Conducted an extensive review of academic papers on fracture detection and CNN applications in medical imaging to gather valuable insights and refine our approach.
   
2. **Model Selection**: 
   - Implemented and trained several state-of-the-art CNN models, including:
     - **InceptionV3**
     - **ResNet50**
     - **DenseNet**
     - **VGG-19**
   - These models were chosen based on their proven performance in computer vision tasks.

3. **Implementation**:
   - Preprocessed the dataset for training and evaluation.
   - Fine-tuned hyperparameters to optimize model performance.

4. **Evaluation**:
   - Analyzed the results to identify strengths and limitations of the models.
   - Noted the challenges in achieving high accuracy for fracture detection and localization.
## Technologies Used
- **Deep Learning Frameworks**: TensorFlow, Keras
- **Programming Language**: Python
- **Dataset**: MURA
- **Models**: InceptionV3, ResNet50, DenseNet, VGG-19
