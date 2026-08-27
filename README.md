# 🚗 Automobile Price Analysis & Exploratory Data Analysis with Python

## 📊 Project Overview

This project performs exploratory data analysis on an automobile dataset to investigate relationships between vehicle specifications and automobile prices.

Using Python, the analysis explores individual feature patterns, descriptive statistics, categorical distributions, grouped averages, correlations, and statistical significance tests to identify variables associated with vehicle price.

The project was completed as a guided project through Cognitive Class / IBM Skills Network.

---

## 🎯 Objectives

- Explore the structure and characteristics of the automobile dataset
- Analyze individual feature patterns using visualization
- Examine relationships between vehicle attributes and price
- Perform descriptive statistical analysis
- Compare average prices across vehicle categories
- Measure linear relationships using Pearson correlation
- Apply ANOVA to test differences in automobile prices across drive-wheel categories

---

## 🗂️ Dataset

The analysis uses the `automobileEDA.csv` dataset.

The dataset contains automobile specifications and pricing information, including variables such as:

- Make
- Body style
- Drive wheels
- Engine size
- Horsepower
- Curb weight
- Wheel base
- Length
- Width
- City MPG
- Highway MPG
- Price

The dataset contains 29 columns after preprocessing and feature preparation.

---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## 🔍 Analysis Performed

### 1. Individual Feature Pattern Analysis

Visualizations were used to investigate relationships between numerical variables and automobile price.

Regression plots were used to examine relationships such as:

- Engine size vs. price
  
  <img width="587" height="429" alt="engine_size_vs_price png" src="https://github.com/user-attachments/assets/1c17c8be-8c52-43f5-823b-5f01c65e4475" />
  
The analysis showed a strong positive relationship between engine size and price.

- Highway MPG vs. price
  
  <img width="598" height="428" alt="highway_mpg_vs_price png" src="https://github.com/user-attachments/assets/418e0d89-f3f6-45b9-ac66-a2319d3880f4" />
  
Highway MPG showed a negative relationship with price.

- Peak RPM vs. price
- Stroke vs. price

Categorical variables were also analyzed using box plots, including:

- Body style vs. price
  
  <img width="588" height="430" alt="body_style_vs_price png" src="https://github.com/user-attachments/assets/9d41a8ca-82c8-4354-9a7f-7a6fb09c229b" />

- Engine location vs. price
  
- Drive wheels vs. price
  
  <img width="589" height="431" alt="drive_wheels_vs_price png" src="https://github.com/user-attachments/assets/66c950b6-d561-4775-8953-6f42ff6f59d0" />

  

---

### 2. Descriptive Statistical Analysis

Descriptive statistics were generated for numerical variables using Pandas.

Both numerical and categorical variables were examined to understand:

- Central tendency
- Distribution
- Variation
- Category frequency

---

### 3. Value Counts

Categorical frequency analysis was performed for variables including:

- Drive wheels
- Engine location

This helped identify the distribution of vehicles across different categories.

---

### 4. Grouping & Pivot Tables

Automobile prices were grouped by drive-wheel and body-style categories.

Grouped averages and pivot tables were created to compare pricing patterns across combinations of categorical variables.

Heatmaps were then used to visualize the grouped results.

<img width="478" height="468" alt="price_heatmap png" src="https://github.com/user-attachments/assets/97407a96-cccb-4742-8cae-24bd235dc815" />


---

### 5. Correlation & Statistical Significance

Pearson correlation analysis was performed to measure the strength and direction of relationships between automobile attributes and price.

Selected results included:

| Variable | Correlation with Price |
|---|---:|
| Engine Size | 0.872 |
| Curb Weight | 0.834 |
| Width | 0.751 |
| Length | 0.691 |
| Wheel Base | 0.585 |
| Highway MPG | -0.705 |
| City MPG | -0.687 |

These results indicate that several vehicle size and engine-related characteristics have strong positive relationships with price, while fuel-efficiency measures show negative relationships.

---

### 6. Analysis of Variance (ANOVA)

ANOVA was used to examine whether automobile prices differed significantly between drive-wheel categories.

The analysis compared:

- FWD vs. RWD vs. 4WD
- FWD vs. RWD
- 4WD vs. RWD
- 4WD vs. FWD

The statistical tests produced different levels of significance across the drive-wheel comparisons.

---

## 📈 Key Insights

The analysis revealed several notable patterns:

- Engine size showed a strong positive relationship with automobile price.
- Curb weight was also strongly positively associated with price.
- Vehicle width and length demonstrated positive relationships with price.
- City MPG and highway MPG showed negative relationships with price.
- Automobile prices varied considerably across drive-wheel and body-style categories.
- Statistical testing provided evidence that some drive-wheel groups differ significantly in their average prices.

---

## 📚 Skills Demonstrated

- Exploratory Data Analysis
- Data Visualization
- Statistical Analysis
- Correlation Analysis
- Hypothesis Testing
- ANOVA
- GroupBy Operations
- Pivot Tables
- Data Interpretation
- Python for Data Analysis

---

## 📁 Project Structure

```text
automobile-price-eda-python/
│
├── data/
│   └── automobileEDA.csv
│
├── notebooks/
│   └── Exploratory_Data_Analysis_with_Python.ipynb
│
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

### Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/automobile-price-eda-python.git
```

### Navigate to the project:

```bash
cd automobile-price-eda-python
```

### Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

### Launch Jupyter Notebook:

```bash
jupyter notebook
```

### Open:

```text
notebooks/Exploratory_Data_Analysis_with_Python.ipynb
```

## 🎓 Certification

### Completed the guided project:

Exploratory Data Analysis with Python

### Provider: Cognitive Class / IBM Skills Network

### Course Code: GPXX0IDQEN

## 👤 Author

**Muhammad**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

LinkedIn • GitHub
