# Stock-Data-Analysis-


---

```markdown
# Stock Data Analysis with Python and Power BI

This repository contains Python code and example outputs for analyzing historical stock price data. The project generates CSV summaries and visualizations that can be imported into Power BI dashboards.

## 📂 Project Structure

```

├── data/
│   └── your\_file.csv                # Raw stock price data (CSV)
├── output/
│   ├── annual\_summary.csv            # Annual-level metrics
│   ├── monthly\_summary.csv           # Monthly-level metrics
│   ├── weekday\_summary.csv           # Weekday-level metrics
│   ├── detailed\_daily\_data.csv       # Enriched daily dataset
│   ├── adj\_close\_trend.png           # Price trend chart
│   ├── volume\_trend.png              # Volume trend chart
│   ├── volatility\_trend.png          # Rolling volatility chart
│   └── monthly\_heatmap.png           # Monthly price heatmap
├── stock\_analysis.py                 # Main analysis script
└── README.md                         # Project documentation

````

## 📈 Features

- **Data ingestion:** Reads stock data (CSV format with `Date`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`).
- **Data enrichment:** Adds daily return %, rolling volatility, and time-based columns.
- **Aggregations:** Produces annual, monthly, and weekday summaries.
- **Visuals:** Generates plots for trends, volume, volatility, and heatmaps.
- **Power BI ready:** Outputs clean CSV files for dashboard integration.

## 🚀 Usage

1️⃣ Place your stock data CSV in the `data/` folder.  
2️⃣ Run the analysis script:
```bash
python stock_analysis.py
````

3️⃣ View results in the `output/` folder — import CSVs/plots into Power BI or other BI tools.

## 🛠 Requirements

* Python 3.x
* Libraries:

  * `pandas`
  * `matplotlib`
  * `seaborn`

Install dependencies:

```bash
pip install pandas matplotlib seaborn
```

## 📊  Outputs

* **Annual Summary:** Open, Close, High, Low, Adj Close, Total Volume, Avg Daily Return, Volatility
* **Monthly Summary:** Same metrics grouped by year and month
* **Weekday Summary:** Avg price, volume, return, and volatility by day of the week
* **Plots:** Line charts, bar charts, heatmaps for Power BI

## ✨ Power BI Integration

* Import CSVs directly for table visualizations
* Use saved plots in image tiles
* Build KPIs, line charts, bar charts, heatmaps based on output files
* ![image](https://github.com/user-attachments/assets/6bf62556-cad8-4e54-b53c-72e91ffdf518)


## 📄 License

This project is licensed under the MIT License — feel free to use, modify, and share.


