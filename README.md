# CNN_CASESTUDY_-MELANOMA
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
## General Information
- Provide general information about your project here.
- What is the background of your project?
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the business probem that your project is trying to solve?

To build a multiclass classification model using a custom convolutional neural network in TensorFlow

- What is the dataset that is being used?

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 

## Conclusions
- Conclusion 1 from the analysis

Initial model, Training accuracy is increasing but the test accuracy is stable at around 50%.
May be overfitting which will limit generalizability. Need to correct overfitting, may be by augmentation

- Conclusion 2 from the analysis
Intermediate model, 
Overfitting corrected by augmentation.
Training and Validation accuracy in the same range but low.may be underfitting

- Conclusion 3 from the analysis
-Used data Augmentation, class imbalance correction to improve teh model accuracy in both training and validation sets



