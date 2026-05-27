# 🎯 Marketing Campaign Data Cleaning with Python
## 📌 Project Overview
This project demonstrates a complete data cleaning and preprocessing workflow using messy marketing campaign data.<br>

Raw business datasets often contain inconsistencies such as:<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Incorrect formatting<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Missing values<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Duplicate columns<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Invalid date sequences<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Inconsistent categorical labels<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Statistical outliers<br>

This project systematically identifies and resolves these issues to produce a clean, analysis-ready dataset for reliable business reporting and decision-making.

## 🚀 Business Problem
Marketing teams rely on accurate campaign performance data to evaluate effectiveness, allocate budgets, and optimize future strategies.<br>

However, poor data quality can lead to:<br>
❌ Misleading campaign performance metrics<br>
❌ Incorrect customer insights<br>
❌ Faulty budget allocation decisions<br>
❌ Inaccurate business reporting<br>
<br>
This project solves that problem by applying structured data quality remediation techniques to ensure analytical integrity.

## 🛠️ What This Project Solves
The notebook addresses common real-world data quality issues, including:<br>

**🧹 1. Column Standardization**<br>
Standardizes inconsistent column naming conventions for better readability and maintainability.<br>

**💰 2. Currency & Numeric Cleaning**
Removes:<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Currency symbols<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Commas<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Formatting inconsistencies<br>

Converts financial values into clean numeric format for analysis.
```
$4,500 → 4500
```

**🏷️ 3. Categorical Data Correction**
Fixes inconsistent channel labels such as:<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Facebok → Facebook<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Gogle → Google<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Tik_Tok → TikTok<br>
<br>
This prevents fragmented grouped analysis.

**✅ 4. Boolean Normalization**<br>
Converts mixed active status representations into standardized boolean values.<br>

**Before**<br>
```
Y, Yes, 1, No, 0
```

**After**<br>
```
True / False
```

**📅 5. Date Validation**<br>
Corrects temporal inconsistencies where:<br>
```
end_date < start_date
```
Ensures campaign timelines are logically valid.<br>

**📊 6. Logical Business Rule Validation**<br>
Validates campaign metrics using business rules such as:
```
clicks < impressions
```

**📈 7. Outlier Detection & Treatment**<br>
Applies IQR-based capping to manage extreme spend values that could distort analysis.<br>

## 💻 Technical Skills Demonstrated
This project showcases proficiency in:

**🐍 Python Programming**<br>
Clean, structured analytical scripting

**📊 Data Wrangling**<br>
Using Pandas for:<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Cleaning<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Transformation<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Validation<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Standardization<br>

**📐 Statistical Analysis**<br>
Applying:<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Quantile calculations<br>
&nbsp;&nbsp;&nbsp;&nbsp;• IQR outlier detection<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Threshold-based anomaly handling<br>

**🔍 Data Quality Assurance**<br>
Systematic validation of business-critical records

**🧠 Analytical Problem Solving**<br>
Diagnosing and resolving real-world data integrity issues

## 🧰 Tools & Libraries Used<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Python<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Pandas<br>
&nbsp;&nbsp;&nbsp;&nbsp;• NumPy<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Jupyter Notebook<br>

## 📂 Project Workflow
```
Raw Dataset
   ↓
Initial Inspection
   ↓
Data Cleaning
   ↓
Validation Checks
   ↓
Anomaly Correction
   ↓
Outlier Treatment
   ↓
Clean Dataset Export
```

## 📈 Key Learning Outcomes
Through this project, I strengthened my ability to:<br>
&nbsp;&nbsp;&nbsp;&nbsp;✔️ Diagnose messy business data<br>
&nbsp;&nbsp;&nbsp;&nbsp;✔️ Apply structured cleaning workflows<br>
&nbsp;&nbsp;&nbsp;&nbsp;✔️ Enforce analytical business rules<br>
&nbsp;&nbsp;&nbsp;&nbsp;✔️ Prepare datasets for downstream analysis<br>
&nbsp;&nbsp;&nbsp;&nbsp;✔️ Build reproducible preprocessing pipelines<br>

## 🎯 Why This Project Matters
Data cleaning is one of the most critical stages of the analytics lifecycle.<br>

This project demonstrates practical skills used in:<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Data Analytics<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Business Intelligence<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Marketing Analytics<br>
&nbsp;&nbsp;&nbsp;&nbsp;• Risk Analytics<br>
&nbsp;&nbsp;&nbsp;&nbsp;• ETL/Data Preparation<br>

It reflects the ability to convert unreliable raw data into trustworthy analytical assets.

## 🧠 Skills Exhibited
This notebook highlights:<br>
&nbsp;&nbsp;&nbsp;&nbsp;✨ Attention to detail<br>
&nbsp;&nbsp;&nbsp;&nbsp;✨ Data validation discipline<br>
&nbsp;&nbsp;&nbsp;&nbsp;✨ Analytical reasoning<br>
&nbsp;&nbsp;&nbsp;&nbsp;✨ Business-focused problem solving<br>
&nbsp;&nbsp;&nbsp;&nbsp;✨ Reproducible workflow design<br>

## 📌 Repository Contents
```
PYTHON_MARKETING_CAMPAIGN_DATA_CLEANING.ipynb
README.md
marketing_campaign_data_messy.csv
```

View notebook with detailed steps here: [MARKETING CAMPAIGN DATA CLEANING](PYTHON_MARKETING_CAMPAIGN_DATA_CLEANING.ipynb)
