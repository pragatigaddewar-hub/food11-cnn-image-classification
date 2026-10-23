# Food-11 Image Classification Using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify food images into 11 different food categories using TensorFlow and Keras.

The model learns visual features from food images and predicts the category of a given image.

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
- **Dataset:** Food-11
- **Training images:** 9,900
- **Validation images:** 1,100
- **Number of classes:** 11
- **Image size:** 128 × 128 pixels

## Model Architecture
The CNN model includes:
- Image augmentation
- Image rescaling
- Convolutional layers
- Max pooling layers
- Flatten layer
- Dense layer with ReLU activation
- Dropout for regularization
- Softmax output layer for multiclass classification

## Data Preprocessing
- Resized images to 128 × 128 pixels
- Rescaled pixel values
- Applied image augmentation using random flipping, rotation, and zoom
- Loaded images using TensorFlow's image dataset utilities

## Model Training
The model was trained using TensorFlow/Keras with categorical classification and validation data.

## Model File
The trained model is saved as:

`food11_cnn_25mb.keras`

The model file is included in this repository for reuse without retraining.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install tensorflow numpy matplotlib seaborn scikit-learn
   ```

3. Download and extract the Food-11 dataset.
4. Update the training and testing dataset paths in the Python script.
5. Run the Python file:

   ```bash
   python food_11_cnn_classification.py
   ```

## Applications
- Food image classification
- Image recognition
- Deep learning and computer vision practice

## Future Improvements
- Improve generalization on unseen images
- Experiment with different CNN architectures
- Apply transfer learning using pretrained models
- Optimize inference speed and model size

## Author
**Pragati Gaddewar**

GitHub: https://github.com/pragatigaddewar-hub
