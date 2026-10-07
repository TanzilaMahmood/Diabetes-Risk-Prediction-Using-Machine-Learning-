# Diabetes Risk Prediction Using Machine Learning
 
## Project Overview
This project uses machine learning techniques to predict diabetes risk using healthcare data. The workflow includes data preprocessing, feature scaling, class balancing using SMOTE, and classification using K-Nearest Neighbours (KNN).
 
## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-Learn
- SMOTE
- Google Colab
 
## Machine Learning Workflow
1. Data exploration
2. Data preprocessing
3. Train-test split
4. Feature scaling using StandardScaler
5. Class balancing using SMOTE
6. KNN model training
7. Model evaluation
 
## Evaluation Metrics
- Accuracy Score
- Recall Score
- Confusion Matrix
 
## Libraries Used
 
```python
import pandas as pd
import matplotlib.pyplot as plt
 
from sklearn.model_selection import train_test_split
from sklearn.neighbors import KNeighborsClassifier
from sklearn.metrics import accuracy_score, recall_score
from sklearn.metrics import ConfusionMatrixDisplay
from sklearn.preprocessing import StandardScaler
 
from imblearn.over_sampling import SMOTE
```
 
## Key Skills Demonstrated
- Data Analysis
- Data Preprocessing
- Machine Learning
- Classification
- Feature Scaling
- Handling Imbalanced Data
- KNN
- Model Evaluation
