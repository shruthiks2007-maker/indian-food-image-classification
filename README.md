# Indian Food Image Classification using MobileNetV2

## Project Overview
This intermediate machine learning project classifies food images into 20 categories using Transfer Learning with MobileNetV2.

## Technologies Used
- Python
- TensorFlow / Keras
- MobileNetV2
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Dataset
- Total images: 6,269
- Training images: 4,262
- Validation images: 1,066
- Test images: 941
- Number of classes: 20

## Methodology
1. Loaded and explored the image dataset.
2. Split the data into training, validation, and test sets.
3. Resized images to 224 × 224 pixels.
4. Applied data augmentation during training.
5. Used pretrained MobileNetV2 through transfer learning.
6. Evaluated the model using test accuracy, loss, a classification report, and a confusion matrix.

## Results
- Test Accuracy: 81.93%
- Test Loss: 0.6739

## How to Run
1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Allow the dataset and pretrained model weights to load.
4. Train and evaluate the model.

## Model
The model was built using MobileNetV2 pretrained on ImageNet, with a custom classification layer for 20 food categories.

## Author
Shruthi K S
