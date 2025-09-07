# week2_project_heatwave_risk_in_india
This is an AICTE week2 internship
# 🌡️ Heatwave Risk Analysis – Week 2 Project

This repository contains the **Week 2 Project** for the AICTE Internship (*Climate Risk & Disaster Management*).  
It builds upon **Week 1 (Project Selection & Dataset Creation)** by adding:

- ✅ **Exploratory Data Analysis (EDA)**
- ✅ **Data Transformation**
- ✅ **Feature Selection**
- ✅ **Processed Dataset Export**



 📂 Project Structure

```
├── HEATWAVE_RISK_WEEK2.ipynb   # Jupyter Notebook for Week 2 Project
├── heatwave_data.csv           # Input dataset (raw data)
├── heatwave_processed.csv      # Output dataset (cleaned & transformed)
├── README.md                   # Project documentation
```

---

 🚀 How to Run

1. Clone this repository or download the files.  
2. Open **`HEATWAVE_RISK_WEEK2.ipynb`** in Jupyter Notebook / JupyterLab.  
3. Run all cells step by step.  
4. The notebook will:  
   - Perform **EDA** (summary, plots, outliers).  
   - Apply **data cleaning, encoding, and scaling**.  
   - Conduct **feature selection (correlation, SelectKBest, RFE)**.  
   - Save a new dataset as **`heatwave_processed.csv`**.  

---

 📊 Dataset Info

- **heatwave_data.csv** → Synthetic dataset with columns:  
  - `Temperature` (°C)  
  - `Humidity` (%)  
  - `WindSpeed` (km/h)  
  - `MortalityRate` (per 1000 people)  
  - `Region` (categorical: North, South, East, West)  

- **heatwave_processed.csv** → Cleaned dataset after transformation and feature selection.  

---

 🎯 Week 2 Objectives Achieved

- Performed **EDA** with correlation heatmap, histograms, and outlier detection.  
- Transformed dataset using **missing value imputation, encoding, and scaling**.  
- Selected best features using **correlation analysis, SelectKBest, and RFE**.  
- Saved **final dataset** for Week 3 modeling.  

---

 🔮 Next Steps (Week 3 Preview)

- Build **ML models** (classification/regression) using the processed dataset.  
- Evaluate model performance using metrics.  
- Deploy insights for **heatwave risk management**.  



👨‍💻 *Developed as part of AICTE Internship Cycle 3 – Climate Risk & Disaster Management (S4F)*
