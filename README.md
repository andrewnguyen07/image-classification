# Image Classification

This project shows a set of Jupyter Notebooks demonstrating a variety of Convolutional Neural Networks models I built and tuned to classify images for the [Intel Image](https://www.kaggle.com/puneet6060/intel-image-classification) dataset. The dataset has been split into train and test folders, each of which contains a series of 150x150 images that range from 6 classes. 

## List of notebooks:

* [1-Convolution Layer CNN](https://github.com/andrewnguyen07/image-classification/blob/master/CNN-1Conv.ipynb): Trained a simple CNN classifier with 1 convolution layer, 1 max-pooling layer, and 2 dense layers, which achieved 94% accuracy for train and 72% for test. Tuned with data augmentation and achieved lower accuracy scores (~70%) yet more stable learning curves.
* [3-Convolution Layer CNN](https://github.com/andrewnguyen07/image-classification/blob/master/CNN-3Conv.ipynb): Trained a deeper CNN classifier with 3 convolution layers, 3 max-pooling layers, 1 dropout layer, and 2 dense layers, which achieved 91% accuracy for train and 80% for test. Tuned with data augmentation and achieved higher accuracy scores (~80%) compared to 1-Conv CNN and more stable learning curves.
* [VGG16](https://github.com/andrewnguyen07/image-classification/blob/master/CNN-VGG16.ipynb): Used a pre-trained model, VGG16, to extract image features, then trained a neural network classifier with 3 dense layers and 2 dropout layers, which achieved 92% accuracy for train and much higher score, 86%, for test.

## Requirements

* pandas
* numpy
* matplotlib
* seaborn
* sklearn
* tensorflow
