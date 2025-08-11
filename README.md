#  Statistical Analysis of Electricity Prices in Southern Norway

**Experimental Findings**

**Author:** Grethel L. Mabilangan
**License:** General License

---

##  Overview

Electricity price forecasting in **Southern Norway** has grown increasingly complex due to volatile global fuel costs, fluctuating demand, hydropower variability, and geopolitical uncertainty.
This project applies **statistical analysis** to investigate how economic indicators, environmental conditions, hydropower storage, and macroeconomic factors influence electricity spot and consumer prices.

The findings aim to support **market participants**, **policymakers**, and **energy-intensive industries** in developing **robust pricing strategies**, improving **risk management**, and optimizing **energy planning** in Norway’s evolving electricity market.

---

## Research Objectives

The study addresses **five core business concerns**:

1. **Gas Prices & Reservoir Levels** – Interaction between natural gas prices and spot prices under high vs. low hydropower storage conditions.
2. **Wind Power vs. Rainfall** – Whether wind power generation is becoming a stronger driver of price changes than rainfall.
3. **Global vs. Local Drivers** – Influence of global commodity prices (oil, gas, coal) vs. local factors (reservoir levels, temperature) on extreme price spikes.
4. **Spot Market Reliability** – How the predictive power of spot prices for consumer prices has changed before, during, and after 2020.
5. **Macroeconomic vs. Meteorological Factors** – Impact of U.S. dollar prices vs. local weather (temperature, precipitation) on spot prices.

---

## Data Description

The dataset combines **economic, environmental, and market variables** from multiple reputable sources, including:

* **Statnett**
* **Nord Pool**
* **Investing.com**
* **Business Insider**
* **U.S. EIA**

**Key Variables:**

* **Economic Factors**: Oil price (€), coal price (€), natural gas price (€), USD exchange rate.
* **Environmental Factors**: Precipitation, average temperature, wind speed.
* **Hydropower**: Reservoir fill levels (%).
* **Market Data**: Spot electricity price, actual consumer electricity price.

---

## Methods

1. **Data Preprocessing**

   * Cleaning missing values.
   * Standardizing units and currencies.
   * Aggregating data to consistent time intervals.

2. **Statistical Analysis**

   * Descriptive statistics.
   * Pearson & Spearman rank correlation analysis.
   * Time series trend analysis.
   * Volatility and anomaly detection.

3. **Visualization**

   * Seasonal price patterns.
   * Correlation heatmaps.
   * Price-driver scatter plots.
   * Time series with volatility highlights.

---

## Tools & Libraries

* **Python**: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels
* **Jupyter Notebook** for exploratory and visual analysis

---

## Key Findings

* **Gas prices** correlate more strongly with spot prices when hydropower reservoir levels are **low**.
* **Wind power** now shows a stronger negative correlation with spot prices than **rainfall**.
* **Extreme price spikes** are driven more by **global commodity prices** than local weather conditions.
* The **spot market** has become **less reliable** in predicting consumer electricity prices post-2020.
* **U.S. dollar fluctuations** have a greater impact on prices than temperature or precipitation.

---

## How to Use

1. Clone the repository:

   ```bash
    git clone https://github.com/GretteThel/Statistical-Analysis-of-Electricity-Prices-in-Southern-Norway.git
    cd Statistical-Analysis-of-Electricity-Prices-in-Southern-Norway
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the analysis:

   ```bash
   jupyter notebook notebooks/
   ```

---

## License

This project is released under the **General License**.


