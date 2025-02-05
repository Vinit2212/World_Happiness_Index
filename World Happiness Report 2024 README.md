# World Happiness Report 2024: Data Analysis

This project provides a comprehensive analysis of the **World Happiness Report 2024**, focusing on global happiness trends, key drivers, and regression modeling for predictive insights.

## Data Overview
The dataset includes the following columns:
- **country_name:** Name of the country.
- **continent:** The continent the country belongs to.
- **happiness_score:** Overall happiness score (0-10 scale).
- Additional columns for key indicators like GDP per capita, Social Support, and Healthy Life Expectancy.

### Key Highlights:
- Europe demonstrates the highest median happiness scores globally.
- Africa lags significantly, with systemic challenges pulling most countries below the global average.
- Afghanistan emerges as the least happy country globally with a score of 1.721.

## Regression Analysis
The regression model examines six independent variables to assess their impact on happiness scores:
- **GDP per Capita:** R² = 0.59
- **Social Support:** R² = 0.66
- **Healthy Life Expectancy:** R² = 0.57
- Other factors like **Generosity** (R² = 0.017) and **Corruption Perception** (R² = 0.20) exhibit weaker correlations.

Model performance metrics:
- **R² = 0.77**
- **MAE = 0.40**
- **RMSE = 0.50**

## Visualizations
This project includes:
- Box-and-whisker plots for happiness score distributions by continent.
- Scatterplots for key factors affecting happiness scores.
- Heatmaps highlighting the top 10 happiest countries.

## Getting Started
To run this project:
1. Clone the repository.
2. Install the required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, and `sklearn`.
3. Run the Jupyter Notebook or Python script.

```bash
pip install -r requirements.txt
