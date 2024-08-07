# Melanoma Detection Assignment
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

- The data set contains the following diseases:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The validation accuracy data exceeds that of training accuracy after Augmenting data. This might point to the quality of augmentation itself.
- The same model fails to come anywhere near the training accuracy or validation accuracy when evaluating test data. This definitely points to overfitting.
- The quality of test data probably needs to be better and we might need more data (without augmentation) so that the model is generalizable.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy - version 1.26.4
- Pandas - version 2.1.4
- Tensorflow - version 2.17.0
- Keras - version 3.4.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [Alok Aparanji](https://github.com/alokaa/) - feel free to contact me!

