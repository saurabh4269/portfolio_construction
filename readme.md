# Sector Analysis For Portfolio Construction

This project aims to predict the performance of various sectors compared to the Nifty 50 benchmark index using econometric and machine learning models based on global and local economic variables.

## Approach

- The project starts by gathering historical data for various Nifty sector indices and relevant macroeconomic variables.
- Collected data on key macroeconomic variables such as GDP, CPI, interest rates, and unemployment from sources like the World Bank, Indian Fama-French Momentum, and Macrotrends.
- EDA is performed to understand the data and identify potential correlations.
- Visualize the data using libraries like `matplotlib` and `seaborn`.
- Predictive models are built and trained on historical data to forecast sector performance.
- Utilize econometric models like ARIMA or machine learning models such as Random Forest, XGBoost, etc.
- Model performance is evaluated using statistical metrics, and the results are compiled into a comprehensive report.

## Setup Instructions

### Prerequisites

- Python 3.x
- Necessary Python libraries: `yfinance`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `scikit-learn`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sector-analysis-portfolio.git
   cd sector-analysis-portfolio
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook and run the cells.


## How It Works



## Resources

- [World Bank Data](https://data.worldbank.org/)
- [Indian Fama-French Momentum](https://faculty.iima.ac.in/iffm/Indian-Fama-French-Momentum/)
- [Macrotrends](https://www.macrotrends.net/global-metrics/countries/IND/india/gdp-gross-domestic-product)