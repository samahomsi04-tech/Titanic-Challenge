# Titanic-Challenge
Kaggle Titanic Dataset Challenge



## Dependencies 
- numpy 
- pandas
- matplotlib
- seaborn
- sklearn
- imblearn
- tensorflow 



## Dataset 
- Training dataset
  - **Training set** : 70%
  - **Validation set** : 30%

- Testing dataset


## Data Preprocessing
- Feature Engineering
  - Drop unmeaningful columns such as **Name** and **Passenger**
  - Drop **Ticket** feature, cuase of the huge virution in feature of more that 400 uniqe categories, the **Pclass** and **Embarked** features will cover the lost of this feature
  - Drop **Cabin** feature, using fillna with mean or median is not an ideal move, since it creates artificial data hard to rely on. the best move is to drop it
  - LabelEncoder **Sex** and **Embarked** features
  - Scale the sets using StandardScaler



## classifier Architecture
  - **Architecture :** Multiple Dense layers with ReLU and linear activation fnction. 
  - **Optimizer :** AdamW (learning rate 0.0015)
  - **Loss Function :** Binary Cross-Entropy


## Evaluation and Results
- Trianing and Validation learning curves
- Best test accuracy
- Evaluation Metrics
  - **F1-Score**
  - **Recall**
  - **Precision**
  - **Confusion Matrix**


## Purpose
This project aims for university educational purpose 
