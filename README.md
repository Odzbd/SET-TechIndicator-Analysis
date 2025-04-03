# SET Technical Analysis

This repository provides a simple tool (`SET_Analysis_Tool.ipynb`) for analyzing stock data from the Stock Exchange of Thailand (SET). It focuses on key technical indicators and visualizations for clear insights.

## Features

-   **Data:** Retrieves stock data via `yfinance` or loads from a Feather file (`tickers_data_020468.feather`).
-   **Indicators:** Calculates EMA (20, 50, 100, 150, 200), RSI, ADX, and Wavetrend.
-   **Volume Analysis:** Categorizes stocks by volume (small, medium, large).
-   **Visualizations:** Generates clean plots for EMAs, RSI, ADX, Wavetrend, and EMA value distributions.
-   **Strength Categorization:** Classifies stocks as Weak, Moderate, or Strong based on EMA ratios.

## Dependencies

-   `yfinance`
-   `pandas`
-   `pandas_ta`
-   `numpy`
-   `matplotlib`
-   `seaborn`

## Usage

1.  **Clone:**

    ```bash
    git clone https://github.com/Odzbd/SET-TechIndicator-Analysis.git
    cd SET-TechIndicator-Analysis
    ```

2.  **Install:**

    ```bash
    pip install yfinance pandas pandas_ta numpy matplotlib seaborn
    ```

3.  **Run:**

    ```bash
    jupyter notebook SET_Analysis_Tool.ipynb
    ```

4.  **Data:**
    -   Use `tickers_020468.txt` for live data from Yahoo Finance.
    -   Or, use `tickers_data_020468.feather` for faster loading.

5.  **Analyze:**
    -   Execute notebook cells for analysis and visualizations.

## Files

-   `SET_Analysis_Tool.ipynb`: Analysis notebook.
-   `tickers_020468.txt`: (Optional) Stock ticker list.
-   `tickers_data_020468.feather`: (Optional) Pre-loaded data.

## Visuals

-   **EMA:** Trends across stock groups.
-   **RSI:** Overbought/oversold levels.
-   **ADX:** Trend strength.
-   **Wavetrend:** Momentum shifts.
-   **EMA Distribution:** Stock strength overview.
-   **Volume Groups:** Performance by volume.
-   **Strength Pie:** Stock category breakdown.

## Author

[Odzbd](https://github.com/Odzbd)
