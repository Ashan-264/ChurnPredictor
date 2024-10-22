# 📊 Customer Churn Prediction Dashboard

Welcome to the **Customer Churn Prediction Dashboard**! This interactive tool leverages machine learning to predict customer churn and provides insightful explanations and personalized communications to retain valuable clients.

# 🌐 **Live Demo:** [Try the App Now](https://ashans-churn-predictor.streamlit.app/)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project](#project)
- [Technical Highlights](#technical-highlights)
- [Dependencies](#dependencies)
- [Contact Information](#contact-information)

---

## Overview

In the competitive banking industry, understanding and preventing customer churn is crucial. This dashboard allows you to:

- Predict the likelihood of a customer leaving the bank.
- Understand the factors influencing their decision.
- Generate personalized communications to encourage them to stay.

By combining interactive visualizations with advanced machine learning models, this tool offers both depth and clarity in customer churn analysis.

## Features

- **Multi-Model Churn Prediction:**
  - Implements algorithms like **XGBoost**, **Random Forest**, and **K-Nearest Neighbors**.
  - Compares predictions across models for comprehensive insights.

- **Interactive User Interface:**
  - Dynamic input of customer data to see real-time predictions.
  - User-friendly sliders, dropdowns, and checkboxes.

- **Advanced Visualizations:**
  - 📈 **Gauge Chart:** Illustrates overall churn probability.
  - 📊 **Bar Chart:** Displays individual model probabilities.

- **Natural Language Explanations:**
  - Integrates with **OpenAI's API** to generate easy-to-understand explanations.
  - Offers personalized insights without technical jargon.

- **Automated Communication:**
  - Generates customized emails to customers with tailored incentives.

---

## Technologies Used

- **Programming Languages:** Python 3.x
- **Web Frameworks:** Streamlit
- **Data Analysis:** Pandas, NumPy
- **Machine Learning:** Scikit-Learn, XGBoost, Imbalanced-Learn
- **APIs and Integration:** OpenAI API
- **Data Visualization:** Plotly
- **Software Engineering Practices:** Modular code, virtual environments, documentation

---

## Getting Started

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/customer-churn-prediction.git
   cd customer-churn-prediction
Set Up a Virtual Environment (Optional but Recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Set Up API Keys:

Add your GROQ API key to your environment variables:

bash
Copy code
export GROQ_API_KEY=<your_groq_api_key>
Ensure you have access to the OpenAI API.

Model Files:

Place the pre-trained model files in the models/ directory:

xgb_model.pkl
mb_model.pkl
rf_model.pkl
dt_model.pkl
svm_model.pkl
knn_model.pkl
voting_clf.pkl
xgboost_SMOTE.pkl
xgboost_featureEngineered.pkl
Dataset:

Add the churn.csv dataset to the root directory.
## Usage
Run the Streamlit App:

bash
Copy code
streamlit run app.py
Interact with the Dashboard:

Select a Customer: Choose from the dropdown menu.
Adjust Parameters: Modify attributes to simulate scenarios.
View Predictions: See real-time updates on churn probabilities.
Explore the Results:

Visualizations: Analyze churn probabilities through charts.
Explanations: Read natural language interpretations.
Emails: Review personalized communication content.

## Project
- **app.py**: The main entry point of the Streamlit application.
- **churn.csv**: Dataset containing customer information for churn analysis.
- **utils.py**: Contains helper functions for creating charts and other visual elements.
- **models/**: Directory that holds all pre-trained machine learning models.
- **requirements.txt**: Lists all the dependencies required for the project.
- **README.md**: Documentation for understanding and navigating the project.


## Technical Highlights
Data Preprocessing:

Handled categorical variables with one-hot encoding.
Managed missing values and ensured data integrity.
Model Training:

Trained multiple classifiers for performance comparison.
Used cross-validation and grid search for tuning.
Imbalanced Data Handling:

Applied SMOTE to address class imbalance.
API Integration:

Integrated with OpenAI's GPT models for explanations.
Secured API keys and tokens.
User Experience:

Intuitive interface with real-time feedback.
Responsive design for seamless interaction.
Deployment:

Deployed on Streamlit Sharing for accessibility.
Optimized for performance and user experience.
## Dependencies
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Key dependencies include:

streamlit
pandas
numpy
scikit-learn
xgboost
openai
plotly
## Contact Information
👨‍💻 Developer: [Ashan Deen]

✉️ Email: [Ashan@gatech.com]

💼 LinkedIn: https://www.linkedin.com/in/ashan264/

🌐 Portfolio: https://www.ashan264.com/

Thank you for exploring the Customer Churn Prediction Dashboard! This project demonstrates a blend of data science expertise and software engineering skills, emphasizing interactive user experiences and effective communication of complex results.

Feel free to reach out with any questions or feedback!

🚀 Check Out the Live App!
Experience the full functionality by visiting the live app:

🌐 Customer Churn Prediction Dashboard
