# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* Problem Statement
* Create a dataset
* Visualize the data
* Create the model
  - Model 1 - Without Dropouts and Without BatchNormalisation techniques
  - Model 2 - Using Modified Images
  - Model 3 - Using added training data and BatchNormalisation technique
  - Model 4 - without BatchNormalisation
* Prediction
<!-- You can include any other section that is pertinent to your problem -->

## General Information
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
 
## Conclusions
* Model 1 Conclusions
  - A notable variance exists between the training accuracy and validation accuracy, suggesting the model's inability to effectively generalize and predict unseen data.
  - High training accuracy coupled with low validation accuracy signifies overfitting.
  - Implementing dropouts can be a valuable strategy to address these issues and enhance model performance.
* Model 2 Conclusions
  - A notable decrease in the disparity between training accuracy and validation accuracy suggests enhanced generalizability and indicates that overfitting has been mitigated.
  - Despite this improvement, the overall accuracy remains relatively low, hovering around 50%, indicating the model's limited ability to accurately predict unseen data.
  - The current situation appears to be indicative of underfitting. Implementing techniques such as batch normalization could be explored to address this issue and potentially improve the model's performance.
* Model 3 Conclusions
  - Observing the depicted graph, it's evident that the validation accuracy exhibits significant fluctuations across epochs, indicating instability within the model.
  - Despite enhancements in training accuracy, the inconsistent behavior of validation accuracy renders the model less dependable.
  - Considering these concerns, a decision is made to construct an alternative model architecture devoid of Batch Normalization layers.
* Model 4 Conclusions
  - Balancing the class distribution in the dataset can indeed contribute to improving the generalization and robustness of the model.
  - The minimal difference in accuracies and consistently high values suggest that the model has learned to generalize well across both the training and validation datasets.


## Acknowledgements
As part of IIT Bangalore's AI/ML Executive Programme, I worked on this project.


## Contact
Created by https://github.com/Sai-Krishna-Rali - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
