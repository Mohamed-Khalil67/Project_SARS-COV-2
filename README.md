# Project_SARS-COV-2

## Introduction à la classification  Image

## Détection du SARS-COVID2 par Image:

Lien du dataset : https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset

Pourquoi on utilise des transfer learning :

To save time and resources from having to train multiple machine learning models from scratch to complete similar tasks. As an efficiency saving in areas of machine learning that require high amounts of resources such as image categorisation or natural language processing.

Resnet50 : 

The ResNet-50 model consists of 5 stages each with a convolution and Identity block. Each convolution block has 3 convolution layers and each identity block also has 3 convolution layers. The ResNet-50 has over 23 million trainable parameters. ... Our ResNet-50 gets to 86% test accuracy in 25 epochs of training.

Confusions des matrix :

![matrix_confusion](https://user-images.githubusercontent.com/71330579/151059884-e9bff168-6998-4bba-9c31-43c934d8260b.png)

![confusion_matrix_2](https://user-images.githubusercontent.com/71330579/151059892-4afec747-e623-459c-85e8-7277745f4620.png)


------------------------------------------------------------------------------------------------------------------------------------------------------------


Resnet 18 ( refaire tout le systéme de learning plus rapidement ) :

ResNet-18 is a convolutional neural network that is 18 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database

### How to see if my model is underfitting or overfitting?

Finding optimal learning rates with the Learning Rate Range Test –  MachineCurve
Use these steps to determine if your machine learning model, deep learning model or neural network is currently underfit or overfit.

* Ensure that you are using validation loss next to training loss in the training phase.
* When my validation loss is decreasing, the model is still underfit.
* When my validation loss is increasing, the model is overfit.
* When my validation loss is equal, the model is either perfectly fit or in a local minimum.

![image](https://user-images.githubusercontent.com/71330579/151071199-e6971253-0cd9-4167-a45e-f30d25ce5bbf.png)

- au premiére tests , il y avait une over fiting result des mauvaises choix des paramtres du fit_one_cycle
- Mais aprés une autre deuxiéme résultat on a eu une meilleur précision ou plustôt raisonable

![image](https://user-images.githubusercontent.com/71330579/151085835-8fd332bb-4ed0-4bb0-af5c-fc41d20ef53b.png)

