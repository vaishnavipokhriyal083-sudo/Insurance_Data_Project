# Insurance_Data_Project
Build and compare multiple regression models to predict medical insurance charges and identify the best-performing model based on prediction accuracy and error metrics.

**🏥 Medical Insurance Cost Prediction using Machine Learning**

🏥 Medical Insurance Cost Prediction using Machine Learning

**📌 Project Overview**

Medical insurance charges are influenced by several demographic and lifestyle factors, making accurate cost estimation a challenging task. This project uses Machine Learning regression algorithms to predict medical insurance charges based on customer information such as age, gender, BMI, number of children, smoking status, and region.

The project compares the performance of Linear Regression, Decision Tree Regressor, Random Forest Regressor, and XGBoost Regressor to identify the most accurate predictive model.


---

**🎯 Problem Statement**

The objective of this project is to build a machine learning model that accurately predicts medical insurance charges using customer demographic and lifestyle information. Multiple regression models are trained and evaluated to determine which algorithm provides the highest prediction accuracy while minimizing prediction errors.


---

**🎯 Objectives**

- Predict medical insurance charges using Machine Learning.

- Perform data preprocessing and cleaning.

- Handle missing values and outliers.

- Encode categorical variables.

- Train multiple regression models.

- Compare model performance using evaluation metrics.

- Select the best-performing model.



---

📂 Dataset Features

- Age

- Sex

- BMI

- -Children

- Smoker
  
- Claim_Amount

- past_consultations

- num_of_steps

- Hospital_expenditure

- Number_of_past_hospitalizations

- Anual_Salary

- region

- Charges (Target Variable)



---

**🛠 Technologies Used**

- Python

- Pandas

- NumPy

- Matplotlib

- Scikit-learn

- XGBoost

- Jupyter Notebook



---

**⚙️ Machine Learning Workflow**

1. Import required libraries


2. Load the dataset


3. Explore the dataset


4. Handle missing values


5. Remove duplicate records


6. Detect and remove outliers using the IQR method


7. Encode categorical variables


8. Split the dataset into training and testing sets


9. Train regression models


10. Evaluate model performance


11. Compare all models


12. Select the best-performing model




---

**🤖 Models Implemented**

- Linear Regression

- Decision Tree Regressor

- Random Forest Regressor

- XGBoost Regressor



---

**📊 Model Performance**

1. Model - Random Forest Regressor 

   R² Score Performance - 98.99% ⭐ Best

2. Model - XGBoost Regressor 

   R² Score Performance - 98.88% Excellent

3. Model - Decision Tree Regressor 

   R² Score Performance - 97.08% Very Good

4. Model - Linear Regression 

   R² Score Performance - 96.95% Good



---

**📈 Evaluation Metrics**

- The models were evaluated using:

- R² Score

- Mean Absolute Error (MAE)

- Mean Squared Error (MSE)

- Root Mean Squared Error (RMSE)



---

**🏆 Best Model**

Random Forest Regressor achieved the best performance with:

✅ Highest R² Score (98.99%)

✅ Lowest MAE

✅ Lowest MSE

✅ Lowest RMSE


Hence, Random Forest was selected as the final prediction model.


---

**📚 Key Learnings**

Through this project, I gained practical experience in:

- Data preprocessing

- Missing value handling

- Outlier detection using IQR

- Label Encoding

- Feature selection

- Regression algorithms

- Model evaluation

- Performance comparison

- Machine Learning workflow

- Visualizations



---

🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV

- Feature engineering

- Cross-validation

- Model deployment using Streamlit or Flask

- Integration with real-world insurance datasets

- Building an interactive prediction dashboard



---

📌 Project Structure

Medical-Insurance-Cost-Prediction/

│

├── Medical_Insurance_Cost_Prediction.ipynb

├── insurance.csv

├── README.md

└── requirements.txt



---

**📸 Results**

- Successfully predicted medical insurance charges using machine learning.

- Compared four regression algorithms.

- Achieved 98.99% R² Score with the Random Forest Regressor.

- Identified the most accurate model through performance comparison.



---

**🤝 Connect With Me**

If you found this project helpful, feel free to ⭐ star the repository and connect with me on LinkedIn.


---

**📄 License**

This project is intended for educational and portfolio purposes. Feel free to use and modify it with proper attribution.


---

⭐ If you like this project, don't forget to star the repository

