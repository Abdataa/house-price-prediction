 House Price Prediction – ML Regression Project

This project uses various regression algorithms to predict house prices based on multiple housing features. The dataset used is similar to the popular Kaggle House Prices: Advanced Regression Techniques dataset.

📌 Problem Statement

Predict the final sale price of houses based on a variety of features like size, neighborhood, year built, number of rooms, etc. This is a classic supervised regression problem.


 🧠 Machine Learning Workflow

🔹 Models Trained
- Linear Regression – baseline model
- Decision Tree Regressor
- Random Forest Regressor – best performing
- Hyperparameter Tuning with `GridSearchCV` to fine-tune Random Forest

📊 Evaluation Metrics
- Cross-validation (CV): 5-fold cross-validation
- Root Mean Squared Error (RMSE): Primary metric used for evaluation


 🛠️ Tools & Libraries
- Python (JupyterLab)
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Joblib (to save the trained model)



⚙️ Project Structure:

---house-price-prediction/ ├── notebook.ipynb # Jupyter notebook with full code and analysis
├── model.joblib # Final trained model (Random Forest) 
├── sample_data.csv # (Optional) Sample dataset 
├── requirements.txt # Python dependencies 
├── README.md # Project overview 
└── .gitignore

