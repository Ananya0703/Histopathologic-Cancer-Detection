# Histopathologic Cancer Detection

## Overview

This repository contains code and resources for a histopathologic cancer detection project. The project aims to use deep learning techniques to identify metastatic tissue in histopathological images. The primary focus is on leveraging the PatchCamelyon Metastatic Tissue Classification Dataset and a ResNet-50 architecture to achieve accurate classification.

## Abstract

Histopathologic cancer detection is a critical component of early cancer diagnosis and treatment planning. This project explores the application of deep learning models to automate the identification of metastatic tissue in histopathological images. The methodology involves transfer learning using a ResNet-50 architecture, fine-tuning it on the PatchCamelyon dataset. The results show promising potential for improving cancer diagnosis.

## Data

The project uses the PatchCamelyon Metastatic Tissue Classification Dataset, a dataset of histopathological images of lymph node sections. The dataset is well-balanced with both malignant and benign samples, making it suitable for model training and evaluation.
Data Source : https://github.com/basveeling/pcam
## Methodology

The core methodology of this project revolves around transfer learning with the ResNet-50 architecture. The model is pretrained on a large dataset to leverage feature transfer learning. Custom layers, data augmentation, and early stopping techniques are employed to fine-tune the model for histopathologic cancer detection.

## Results

The results demonstrate the effectiveness of the deep learning model in accurately identifying cancerous regions in histopathological images. Metrics such as accuracy, precision, recall, and F1-score, along with the Receiver Operating Characteristic (ROC) curve, reflect the model's strong performance.

## Usage

To use this project:

1. Clone this repository to your local machine.
2. Run the Jupyter Notebook to train and test the histopathologic cancer detection model.
3. Feel free to adjust hyperparameters, experiment with different architectures, or further customize the code to suit your needs.

## Contributing

If you wish to contribute to this project, you are welcome to open issues, provide feedback, or submit pull requests. Your contributions are greatly appreciated.

