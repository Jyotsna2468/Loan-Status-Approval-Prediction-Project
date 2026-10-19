# 🏦 Loan Status Approval Prediction

## 📌 Project Overview

The **Loan Status Approval Prediction** project uses Machine Learning to predict whether a loan application is likely to be approved or rejected based on applicant details and financial information.

The project involves data cleaning, exploratory data analysis (EDA), feature engineering, model training, and evaluation. A trained machine learning model is deployed using Streamlit, allowing users to enter applicant details and receive a prediction through a simple web interface.

## 🚀 Live Demo

Try the deployed application here:

🔗 **[Loan Status Approval Prediction – Live App](https://loan-status-approval-prediction-project-jyotsna.streamlit.app/)**

## 🎯 Project Objectives

- Predict loan approval status using Machine Learning.
- Analyze applicant and financial information.
- Clean and preprocess the dataset.
- Explore important patterns and relationships in the data.
- Train and evaluate classification models.
- Deploy the trained model using Streamlit.

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical computations
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine Learning and model evaluation
- **Streamlit** – Web application and deployment
- **Joblib / Pickle** – Saving and loading trained models, if used in the project

## 🔄 Project Workflow

The project follows these steps, from data gathering to deployment:

### 1. Data Gathering
Collected the loan application dataset containing applicant details, income, loan amount, credit history, property information, and loan status.

### 2. Data Understanding
Examined the dataset's rows, columns, data types, and structure using Pandas to understand the available features and target variable.

### 3. Data Cleaning
- Identified and handled missing values.
- Checked for duplicate records.
- Corrected data types where necessary.
- Prepared the dataset for analysis.

### 4. Exploratory Data Analysis (EDA)
- Analyzed the distribution of loan approvals and rejections.
- Studied applicant income and loan amount.
- Explored relationships between categorical features and loan status.
- Used charts and visualizations to identify patterns in the data.

### 5. Feature Engineering and Preprocessing
- Separated input features and the target variable.
- Encoded categorical variables into numerical values.
- Handled missing values using suitable techniques.
- Scaled numerical features when required by the selected model.

### 6. Train-Test Split
Divided the dataset into training and testing sets to train the model and evaluate its performance on unseen data.

### 7. Model Training
Trained suitable Machine Learning classification algorithms to predict loan approval status.

### 8. Model Evaluation
Evaluated the trained model using appropriate classification metrics, such as:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The final model should be selected based on its performance and suitability for the prediction task.

### 9. Model Saving
Saved the trained model and any required preprocessing objects so they could be reused by the deployment application.

### 10. Application Development
Built an interactive Streamlit application where users can enter loan applicant details and obtain a predicted loan status.

### 11. Model Deployment
Deployed the Streamlit application online so users can access the loan prediction system through a web browser.

🌐 **Live Application:** [Open Loan Prediction App](https://loan-status-approval-prediction-project-jyotsna.streamlit.app/)

## 📊 Key Features

- Interactive loan status prediction
- Applicant information input form
- Machine Learning-based classification
- Data preprocessing and model evaluation
- User-friendly Streamlit interface
- Online deployment for easy access

## 💻 How to Run Locally

1. Clone the repository:

   ```bash
   git clone <your-github-repository-url>
   ```

2. Navigate to the project folder:

   ```bash
   cd <your-project-folder>
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit application:

   ```bash
   streamlit run app.py
   ```

   *Replace `app.py` with your actual application filename if it differs.*

## 🎓 Learning Outcomes

- Learned the complete Machine Learning workflow.
- Practiced data cleaning and preprocessing.
- Performed exploratory data analysis and visualization.
- Understood classification algorithms and evaluation metrics.
- Learned how to save and reuse a trained model.
- Gained practical experience deploying a Machine Learning application with Streamlit.

## 👩‍💻 Author

**Jyotsna Shinde**



## 📌 Conclusion

This project demonstrates the end-to-end development of a Machine Learning application, from collecting and preparing data to training, evaluating, and deploying a model. It provides an interactive way to explore loan status predictions based on applicant information.


