# IBM HR Attrition Analysis Dashboard

📊 **Interactive Power BI Dashboard** analyzing employee attrition patterns using the IBM HR Analytics dataset.  
The project identifies key drivers of turnover and provides actionable insights to help HR teams improve retention.

---

## 📌 Project Overview
Employee attrition is one of the biggest challenges for HR departments — losing skilled employees increases recruitment costs, disrupts workflows, and can impact morale.

In this project, I:
- Analyzed the **IBM HR Analytics dataset** to uncover **patterns behind employee attrition**.
- Built an **interactive Power BI dashboard** to allow filtering by department, job role, and other employee attributes.
- Created **custom DAX measures** to calculate and visualize attrition drivers dynamically.

---

## 🛠 Tools & Technologies
- **Power BI** – Data modeling, visualizations, interactive dashboard
- **DAX** – Custom measures for KPIs and attrition reason analysis
- **IBM HR Analytics Dataset** – Sample HR data from [IBM Watson Analytics](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2016/09/02/hr-employee-attrition)

---

## 📊 Dashboard Features
### **1. Attrition Overview**
- **Total Employees**, **Attrition Count**, and **Attrition Rate** KPIs
- Dynamic filtering by Department, Job Role, and other demographics

### **2. Key Metrics**
- **Attrition by Age Group, Tenure, and Salary Range**
- **Attrition Rate by Job Level**
- **Average Time in Role Before Leaving**

### **3. Reasons for Leaving (Custom DAX)**
Instead of showing only raw counts, I developed a **DAX-driven stacked bar chart** to visualize key attrition drivers:
- **Overtime** – High workload correlation
- **No Promotion in Last 2 Years**
- **Frequent Travel**
- **Low Job Satisfaction**

This is built entirely with DAX (no unpivoting), preserving the original dataset structure.

---

## 🔍 Key Insights from the Analysis
- **Early Tenure Attrition**: Most leavers had <3 years at the company.
- **Salary Gap**: Employees leaving had a median salary significantly below the overall median.
- **Workload Impact**: Overtime was a major factor in several departments.
- **Career Progression**: Lack of promotion opportunities strongly correlated with leaving.
