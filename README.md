# cnn-cat-dog-classifier
CNN-based image classification model for binary classification using image augmentation techniques.

Cat vs Dog Image Classification Model
This is a Convolutional Neural Network (CNN) model built using TensorFlow and Keras to classify images of cats and dogs. The model uses a simple architecture of convolutional layers followed by fully connected layers for binary classification.

Requirements.
Python 
TensorFlow 
Keras
NumPy
Jupyter (optional for notebook usage)

License
This project is licensed under the MIT License - see the LICENSE file for details.

Dataset Structure:

dataset/
├── training_set/
│   ├── cat/
│   │   ├── cat1.jpg
│   │   ├── cat2.jpg
│   │   ├── ...
│   └── dog/
│       ├── dog1.jpg
│       ├── dog2.jpg
│       ├── ...
├── test_set/
│   ├── cat/
│   │   ├── cat1.jpg
│   │   ├── cat2.jpg
│   │   ├── ...
│   └── dog/
│       ├── dog1.jpg
│       ├── dog2.jpg
│       ├── ...
└── single_prediction/
    ├── cat_or_dog_1.jpg
    ├── cat_or_dog_2.jpg
    └── ...
