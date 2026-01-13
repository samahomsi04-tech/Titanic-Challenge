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
1. The dataset was slightly balance across both classes Bengin and Malignant
   - A 2,000 sample was taken from Malignant calss to address imbalancd scenario


2. The dataset is splitted into
  - **Training set** : 80%
  - **Validation set** : 10%
  - **Test set** : 10%


## Data Preprocessing
- Image resize to 64X64X3,  only for WGAN-base approach 128X128X3
- Image normalization

- Augmanting traning set
   - All augmantation approaches were applyed only on training set. Vallidation and testing kept imbalance to mimic real-life scenario 



## CCN-based classifier Architecture
  - **Architecture :** Multiple convolutional layers, pooling layers, and a fullyconnected layer. 
  - **Optimizer :** Adam (learning rate 0.0001)
  - **Loss Function :** Binary Cross-Entropy


## Evaluation and Results
- Best test accuracy
- Evaluation Metrics
  - **F1-Score**
  - **Recall**
  - **Precision**
  - **Confusion Matrix**


## Purpose
This project aims for university educational purpose 
