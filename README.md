# Google Trends Data Visualization & Time-Series Analysis

An advanced data analytics project investigating the relationship between Google Search popularity trends and real-world economic metrics using Python and Pandas.

## 🚀 Key Analysis Features
* **Tesla Performance:** Mapping stock market closing prices against web search hype.
* **Bitcoin Resampling:** Aggregating high-frequency daily price data into clean monthly trend lines to match Google Trends search intervals.
* **Unemployment Seasonality:** Identifying predictive search behavior shifts around December job markets using a 6-month rolling average.

## 🛠️ Data Science Toolkit Used
* **Language:** Python
* **Libraries:** Pandas, Matplotlib, Matplotlib.dates (YearLocator, MonthLocator)
* **Key Concepts:** Data Cleaning (`.dropna()`), Time-Series Data Type Casting (`pd.to_datetime()`), Data Resampling (`.resample()`), Rolling Window Calculations (`.rolling()`), and Dual-Axis Presentation Charting (`.twinx()`).

## 📁 Repository Structure
* `Untitled1.ipynb` - The primary data analysis notebook.
* `Bitcoin Search Trend.csv` - Monthly search frequency data for Bitcoin.
* `Daily Bitcoin Price.csv` - Daily financial exchange tracking for Bitcoin.
* `TESLA Search Trend vs Price.csv` - Combined monthly web metrics for Tesla.
* `UE Benefits Search vs UE Rate 2004-19.csv` - Macroeconomic dataset tracking US employment metrics.

## 💻 How to Run This Project
1. Download this repository as a `.zip` file or open the notebook file directly inside **Google Colab**.
2. Ensure all `.csv` files are placed in the same folder directory level as the notebook file.
3. Run the notebook cells sequentially to generate the high-resolution charts!
