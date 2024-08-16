# Melanoma detection using CNN in Tensorflow and Keras.

Multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:

Actinic keratosis Basal cell carcinoma Dermatofibroma Melanoma Nevus Pigmented benign keratosis Seborrheic keratosis Squamous cell carcinoma Vascular lesion


## Conclusions

Inference from Model 1: As we can see from the plots,the difference between training accuracy and validation accuracy is more hence the model is an example of overfiting. 

Inference from Model 2: As we can see from the plots, after using an appropriate data augumentation strategy overfitting is reduced Significantly.

Inference from Model 3: The above results in graph and training data indicate that the accuracy has improved and that there is no overfitting of the model. class rebalancing helped to increse the accuracy significantly.


## Technologies Used

* Python - version 3.9.7
    Packages used within Python with versions:
    Tensorflow - version 2.16.1
    NumPy - version 1.25.2
    Pandas - version 1.3.4
    MatplotLib - version 3.4.3


## Acknowledgements

- This project wasbased on CNN topic assignment as part of IIIT-Bangalore AI & ML course.


## Contact

Created by [@Varun-Mohite] - feel free to contact me!
