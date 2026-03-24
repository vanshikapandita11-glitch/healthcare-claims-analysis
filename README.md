# 🏥 Healthcare Claims & Provider Payment Analysis

## 🔍 Project Overview

This project analyzes Medicare provider billing data to identify cost patterns, high-spending specialties, geographic variations, and potential outliers in reimbursement behavior.

The analysis focuses on understanding how healthcare costs are distributed across providers, specialties, and regions using real-world CMS data.

---

## ⚙️ Tech Stack

* **Python (Pandas, Matplotlib)** – Data cleaning, transformation, and exploratory data analysis
* **SQL (conceptual)** – Data structuring and aggregation logic
* **Tableau** *(optional)* – Visualization of key insights

---

## 📁 Project Structure

* `healthcare_analysis.ipynb` – Data cleaning, processing, and analysis
* `healthcare_cleaned.csv` – Processed dataset used for analysis
* `dashboard.png` *(optional)* – Visualization of key findings

---

## 📊 Key Analyses Performed

* Provider-level payment analysis
* Specialty-wise Medicare spending
* State-wise cost distribution
* Outlier detection using percentile thresholds
* Service utilization vs beneficiary analysis

---

## 💡 Key Insights

* Medicare payment distribution is highly skewed, with mean (~86) significantly higher than median (~52), indicating concentration among high-value providers
* Top 1% providers exhibit payments up to ~20× higher than median levels, suggesting extreme outliers and potential overbilling patterns
* Specialties such as **Ambulatory Surgical Centers and surgical domains** contribute the highest Medicare reimbursements
* Significant geographic variation exists, with states like **California and Florida** leading total spending
* Service counts exceed beneficiary counts, indicating repeated procedures and cost driven by service intensity rather than patient volume

---

## 📈 Visualizations

The analysis includes visualizations for:

* Top specialties by Medicare payments
* State-wise spending distribution
* High-cost provider segments

---

## 🚀 How to Run

1. Clone the repository
2. Open `healthcare_analysis.ipynb`
3. Run all cells to reproduce analysis

---

## 📌 Note

This dataset is a resampled version of CMS Medicare data. It represents aggregated provider-level information rather than raw transactional claims.

---

## 👤 Author

Developed as part of a data analytics portfolio project.
