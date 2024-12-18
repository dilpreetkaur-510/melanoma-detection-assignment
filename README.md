# Melanoma Detection via Convolutional Neural Network (CNN)
> The objective of this project is to create a Convolutional Neural Network (CNN) to classify a dermoscopic image of a skin lesion in 9 different classes. A dermoscopic image is a picture of the skin using a microscope and illumination.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The data set contains 2357 images of the following diseases:
    * Actinic keratosis
    * Basal cell carcinoma
    * Dermatofibroma
    * Melanoma
    * Nevus
    * Pigmented benign keratosis
    * Seborrheic keratosis
    * Squamous cell carcinoma
    * Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The custom CNN model shows promising results, with accuracy gradually increasing through training. However, we observed some overfitting, which was addressed with data augmentation   techniques.
- After applying augmentation, the model's performance improved, particularly in its ability to generalize across different types of skin lesions.
- Handling class imbalances with the Augmentor library significantly improved model robustness, especially for underrepresented classes.
- The model's final validation accuracy and loss show satisfactory results, indicating its potential for real-world deployment in aiding melanoma detection.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- TensorFlow
- Keras
- Python

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was based in Melanoma detection assignment in upGrad course.

## Contact
Created by @dilpreetkaur-510

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->