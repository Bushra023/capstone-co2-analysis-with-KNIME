# Analyzing the Impact of Development Indicators on CO₂ Emissions

This project explores how various development indicators influence CO₂ emissions per capita across countries using data science and low-code tools. The analysis combines Python-based data cleaning and exploratory analysis with machine learning modeling in KNIME.

---

## Objective

To identify relationships between development indicators and CO₂ emissions per capita, and build a predictive model using low-code tools.

---

## Project Structure
capstone-co2-analysis/
├── data/ 
├── notebook/ # Jupyter Notebook for data cleaning and EDA
│ └── co2_analysis.ipynb
├── knime_project/ # KNIME workflow file
│ └── co2_model.knwf
├── presentation/ # Final presentation
│ └── capstone_slides.pdf
├── requirements.txt # Python packages used
└── README.md # This file

## Datasets

1. **World Bank Development Indicators (2022)**  
   - Source: [World Bank DataBank](https://databank.worldbank.org/source/world-development-indicators)
   
2. **CO₂ Emissions Dataset**  
   - Source: [OWID GitHub - CO₂ Emissions](https://github.com/owid/co2-data)

---

## Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- KNIME Analytics Platform (Low-code modeling)
- Git & GitHub (Version Control)

---

## Key Steps

- Data cleaning and preparation in Jupyter:
  - Removed columns with excessive nulls
  - Filled missing values with median
  - Merged datasets by country code
- Exploratory Data Analysis (EDA)
  - Distribution plots, correlation matrix, PCA
- Clustering countries based on indicators
- Exported cleaned data to KNIME for modeling
- Built and evaluated a **Linear Regression model** in KNIME

---

## Model Results

- **Algorithm Used:** Linear Regression (KNIME)
- **Target Variable:** CO₂ Emissions per Capita
- **Features:** Development indicators (GDP per capita, Internet usage, School enrollment, etc.)
- **R² Score:** **0.476**
  - Indicates moderate correlation between selected indicators and CO₂ emissions
  - Suggests potential for improved modeling with more features or advanced algorithms

---

## Learnings & Insights

- Low-code platforms like KNIME enable quick modeling without programming
- Development indicators partially explain CO₂ emissions, but other environmental and policy-related factors may also play a role
- Combining traditional code-based analysis with low-code tools offers flexibility and accessibility

---

## Requirements

Install required Python libraries using:
## Presentation

Final project presentation included in `/presentation/capstone_slides.pdf`.

---

## About the Author

**Bushra Jabeen**  
Data Science Professional with a background in Physiotherapy & Public Health, passionate about using data for sustainability and impact.  


