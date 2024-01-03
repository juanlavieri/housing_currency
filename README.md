# Real Estate Valuation Analysis: USD, Bitcoin, and Gold

## Introduction
This project analyzes historical housing prices in the United States, comparing the value changes when priced in traditional U.S. dollars, Bitcoin, and gold. The goal is to provide insights into the stability and volatility of real estate as an investment compared to digital and traditional assets.

## Project Structure

### Data
The `Resources` directory contains all the datasets used and generated during this analysis. 
We also included a quick "cheat-sheet" on how to use github collaboratively for our own purpose but decided to leave it in case it is useful for anyone else `Resources/git_instructions.md`

### Notebooks
The project includes Jupyter notebooks with detailed analysis:
- `Bitcoin_Prices_Analysis.ipynb`: Procedures for BTC data collection, cleansing, and alignment.
- `Dollar_Value_Analysis.ipynb`: Exploratory data analysis and statistical summaries for CPI data.
- `Gold_Prices_Analysis.ipynb`: Gold data collection, cleansing, and varios vizualizations.
- `Housing_Prices_Analysis.ipynb`: Collection, cleansing, modelling, and predictions on housing prices.
- `Comparative_Housing_Prices_Analysis.ipynb`: USD, Gold, and BTC housing prices conversion, comparison, and analysis

## Usage
To replicate this analysis, ensure that you have all the required libraries installed, then run the Jupyter notebooks, feel free to experiment and derive your own conclusions.

## Contributing
We welcome contributions to this project. Please fork the repository, make your changes, and submit a pull request for review.

## Acknowledgments
- Housing price data provided by U.S. Census Bureau and U.S. Department of Housing and Urban Development, Median Sales Price of Houses Sold for the United States [MSPUS], retrieved from FRED, Federal Reserve Bank of St. Louis; https://fred.stlouisfed.org/series/MSPUS, December 21, 2023.
- Bitcoin price data sourced from 'https://raw.githubusercontent.com/colaberry/data/master/Bitcoin/bitcoin_dataset.csv' and `https://www.edx.org/` 
- Gold price data obtained from Macretrends `https://macrotrends.net/1333/historical-gold-prices-100-year-chart`.
- CPI data acquired from U.S. Bureau of Labor Statistics, Consumer Price Index for All Urban Consumers: All Items Less Food and Energy in U.S. City Average [CPILFESL], retrieved from FRED, Federal Reserve Bank of St. Louis; https://fred.stlouisfed.org/series/CPILFESL, December 20, 2023..

Further acknowledgments will be added upon project completion and final data source credits.

## License
This project is licensed under the MIT - see the LICENSE.md file for details.

