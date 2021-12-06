# Emotion-Classifier-RandomForest
Project of Cal CS294-082 Fall 2021

# Data
[Fer2013](https://www.kaggle.com/deadskull7/fer2013)

Create a data folder and place training and test data in torch.ImageFolder style.

# Train & Test
I directly use the image pixel as random forest input, another three types of feature are also applied in notebook.\
Run the **Random-Forest-Image-Classification-using-Python.ipynb**

> Result
```
training acc:	0.9985022118499425
training acc:	0.4856505990526609
Model's confusion matrix on training data
[[3988    0    1    0    1    4    1]
 [   0  435    0    0    0    0    1]
 [   3    1 4080    0    3    3    7]
 [   1    0    0 7213    0    0    1]
 [   2    0    0    0 4962    1    0]
 [   5    0    4    0    0 4821    0]
 [   1    0    3    0    0    0 3167]]
Model's confusion matrix on test data
[[ 199    0   53  355  142  163   46]
 [   6   32    5   43   10   10    5]
 [  43    0  281  293  158  162   87]
 [  20    0   38 1423  102  146   45]
 [  20    0   35  430  527  193   28]
 [  36    0   62  405  223  500   21]
 [  14    0   45  135   61   52  524]]
```
