# A repository for my Kaggle notebooks
## Wild and farm salmon image classification using ResNet152
Link to dataset: [Github](https://www.kaggle.com/datasets/tanakritsaipahn/salmon-raw) 
> This dataset is binary salmon class dataset that classifly between farm raw salmon and natural raw salmon. Different things about farm raw and natural raw are fat layer, meat color and size.

A pre-trained image classification network named ResNet152 is used via transfer learning. The model was implemented using Tensorflow. Parts of code were based on codes from [this notebook](https://www.kaggle.com/code/tanakritsaipahn/basic-salmon-classification).

The trained model can classify 94.62% of the test images correctly (334/353 images). 19 images were misclassified.

## Breast cancer patient mortality prediction
The task is to predict whether the breast cancer patient with the given background and clinical data is alive or not. More information about the dataset is available [here](https://www.kaggle.com/datasets/reihanenamdari/breast-cancer). The code on kaggle is [here](https://www.kaggle.com/code/pkhamchuai/breast-cancer-prediction-dnn).

The model is created as a DNN, implemented using Tensorflow. The model achieve about 89.44% accuracy in predicting mortality. It could be better.
