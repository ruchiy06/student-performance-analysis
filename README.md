# Wholesale Customers Data Analysis

## Overview

This project presents an exploratory data analysis (EDA) of the **Wholesale Customers Dataset**, a well-known benchmark dataset from the UCI Machine Learning Repository. The dataset captures the annual spending (in monetary units) of clients of a wholesale distributor across six product categories: **Fresh**, **Milk**, **Grocery**, **Frozen**, **Detergents_Paper**, and **Delicatessen**.

The analysis explores:
- Distribution and statistical summary of customer spending behaviour
- Correlations between product categories
- Identification of customer segments based on purchasing patterns
- Insights into channel (Hotel/Restaurant/Café vs. Retail) and region-based differences

The full analysis and visualisations are available in the included HTML report, generated programmatically for easy sharing and reproducibility.

---

## Files Included

| File | Description |
|------|-------------|
| `wholesale_customers_data.csv` | The raw dataset containing annual spending data for 440 wholesale customers across 8 features (Channel, Region, and 6 product categories). |
| `Wholesale Customer Data.html` | An interactive HTML report containing the complete data analysis, including summary statistics, correlation heatmaps, distribution plots, and key findings. |
| `README.md` | This documentation file. |
| `.gitignore` | Specifies files and directories intentionally untracked by Git. |

---

## Dataset Details

- **Source**: UCI Machine Learning Repository — Wholesale Customers Dataset
- **Records**: 440 customers
- **Features**:
  - `Channel` — Customer channel: 1 = Hotel/Restaurant/Café (Horeca), 2 = Retail
  - `Region` — Customer region: 1 = Lisbon, 2 = Porto, 3 = Other
  - `Fresh` — Annual spending on fresh products (monetary units)
  - `Milk` — Annual spending on milk products
  - `Grocery` — Annual spending on grocery products
  - `Frozen` — Annual spending on frozen products
  - `Detergents_Paper` — Annual spending on detergents and paper products
  - `Delicatessen` — Annual spending on delicatessen products

---

## How to View

### Option 1 — Open Locally
1. Clone or download this repository.
2. Navigate to the project folder.
3. Open `Wholesale Customer Data.html` directly in any modern web browser (Chrome, Firefox, Edge, Safari).

### Option 2 — Via GitHub Pages
If GitHub Pages is enabled for this repository:
1. Go to the repository **Settings** → **Pages**.
2. Under **Source**, select the `main` branch and root folder (`/`).
3. Save the settings and wait for GitHub Pages to deploy.
4. The report will be accessible at:
   `https://<your-github-username>.github.io/wholesale-customers-analysis/Wholesale%20Customer%20Data.html`

---

## Requirements

No special software is required to view the HTML report — just a web browser. If you wish to re-run or extend the analysis programmatically:

- **Python 3.8+**
- Recommended libraries: `pandas`, `matplotlib`, `seaborn`, `numpy`, `plotly`

---

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
