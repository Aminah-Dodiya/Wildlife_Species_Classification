# Wildlife Species Classification
![Example Image](https://www.earthtouchnews.com/media/1952590/collage-rainforest-camera-trap_2020-06-01.jpg?width=710&height=10000&mode=max&upscale=false)

## Overview

This project implements an image classification model to identify different wildlife species from images. It uses a Convolutional Neural Network (CNN) to classify images of various wildlife species. This project is designed for educational purposes and demonstrates a practical application of deep learning in wildlife conservation.

## Table of Contents

1.  [Introduction](#introduction)
2.  [Dataset](#dataset)
3.  [Model Architecture](#model-architecture)
4.  [Installation](#installation)
5.  [Results](#results)
6.  [Future Work](#future-work)
7.  [Contributing](#contributing)
8.  [License](#license)

## 1. Introduction

This project addresses the challenge of automatically identifying wildlife species from images. Accurate species identification is crucial for various applications, including:

*   **Wildlife Monitoring:** Tracking populations and distributions.
*   **Conservation Efforts:** Identifying endangered species and prioritizing conservation efforts.
*   **Research:** Automating species identification for ecological studies.

## 2. Dataset

The model was trained and evaluated on a dataset consisting of images of various wildlife species.

*   **Source:** This project uses the dataset from ConserVision: Image Classification competition on DrivenData. [Data Download](https://www.drivendata.org/competitions/87/competition-image-classification-wildlife-conservation/data/)
*   **Classes:** The dataset includes images of 'hog', 'blank', 'monkey_prosimian', 'antelope_duiker', 'leopard', 'civet_genet', 'bird', and 'rodent'.
*   **Dataset Size:** "The training set contains 16488 images, and the test set contains 4464 images."

## 3. Model Architecture

The model architecture is a custom Convolutional Neural Network (CNN) implemented in Pytorch.

## 4. Installation

1.  Clone the repository:

    ```
    git clone https://github.com/Aminah-Dodiya/Computer-Vision
    cd wildlife-species-classification
    ```

2.  (Optional) Create a virtual environment:

    ```
    conda create -n conserviz-compitition python=3.8
    conda activate conserviz
    ```

3.  Install the dependencies 

    ```
    pip install pandas matplotlib Pillow tqdm scikit-learn torch torchvision
    ``` 

## 5. Results

*   The model achieved an accuracy of 85% on the validation set.
*   The confusion matrix reveals that the model performs well on identifying 'hog', 'leopard' and 'bird', but struggles with differentiating between 'antelope_duiker' and 'blanck'.
*   The visualization indicates the learning rate is optimal. We can see a clear convergence of both validation and training set.

## 6. Future Work

*   Explore different model architectures (e.g., EfficientNet, Vision Transformer).
*   Implement data augmentation techniques.
*   Fine-tune hyperparameters to optimize model performance.
*   Deploy the model as a web application or API.
*   Focus more on high performing classes and high performing images.

## 7. Contributing

Contributions to this project are welcome! Feel free to submit pull requests with bug fixes, new features, or improvements to the documentation.

## 8. License

This project is licensed under the MIT License. Please review the LICENSE file for more details.
