# 🇬🇧 UK Immigration Trends: A Visual Analytics Project

This project explores socio-economic trends in England and Wales, focusing on immigration-related patterns using UK Census data (2011 and 2021). It combines data cleaning, exploratory analysis, dimensionality reduction, and interactive dashboards to support visual storytelling and decision-making.

---

## 📌 Objectives

- Identify migration and employment trends over time
- Apply dimensionality reduction (PCA & t-SNE) for cluster visualization
- Create interactive Tableau dashboards for geographic and temporal insights

---

```markdown
## 📁 Project Structure

UK_Immigration_Trends/
├── Data/
│   ├── raw/                          # Original census datasets
│   │   ├── 2011/
│   │   └── 2021/
│   └── processed/
│       ├── cleaned/                 # Cleaned data ready for analysis
│       └── migrant_activity_PCA_tSNE.csv  # Precomputed PCA+t-SNE results
├── UK_Immigration_Trends_Analytics.ipynb  # Full Python analysis workflow
├── UK_Immigration_Trends_Analytics.pdf    # Final academic report
├── UK_Immigration_Trends_Analytics.twbx   # Tableau workbook (interactive dashboard)
├── readme.md
└── project_structure.txt
```

---

## 📊 Tableau Dashboard

> The interactive dashboard visualizes employment and immigration metrics across geographies and time periods.

🔗 **https://public.tableau.com/app/profile/amrita.moyade/viz/UK_Immigration_Trends_Analytics/Story**  

---

## 🧪 Methods & Tools

- **Dimensionality Reduction**: PCA and t-SNE (via scikit-learn)
- **Visualization**: Tableau for dashboarding, matplotlib for Python plots
- **Data Processing**: pandas, numpy
- **Notebook Platform**: Jupyter

---

## 🧠 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/amritamoyade6/Projects.git
   cd Projects/UK_Immigration_Trends
   ```

2.	Open the notebook:
	•	Launch UK_Immigration_Trends_Analytics.ipynb to explore the analysis workflow.

3.	Use the processed file:
	•	Data/processed/migrant_activity_PCA_tSNE.csv contains precomputed embeddings for faster visual analysis.

4.	View the dashboard:
	•	Open UK_Immigration_Trends_Analytics.twbx in Tableau Desktop or download the dashboard from Tableau Public-

https://public.tableau.com/app/profile/amrita.moyade/viz/UK_Immigration_Trends_Analytics/Story.

📚 References
	•	UK Census 2011 and 2021 (ONS)
	•	sklearn PCA and t-SNE documentation
	•	Munzner, T. (2014). Visualization Analysis and Design

📌 Author

Amrita Moyade