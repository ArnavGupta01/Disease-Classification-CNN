# Disease-Classification-CNN

This is a Convolutional Neural Network (CNN) model designed for accurate and efficient classification of medical images into four categories: Monkeypox, Chickenpox, Measles, and Normal. This repository contains the implementation of the CNN model, along with all the images used and the necessary data preprocessing scripts. The model has been trained on a decently big dataset of annotated medical images to provide reliable disease classification results. Researchers and healthcare professionals can utilize this repository to enhance disease diagnosis, surveillance, and monitoring efforts. 

All the images used have been obtained from authenticated websites which are run by medical practitioners(dermatologists) and governmental organisations.

*The stats of the images used are:*

| **Type Of Image** | **Number of Images** |
| ---- |:-------------:|
|   ChickenPox    | 176 |
|   MonkeyPox    | 472      |
|   Measles | 101      |   
|   Normal | 290      |  

A 80-20 split of these images was made into training and validation dataset and all the images lying in the training dataset were augmented three times to expand the dataset.
