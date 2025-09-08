# **HR Attrition Analysis – End-to-End Project**

## 📌 **Project Overview**
Employee attrition (turnover) is a critical issue for organizations. This project analyzes HR data to identify key factors influencing attrition and provide actionable insights.  

The project is implemented in **two stages**:  
1. **Exploratory Data Analysis (EDA) with Python**  
2. **Interactive Dashboard with Power BI**

---

## 📂 **Dataset Details**
- **Dataset Name:** HR Attrition Dataset  
- **Records:** 1,470 employees  
- **Features Include:**  
  - `EmployeeNumber`, `Age`, `Gender`, `Department`, `JobRole`, `Attrition`  
  - `MonthlyIncome`, `HourlyRate`, `OverTime`, `YearsAtCompany`  

---

## 🛠 **Tools & Technologies**
- **Python:** Pandas, Matplotlib, Seaborn, Scikit-learn  
- **Power BI:** Dashboard & data visualization  
- **Excel:** Initial data cleaning  

---

## ✅ **Project Workflow**
### **Step 1: Data Cleaning & Preprocessing**
✔ Removed missing values  
✔ Renamed inconsistent columns  
✔ Converted date columns to proper format  

### **Step 2: Exploratory Data Analysis (Python)**
✔ Key Python tasks:
- Age distribution visualization  
- Attrition by department and job role (bar plots)  
- Correlation heatmap for numerical features  
- Overtime vs Attrition analysis  

*(Python code and Jupyter Notebook are included in the repository.)*

### **Step 3: Dashboard Development (Power BI)**
✔ Imported cleaned dataset into Power BI  
✔ Created KPIs and measures using DAX:
- `Attrition Count`
- `Attrition Rate %`
- `Average Monthly Income`
- `Average Hourly Rate`  
✔ Built interactive visuals:
- Attrition by Department (Bar Chart)
- Attrition by Job Role (Tree Map)
- Attrition by Age Band (Bar Chart)
- Attrition vs Years at Company (Line Chart)
- Overtime Impact (Pie Chart)
- Income Distribution (Histogram)

---

## 📌 **Key Insights**
- **Overall Attrition Rate:** 16%  
- **By Department:** Research & Development has the highest attrition.  
- **By Job Role:** Sales Executives and Laboratory Technicians have the most attrition.  
- **By Age:** Younger employees (18–25) leave more often than older groups.  
- **Overtime Impact:** Employees working overtime have a significantly higher attrition rate.  

---

## 📂 **Files in Repository**
- `hr_attrition_eda.ipynb` – Jupyter Notebook for EDA using Python  
- `HR_Attrition.pbix` – Power BI dashboard  
- `HR_Attrition_Report.pdf` – Dashboard export with insights  
- `Dashboard_Screenshot.png` – Preview of the dashboard  
- `Dataset.csv` – Cleaned dataset  
- `README.md` – This documentation  

---
