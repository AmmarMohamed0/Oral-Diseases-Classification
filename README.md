# Oral-Diseases-Classification
## Introduction

Oral-Diseases-Classification is a deep learning project designed to classify oral diseases such as Calculus, Caries, Gingivitis, Ulcers, Tooth Discoloration, and Hypodontia from images. The project leverages a ResNet18 model to automate the diagnosis process, aiding healthcare professionals in identifying oral conditions efficiently. By providing accurate and fast classification, this tool aims to improve early detection and treatment planning for oral diseases.

## Features
- **Multi-Class Classification**: Classifies six common oral diseases.

- **Data Augmentation**: Enhances model robustness with transformations like rotation and flipping.

- **Early Stopping**: Prevents overfitting by halting training when validation loss stops improving.

- **Learning Rate Scheduling**: Optimizes training with dynamic learning rate adjustments.

- **Visualization Tools**: Includes loss/accuracy curves, confusion matrix, and classification reports.

- **Pre-Trained Model**: Utilizes ResNet18 for efficient transfer learning.

## Technologies
**Frameworks**: PyTorch

**Libraries**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, PIL

**Tools**: Torchvision, DataLoader, ReduceLROnPlateau

**Pre-Trained Model**: ResNet18

**Link of Dateset** https://www.kaggle.com/datasets/salmansajid05/oral-diseases
