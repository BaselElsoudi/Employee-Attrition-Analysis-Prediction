# 🧠 Employee Attrition Prediction System

This project is a full machine learning solution designed to help companies predict employee attrition using historical HR data. It was developed as part of the [AI & Data Science Diploma – DEPI], delivered by EYouth and MCIT.

📊 Project Description

Modulzy is a predictive analytics system designed to support modern HR teams with data-driven hiring and retention strategies. By analyzing historical employee data, Modulzy forecasts the likelihood that a job applicant will complete their contract or leave prematurely. The system combines machine learning with real-world HR insight to transform raw data into actionable predictions — helping organizations reduce turnover before it begins.

🎯 Project Goal

The primary objective of Modulzy is to empower Human Resources departments with a smart screening and decision-support tool. By applying robust classification models to key applicant and employment attributes, the platform flags high-risk candidates early in the hiring process. This not only reduces the cost of premature attrition but also improves long-term employee fit and retention — optimizing the recruitment pipeline from day one.

---
🔍 Project Highlights

1️⃣ Data Cleaning & Preprocessing
🔹Cleaned and standardized HR data (e.g., handling missing values, encoding categorical fields).
🔹Performed correlation analysis and feature selection to reduce noise and improve accuracy.
🔹Engineered new features (e.g., total tenure, satisfaction ratings) from raw fields.
2️⃣ Exploratory Data Analysis (EDA)
🔹Explored patterns between attrition and features like department, overtime, job level, and income.
🔹Visualized trends using histograms, pie charts, and satisfaction-level comparisons.
3️⃣ Modeling & Evaluation
🔹Trained multiple classification models: Random Forest, Gradient Boosting, and VotingClassifier.
🔹Chose the best model using Accuracy, F1-Score, and ROC-AUC.
🔹Exported the final model as a .pkl file for production.
4️⃣ Deployment & Integration
Built a full-stack system:
🔹 Frontend: React.js form for HR data input
🔹 Backend: .NET Core API calling the Python model via stdin
🔹 Database: Logs predictions in SQLite with EF Core
🔹 Dashboard: Visualizes live prediction results and user insights

📈 Results & Impact
Enables real-time attrition prediction from HR input
Helps HR teams focus retention strategies where they matter most
Fully functional system that simulates a real-world SaaS use case

---

## 📂 Project Structure

├── data/ # Cleaned HR dataset
├── model/ # Trained .pkl model
├── Employee_Attrition.ipynb # Main notebook with EDA & modeling
├── README.md 


---

## ▶️ How to Run

1. Clone the repo
2. Open the notebook: `Employee_Attrition.ipynb`
3. Explore the data, modeling process, and results

---

## 🙌 Team & Acknowledgments

This project was built as part of the DEPI capstone project by:
- Basel Elsoudi
- Yousef abdlaziz
- Mostafa Mokhtar
- Menna Elmokadem
- Moustafa Fathy
- Mohamed Samir

**Supervised y**: Dr. Mahmoud Talaat  


---

## 📬 Contact

For collaboration or inquiries, feel free to connect with me on [LinkedIn](https://linkedin.com/in/baselelsoudi)

---

> 🔜 Stay tuned for new projects — more real-world AI solutions are on the way!

