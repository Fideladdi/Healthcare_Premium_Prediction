# Health Insurance Premium Prediction

This project develops a machine learning model to predict health insurance premiums based on applicant information such as age, smoking habits, BMI, income, and medical history. The model is deployed in a Streamlit application so that underwriters and decision-makers can generate premium estimates quickly and consistently.

## Project Overview

Health insurance pricing needs to be accurate and fair. Predicting premiums helps companies:

* Ensure fair pricing for customers
* Reduce risk for the company
* Speed up the underwriting process

By training a machine learning model, underwriters can:

* Approve low-risk applicants quickly
* Flag high-risk applicants for further review
* Standardize pricing decisions

The Streamlit app makes it possible to access predictions instantly through a simple web interface.


## Dataset

The dataset includes the following attributes:

* **Demographics:** age, gender, region, marital\_status
* **Family:** number\_of\_dependants
* **Lifestyle and health:** bmi\_category, smoking\_status, medical\_history
* **Socioeconomic:** employment\_status, income\_level, income\_usd
* **Insurance information:** insurance\_plan, annual\_premium\_usd

The target variable is **annual\_premium\_usd**.


## Tools and Libraries

* Python
* pandas, numpy, scikit-learn
* matplotlib, seaborn
* Streamlit


## Workflow

1. **Exploratory Data Analysis (EDA)**

   * Visualize data distributions
   * Check correlations
   * Identify outliers and important features

2. **Data Preprocessing**

   * Encode categorical variables
   * Scale numerical features
   * Handle missing values

3. **Model Training**

   * Train regression models
   * Compare performance (R², MAE, RMSE)

4. **Model Deployment**

   * Save the best model
   * Build a Streamlit app to serve predictions


## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/health-insurance-premium-prediction.git
   cd health-insurance-premium-prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

