# 🐍 Data Science Python Imports (Industry Standard)

A comprehensive collection of the most commonly used Python imports for **Data Science**, **Machine Learning**, **Deep Learning**, **Computer Vision**, **NLP**, **MLOps**, **Big Data**, and **Generative AI**.

---

# Basic Python Libraries

```python
import os
import sys
import math
import random
import time
import datetime
import json
import csv
import re
import warnings
from pathlib import Path

warnings.filterwarnings("ignore")
```

---

#  Numerical Computing

```python
import numpy as np
```

---

#  Data Manipulation

```python
import pandas as pd
```

---

#  Data Visualization

```python
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import plotly.graph_objects as go
```

---

#  Scientific Computing

```python
import scipy
from scipy import stats
```

---

#  Scikit-learn

## Import Library

```python
import sklearn
```

### Model Selection

```python
from sklearn.model_selection import (
    train_test_split,
    GridSearchCV,
    RandomizedSearchCV,
    cross_val_score,
)
```

### Data Preprocessing

```python
from sklearn.preprocessing import (
    StandardScaler,
    MinMaxScaler,
    LabelEncoder,
    OneHotEncoder,
)
```

### Missing Value Handling

```python
from sklearn.impute import SimpleImputer
```

### Pipelines

```python
from sklearn.pipeline import Pipeline
from sklearn.compose import ColumnTransformer
```

### Evaluation Metrics

```python
from sklearn.metrics import (
    accuracy_score,
    precision_score,
    recall_score,
    f1_score,
    confusion_matrix,
    classification_report,
    mean_squared_error,
    mean_absolute_error,
    r2_score,
)
```

---

#  Machine Learning Algorithms

## Linear Models

```python
from sklearn.linear_model import (
    LinearRegression,
    LogisticRegression,
)
```

## Decision Tree

```python
from sklearn.tree import DecisionTreeClassifier
```

## Random Forest & Ensemble

```python
from sklearn.ensemble import (
    RandomForestClassifier,
    RandomForestRegressor,
    GradientBoostingClassifier,
)
```

## Support Vector Machine

```python
from sklearn.svm import SVC
```

## K-Nearest Neighbors

```python
from sklearn.neighbors import KNeighborsClassifier
```

## Naive Bayes

```python
from sklearn.naive_bayes import GaussianNB
```

## Clustering

```python
from sklearn.cluster import KMeans
```

## Dimensionality Reduction

```python
from sklearn.decomposition import PCA
```

---

#  Gradient Boosting Libraries

## XGBoost

```python
from xgboost import (
    XGBClassifier,
    XGBRegressor,
)
```

## LightGBM

```python
from lightgbm import (
    LGBMClassifier,
    LGBMRegressor,
)
```

## CatBoost

```python
from catboost import (
    CatBoostClassifier,
    CatBoostRegressor,
)
```

---

#  Deep Learning

## TensorFlow

```python
import tensorflow as tf

from tensorflow.keras.models import Sequential

from tensorflow.keras.layers import (
    Dense,
    Dropout,
    Conv2D,
    MaxPooling2D,
    Flatten,
)
```

## PyTorch

```python
import torch
import torch.nn as nn
import torch.optim as optim
```

---

#  Computer Vision

```python
import cv2
from PIL import Image
```

---

#  Natural Language Processing (NLP)

```python
import nltk
import spacy

from transformers import pipeline
```

---

#  Database Connectivity

```python
import sqlite3
import sqlalchemy
import pymongo
```

---

#  Web Scraping

```python
import requests

from bs4 import BeautifulSoup

from selenium import webdriver
```

---

#  Big Data

```python
import pyspark
```

---

#  Dashboard Development

```python
import streamlit as st
```

---

#  API Development

```python
from fastapi import FastAPI
```

---

#  MLOps

```python
import mlflow
```

---

#  Model Explainability

```python
import shap
```

---

#  Hyperparameter Optimization

```python
import optuna
```

---

#  Generative AI & LLMs

```python
from langchain_openai import ChatOpenAI

from langchain_core.prompts import ChatPromptTemplate

from langchain_core.output_parsers import StrOutputParser
```

---

#  Utility Libraries

```python
from tqdm import tqdm
```

---

#  Recommended Installation

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn \
xgboost lightgbm catboost tensorflow torch torchvision torchaudio \
opencv-python pillow nltk spacy transformers sqlalchemy pymongo \
requests beautifulsoup4 selenium pyspark streamlit fastapi \
mlflow shap optuna langchain langchain-openai tqdm plotly
```

---

#  Industry-Level Learning Order

1. NumPy
2. Pandas
3. Matplotlib
4. Seaborn
5. Plotly
6. SciPy
7. Scikit-learn
8. XGBoost
9. LightGBM
10. CatBoost
11. TensorFlow
12. PyTorch
13. OpenCV
14. NLTK
15. spaCy
16. Transformers
17. SQLAlchemy
18. PySpark
19. FastAPI
20. Streamlit
21. MLflow
22. SHAP
23. Optuna
24. LangChain
25. LlamaIndex
