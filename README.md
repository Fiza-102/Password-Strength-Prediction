# PASSWORD-STRENGTH-PREDICTION

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Installations](#installations)
- [Results](#results)
## Overview
A user must create a strong password so that their data is secure from unauthorized users.
I have build a model to predict the password strength using the Logistic
Regression, Machine Learning Algorithm & Natural Language Processing (NLP) in Python. In NLP i am using TF-IDF, purpose of using it is to reduce the influence of tokens that are experimentally less informative than characteristics that appear in a small portion of the training corpus and occur often in a particular corpus.
So, using this model, I will predict whether the password strength is strong or average, or weak.
<br>
## Dataset
The dataset contains around 670,000 different passwords of different strengths. The strength of a
password is denoted by a number i.e., if
- password strength=2, it is a strong password
- password strength=1, it is an average strength password
- password strength=0, it is a weak password 
## Prerequisites
 jupyter notebook, python libraries: Numpy, Pandas, Matplotlib, NLP.
## Installations
```r
import pandas as pd 

import numpy as np

import matplotlib.pyplot as plt 

import seaborn as sns 

from sklearn.feature_extraction.text import TfidfVectorizer

from sklearn.model_selection import train_test_split

from sklearn.linear_model import LogisticRegression
```
## Results
To properly format our dataset, I first pre-processed the data. After that, I trained model using this dataset.
The model was able to generate precise predictions after being trained. This model can be utilised in actual applications going forward.


