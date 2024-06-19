# Melanoma Detection
> For this assignment, we have developed a multiclass classification model utilizing a custom convolutional neural network implemented in TensorFlow.


## Table of Contents
* [Problem statement](#problem-statement)
* [Acknowledgements](#project-pipeline)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## Problem statement
 We aim to build a CNN-based model capable of accurately detecting melanoma, a type of skin cancer that can be fatal if not detected early. Melanoma is responsible for 75% of skin cancer-related deaths. Developing a solution that can analyze images and alert dermatologists to the presence of melanoma can significantly reduce the manual effort required for diagnosis.

The dataset used for this model consists of 2357 images of malignant and benign oncological diseases, sourced from the International Skin Imaging Collaboration (ISIC). These images are classified according to ISIC guidelines, with subsets divided into equal quantities, except for melanomas and moles, which are slightly more prevalent.

The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion


## Project Pipeline
- Understanding the dataset by reading and examining the images and labels.
- Creating the dataset by splitting it into training, validation, and test sets.
- Visualizing the dataset to gain insights into the class characteristics.
- Building and training an initial CNN model for multiclass classification.
- Implementing data augmentation to mitigate underfitting or overfitting.
- Rebuilding and retraining the model with the augmented data.
- Analyzing the class distribution to identify any imbalances.
- Addressing class imbalances using resampling or class weighting techniques.
- Training the model on data with rectified class imbalances for better accuracy.


## Conclusions
- The issues of overfitting and underfitting were resolved, resulting in a well-trained model for predictions. Data augmentation, outlier handling, and class rebalancing significantly improved model performance in this instance.


## Technologies Used
- Keras
- TensorFlow
- Python 3
- Pandas, Numpy, Matplotlib,
- Augmentor


## Contact
Created by @akashmania068
