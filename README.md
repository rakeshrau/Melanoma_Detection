# Melanoma\SkinCancer Detection

## Business Objective:
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. We have to build a CNN based model which can accurately detect melanoma and other types of Skin cancer.

## Table of Contents
* [Dataset](#Dataset)
* [Technologies](#Technologies)
* [Conclusions](#Conclusions)
* [Contributors](#Contributors)


## Dataset
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


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

## Technologies
- Python-3.10.12
- Augmentor-0.12.2
- Numpy-1.23.5
- Matplotlib-3.7.1
- Pandas-1.5.3
- Google Colab

## Conclusions
- Without Data Augmentation there was a huge overfitting in the validation set.
- After image augmentation we were able to reduce the overfitting considerably(but not completely).
- There was a Class Imbalance in the data, we used a library called Augmentor to handle the Class Imbalance and retrain the model.This solved the Overfitting issue completely and boost the accuracy in the validation data.

## Contributors
Created by [@rakeshrau] - Rakesh Raushan
