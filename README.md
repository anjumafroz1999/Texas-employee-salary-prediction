# Texas-employee-salary-prediction
# Texas Employee Salary Prediction

## 📌 Project Overview
This repository contains analysis and predictive modeling on the **Texas Employee Salary Dataset**.  
The dataset includes employee salary records across departments, roles, and time periods, enabling insights into wage disparities and salary trends.

The primary objectives of this project are:
- 🔍 **Analyze salary trends** across departments and roles  
- 📊 **Identify wage disparities** between managers and employees  
- 🤖 **Build predictive models** to estimate employee salaries  
- 💡 **Provide insights** for workforce compensation and HR analytics  

---

## 📂 Dataset
The dataset includes features such as:
- **Employee attributes**: Department, Role, Job Title  
- **Compensation details**: Base Salary, Total Compensation  
- **Time-based features**: Year, Hiring Date  
- **Demographics**: Region, Employment Type  

---

## ⚙️ Methodology
1. **Exploratory Data Analysis (EDA)**  
   - Salary distribution by department and role  
   - Wage disparity analysis between managers and employees  
   - Trend analysis over time  
2. **Data Preprocessing**  
   - Handling missing values  
   - Outlier detection and removal  
   - Feature engineering for predictive modeling  
3. **Model Building**  
   - Linear Regression, Random Forest Regressor, Gradient Boosting  
   - Hyperparameter tuning using GridSearchCV and RandomizedSearchCV  
4. **Model Evaluation**  
   - R² score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)  
   - Best model: **Random Forest Regressor** with R² ≈ 0.91 and low error rate  

---

## 📈 Key Insights
- **Managers vs Employees**: Managers consistently earn 2–3× more than employees, with chief executives averaging ~$298,000 compared to ~$61,000 for general staff.  
- **Departmental disparities**: Tech, healthcare, and management roles show faster salary growth compared to administrative positions.  
- **Trend analysis**: Salaries have steadily risen since the late 1990s, with widening disparities over time.  
- **Predictive accuracy**: The Random Forest model generalizes well to unseen samples, making it suitable for compensation forecasting.  

---

```bash
git clone https://github.com/yourusername/texas-salary-prediction.git
cd texas-salary
