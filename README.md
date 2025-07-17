# 📊 Hiring Data Analytics Case Study

**Author**: Jeenal Bolia  
**Tool Used**: Microsoft Excel 2022  
**Dataset**: [📂 View Excel Sheet](https://docs.google.com/spreadsheets/d/1Hs6xm2c3ZF2iGhE5wgk84II1TTubev3L/edit?usp=sharing&ouid=113303105779339690895&rtpof=true&sd=true)

---

## 📁 Project Overview

This project explores hiring trends within a company using a real-world HR dataset. The objective was to analyze recruitment patterns based on **gender**, **salary distribution**, **department-level hiring**, and **position tiers**, with the goal of informing smarter hiring decisions and workforce planning.

---

## 🧠 Key Objectives

- Assess gender distribution in hiring  
- Evaluate salary ranges and detect outliers  
- Analyze departmental hiring patterns  
- Identify focus tiers of recruitment  
- Deliver actionable insights for HR and operations  

---

## 🛠️ Tech Stack

| Tool                  | Purpose                                                                 |
|-----------------------|-------------------------------------------------------------------------|
| **Microsoft Excel 2022** | Data cleaning, processing, PivotTables, statistical functions, visualizations |

---

## 🔍 Approach

### ✅ Data Cleaning

- Replaced missing or dash values with “Unknown”
- Detected outliers in salary using **IQR method**:
  - **Q1** = ₹25,460.5  
  - **Q3** = ₹74,438  
  - **IQR** = ₹48,977.5  
  - **Outlier Threshold** = ₹147,905.25  

### 📊 Analysis Conducted

- **Gender-Based Hiring** using PivotTables  
- **Average Salary** using `=AVERAGEIFS()`  
- **Salary Binning** into class intervals using nested `IF()` formulas  
- **Departmental Distribution** via Bar and Pie Charts  
- **Position Tier Distribution** visualized using charts  

---

## 📈 Insights & Findings

- **Gender Balance**: Hiring is relatively equal between male and female candidates; very few are non-binary or unknown.  
- **Average Salary Offered**: ₹49,983.03  
- **Salary Distribution**: Most offers lie in the ₹40K–₹80K range.  
- **Salary Outliers**: Values above ₹147,905 were flagged.  
- **Departmental Hiring**: Highest in **Service** and **Operations**, lowest in HR and General Management.  
- **Tier-Level Hiring**: Focus on mid-level positions (e.g., i4, i5), indicating operational growth.  

---

## 📌 Excel Logic & Formulas

| Task                          | Formula |
|-------------------------------|---------|
| Average Salary (Hired)        | `=AVERAGEIFS(G2:G7169, C2:C7169, "Hired")` |
| Salary Band Classification    | `=IF(G2<=20000,"0–20K",IF(G2<=40000,"20K–40K",IF(G2<=60000,"40K–60K",IF(G2<=80000,"60K–80K",IF(G2<=100000,"80K–1L","1L+")))))` |

---

## 📊 Visualizations

- 📉 **Histogram** of salary bands  
- 🧁 **Pie chart** for department-wise hiring  
- 📊 **Bar graph** for tier-wise recruitment  

_All charts were created using Microsoft Excel._

---

## 🚀 Business Impact

This analysis helps the HR team:

1. Identify potential over- or under-staffing patterns  
2. Ensure fair gender-based hiring and pay structure  
3. Standardize salary offers by flagging inconsistencies  
4. Strategize hiring focus by department and position levels  

---

## 📎 Project Link

📂 [Google Sheet - Dataset & Analysis](https://docs.google.com/spreadsheets/d/1Hs6xm2c3ZF2iGhE5wgk84II1TTubev3L/edit?usp=sharing&ouid=113303105779339690895&rtpof=true&sd=true)

---

## 🙌 Acknowledgement

This project was independently carried out using Microsoft Excel with the goal of enhancing real-world HR analytics skills.

---
