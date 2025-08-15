# 🩺 Chronic Disease Data Analysis

## 📌 Project Overview  
This project analyzes **chronic disease trends** across the United States using the **U.S. Chronic Disease Indicators (CDI)** dataset from the CDC.  
The primary objective is to **identify regional and demographic differences** in the prevalence of chronic diseases such as **diabetes, cardiovascular disease, and asthma**.  

By leveraging statistical analysis, geospatial mapping, and an interactive dashboard, the study aims to support **targeted public health interventions** and improve health policy decision-making.

---

## 📂 Data Source & Description  
- **Source:** [CDC – U.S. Chronic Disease Indicators](https://data.cdc.gov/Chronic-Disease-Indicators/U-S-Chronic-Disease-Indicators/hksd-2xuw/about_data)  
- **Data Type:** Structured, CSV format  
- **Size:** `309,216` rows × `34` columns  

---

## 🛠️ Preprocessing Steps  

### 1️⃣ Data Cleaning  
- Dropped columns containing no values at all.  
- Filled missing **numeric values** with the **median**.  
- Filled missing **categorical values** with `"Unknown"`.  

### 2️⃣ Data Aggregation  
- Removed **national-level** entries to focus on **state-specific** trends.  
- Grouped data by **Year**, **State**, and **Disease Type** for detailed summaries.  

---

## 📊 Analysis Performed  

### 1. **Trend Analysis**  
- Examined **mortality rate patterns** for **diabetes** and **asthma** over time.  
- Used **Matplotlib** line plots to visualize year-by-year changes.  

### 2. **Comparative Analysis**  
- Compared **cardiovascular disease prevalence by gender** across states.  
- Used **bar plots** for state-level comparisons.  

### 3. **Geospatial Analysis**  
- Mapped **alcohol-related mortality rates** across the U.S.  
- Used **Cartopy** for state-wise choropleth maps.  

---

## 📚 Libraries Used  
- **Pandas** – Data loading, cleaning, aggregation, manipulation  
- **Matplotlib** – Static visualizations (line plots, bar charts)  
- **Cartopy** – Geospatial mapping  
- **Dash** – Interactive dashboard development  
- **IPython.display** – Rendering styled DataFrames and rich HTML content  

---

## 📈 Interactive Dashboard  
Built using **Dash** to allow **dynamic exploration** of chronic disease trends.  

**Features:**  
- **Drop-down selector** for choosing states.  
- **Interactive line charts** updating in real time.  
- Focused on **Binge Drinking Prevalence Among Adults** as a case study.  

💡 This dashboard enables **stakeholders and policymakers** to quickly explore and compare health patterns.  

---

## ✅ Key Findings & Recommendations  
- Significant **gender differences** exist in cardiovascular disease prevalence.  
- Certain states show **persistently high mortality rates** for specific diseases.  
- **Recommendations:**  
  - Implement **gender-specific health policies**.  
  - Target **high-mortality areas** with tailored public health initiatives.  
  - Increase **outreach to high-risk groups**.  
  - Monitor chronic disease patterns **continuously** to prevent future health crises.  

---

## 📌 Project Structure  

```
.
├── CDI Analysis-4.ipynb    # Main Jupyter Notebook containing the full analysis
└── README.md               # Project documentation
```

---

## 🚀 How to Run the Project  

1. **Clone the repository**  
   ```bash
   git clone <repo-link>
   cd chronic-disease-data-analysis
   ```

2. **Install dependencies**  
   ```bash
   pip install pandas matplotlib cartopy dash
   ```

3. **Run the Jupyter Notebook**  
   ```bash
   jupyter notebook "CDI Analysis-4.ipynb"
   ```

4. **Launch the Dashboard**  
   Inside the notebook, run the Dash app cell, then open the displayed **localhost** link in your browser.  

---

## 📬 Contact  
For questions or collaboration:  
**Name:** Yaswanth Lalpet Vari
**Email:** _[lvyaswanth141@gmail.com]_  
