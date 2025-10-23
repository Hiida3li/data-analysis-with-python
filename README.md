# Data Analysis with Python - Superstore Sales

A comprehensive data analysis project that explores and visualizes Superstore sales data using Python and Tableau.

## Overview

This project performs exploratory data analysis (EDA) on the Sample Superstore dataset to uncover insights about sales performance, customer behavior, and business trends. The analysis combines Python for statistical analysis and data visualization with Tableau for interactive dashboards.

## Features

- **Exploratory Data Analysis**: Comprehensive statistical analysis of sales, profits, and customer segments
- **Data Cleaning**: Preprocessing and cleaning of raw sales data
- **Interactive Visualizations**: Dynamic charts and graphs using Plotly
- **Tableau Dashboard**: Interactive business intelligence dashboard for stakeholder reporting

## Technologies Used

- **Python 3.x**
  - Plotly 6.2.0 - Interactive visualizations
  - Kaleido 1.0.0 - Static image export
  - Pandas (for data manipulation)
  - Jupyter Notebook (for analysis)
- **Tableau** - Business intelligence and dashboards

## Project Structure

```
data-analysis-with-python/
├── data/
│   ├── Sample-superstore.xls      # Raw data
│   └── superstore_cleaned.csv     # Cleaned data
├── notebooks/
│   ├── EDA_sales.ipynb            # Main exploratory analysis
│   └── drafts_space.ipynb         # Draft analysis workspace
├── images/                         # Visualization outputs
├── Book1_tst.twb                  # Tableau workbook
├── requirements.txt               # Python dependencies
└── README.md
```

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/data-analysis-with-python.git
cd data-analysis-with-python
```

2. Install required Python packages:
```bash
pip install -r requirements.txt
```

## Usage

1. **Run the Analysis**:
   - Open `notebooks/EDA_sales.ipynb` in Jupyter Notebook or JupyterLab
   - Execute cells to perform the analysis

2. **View Tableau Dashboard**:
   - Open `Book1_tst.twb` in Tableau Desktop
   - Explore interactive visualizations

## Data Source

The project uses the Sample Superstore dataset, which contains:
- Sales transactions
- Customer information
- Product categories
- Regional data
- Profit and discount information

## Contributing

Feel free to fork this project and submit pull requests for any improvements.

## License

This project is open source and available for educational purposes.
