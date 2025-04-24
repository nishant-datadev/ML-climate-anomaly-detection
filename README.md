🌡️ Global Temperature Anomaly Detection by Studying Temperature Trends from 1800 to 2024
========================================================================================

A data-driven exploration of land, ocean, and combined temperature anomalies from 1880 to 2024. This project leverages visualization and statistical techniques to uncover long-term climate trends, detect outliers and highlight patterns in global temperature behavior.
It also illustrates a consistent rise in average global temperatures over time, highlighting the ongoing impact of global warming.

📁 Project Structure
--------------------

├── data/                     Original dataset from Kaggle (or link to it)
├── notebooks/                Jupyter Notebook with full analysis
├── requirements.txt          Python environment dependencies
└── README.md                 Project documentation

📊 Project Overview
-------------------

🔍 Objective
- Explore historical temperature anomaly data.
- Identify trends and climate shifts.
- Visualize anomalies (land, ocean, combined).
- Detect outliers using Z-score analysis.

📈 Dataset
- Source: Kaggle->global-temperature-anomaly-data
- Fields: YearMonth, Station, Land_Ocean, Land_Only, Open_Ocean
- Processed: Parsed date, added Z-score columns.

🧪 Technologies Used
--------------------
- Python (Miniconda)
- Jupyter Notebook
- Pandas
- Matplotlib, Seaborn
- NumPy

📌 Key Features
---------------
- Date parsing and formatting
- Z-score based outlier detection
- Trend visualization
- Combined plots with legends

🖥️ How to Run Locally
----------------------

1. Clone the repository

2. Set up the environment (optional):
   conda create -n temp-anomaly python=3.9
   conda activate temp-anomaly
   pip install -r requirements.txt

3. Launch Jupyter Notebook:
   jupyter notebook

4. Open the notebook inside `notebooks/` to view the analysis.

📚 Project Insights
-----------------
- Handling messy time formats
- Z-score analysis for outlier detection
- Storytelling with data visuals
- Organizing and documenting data projects

🚀 Future Enhancements
----------------------
- Regional breakdown of anomalies
- Packaging into reusable module
- Forecasting with ML

👨‍💻 Author
-----------
Nishant B.
GitHub: https://github.com/nishant-datadev

📜 License
----------
MIT License
