# Credit Card Frauds Classifier - Machine Learning Project

The goal of this project is to create a **classifier algorithm** that can identify credit card fraudolent transactions.

The **Dataset** used to train the model contains a list of transactions labeled as fraudolent or genuine and it is avaliable on *kaggle*.com at the link [ https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud ] 

### Dataset Details
```
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 1000000 entries, 0 to 999999
Data columns (total 8 columns):
 #   Column                          Non-Null Count    Dtype  
---  ------                          --------------    -----  
 0   distance_from_home              1000000 non-null  float64
 1   distance_from_last_transaction  1000000 non-null  float64
 2   ratio_to_median_purchase_price  1000000 non-null  float64
 3   repeat_retailer                 1000000 non-null  float64
 4  	used_chip                       1000000 non-null  float64
 5   used_pin_number                 1000000 non-null  float64
 6   online_order                    1000000 non-null  float64
 7   fraud                           1000000 non-null  float64
 ```
## Project Structure
1. EDA - Exploratory Data Analysis
2. Data Pre-Processing
3. Model Selection
   - Logistic Regression
   - K-Nearest Neighbors classifier
   - Neural Network - MLP
4. Model Assessment

All details and results of the project are described in the Python Notebook [credit_card_fraud_final_project.ipynb](./credit_card_fraud_final_project.ipynb)
