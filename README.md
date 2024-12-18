# US Stock Value Forecasting with Technical Indicators

This project analyzes the use of technical indicators to predict stock prices for computer hardware companies listed on the New York Stock Market. The goal is to verify how closely the predicted values align with actual U.S. stock prices. 

We employ:
- **LSTM (Long Short-Term Memory)**: A machine learning technique.
- **ARIMA (AutoRegressive Integrated Moving Average)**: A statistical model.
- **Technical Indicators**: CCI (Commodity Channel Index), RSI (Relative Strength Index) MACD (Moving Average Convergence/Divergence), Parabolic SAR and Bollinger Bands.

The analysis covers **NVIDIA**, **AMD**, and **Intel**, using 5 years of historical data. Results highlight the effectiveness of certain technical indicators for forecasting and future investment planning.

## Project Contents

### 1. Folder Structure
The project is organized with separate folders for each company analyzed (**NVIDIA**, **AMD**, and **Intel**). Each company folder contains the following:

- **`Codes/`**: A collection of Jupyter notebooks implementing technical indicators on the company's stock data, using the [Technical Analysis Library](https://technical-analysis-library-in-python.readthedocs.io/en/latest/). These include:
  - `Bollinger Bands - <Company>.ipynb`: Implementation of Bollinger Bands.
  - `CCI - <Company>.ipynb`: Implementation of Commodity Channel Index (CCI).
  - `MACD - <Company>.ipynb`: Implementation of Moving Average Convergence/Divergence (MACD).
  - `Parabolic SAR - <Company>.ipynb`: Implementation of Parabolic Stop and Reverse (SAR).
  - `RSI - <Company>.ipynb`: Implementation of Relative Strength Index (RSI).

- **`Database 5 years <Company>/`**: Contains the raw historical stock data for the company.
  - `<Company> 5Y.csv`: A CSV file with 5 years of stock data.

- **`LSTM and ARIMA without Technical Indicators - <Company>/`**: Baseline analysis of stock data using LSTM and ARIMA models without incorporating technical indicators.
  - `LSTM_and_ARIMA_without_Techincal_Indicators_<Company>.ipynb`: A Jupyter notebook implementing this analysis.

This structure ensures consistency across all three companies and facilitates comparative analysis between models and indicators.

### 2. Technical Details
- **Language**: Python
- **Environment**: Jupyter Notebook

### 3. Datasets
- Historical stock data for NVIDIA, AMD, and Intel spanning 5 years.
- Implementation of various technical indicators using Python libraries.
- Comparative analysis using LSTM and ARIMA models.

## How to Use

### 1. Clone the Repository
Clone the repository using the following command:
```bash
git clone https://github.com/ThomasFrentzel/U.S-Stock-Forecasting-with-Technical-Indicators
```

### 2. Run the Notebooks
- Navigate to the desired company folder (AMD, Intel, or NVIDIA).
- Open the `Codes` folder and explore the Jupyter notebooks for technical indicators.
- Use the `Database 5 years <Company>` folder for raw data.
- Explore the `LSTM and ARIMA without Technical Indicators` folder for baseline analysis.

## Results and Insights
The project evaluates the effectiveness of different technical indicators in predicting future stock prices, with significant findings for investment strategies.

### Scientific Article
The scientific article with the analysis will be available [here](#).




## Authors

- [Thomas Frentzel](https://github.com/ThomasFrentzel)
- [Gabriel Sposito Conciani](https://github.com/GabrielScon)
