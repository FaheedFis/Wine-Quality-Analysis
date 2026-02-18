# 🍷 Wine Quality Analysis

This project explores the chemical factors influencing wine quality using data-driven techniques and visualizations. 
The focus is on how **alcohol content** and **volatile acidity** affect quality ratings, and a comparison between **red and white wines**.

##  Datasets Overview

- **Source**: UCI Machine Learning Repository  
- **Red Wines**: 1,599 samples  
- **White Wines**: 4,898 samples  
- **Features**:
  - Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides
  - Free and total sulfur dioxide, density, pH, sulphates, alcohol
  - **Target**: Quality score (0–10)

## Key Questions

- What is the relationship between **alcohol** and **volatile acidity** with wine **quality**?
- Do **red or white wines** tend to have higher quality ratings?
- Which chemical properties are **most predictive** of high-quality wine?

## ✅ Main Findings

- **Alcohol** is positively correlated with quality.
- **Volatile acidity** has a negative correlation — high levels lower perceived quality.
- **White wines** slightly outperform red wines in average quality scores.
- Some variables (like density) may show **spurious correlations**.

##  Visualizations

The notebook includes:
- Scatter plots: Alcohol vs. Volatile Acidity (by wine type)
- Histograms of quality scores
- Bar chart of average quality
- Grouped summaries by wine type

##  How to Run

1. Clone this repository or download the files
2. Open `Wine.ipynb` in Jupyter Notebook or Google Colab
3. Ensure `winequality-red.csv` and `winequality-white.csv` are in the same folder
4. Run cells to explore, visualize, and analyze

##  Skills & Concepts

- Data exploration with `datascience`, `numpy`, `matplotlib`
- Data storytelling with charts and narrative
- Classification based on chemical features
- Spurious vs. causal interpretation

##  References

- [Wine Quality Dataset - UCI Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality)

##  License

This project is for educational use. Dataset under UCI license.
