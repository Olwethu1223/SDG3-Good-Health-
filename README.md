# 🧠 SDG3-Good-Health: Healthcare Data Analysis Using Machine Learning

## 📌 Project Overview

This project addresses **Sustainable Development Goal 3: Good Health and Well-being** by using **machine learning** to analyze healthcare data. Our goal is to identify meaningful patterns in patient care, medical conditions, and healthcare costs to improve **resource allocation** and **patient care strategies** in healthcare systems.

---

## 💡 Problem Statement

Access to quality healthcare remains a global challenge. Hospitals often face constraints in resources, and decision-makers lack data-driven tools to segment patients effectively. 

We use **K-Means Clustering** to group patients based on:
- **Age**
- **Billing Amount**
- **Medical Condition**

This allows healthcare providers to better understand patient needs and allocate resources more effectively.

---

## 🤖 Machine Learning Solution

### ✳️ Model Used: K-Means Clustering (Unsupervised Learning)

**Libraries:**  
`scikit-learn`, `pandas`, `matplotlib`, `seaborn`

**Steps:**
1. **Preprocessing**  
   - Standard scaling of numerical features  
   - Label encoding of categorical features  
2. **Clustering Configuration**
   - K = 4 clusters  
   - `random_state=42` for reproducibility  
3. **Evaluation**
   - Scatter plots to visualize cluster distribution  
   - Cluster interpretation based on age, cost, and conditions  

---

## 📊 Results & Key Insights

- 4 distinct patient clusters were identified.  
- Age and billing amount showed strong clustering patterns.  
- Some clusters had significantly higher healthcare costs.  
- Medical conditions are not uniformly distributed across age groups.  

---

## ⚖️ Ethical Considerations

- 🔐 **Data Privacy:** All patient data must be anonymized and securely handled.  
- ⚖️ **Fairness:** Clustering must not cause discrimination or unequal healthcare access.  
- 👨‍⚕️ **Human Oversight:** AI supports doctors but doesn't replace their decisions.  
- 🔁 **Ongoing Monitoring:** Regular validation of the model is necessary to reduce bias.  

---

## 🧭 Recommendations

- Use clusters to optimize **preventive care** and **resource allocation**.  
- Monitor healthcare cost trends for high-risk patient groups.  
- Update the model regularly with new data to improve predictions.  
- Ensure **transparency** in decision-making processes.  

---

## 🖥️ Demo & Notebook

Check out the **Jupyter Notebook** for full code implementation:  
👉 [Demo Notebook](./healthcare-clustering.ipynb)

**Includes:**
- Dataset preprocessing  
- K-Means implementation  
- Cluster visualization (scatter plot)  
- Interpretation of results  

---

## 📌 Project Structure

These are the files in the repo:

```
Good Health.ipynb           # Jupyter notebook with full analysis
Project Article             # Written article explaining the project
README.md                   # Project documentation
Report.txt                  # Summary of project findings
kmeans_cluster.png          # Visual of clustering result
unsupervised.py             # Script of ML model implementation
```

---

## 👥 Group 13 – Contributors

- Amahle Mathebula  
- Victor Muthomi  
- Geofrey Killeta  
- Brian Sangura  
- Achieng Verra  

---

## 📎 SDG Alignment

This project supports the UN's **Sustainable Development Goal 3**:  
> _"Ensure healthy lives and promote well-being for all at all ages."_  

By enabling data-driven patient insights, this solution contributes to **universal health coverage**, **cost reduction**, and **targeted care**.

---

## 🛠️ Requirements

```bash
python >= 3.8  
pandas  
scikit-learn  
matplotlib  
seaborn  
```

