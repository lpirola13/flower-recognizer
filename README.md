# Flower recognizer for mobile application

The aim of the project is to create a model for classifying flowers from images, which can be used for a mobile application. It was comparison amoung three models based on different architectures (MobileNetV2, DenseNet-121, EfficientNet-B0)
## Code
This [repository](https://github.com/lpirola13/flower_recognizer) or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1I9SpRPgjiCLpr2k7_Y2LS8iCGJlHYWw8?usp=sharing)
## Prerequisites
Since it was used tensorflow is mandatory python 3.5 - 3.8 on a 64-bit system.

## Installation
The code was executed on Google Colab. To run it on local runtime, use the package manager pip to install the required libraries: 
* numpy
* pandas
* matplotlib
* sklearn
* glob
* tensorflow
* tensorflow_model_optimization

## Usage
The code is executable directly on Google Colab without changes. If you are running it on local runtime pay attention on paths, since Colab use the absolute path: 
```python
 '/content/...'
```
The dataset is downloaded using some commands executed directly in terminal. These commands starts with "!", e.g.:
```python
 !wget https://www.robots.ox.ac.uk/~vgg/data/flowers/102/102flowers.tgz
```
In order to run the entire code it is necessary to run this command on terminal without the "!" character.
## Data
The dataset used was **Oxford Flowers 102** [[link]](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/).
Which contains 8189 images in 102 different classes.

## Refrences
[1] M.-E. Nilsback, “An automatic visual Flora – segmentation and classification of flowers images,” Ph.D. dissertation, University of Oxford, 2009. [Online]. Available: https://www.robots.ox.ac.uk/∼vgg/publications/2009/Nilsback09/

[2] M. Sandler, A. G. Howard, M. Zhu, A. Zhmoginov, and L. Chen, “Inverted residuals and linear bottlenecks: Mobile networks for classification, detection and segmentation,” CoRR, vol. abs/1801.04381, 2018. [Online]. Available: http://arxiv.org/abs/1801.04381

[3] A. G. Howard, M. Zhu, B. Chen, D. Kalenichenko, W. Wang, T. Weyand, M. Andreetto, and H. Adam, “Mobilenets: Efficient convolutional neural networks for mobile vision applications,” CoRR, vol. abs/1704.04861, 2017. [Online]. Available: http://arxiv.org/abs/1704.04861

[4] G. Huang, Z. Liu, and K. Q. Weinberger, “Densely connected convolutional networks,” CoRR, vol. abs/1608.06993, 2016. [Online]. Available: http: //arxiv.org/abs/1608.06993

[5] M. Tan and Q. V. Le, “Efficientnet: Rethinking model scaling for convolutional neural networks,” CoRR, vol. abs/1905.11946, 2019. [Online]. Available: http://arxiv.org/abs/1905.11946

[6] I. Goodfellow, Y. Bengio, A. Courville, and Y. Bengio, Deep learning. MIT press Cambridge, 2016, vol. 1, no. 2, ch. 7.12, p. 253.


## Authors
Matteo Romanato - 816852 - m.romanato@campus.unimib.it\
Lorenzo Pirola - 816418 - l.pirola13@campus.unimib.it   
Youssef Karrati - 817435 - y.karrati@campus.unimib.it   
