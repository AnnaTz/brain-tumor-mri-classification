
This project focuses on classifying brain tumors from MRI images using a deep learning model based on the EfficientNet B3 architecture. The goal is to assist in the early and accurate diagnosis of brain tumors, contributing positively to treatment outcomes.

## Key Features

- Utilizes EfficientNet B3 with a slightly altered architecture for brain tumor classification.
- Implements the data preprocessing steps needed to leverage the MRI image data.
- Employs data augmentation methods to enhance the model's robustness.
- Performs hyperparameter tuning using Ray Tune to optimize the model's training.
- Includes a comprehensive assessment of the model's performance on unseen data.

## Getting Started

### Prerequisites

- Python 3.8+
- PyTorch, torchvision, Ray, timm, and other required libraries listed in `requirements.txt`.

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/AnnaTz/brain-tumor-mri-classification
   ```
2. Install the dependencies:
   ```
   pip install -r requirements.txt
   ```

### Running the Project

Navigate to the project directory and launch the Jupyter notebook:
```
jupyter notebook mri_classification.ipynb
```

Follow the notebook's content for detailed steps on data preprocessing, model training, and evaluation.

## References

- Tan, M., & Le, Q. (2019). EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks. [Link to the paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10287923).
- Brain Tumor Classification (MRI) dataset on Kaggle: [Link to the dataset](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri).
