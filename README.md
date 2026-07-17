 🤖 AI-Based Hiring Prediction System
An end-to-end Machine Learning project that predicts whether a candidate is likely to be **Hired** or **Rejected** based on resume-related information. This project simulates an AI-powered resume screening system used in modern HR analytics to assist recruiters in making data-driven hiring decisions.

 📖 Project Overview
Recruiting the right candidate is a time-consuming process, especially when organizations receive hundreds or thousands of resumes for a single job opening. This project demonstrates how Machine Learning can automate the initial resume screening process by analyzing candidate attributes and predicting hiring decisions.
The model is trained on a synthetic hiring dataset containing information such as technical skills, work experience, educational qualifications, certifications, salary expectations, project count, and AI assessment scores. Using these features, the model predicts whether a candidate is likely to be selected or rejected.

🎯 Project Objectives

- Build an end-to-end Machine Learning pipeline for hiring prediction.
- Perform data cleaning and preprocessing.
- Explore and visualize the dataset using Exploratory Data Analysis (EDA).
- Convert categorical data into numerical format using Label Encoding.
- Train a Random Forest Classifier for classification.
- Evaluate the model using multiple performance metrics.
- Predict hiring decisions for new candidate profiles.
- Save the trained model for future use.

 ⚙️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

🔄 Machine Learning Workflow

Dataset Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Data Preprocessing
        │
        ▼
Label Encoding
        │
        ▼
Train-Test Split
        │
        ▼
Random Forest Classifier
        │
        ▼
Model Evaluation
        │
        ▼
Feature Importance Analysis
        │
        ▼
Prediction on New Candidate

📊 Exploratory Data Analysis (EDA)

The following visualizations were created to better understand the dataset:

- Hiring vs Rejection Distribution
- Education Distribution
- Job Role Distribution
- Experience Distribution
- Salary Expectation Distribution
- Projects Count Distribution
- Correlation Heatmap
- Feature Importance Chart
- Confusion Matrix

 🧹 Data Preprocessing

Before training the model, the dataset was prepared through several preprocessing steps:

- Removed unnecessary columns (`Resume_ID` and `Name`)
- Checked for missing values
- Removed duplicate records
- Encoded categorical variables using Label Encoding
- Prepared feature and target datasets
- Split the dataset into training and testing sets

 🤖 Machine Learning Model

Algorithm Used: Random Forest Classifier
Why Random Forest?

- Handles both numerical and categorical data efficiently.
- Reduces overfitting through ensemble learning.
- Provides high prediction accuracy.
- Generates feature importance scores.
- Performs well on structured datasets.

 📈 Model Evaluation

The model was evaluated using the following metrics:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

📌 Feature Importance

The trained model identifies the most influential features affecting hiring decisions, including:

- Experience
- AI Score
- Skills
- Education
- Certifications
- Projects Count
- Salary Expectation

 📁 Project Structure

AI-Based-Hiring-Prediction-System/
│
├── AI_Based_Hiring_Prediction.ipynb
├── AI-Based Hiring Prediction System.csv
├── README.md

📚 Key Learning Outcomes

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Label Encoding
- Machine Learning Model Development
- Model Evaluation
- Feature Importance Analysis
- Model Serialization using Pickle

👩‍💻 Author

Anveshi Srivastava

B.Tech (Artificial Intelligence & Machine Learning)

 ⭐ Show Your Support

If you found this project helpful or interesting, please consider giving it a ⭐ Star on GitHub. It helps support my work and encourages me to build more Machine Learning and Data Science projects.
