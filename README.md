# AICTE Skills4Future Project - P-5

This repository contains analysis and code related to supply chain emission factors for various US industries and commodities. It is part of the AICTE Skills4Future program, focusing on environmental data analysis, data science techniques, and visualization of greenhouse gas (GHG) emissions within supply chains.

## Repository Structure

- `WEEK1.ipynb`: Jupyter notebook performing initial data loading, cleaning, exploration, and visualization of supply chain emission factors. It includes:
  - Data import and preprocessing
  - Handling missing values
  - Summary statistics and descriptive analytics
  - Visualization of top emitting industries and substances
  - Correlation analysis of data quality metrics

- `Week2/`
  - `week2task.ipynb`: Jupyter notebook (details not shown here, but likely continues or expands on the analysis).
  - `SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx`: Excel file containing emission factors data.
  - `models/`: (Contents not listed; likely contains scripts or models related to the analysis).

## Key Features and Analysis

### Data Handling & Cleaning
- The workflow starts by importing relevant libraries (Pandas, NumPy, Matplotlib, Seaborn).
- Loads supply chain emissions data (e.g., `SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx`).
- Cleans the data by removing empty columns, handling headers within data rows, and converting columns to numeric types.
- Handles missing values and resets the DataFrame index for clean analysis.

### Exploratory Data Analysis
- Summarizes the dataset for shape, column types, and descriptive statistics.
- Visualizes:
  - Top 10 industries by total emissions (bar plots)
  - Distribution of emission factors (histograms)
  - Emissions by substance type (bar plots)
  - Correlation heatmap of data quality metrics
  - (Optionally) Pie chart of emissions share by top industries

### Data Columns (Sample from `WEEK1.ipynb`)
- **Industry Code / Name**: Identifies each industry.
- **Substance**: GHG type (e.g., carbon dioxide, methane).
- **Unit**: Measurement unit (e.g., kg CO₂e per 2018 USD, purchaser price).
- **Emission Factors (with/without margins)**: Quantitative emission metrics.
- **Data Quality (DQ) Metrics**: Scores for reliability, temporal/geographical/technological correlation, and data collection quality.

### Technologies Used
- Python 3 (Jupyter Notebooks)
- Pandas, NumPy for data handling
- Matplotlib, Seaborn for data visualization

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sayantanpoddar/AICTE-skills4future-P-5.git
   cd AICTE-skills4future-P-5
   ```

2. **Install dependencies:**
   - Ensure Python 3 and Jupyter are installed.
   - Install required libraries:
     ```bash
     pip install pandas numpy matplotlib seaborn jupyter
     ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Open `WEEK1.ipynb` or `Week2/week2task.ipynb` to explore the analyses.

## Data Source

- Emission factors data sourced from US industry/commodity supply chains, targeting GHG accounting and environmental impact analysis.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for suggestions or improvements.

## License

This project is for educational and research purposes. Please check with the repository owner for licensing details.

---

*Developed as part of the AICTE Skills4Future Program.*
