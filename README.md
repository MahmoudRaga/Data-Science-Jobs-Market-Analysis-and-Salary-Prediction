# 💼 Data Science Jobs Market Analysis & Salary Prediction

This project analyzes the data jobs market using **Power BI dashboards** and predicts **data scientist salaries** using a Machine Learning model in **Python**.

![](https://github.com/MahmoudRaga/Data-Science-Jobs-Market-Analysis-and-Salary-Prediction/blob/main/Cover.png)

---

## 📊 Power BI Dashboard

We built a comprehensive 3-page dashboard from a dataset containing thousands of data job postings. Each page explores a different business perspective:

### 🔹 Page 1: General Overview
- Total number of job listings
- Number of unique job titles and companies
- Top 10 countries hiring the most
- Most demanded work settings and employment types
![](https://github.com/MahmoudRaga/Data-Science-Jobs-Market-Analysis-and-Salary-Prediction/blob/main/Page1.png)
---
### 🔹 Page 2: Salary & Role Insights
- Average salary by:
  - Work setting (remote/in-office/hybrid)
  - Experience level
  - Employment type
- Comparison of average salary across top job titles
![](https://github.com/MahmoudRaga/Data-Science-Jobs-Market-Analysis-and-Salary-Prediction/blob/main/Page2.png)
---
### 🔹 Page 3: Job Market Exploration
- Top 10 job titles
- Distribution by employment type, experience, and location
- Dynamic filters:
  - Experience Level
  - Employment Type
  - Work Setting
  - Company Location
  - Job Title (searchable)
![](https://github.com/MahmoudRaga/Data-Science-Jobs-Market-Analysis-and-Salary-Prediction/blob/main/Page3.png)
---
Tooltips and filters were added to enhance interactivity.

---

## 📈 Salary Prediction – Jupyter Notebook

The notebook (`Data science jobs Salary Prediction.ipynb`) contains a machine learning pipeline to predict **data scientist salaries** based on job features.

### 🔍 Features used:
- Job Title
- Experience Level
- Employment Type
- Work Setting
- Company Location
- Employee Residence

### 🔧 Model:
- Preprocessing: Label Encoding, Data Standarization , 
- Model: CatBoostRegressor (can be changed to XGBoost or other models)
- Evaluation: MAE, R² Score

### 📁 Files:
- `jobs_in_data.csv`: The original dataset used for both dashboard and modeling.
- `Data-science-jobs-Salary-Prediction.ipynb`: The notebook containing preprocessing, model training, and evaluation.
- `PowerBI_Dashboard.pbix`: The dashboard file (optional if shared).
- `README.md`: You are here.

---

## 🙋 Author

**Mahmoud Ragab**  
Data Analyst | ML Engineer

📬 Email: mahmoudragabsaber2001@gmail.com  
🔗 [GitHub](https://github.com/MahmoudRaga) | [LinkedIn](https://www.linkedin.com/in/mahmoud-ragab-0842511b7/)

---

## 🚀 How to Run the Notebook

```bash
# 1. Clone the repo
git clone https://github.com/MahmoudRaga/Data-science-jobs-Salary-Prediction/blob/main/Data%20science%20jobs%20Salary%20Prediction.ipynb
cd Data science jobs Salary Prediction.ipynb

# 2. Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the notebook
jupyter notebook Data science jobs Salary Prediction.ipynb
