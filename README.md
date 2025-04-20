# End-to-End F1 Race Analysis using Machine Learning

Welcome to my Formula 1 analytics project! This repository demonstrates a complete, end-to-end workflow for analyzing F1 race data using Python, pandas, and machine learning tools. The project is designed to be modular, transparent, and easily extensible to any race or season. Whether you're an F1 fan, a data enthusiast, or a hiring manager looking for real-world data science skills, you'll find this project both insightful and practical.

---

## 🚦 Project Overview

This project walks through the entire data science lifecycle:
- **Data Acquisition:** Automatically fetches official F1 race results using the FastF1 library.
- **Data Storage:** Saves raw results to CSV for reproducibility and easy sharing.
- **Exploratory Data Analysis (EDA):** Uses pandas to explore, summarize, and visualize race data.
- **Machine Learning Ready:** Sets up the foundation for predictive modeling and deeper analytics.
- **Extensible Design:** Easily adapt to analyze multiple races or the whole season by changing parameters.

---

## 🏎️ What’s Included

- **Jupyter Notebook:** The main notebook (`F1.ipynb`) contains all code, explanations, and outputs.
- **Sample Data:** Example output CSV (`bahrain_2023_results.csv`) for Bahrain 2023, ready for further analysis.
- **Caching:** Uses FastF1's cache to minimize repeated API calls and speed up data retrieval.

---

## 📊 Example Analysis

- Load race results for any Grand Prix (e.g., Bahrain 2023).
- Explore driver and team performance, positions, and points.
- Analyze grid vs. finish positions, classification, and status.
- Summarize points distribution and identify top performers.

---

## 🛠️ How to Run

1. **Clone this repository** and navigate to the project folder.
2. **Install dependencies** (preferably in a virtual environment):
    ```
    pip install fastf1 pandas scikit-learn matplotlib
    ```
3. **Open the notebook**:
    - Launch Jupyter Notebook or JupyterLab and open `F1.ipynb`.
    - Run the cells sequentially to fetch, save, and analyze race data.

---

## 🧩 Key Data Columns

- `DriverNumber`, `BroadcastName`, `Abbreviation`, `DriverId`
- `TeamName`, `TeamColor`, `TeamId`
- `FirstName`, `LastName`, `FullName`
- `CountryCode`
- `Position`, `ClassifiedPosition`, `GridPosition`
- `Status`, `Points`
- (and more, depending on data availability)

---

## 💡 Extending the Project

- **Multiple Races:** To analyze more races, simply change the year and race name in the notebook and re-run.
- **Season Analysis:** Loop through a list of races to aggregate season-level stats.
- **Machine Learning:** The notebook is set up for you to add feature engineering and predictive models (e.g., predicting finishing position or points).
- **Visualization:** Use matplotlib or seaborn to create insightful plots (e.g., points by driver, team comparisons).

---

## ⚠️ Notes & Troubleshooting

- **API Rate Limits:** FastF1 and F1 APIs may have rate limits. If you encounter errors, wait a while or use the cache to avoid repeated downloads.
- **Data Availability:** Not all columns are populated for every race/session; check for NaNs before modeling.
- **Reproducibility:** All steps are reproducible—just follow the notebook from top to bottom.

---

## 📚 Dependencies

- [FastF1](https://theoehrly.github.io/Fast-F1/)
- pandas
- scikit-learn
- matplotlib

---

## 📢 About

This project was built to showcase practical data science and machine learning skills on real-world, complex sports data. If you have questions, suggestions, or want to collaborate, feel free to open an issue or connect with me on LinkedIn!

---

*For educational and demonstration purposes only. Not affiliated with Formula 1 or its data providers.*
