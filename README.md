
# 💼 San Francisco Employee Salaries Analysis 📊

This project provides an in-depth analysis and salary prediction model for public employees in San Francisco between 2011 and 2018. It explores salary components, highlights high-paying job titles, and predicts total compensation using Linear Regression. The data is visualized using Python and Tableau to support decision-making, transparency, and compensation planning.

## 📁 Dataset

**Name:** Salaries for San Francisco Employees  
**Source:** Nevada Policy Research Institute (publicly available)  

**Columns:**  
- `EmployeeName`: Name of the employee  
- `JobTitle`: Designation/Role of the employee  
- `BasePay`: Basic salary (annual)  
- `OvertimePay`: Compensation for overtime work  
- `OtherPay`: Additional pay/allowances  
- `Benefits`: Non-cash benefits (e.g., insurance)  
- `TotalPay`: Total compensation excluding benefits  
- `TotalPayBenefits`: Total compensation including all benefits  
- `Year`: Year of the payroll record  

## 🎯 Objectives

- Analyze historical salary data from 2011–2018  
- Visualize trends in total pay and benefits  
- Identify top-paying job titles and salary distribution  
- Predict total compensation using Linear Regression  
- Create interactive Tableau dashboards for stakeholder insights  

## 🛠️ Tools & Technologies

| Tool             | Usage                           |
|-----------------|----------------------------------|
| Python          | Data analysis, modeling         |
| Jupyter Notebook| Exploratory & predictive analysis |
| Scikit-learn    | Linear Regression implementation |
| Tableau         | Interactive salary visualizations |
| Git & GitHub    | Version control & project sharing |

## 📈 Python Analysis & Modeling

### Key Steps:

✅ **Data Cleaning**  
- Handled missing values and `"Not Provided"` entries  
- Converted pay columns to numeric  

✅ **Exploratory Data Analysis (EDA)**  
- Visualized trends using Matplotlib and Seaborn  
- Identified top job titles by pay  
- Analyzed salary distributions and correlations  

✅ **Predictive Modeling: Linear Regression**  
- Encoded job titles  
- Trained Linear Regression model to predict `TotalPayBenefits`  
- Evaluation using MAE and R² Score:  
  - Mean Absolute Error: ~\$65  
  - R² Score: ~0.92 (explains 92% of variability)  

## 📊 Tableau Dashboard

The project includes an interactive Tableau dashboard featuring:

- Total Pay and TotalPayBenefits trends over time  
- Top job titles with highest average compensation  
- Salary distribution with box plots  
- Breakdown of pay components (BasePay, OvertimePay, OtherPay, Benefits)  
- Filters for year and job title for interactive exploration  

**[Tableau Dashboard Link Placeholder]**

## 📌 Results & Takeaways

✅ Total compensation has increased steadily from 2011 to 2018  
✅ Roles like CEO, senior law enforcement, and executives have the highest pay  
✅ BasePay is the primary component, with Benefits and Overtime boosting total earnings  
✅ Linear Regression provides reliable predictions for total pay  
✅ Tableau dashboard enables transparent, interactive insights for stakeholders  

## 🔍 Future Improvements

- Incorporate department or experience-level factors  
- Extend modeling with Random Forest or XGBoost  
- Forecast future salary trends with time-series models  
- Add predictive segmentation by job title or year  

## 🤝 Contact

**Author:** Manasi Mudadla  
**Connect:** LinkedIn  
**Email:** manasimudadla0902@gmail.com  

⭐ If you found this project helpful, feel free to star the repo and share your feedback!
