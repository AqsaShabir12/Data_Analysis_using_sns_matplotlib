# Iris Dataset Exploratory Data Analysis (EDA)

This repository contains a simple yet insightful exploratory data analysis (EDA) of the classic **Iris flower dataset**, using Python libraries like Pandas, NumPy, Matplotlib, and Seaborn.

The notebook/script demonstrates **univariate, bivariate, and multivariate** visualizations to understand the distribution and relationships between features for different Iris species.

---

## File Overview

- `iris_eda.py` or `iris_eda.ipynb` – Python script or Jupyter Notebook containing the full EDA code.

---

## Dataset

- **Source:** [Iris Dataset from UCI (hosted on GitHub)](https://raw.githubusercontent.com/uiuc-cse/data-fa14/gh-pages/data/iris.csv)
- **Features:**  
  - Sepal length  
  - Sepal width  
  - Petal length  
  - Petal width  
  - Species (setosa, versicolor, virginica)

---

##  Exploratory Techniques Used

### Univariate Analysis
- Distribution of `petal_length` using dot plots for each species

### Bivariate Analysis
- Scatter plots of `sepal_length` vs `sepal_width` using `FacetGrid` per species
- Comparison across species for two variables

### Multivariate Analysis
- `pairplot` to visualize pairwise relationships across all features with color coding by species

---

## Libraries Required

Install the necessary packages using pip:

```bash
pip install pandas numpy matplotlib seaborn
```

## How to Run
Run the script or Jupyter notebook in any Python environment with the required libraries:
```bash
python main.py
# OR
jupyter main.ipynb
```

## Visual Outputs
- Univariate dot plots of petal length by species
- Species-wise scatter plots (2D bivariate)
- Complete feature correlation through pairwise multivariate analysis