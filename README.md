## **📌 Project Overview**  
This project performs an **Exploratory Data Analysis (EDA)** on the **Haberman’s Survival Dataset**, analyzing factors influencing breast cancer patient survival post-surgery.  

## **📊 Dataset Description**  
- **Features:**  
  - `Age` (Patient’s age at operation)  
  - `Year` (Year of operation, 1958-1969)  
  - `Nodes` (Number of lymph nodes detected)  
  - `Survival` (1 = Survived ≥5 years, 2 = Died within 5 years)  

## **🔍 Key Analyses**  
### **1️⃣ Univariate Analysis**  
- **Age Distribution:** Median age = **52**, most patients between **40-65**.  
- **Survival Rate:** **73%** survived beyond 5 years.  

### **2️⃣ Bivariate Analysis**  
- **Nodes vs. Survival:** Patients with **≤4 nodes** had better survival rates.  

### **3️⃣ Multivariate Analysis**  
- **Age + Nodes Impact:** Younger patients (<52) with fewer nodes had higher survival rates.  

## **📈 Visualizations**  
- **Histograms, ECDFs, Box Plots, Scatter Plots**  
- **Pair Plots** for feature correlation  

## **💡 Insights & Conclusions**  
- **Early detection** (fewer lymph nodes) improves survival.  
- **Dataset imbalance** (73% survival) may require resampling for ML models.  

## **🛠 Tools Used**  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Statistical Analysis (PDF, CDF, ECDF)  
