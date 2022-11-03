# ML and DL architecture comparison for COVID-19 classification using Chest X-ray Images
### The documentation for the whole approach can be found in the following published book chapter:
- Afzal, E., Saba, T., Ali, H., Karim, A., Javed, K. (2022). ML and DL Architectures Comparisons for the Classification of COVID-19 Using Chest X-Ray Images. In: Saba, T., Rehman, A., Roy, S. (eds) Prognostic Models in Healthcare: AI and Statistical Approaches. Studies in Big Data, vol 109. Springer, Singapore. https://doi.org/10.1007/978-981-19-2057-8_16

# The overall Approach
### The whole study can be divided into the following sections:
## 1. Data Collection
The data used in this study can be found on Kaggle through the folowing link:
[COVID-19-Pneumonia-Normal-Chest-Xray-Dataset](https://www.kaggle.com/amanullahasraf/covid19-pneumonia-normal-chest-xray-pa-dataset)

## 2. Data Preprocessing
The whole dataset was divided into 2 categories, as follows:
1. Normal
2. COVID-19

The dataset of the pneumonia X-rays was omitted for the study. After the split, a number of preprocessing and augmentation techniques were used to introduce variation in the data and also to populate it.
## 3. Model development
The study was conducted so as to compare both machine and deep learning models. The machine learning models used in the study include:
1. Support Vector Machine
2. Logistic Regression
3. Decision Tree

The code for the machine learning models can be found in the `Machine_learning_models` folder.\
Apart from this, the deep learning models used include convolutional neural networks, both with self defined layers and pre-trained models used for transfer learning. The deep learning models used include:
1. Convolutional Neural Network (Self Defined)
2. VGG-19
3. ResNet-50
4. AlexNet

The Convolutional Neural Networks (CNN's) code is contained in the folder `Convolutional_neural_network`, while the other three models are located in `Transfer_learning_models`.

## 4. Model Evaluation
Multiple evaluation metrices have been used for the evaluation of these models. The metrices we used in the study are:
1. Accuracy
2. Precision
3. Recall
4. F1-measure
5. Area Under Curve (AUC)
