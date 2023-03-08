# Melanoma-Detection-Using-CNN

## Table of Contents
1. General Info
2. Technologies Used
3. Conclusions

## General Information

-Project: Melanoma Detection To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

-The business probem that your project is trying to solve and Dataset Used? The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis Basal cell carcinoma Dermatofibroma Melanoma Nevus Pigmented benign keratosis Seborrheic keratosis Squamous cell carcinoma Vascular lesion

## Observations

1. The accuracy of test set is 90%
2. Accuracy of validation dats set is 80%
3. Here we went for some extra epochs to try if the model gets improved. But, infact the model tend to increase the overfitting once we for extra epochs.
4. The model with the above accuracy shows an increased performace of the model when we get a class balanced training data as we can see from the model performace on the augmented data.

## Technologies Used

1. Google Colab
2. Python
3. Tensorflow
