🏥 Medical Insurance Cost Prediction using Machine Learning
📌 Project Overview

This project predicts medical insurance charges using Machine Learning regression models. By analyzing factors such as age, BMI, smoking status, number of children, and region, the model estimates insurance costs and helps understand the key drivers influencing medical expenses.

🎯 Objectives
Analyze insurance customer data.
Identify factors affecting insurance charges.
Build regression models for cost prediction.
Optimize model performance using GridSearchCV.
Generate accurate insurance cost estimates.
📂 Dataset

Dataset: insurance.csv

Feature	Description
age	Age of the customer
sex	Gender
bmi	Body Mass Index
children	Number of dependents
smoker	Smoking status
region	Residential region
charges	Medical insurance cost (Target Variable)
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
XGBoost
🔄 Project Workflow
1. Data Collection
Loaded insurance dataset.
Explored dataset structure and statistics.
2. Exploratory Data Analysis (EDA)
Analyzed relationships between features and insurance charges.
Visualized cost distribution and feature correlations.
3. Data Preprocessing
Handled categorical variables.
Applied feature encoding and scaling.
Built preprocessing pipelines.
4. Model Development
Created baseline regression models.
Performed train-test split.
Applied cross-validation.
5. Hyperparameter Tuning
Used GridSearchCV to find optimal parameters.
Compared model performance.
6. Model Evaluation

Evaluated using:

MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
R² Score
7. Prediction
Predicted insurance costs for new customer data.
Compared predicted and actual charges.
📊 Key Features

✅ Medical Cost Prediction

✅ Regression Analysis

✅ Feature Engineering

✅ Cross Validation

✅ Hyperparameter Tuning

✅ XGBoost Integration

✅ Model Performance Evaluation

📈 Results

The model successfully predicts medical insurance charges based on customer demographics and health-related factors. Analysis revealed that smoking status, age, and BMI are among the most influential factors affecting insurance costs.

📁 Project Structure
Medical-Insurance-Cost-Prediction/
│
├── insurance.csv
├── 15_5_medical_insurance_cost_pred.ipynb
├── README.md
└── requirements.txt
🚀 How to Run
git clone https://github.com/your-username/medical-insurance-cost-prediction.git

cd medical-insurance-cost-prediction

pip install -r requirements.txt

jupyter notebook

Open:

15_5_medical_insurance_cost_pred.ipynb
🔮 Future Improvements
Deploy using Streamlit.
Integrate healthcare cost analytics dashboard.
Experiment with advanced ensemble models.
Add real-time prediction interface.
👨‍💻 Author

Manasvi Pusam

⭐ Skills Demonstrated

Machine Learning • Regression Analysis • XGBoost • Data Preprocessing • Feature Engineering • GridSearchCV • Predictive Analytics • Python • Scikit-Learn • Data Visualization
