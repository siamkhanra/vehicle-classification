# vehicle-classification using Deep Learning
This project classifies vehicle images into 4 categories using a Convolutional Neural Network (CNN) built with TensorFlow/Keras.

## Dataset
- Total images: 3200
- Categories: 4 vehicle types
- Split: 80% Training, 20% Validation

📥 Dataset download link: https://drive.google.com/file/d/1Q_GWeoU4Ivv3UEWD5rtKtwzx_YNHHP02/view?usp=drive_link

## Model Architecture
- 3 Convolutional layers with BatchNormalization
- MaxPooling after each conv layer
- Dense layers with Dropout for regularization
- Output: 4 classes with Softmax activation

## Results
- Validation Accuracy: 0.8875 (88.75%)
- Loss: 0.3535

## Features
- Image preprocessing and augmentation
- Real-time visualization of predictions
- Gradio web interface for easy testing
- Confusion matrix and classification report
