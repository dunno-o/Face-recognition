# Face-recognition
Face recognition model based on HOG, CV Haar Cascade and image augmentations. 

## [Baseline solution using linear regression](baseline.ipynb)

## [Improved solution with Haar Cascade, HOG, PCA, SVM, etc](main.ipynb)

To begin with, I detect face with Haar Cascade (use more than one in case it helps), then define features via HOG. After that, applying PCA to reduce dimension of the features.

At the end of proccess, we need to use GridSerch to find better parameters and after prediction, take result of model without Haar Cascades and cutting for images, where main model probability is not so high.

### [Catboost Gradient Classifier experiments](Catboost.ipynb)
