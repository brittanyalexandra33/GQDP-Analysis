# GQDP-Analysis

**Objective/Goal:**

The objective of this project was to analyze the Quarterly GDP (QGDP) data for the retail trade industry in New Zealand using time series analysis techniques and forecast the future trends in the industry.


**Data:**

The data used for the project was obtained from the qgdp_retail.csv file provided by Statistics New Zealand. The data contains quarterly (chain volume) gross domestic product (QGDP) for the retail trade industry in New Zealand measured in the prices from 2009/10 in NZD Millions.


**Models and Tools Used:** 

The project was implemented using R programming language and the RStudio software. The following models and tools were used:

- Lubridate function
- Tsibble object
- STL Decomposition
- SNAIVE Method
- Naive (NAIVE) and the Random Walk with Drift (RW) Benchmark Forecast Methods
- Autoplot
- Ljung-Box Portmanteau Test


**Code:**

The code for the project can be found at [insert link here].


**Results:**

The time series analysis of the QGDP data revealed that the actual and seasonally-adjusted series have a similar trend with a slight increase in the recent years. Two real-world events that could have affected these time series are the COVID-19 pandemic and the economic recession in 2008. The STL decomposition of the actual QGDP series showed a clear trend, seasonal, and remainder components. The seasonally-adjusted series produced by the STL decomposition was slightly different from the seasonally-adjusted series produced by Statistics New Zealand. The Ljung-Box Portmanteau Test showed that the remainder series was consistent with white noise. The forecast models showed that the Naive (NAIVE) benchmark method outperformed the Random Walk with Drift (RW) method in terms of forecast accuracy.

Overall, this project demonstrated the use of time series analysis techniques and forecast models to analyze QGDP data for the retail trade industry in New Zealand.
