# Bank Marketing Analysis (Machine Learning)

## Project Purpose
This project analyzes a bank marketing dataset to predict whether clients will subscribe to a term deposit based on their demographic and campaign-related features.  

## Dataset
The bank marketing dataset includes the following features:  
- Age  
- Job  
- Marital status  
- Education  
- Default status  
- Account balance  
- Housing loan  
- Personal loan  
- Contact type  
- Day and month of contact  
- Duration of last contact  
- Number of contacts during the campaign  
- Outcome of previous campaigns  
- Target variable: Deposit subscription (`deposit_yes`)  

## Data Preprocessing
- Categorical variables were converted to numerical format using **one-hot encoding**.  
- The dataset was split into **training and test sets**.  

## Models
- **Logistic Regression** (scikit-learn)  
- **Decision Tree Classifier** (max_depth=4, min_samples_split=10)  
- **Random Forest Classifier** (n_estimators=400, max_depth=5)  
- Models were trained on numerical and encoded categorical features.  

## Evaluation
- Logistic Regression accuracy: ~0.79 (test data)  
- Decision Tree Classifier accuracy: ~0.79 (training data)  
- Random Forest Classifier accuracy: [insert score from your run] (test data)  
- Decision tree visualization highlights the most influential features.  

## Prediction Example
The models can predict deposit subscription for new client data based on demographic and campaign-related features.  

## Notes
- This is a learning-focused project.  
- Future improvements may include feature scaling, hyperparameter tuning, and testing additional classification models.  

