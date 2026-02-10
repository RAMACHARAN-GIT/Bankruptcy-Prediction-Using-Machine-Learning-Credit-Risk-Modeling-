Bankruptcy Prediction (Machine Learning) 

This project predicts whether a company is likely to go bankrupt using financial ratio data. It applies 
machine learning classification models, evaluates performance using ROC-AUC and classification 
metrics, and compares results across models. 

Project Overview 

Bankruptcy prediction is a critical task in finance and risk management. This project uses a dataset of 
company financial indicators to classify whether a company is bankrupt or not bankrupt. 
The target column used is: 
 Bankrupt? → (1 = Bankrupt, 0 = Not Bankrupt) 

Features of This Project  

Data loading and exploration 
Data preprocessing (splitting into train/test) 

Training ML models: 
 Logistic Regression 
 Random Forest Classifier

Model evaluation using: 
 Confusion Matrix 
 Classification Report 
 ROC-AUC Score 

Machine Learning Models Used 
Logistic Regression 
A simple baseline model for binary classification. 
Random Forest Classifier 
An ensemble model that improves performance using multiple decision trees.

Evaluation Metrics 
The notebook evaluates models using: 
 ROC-AUC Score 
 Confusion Matrix 
 Classification Report 

Technologies Used 
 Python 
 Pandas 
 NumPy 
 Scikit-learn 
 Matplotlib 

Results 
The models are evaluated and compared based on ROC-AUC score and classification metrics. 
Random Forest typically performs better due to its ensemble nature. 


How to Run This Project 

Clone the repository 
git clone https://github.com/your-username/Bankruptcy-Prediction.git 
cd Bankruptcy-Prediction 

Install dependencies 
pip install -r requirements.txt 

Run the notebook 
jupyter notebook One.ipynb 

Through this project, I learned: 
How to understand a real-world financial dataset and identify the target column (Bankrupt?) 
How to build a complete machine learning classification pipeline 
How Logistic Regression works as a baseline model 
Why Random Forest performs better in many classification problems 
How to evaluate models using: 
 Confusion Matrix 
 Classification Report 
 ROC-AUC Score 
How to compare multiple models and select the best one based on performance 
The importance of using proper evaluation metrics instead of only accuracy 
How to interpret results and understand whether the model is overfitting or underfitting 

Future Improvements 
 Add feature scaling where needed 
 Use advanced models (XGBoost, LightGBM) 
 Add cross-validation 
 Deploy as a web app (Streamlit / Flask) 
