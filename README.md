# End-to-End-Machine-Learning-Python

Insurance Inc. offers affordable health insurance to thousands of customer all over the United States. As the lead data scientist at ACME, you're tasked with creating an automated system to estimate the annual medical expenditure for new customers, using information such as their age, sex, BMI, children, smoking habits and region of residence.

Estimates from your system will be used to determine the annual insurance premium (amount paid every month) offered to the customer. Due to regulatory requirements, you must be able to explain why your system outputs a certain prediction.

🚀 Predicting Insurance Charges with Machine Learning: A Scaled Pipeline Approach
💡 How do insurance companies calculate premiums? This project builds a machine learning pipeline that predicts insurance charges based on factors like age, BMI, smoking status, and region.

🔍 Project Overview
This project focuses on predicting insurance costs using Polynomial Regression, Random Forest, and XGBoost, while addressing key preprocessing challenges: ✅ Feature Engineering – Converts categorical variables (sex, smoker, region) into numerical values
✅ Feature Scaling – Standardizes independent variables for better model performance
✅ Multicollinearity Handling – Removes highly correlated variables to improve model stability
✅ Pipeline Implementation – Automates data transformation & modeling
✅ One-Call Prediction – Predict insurance charges instantly with a single function

📌 Key Features
🔹 Dataset: Health Insurance Cost Prediction Dataset
🔹 Models: Polynomial Regression, Random Forest, XGBoost
🔹 Scaling: StandardScaler() for independent variables & TransformedTargetRegressor() for the target variable
🔹 Pipeline: Automates data transformation and model training
🔹 One-Call Function: Predict insurance charges instantly

⚙️ How It Works
1️⃣ Load & Preprocess Data
2️⃣ Convert Categorical Features (Sex, Smoker, Region → One-Hot Encoding)
3️⃣ Scale Features using StandardScaler()
4️⃣ Train Machine Learning Models (Polynomial Regression, Random Forest, XGBoost)
5️⃣ Evaluate Performance & Choose the Best Model
6️⃣ Save & Load Pipelines for Future Predictions
7️⃣ Deploy a One-Call Function for Real-Time Predictions

🖥️ Example: Predicting Insurance Charges

predicted_charge = predict_insurance_charge(age=45, bmi=28.5, children=2, smoker="yes", sex="male", region="southeast")

print(f"💰 Predicted Insurance Charge: ${predicted_charge:,.2f}")
💰 Output: 💵 Predicted Insurance Charge: $12,340.50

📊 Results & Performance
🔹 R² Score (Polynomial Regression): ~0.86
🔹 R² Score (Random Forest): ~0.89
🔹 R² Score (XGBoost): ~0.90
✅ XGBoost performed best and is recommended for deployment!

📌 Why This Matters?
🏥 Insurance pricing models determine costs based on various risk factors.
📈 Machine Learning pipelines automate and improve premium calculations.
🔍 Fair & Explainable ML models help insurance companies set transparent rates.

If you're working on predictive analytics in healthcare or finance, this end-to-end ML pipeline can be adapted for various regression problems.

👨‍💻 How to Use This Project
1️⃣ Clone the repository or load the dataset
2️⃣ Train the pipeline using PolynomialRegression, RandomForestRegressor, or XGBRegressor
3️⃣ Save the trained model for real-time predictions
4️⃣ Use the one-call function to predict insurance charges in a single step

🔗 Connect & Learn More
📢 Let’s discuss: How can ML improve insurance pricing fairness?
💬 Drop your thoughts in the comments or DM me!

🚀 Follow me for more ML & data science projects! 🙌
