---

# Exploratory Data Analysis (EDA) - Titanic Dataset

---

### Objective: Extract insights from the Titanic dataset using visual and statistical exploration techniques.

### Tools Used: Python (Pandas, Matplotlib, Seaborn), Jupyter Notebook

### Dataset: [Titanic Dataset from Kaggle](https://www.kaggle.com/c/titanic/data?select=train.csv)

---

## 🛠 Deliverables
The following EDA techniques were implemented for comprehensive data analysis:

1. **Data Loading & Overview** – Initial dataset exploration using `.info()`, `.describe()`, `.shape`
2. **Missing Value Analysis** – Identifying missing data patterns
3. **Survival Rate Analysis** – Overall survival statistics and distribution
4. **Categorical Analysis** – Gender, passenger class, and embarkation port analysis
5. **Numerical Analysis** – Age, fare, and family size distributions
6. **Correlation Analysis** – Using `sns.heatmap()` for feature correlations
7. **Pairplot Visualization** – Using `sns.pairplot()` for multivariate analysis
8. **Multi-dimensional Analysis** – Cross-tabulation and advanced visualizations
9. **Statistical Summaries** – Key insights and pattern identification
10. **Comprehensive Report** – Complete findings and observations documentation

---

## 📂 Project Structure

```
Exploratory-Data-Analysis-Demo/
├── titanic_eda.ipynb                  # Jupyter 
├── requirements.txt                   # Python pip requirements file
├── data/
│   ├── titanic.csv                    # Original dataset
│   └── titanic_with_features.csv      # Enhanced dataset with new features
├── visualizations/
│   ├── survival_analysis.png          # Survival distribution plots (bar plot, pie plot)
│   ├── gender_analysis.png            # Gender vs Survival rates (count plot, bar plot)
│   ├── passenger_class_analysis.png   # Passenger Class Survival rates (count plot, bar plot)
│   ├── embarkation_port_analysis.png  # Survival Rate by Embarkation Port (count plot, bar plot)
│   ├── age_analysis.png               # Age vs Survival (frequency distribution, box plots)
│   ├── fare_analysis.png              # Fare vs Survival (frequency distribution, box plots)
│   ├── family_size_analysis.png       # Family size impact on survival
│   ├── correlation_heatmap_matrix.png # Feature correlation matrix 
│   ├── pair_plot_visualization.png    # Pairplot of Key Variables
│   └── multi-dimensional_analysis.png # Multi-dimensional analysis
├── reports/
│   ├── EDA_Output.html              # Notebook Run Output in HTML
│   ├── EDA_Report.pdf               # Comprehensive PDF report
│   └── key_insights.md              # Summary of findings
└── README.md                        # Project documentation
```

## 🚀 How to Reproduce
### Prerequisites - Python, IDE or Jupyter Notebook
### Steps:
Note : Some steps and commands may vary as per OS installed
1. Download the dataset from Kaggle and save as `data/titanic.csv`
2. Copy `requirements.txt` and `titanic_eda.ipynb` to working directory
3. Open terminal inside working directory and run the following commands:
    - python -m venv .titanic_env
    - Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
    - .\\.titanic_env\Scripts\Activate.ps1
    - python -m pip install --upgrade pip
    - python -m pip install -r .\requirements.txt
4. Open suitable IDE like VSCode or Jupyter Notebook in working directory
5. Open `titanic_eda.ipynb`
3. **Run all cells** in sequential order
4. **Generate visualizations** – All plots will be displayed inline
5. **Export results:**
   - Save notebook as PDF or HTML
   - Export enhanced dataset: `titanic_with_features.csv`

---

## 📈 Visualization Highlights

### Primary Analysis Charts
- **Survival Distribution:** Count plots and pie charts
- **Gender Analysis:** Survival rates by gender with statistical significance
- **Class Analysis:** Passenger class impact on survival probability
- **Age Distribution:** Histograms and box plots with survival overlay
- **Correlation Matrix:** Heatmap showing feature relationships
- **Pairplot:** Multi-dimensional variable relationships

### Advanced Visualizations
- **Multi-dimensional Heatmaps:** Gender × Class × Survival interactions
- **Fare Group Analysis:** Survival by economic status
- **Family Size Impact:** Optimal family size for survival
- **Age Group Stratification:** Survival patterns across age categories

---
