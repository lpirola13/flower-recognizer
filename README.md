# AML final project

The aim of the project is to create a model for classifying  owers from flowers images, which can be used for a mobile application to obtain information about a ower from its photo.
It was comparison amoung three models based on different architectures (MobileNetV2, DenseNet-121, EfficientNet-B0)
## Code
The code is avaible [[here]](https://colab.research.google.com/drive/1I9SpRPgjiCLpr2k7_Y2LS8iCGJlHYWw8?authuser=1#scrollTo=l2mnQv_nctTK).
## Prerequisites
Since it was used tensorflow is mandatory python 3.5 - 3.8 on a 64-bit system.
The preferred way is to use Google Colab.

## Installation
Use the package manager pip to install the requirements.

```bash
pip install requirements.txt
```

Requirements: 
* numpy
* pandas
* matplotlib
* sklearn
* glob
* tensorflow
* tensorflow_model_optimization

## Usage
The code is executable directly on Google Colab without changes.

If you are using your PC pay attention on the dataset path. On Colab the path was: 
```python
 '/content/...'
```
Therefore if you want run on your computer change the path.

Other important point is that the dataset was downloaded using
```python
 !wget https://www.robots.ox.ac.uk/~vgg/data/flowers/102/102flowers.tgz
```
For a local use you should flollow this example [[link]](https://pypi.org/project/wget/).
```python
>>> import wget
>>> url = 'https://www.robots.ox.ac.uk/~vgg/data/flowers/102/102flowers.tgz'
>>> filename = wget.download(url)
```
## Data
The dataset used was **Oxford Flowers 102** [[link]](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/).
Which contains 8189 images in 102 different classes.

## Refrences
[1]  M.  Sandler,  A.  G.  Howard,  M.  Zhu,  A.  Zhmoginov,  and  L.  Chen,  “Invertedresiduals  and  linear  bottlenecks:    Mobile  networks  for  classification,  detectionand   segmentation,”CoRR,   vol.   abs/1801.04381,    2018.   [Online].   Available:http://arxiv.org/abs/1801.04381.

[2]  A.  G.  Howard,  M.  Zhu,  B.  Chen,  D.  Kalenichenko,  W.  Wang,  T.  Weyand,M. Andreetto, and H. Adam, “Mobilenets:  Efficient convolutional neural networksfor   mobile   vision   applications,”CoRR,   vol.   abs/1704.04861,   2017.   [Online].Available:  http://arxiv.org/abs/1704.04861.

[3]  G.  Huang,  Z.  Liu,  and  K.  Q.  Weinberger,  “Densely  connected  convolutionalnetworks,”CoRR,   vol.   abs/1608.06993,    2016.   [Online].   Available:http://arxiv.org/abs/1608.06993.

[4]  M.  Tan  and  Q.  V.  Le,  “Efficientnet:  Rethinking  model  scaling  for  convolutionalneural   networks,”CoRR,   vol.   abs/1905.11946,    2019.   [Online].   Available:http://arxiv.org/abs/1905.1194613


## Authors
Matteo Romanato - 816852 - m.romanato@campus.unimib.it\
Lorenzo Pirola - 816418 - l.pirola13@campus.unimib.it   
Youssef Karrati - 817435 - y.karrati@campus.unimib.it   
