

##  Uber NYC 2014 Exploratory Data Analysis

### 📊 Project Overview

The **Uber NYC 2014 EDA** project explores over **4.5 million Uber pickup records** in New York City to uncover patterns in **ride demand, timing, and location trends** throughout 2014.
This dataset, sourced from [Kaggle’s FiveThirtyEight Uber Pickups dataset](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city), provides a fascinating view into urban mobility behavior.

### 🎯 Objective

The goal of this project is to:

* Analyze **temporal trends** — identify peak hours, days, and months for Uber rides.
* Examine **geospatial distributions** of pickups across NYC boroughs.
* Visualize **seasonal patterns** and potential operational insights for Uber’s service optimization.

### 🧠 Key Insights

* Peak demand occurs during **evening commute hours** and **weekends**.
* **Manhattan** dominates total pickups, highlighting its dense commercial and nightlife zones.
* Seasonal analysis reveals **increased ride frequency** in warmer months.

### ⚙️ Tech Stack & Skills Used

| Category                 | Tools / Skills                                       |
| ------------------------ | ---------------------------------------------------- |
| **Programming Language** | Python 🐍                                            |
| **Data Handling**        | Pandas, NumPy                                        |
| **Visualization**        | Matplotlib, Seaborn, GeoPandas, Geoplot              |
| **Geospatial Analysis**  | NYC shapefiles, coordinate mapping                   |
| **Data Source**          | Kaggle Dataset (FiveThirtyEight Uber pickups in NYC) |
| **Environment**          | Jupyter Notebook / Kaggle Notebook                   |

### 📂 Project Structure

```
Uber_NY_2014_EDA/
│
├── Uber_NY_2014_EDA.ipynb     # Main analysis notebook
├── README.md                   # Project documentation
└── datasets/                   # (Optional) Uber pickup data from Kaggle
```

### 🧩 Analysis Highlights

* **Data Cleaning & Preprocessing:** Handling missing values, formatting timestamps, feature extraction (hour, day, month).
* **Temporal Analysis:** Trend analysis by hour, weekday, and month.
* **Spatial Visualization:** Mapping pickup density using GeoPandas and heatmaps.
* **Exploratory Visualization:** Multi-layer visualizations using Seaborn and Matplotlib.

### 📸 Sample Visualizations

* Heatmaps showing pickup density by hour and weekday.
* Geographic pickup clusters across NYC boroughs.
* Monthly demand variations visualized using line and bar charts.

### 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/Uber_NY_2014_EDA.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:

   ```bash
   jupyter notebook Uber_NY_2014_EDA.ipynb
   ```

### 📈 Future Enhancements

* Add **interactive dashboards** using Plotly or Streamlit.
* Apply **clustering algorithms (K-Means)** for ride hotspot detection.
* Extend analysis to **multi-year Uber datasets** for trend comparison.



