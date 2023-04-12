---

layout: post

title: "Lung Disease Detection"

description: “A project to detect lung diseases in patients using chest x-rays through deep learning techniques, more specifically, falls under medical imaging. "

categories: compsoc

thumbnail: "lung.jpg"

year: 2022

gmeet: "https://meet.google.com/bfj-paye-dei?authuser=0&hl=en"

---


![lung](https://user-images.githubusercontent.com/88723771/162439463-f9b6b782-85d5-4313-8234-16b69f234439.png)
## Mentors


- Pranav DV

- Sanjkeet Jena

- Harshwardhan Singh Rathore


### Members


-Amandeep Singh

-RS Muthukumar

-Mohan Nayak 

-Anirudh Prabhakaran




## Aim

The goal of this project is to build a web app to diagnose lung diseases from chest x-ray images using deep learning.

## Introduction

Deep learning, also known as hierarchical learning or deep structured learning, is a type of machine learning that uses a layered algorithmic architecture to analyze data. Unlike other types of machine learning, deep learning has the added advantage of being able to make decisions with significantly less human intervention. While basic machine learning requires a programmer to identify whether a conclusion is correct or not, deep learning can gauge the accuracy of its answers on its own due to the nature of its multi-layered structure.




## Model

The proposed ChildNet model includes five blocks consisting of 21 convolutions layers with the filters of {64, 128, 256, 512, 4608} depth and 5 max-pooling layers. The first block of the ChildNet model uses 64 filters, the second block 128 filters, the third block 256 filters, the fourth block 512 filters, and the fifth block 4608 filters. Note that the number of filters in the convolution layers is either remained or doubled in each following layer. The RGB images of (100 × 100) size are fed to the input of the proposed model. The first two fully connected layers of the model include 4608 nodes (neurons). The last fully-connected layer includes n number of nodes. Here, n is the number of classes, in our case, n = 2. Relu activation function is used to obtain nonlinearity in all layers except the last fully connected layer. However, the Softmax regression function is used to perform the classification on the last fully connected layer.

- Input layer
- 1x1 convolution layer
- 3x3 convolution layer
- 5x5 convolution layer
- Max pooling layer
- Concatenation layer

we've trained them on 1.5k images;
The model will use 5 classes for outputs them being firearms,fire, gore, fight,cold-arms and give percentage of each.

The output files are there in a sepaerate folder.

## Conclusion


In this project, we proposed the diagnosis of lung disease from the patient's X-ray data plus some additional information. We did this by :

` `• Testing multiple architectures, optimizing and testing on a sample dataset.

` `• Using good architects to test the full dataset, continue optimizing and statistics.

The results of this project have achieved our initial expectations, but to be able to apply in hospitals, more improvements are needed to increase the precision of the model. 

## References

1. Notebooks and datasets,
` `• [Link](https://www.kaggle.com/nih-chest-xrays/data)
` `• [Link](https://www.kaggle.com/datasets/nih-chest-xrays/data)

2. Courses used,
` `• [Link](https://www.coursera.org/learn/neural-networks-deep-learning)
` `• [Link](https://www.coursera.org/learn/neural-networks-deep-learning)
` `• [Link](https://www.coursera.org/learn/introduction-tensorflow?specialization=tensorflow-in-practice)
` `• [Link](https://www.coursera.org/learn/convolutional-neural-networks-tensorflow)
` `• [Link](https://www.kaggle.com/learn/intro-to-deep-learning)
` `• [Link](https://www.kaggle.com/learn/computer-vision)

3. Research Papers,
` `• [Link](https://www.sciencedirect.com/science/article/pii/S2352914820300290)
` `• [Link](https://www.sciencedirect.com/science/article/pii/S0010482521001426)



-->
