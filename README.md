# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis


## Table of Contents
* General Info
* Technologies Used
* Conclusions
* Acknowledgements

## General Information
- CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. 
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
- All images were sorted according to classification ISIC. All subsets divided into same number of images, with exception of melanomas mole and whose images are slightly dominant.


## Conclusions

- The model is still overfitting with training accuracy of 93% and validation accuracy of 70% on the 50th Epoch.
- There is no great change in validation accuracy beyond 74% after 19th Epoch
- Validation loss is higher around 38th Epoch.
- Data Augmentation increased the accuracy of training set slightly. 
- Class rebalance was of not much help as the model is still overfitting
- Model overfitting can be addressed further by adding more layers and tuning hyperparameters


## Technologies Used
- Python 3.0


## Acknowledgements
Give credit here.
- Upgrad - Thanks for sharing the dataset and details related to the dataset
- Stackoverflow.com 

## Contact
Created by [@durgaavrs] - feel free to contact me!
