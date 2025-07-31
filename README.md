📊 Employee Salary Prediction – IBM SkillsBuild Internship Project

 -This project was developed during my internship with IBM SkillsBuild (via Edunet Foundation) and focuses on predicting employee salaries based on job-related features. A Linear Regression model is used to         estimate annual salary, and the solution is deployed through a Streamlit web application for real-time user interaction.

🔍 Overview
The objective of this project is to predict an employee's Annual Salary using two key features:

  -Years of experience
  -Job Rate

The project workflow includes:

  -Data cleaning and analysis
  -Feature engineering
  -Model building and evaluation
  -App deployment for real-time predictions

✅ Features

  -📈 Exploratory Data Analysis (EDA) with visual insights
  -🧠 Linear Regression model for salary estimation
  -🌐 Streamlit Web Interface for real-time interaction
  -💾 Saved Model (.pkl) for fast prediction
  -📊 Interactive Visualizations using Matplotlib

📁 Repository Structure
File	                                       Description
prediction.ipynb	         -              Data analysis, visualization, model training, saving the model
my_app.py	                 -              Streamlit based app for live salary prediction
Employees.xlsx	           -              Dataset containing job-related attributes
linearmodel.pkl	           -              trained and serialized regression model

📚 Dataset Info
  Format: .xlsx

  Key Columns:

  -Years – Experience level
  -Job Rate – Performance or job complexity metric
  -Annual Salary – Target variable to be predicted

Dataset Source: Public sample available via Kaggle or similar repositories.

🚀 How to Run the Project:

🧪 Step 1: Train the Model
jupyter notebook

-Open prediction.ipynb
-Run all cells to generate linearmodel.pkl

🌐 Step 2: Launch the Streamlit App
streamlit run my_app.py

-A web app will launch in your browser.
-Enter Years and Job Rate to get the predicted salary.

🔧 Technologies Used

 -Python
 -Pandas, NumPy – Data manipulation
 -Matplotlib – Visualization
 -Scikit-learn – Linear Regression modeling
 -Joblib – Model persistence
 -streamlit – Web UI development


📌 Internship Acknowledgement
This project is part of my learning journey under the
IBM SkillsBuild Internship (in collaboration with Edunet Foundation)
🧠 Focus Area: Applied Machine Learning & AI
🎓 Mode: Remote
