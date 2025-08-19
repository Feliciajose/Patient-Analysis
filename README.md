# Patient Data Analysis – Python & Power BI  

## Overview  
This project combines **inpatient** and **outpatient** datasets into a single unified **patient dataset**, performs **data cleaning**, **exploratory data analysis (EDA)**, and generates **visualizations** using Python.  
The cleaned dataset can also be exported for use in **Power BI dashboards**.  

---

## Features  
- Load and merge multiple inpatient & outpatient CSV datasets (2018–2021).  
- Add a `Case_Type` column to differentiate Inpatient vs Outpatient records.  
- Data Cleaning:  
  - Convert date fields to datetime.  
  - Remove duplicates.  
  - Handle missing values in categorical fields.  
- Exploratory Data Analysis (EDA):  
  - Dataset summary, missing values check, and statistical insights.  
- Visualizations:  
  - Patient distribution by case type.  
  - Yearly patient trends by case type.  
  - Specialty-wise patient distribution.  
  - Age profile analysis.  
  - Waitlist comparison scatter plot.  
- Save final cleaned dataset as **Cleaned_Patient_Data.csv**.  

---

## Technologies Used  
- **Python 3.x**  
- **Pandas** – Data loading, cleaning, preprocessing  
- **NumPy** – Numerical operations  
- **Matplotlib & Seaborn** – Data visualization  
- **Power BI** (for dashboard building with cleaned data)  

---

## File Structure  
```
patient_analysis.py          # Main Python script  
Op_WL 2018.csv               # Outpatient dataset 2018  
Op_WL 2019.csv               # Outpatient dataset 2019  
Op_WL 2020.csv               # Outpatient dataset 2020  
Op_WL 2021.csv               # Outpatient dataset 2021  
IN_WL 2018.csv               # Inpatient dataset 2018  
IN_WL 2019.csv               # Inpatient dataset 2019  
IN_WL 2020.csv               # Inpatient dataset 2020  
IN_WL 2021.csv               # Inpatient dataset 2021  
Cleaned_Patient_Data.csv     # Final combined and cleaned dataset (output)  
README.md                    # Project documentation  
```

---

## How to Run  
1. Install dependencies:  
   ```bash
   pip install pandas matplotlib seaborn
   ```  

2. Place all **inpatient** and **outpatient CSV files** in the same folder as `patient_analysis.py`.  

3. Run the script:  
   ```bash
   python patient_analysis.py
   ```  

4. Check the generated charts and the cleaned dataset file:  
   ```
   Cleaned_Patient_Data.csv
   ```  

---

## Example Insights  
- Outpatient vs Inpatient patient count distribution.  
- Yearly trends across 2018–2021.  
- Top 10 specialities by patient count.  
- Age profile distribution by case type.  
- Waitlist performance comparison.  

---

## Future Enhancements  
- Automate export to Power BI via APIs.  
- Add advanced statistical analysis (correlation, regression).  
- Include anomaly detection for patient waitlists.  
Internship at **QSpiders, Panimalar Engineering College (Chennai)**  
Duration: **July 1, 2025 – August 1, 2025**  
