🕵️‍♂️ Credit Card Fraud Detection
This project focuses on developing a machine learning model to efficiently detect fraudulent credit card transactions, minimizing false positives while maintaining high accuracy.

🎯 Objective
Develop a classification model to predict fraudulent transactions.
Handle data preprocessing effectively, including feature scaling and encoding.
Evaluate the model using performance metrics such as Precision, Recall, and AUC-ROC.
Optimize the model to minimize false positives while maintaining high sensitivity.

🛠️ Project Overview
This repository contains a step-by-step implementation of a fraud detection system using machine learning techniques. The workflow follows a structured pipeline that includes:
Data Exploration: Initial exploration of data, visualization, and identifying key patterns.
Data Preprocessing: Handling missing values, feature scaling, and encoding.
Model Training: Training and optimizing multiple classification models.
Model Evaluation: Evaluating model performance using key metrics.

How to Run the Project
1.	Clone the Repository:
bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
2.	Navigate to the Project Directory:
cd credit-card-fraud-detection
3.	Install Required Packages:
pip install -r requirements.txt
4.	Open and Run Jupyter Notebooks:
jupyter notebook

Run the notebooks in the following order:
1.	01_data_exploration.ipynb
2.	02_preprocessing.ipynb
3.	03_model_training.ipynb
4.	04_model_evaluation.ipynb

📈 Model Evaluation Metrics
•	ROC-AUC Score: High discriminatory power between fraud and legitimate transactions.
•	Precision: Accuracy of detecting fraudulent transactions.
•	Recall: Ability to capture most fraudulent transactions.
•	Confusion Matrix: Shows classification results with true positives, false positives, etc.

🔥 Technologies Used
•	Python
•	Pandas, NumPy for data handling
•	Matplotlib, Seaborn for visualization
•	Scikit-learn for model training and evaluation
•	Joblib for model persistence
•	Jupyter Notebook for project execution

