# Breast-cancer-classification
Benign vs Malignant classifier using convolutional neural networks

## Data

The dataset can be downloaded from [here](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/).

## Environment and tools

1. Jupyter Notebook
2. Numpy
3. Pandas
4. Scikit-image
5. Matplotlib
6. Scikit-learn
7. Keras

## Installation

`pip install numpy pandas scikit-image matplotlib scikit-learn keras`

`jupyter notebook`

## Results

### Loss/Accuracy vs Epoch

![loss/accuracy](image1.png)

![loss/accuracy](image2.png)

### Confusion Matrix

![roc-auc](image3.png)

### ROC-AUC curve

![roc-auc](image4.png)

### Correct/Incorrect classification samples

![results](image5.png)

The model is able to reach a validation accuracy of 98.3%, precision 0.65, recall 0.95, f1 score of 0.77 and ROC-AUC as 0.692.

## Citing

```
@misc{Abhinav:2019,
  Author = {Abhinav Sagar},
  Title = {Grocery Image Classification},
  Year = {2019},
  Publisher = {GitHub},
  Journal = {GitHub repository},
  Howpublished = {\url{https://github.com/abhinavsagar/Grocery-Image-Classification}}
}
```


