# Exoplanet Host Star Characterization with Gaia & NASA Archives

## Project Overview
This project analyzes M-dwarf stars that host exoplanets using data from multiple astronomical catalogs, including:
- **M-Dwarf Catalog**
- **NASA Exoplanet Archive**
- **Gaia DR2 and DR3**

We perform crossmatching, data cleaning, normalization, and Bayesian statistical modeling to uncover stellar and planetary characteristics. The analysis includes uncertainty quantification using `emcee` and visualization of posterior distributions with `corner` plots.

## Skills Demonstrated
- **Data Acquisition & Integration:** Querying and merging multiple large-scale astronomical datasets.
- **Data Cleaning & Processing:** Handling missing values, normalizing variables, and matching IDs across catalogs.
- **Statistical Modeling:** Bayesian parameter estimation using Markov Chain Monte Carlo (MCMC).
- **Scientific Visualization:** Creating professional-quality plots with `matplotlib` and `corner`.
- **Astrophysical Insights:** Investigating correlations between stellar properties and exoplanetary systems.

## Technologies Used
- Python
- Pandas, NumPy
- Astroquery, Astropy
- emcee, corner
- Matplotlib, Seaborn

## Example Outputs
### 1. Cleaned & Merged Dataset
Shows the crossmatched dataset between the M-dwarf catalog, NASA Exoplanet Archive, and Gaia data.

### 2. Posterior Distributions
Corner plots from `emcee` visualizing parameter uncertainties.

### 3. Stellar & Planetary Trends
Visual analysis of relationships between stellar parameters and exoplanet characteristics.

## Results & Insights
- Successfully crossmatched thousands of stellar records across multiple datasets.
- Identified distributions of key stellar parameters for exoplanet hosts.
- Demonstrated reproducible workflow for catalog-level astronomical data analysis.

## Repository Structure
```
├── notebook.md         # Polished Jupyter Notebook in Markdown format
├── README.md           # Project overview (this file)
└── data/               # Links or instructions to download datasets
```

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/exoplanet-gaia-analysis.git
cd exoplanet-gaia-analysis
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Open and run the notebook:
```bash
jupyter notebook FINAL.ipynb
```
