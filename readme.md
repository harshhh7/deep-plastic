## Abstract

Understanding how plastic waste accumulates in the world's oceans and identifying areas for concentrated cleanup efforts relies on the quantification of buoyant marine plastic trash. Currently, visual surveys are used to detect marine plastic debris, but they are time-consuming, labor-intensive, and may miss smaller or submerged particles. This project proposes a Convolutional Neural Network (CNN) approach to improve the accuracy of plastic waste detection in underwater environments.

## Background

A Convolutional Neural Network (CNN) is a deep learning algorithm designed for image processing, recognition, and classification. Inspired by the human visual cortex, CNNs consist of layers of convolutional filters that extract relevant features from images. CNNs are widely used for object detection and identification, making them suitable for tasks like plastic waste detection.

### Proposed Model

#### Dataset Description

The dataset for this project was collected from an online accessible university website in the USA, containing images of marine plastic after a survey conducted in a lake. It includes images of underwater plastic split into training, validation, and testing data.

- **Training Data**: Contains 2 folders representing classes "Underwater_Plastic" and "Not_Plastic," with a total of 2192 images.
- **Validation Data**: Also divided into "Underwater_Plastic" and "Not_Plastic" classes, with 655 images.
- **Testing Data**: Contains 10-15 random images, suitable for localized training depending on the project's needs.

