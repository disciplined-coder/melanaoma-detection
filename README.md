# Project Name
Melanoma Detection Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The project builds a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early.
- The dataset comprises 2357 images depicting malignant and benign oncological conditions, sourced from the International Skin Imaging Collaboration (ISIC). These images were categorized based on the classification provided by ISIC, with each subset containing an equal number of images.
- The modeling is done using CNN
- In order to address the challenge of class imbalance, the Augmentor Python package (https://augmentor.readthedocs.io/en/master/) was employed to augment the dataset. This involved generating additional samples for all classes, ensuring that none of the classes had insufficient representation.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Python - version 3.8.10
- Pandas - version 2.2.2
- Matplotlib - version 3.7.5
- TensorFlow - version 2.7.0
- Keras - version 2.7.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
A stable model has been built by implementing Augmentation, Batch Normalization, Dropout and Regularization techniques which can predict Melanoma early

## Contact
Created by [@disciplined-coder] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->