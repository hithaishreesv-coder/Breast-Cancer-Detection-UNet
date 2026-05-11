# Breast Cancer Detection using U-Net

## Project Overview

This project uses a U-Net deep learning model for breast cancer image segmentation. The model is trained on breast ultrasound images and their corresponding mask images to identify affected regions.

The aim of this project is to support early breast cancer detection by applying medical image segmentation techniques.

## Dataset

The dataset contains breast ultrasound images divided into three categories:

- Benign
- Malignant
- Normal

Each image has a corresponding mask image used for segmentation training.

> Note: The dataset is not included in this repository due to file size and licensing considerations.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Imported required Python libraries
2. Loaded ultrasound images and mask images
3. Resized images and masks to 128x128 pixels
4. Normalised image and mask data
5. Split the dataset into training and validation sets
6. Built a U-Net model architecture
7. Trained the model using binary cross-entropy loss and Adam optimiser
8. Evaluated model performance
9. Predicted segmentation masks
10. Visualised original images, actual masks, and predicted masks

## Model Architecture

The U-Net model contains:

- Encoder path for feature extraction
- Decoder path for image reconstruction
- Skip connections to preserve spatial information
- Convolutional layers
- Max pooling layers
- Transposed convolution layers

## Results

The model generates predicted segmentation masks for breast ultrasound images. The output comparison includes:

- Original ultrasound image
- Actual mask
- Predicted mask
- Binary predicted mask

## How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/hithaishreesv-coder/Breast-Cancer-Detection-UNet.git

Open the project folder:
cd Breast-Cancer-Detection-UNet
Install the required libraries:
pip install numpy pandas matplotlib opencv-python pillow scikit-learn tensorflow keras jupyter
Open the Jupyter Notebook:
jupyter notebook "unet mask1.ipynb"
Run all cells in order.
Repository Files
unet mask1.ipynb - Jupyter Notebook containing the U-Net implementation
20022792_FPR-1.docx - Final project report
README.md - Project documentation

Author

Hithaishree Salur Vijay
