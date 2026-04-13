# 🏠 Ontario Housing Market Analysis

A data-driven exploration of housing prices across Ontario, Canada — examining regional trends, affordability patterns, and what drives property values beyond the Greater Toronto Area.

---

## About Me

I hold a Bachelor's degree in Civil Engineering and two Post-Graduate Diplomas — one in Construction Project Management and one in Supply Chain Management. My career so far spans two very different worlds: three years managing retail stores and gas stations, and three years working in Ontario's construction industry.

That combination taught me how to read both spreadsheets and blueprints. On job sites, I watched housing costs shift in real time. In retail and fuel operations, I learned how to track inventory, spot trends, and make decisions based on numbers — not guesses. Both experiences pointed me toward the same realization: data tells better stories than assumptions.

This project is my capstone as I transition into data analytics. It brings together everything I have learned — from managing real-world operations to the analytical skills I developed through the Google Data Analytics Professional Certificate and self-directed Python learning. I built this project to show that my background is not a detour — it is a foundation.

This project analyzes the housing market in Ontario using data from the top 45 cities.
---

## Dataset

<!-- UPDATE: Replace with your actual dataset source and link -->

- **Source:** [Ontario housing dataset — e.g., Kaggle / CREA / Ontario Open Data]
- **Format:** CSV
- **Records:** <!-- UPDATE: e.g., ~X,XXX rows -->
- **Coverage:** Regions across Ontario (not limited to Toronto/GTA)
- **Key fields:** location, property type, price, year, bedrooms, square footage, and more

---

## Project Goals

1. Understand how housing prices vary across Ontario's diverse regions
2. Identify the factors that have the strongest relationship with price
3. Assess affordability trends over time
4. Present findings in a clean, visual format that anyone can follow

---

## Key Questions

- How do housing prices differ between Ontario regions?
- Which property features correlate most strongly with price?
- Has housing become less affordable over time, and where is it worst?
- Are there regional patterns that simple averages would miss?

---

## Methodology

| Phase | Description |
|-------|-------------|
| **Ask** | Defined questions around regional pricing, affordability, and price drivers |
| **Prepare** | Sourced and reviewed the dataset for completeness and relevance |
| **Process** | Cleaned, transformed, and validated the data using Python and Pandas |
| **Analyze** | Explored distributions, trends, correlations, and regional comparisons |
| **Share** | Built clear visualizations using Matplotlib and Seaborn |
| **Act** | Summarized findings and actionable insights |

---

## Data Cleaning

Steps taken to prepare the dataset for analysis:

- Removed duplicate records
- Handled missing values (dropped or imputed based on column context)
- Standardized region and property-type names for consistency
- Converted data types (dates, numeric fields) where needed
- Filtered out extreme outliers that would distort visualizations
- Created new calculated columns (e.g., price per square foot, affordability ratios)

<!-- UPDATE: Add or remove bullet points to match your actual cleaning steps -->

---

## Visualizations

All charts follow a clean, minimal style — no clutter, clear labels, readable scales.

### 1. Average Housing Price by Region
> Bar chart comparing mean prices across Ontario regions. Shows clear variation — some areas are significantly more expensive than others, even outside the GTA.

### 2. Price Trend Over Time
> Line chart tracking how median prices have changed year over year. Highlights the acceleration in recent years.

### 3. Price Distribution by Property Type
> Box plot showing how prices spread within each property type. Useful for spotting where the most variability lives.

### 4. Correlation Heatmap
> Heatmap of numeric features vs. price. Quickly identifies which variables have the strongest linear relationship with housing cost.

### 5. Affordability Index Over Time
> Line or area chart showing how affordability has shifted. Connects price growth to income benchmarks where available.

<!-- UPDATE: Add, remove, or rename these to match your actual charts -->

---

## Key Insights

<!-- UPDATE: Replace these with your actual findings and numbers -->

- **Regional gaps are significant.** Prices in some Ontario regions are several times higher than others, even after removing GTA data.
- **Property size matters — but not equally everywhere.** Square footage correlates with price, but the strength of that relationship varies by region.
- **Recent years show acceleration.** Price growth has not been steady — the sharpest increases are concentrated in the most recent years of the dataset.
- **Detached homes dominate the high end.** But condos and townhouses show tighter, more predictable pricing.

---

## Affordability Analysis

<!-- UPDATE: Plug in your specific affordability findings -->

- Compared median housing prices against regional or provincial income benchmarks
- Calculated price-to-income ratios to measure affordability across regions
- Found that affordability has worsened in most regions over time, with some areas crossing into critical territory
- Smaller cities that were once considered affordable are trending toward GTA-level ratios

---

## Correlation Findings

<!-- UPDATE: Add your actual correlation values -->

| Feature | Correlation with Price |
|---------|----------------------|
| Square footage | <!-- e.g., 0.72 --> |
| Number of bedrooms | <!-- e.g., 0.58 --> |
| Year built | <!-- e.g., 0.15 --> |
| Lot size | <!-- e.g., 0.45 --> |

- Strongest positive correlator: <!-- UPDATE -->
- Weakest or negligible: <!-- UPDATE -->
- No single feature explains price alone — location and property type add important context

---

## Summary

This project shows that Ontario's housing market is not one story — it is many. Prices, affordability, and the features that drive value all shift depending on where you look. The data confirms what many suspect: housing is becoming less affordable across the province, not just in Toronto.

As someone who has built structures in this market, translating that experience into data analysis felt natural. This project represents my first full end-to-end analysis — from raw data to clean visuals to actionable findings.

---

## How to Run This Notebook

### Requirements

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Setup

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/ontario-housing-analysis.git
cd ontario-housing-analysis

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook


## Analysis Visualizations

Here are some key visualizations from the analysis:

![Average House Price](images/AVG-House%20Price.png)

![Bathroom vs Price](images/Bathroom%20vs%20price.png)

![Bedroom vs Price](images/Bedroom%20vs%20Price.png)

![Median Family Income vs Price](images/Median%20Family%20Income%20vs%20Price.png)
