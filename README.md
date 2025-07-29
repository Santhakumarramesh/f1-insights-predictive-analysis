# 🏎️ F1 Advanced Analysis Pipeline

This project analyzes the 2023 Formula 1 season using simulated race data to extract meaningful insights into driver performance, qualifying pace, race strategies, and team-level patterns. It demonstrates how motorsport data can be used for competitive analysis, predictive modeling, and circuit-level insights.

---

## 📁 Dataset

**Source:** Simulated from Ergast API structure

**Files Included:**
- `race_schedule.csv`
- `driver_standings_2023.csv`
- `qualifying_results_2023.csv`
- `lap_times_2023.csv`
- `pit_stops_2023.csv`

**Key Features:**
- `driver`, `constructor`, `qualifying time`, `position`, `lap`, `pit stop duration`
- `circuit`, `round`, `points`, `championship rank`

---

## 🔍 Project Workflow

1. **Load and clean CSV data**
2. **Visualize trends**:
   - Driver standings
   - Pit stop patterns
   - Fastest lap comparisons
   - Qualifying performance
3. **Engineer features** for modeling
4. **Apply machine learning** to predict top 3 finishers
5. **Cluster circuits** based on racing conditions
6. **Evaluate driver consistency**

---

## 📊 Key Insights

1. **Championship Point Trends**
2. **Lap-by-Lap Position Evolution**
3. **Fastest Lap Time Comparisons**
4. **Qualifying Time Trends**
5. **Finish Position vs Grid Start**
6. **Pit Strategy Efficiency**
7. **3D Circuit Clustering (AvgSpeed, PitStops, Laps)**

Each insight is visualized using rich Plotly charts, Seaborn regressions, or 3D clustering maps.

---

## 🛠 Tools & Libraries

- Python 3.x
- `pandas`, `numpy` for data processing
- `matplotlib`, `seaborn`, `plotly` for visualizations
- `sklearn` for clustering and classification
- `jupyter` / `Google Colab` for running the notebook

---

## 🧠 How to Use

1. Clone or download the repository
2. Make sure all five CSV files are in the same directory
3. Open `F1_Analysis.ipynb` in Jupyter or Colab
4. Run all cells to:
   - Load data
   - Generate interactive plots
   - Train the prediction model

---

## ✅ Output Preview

> 📈 Visualizations include:
- Standings bar charts
- Q3 qualifying time trends
- Fastest lap line plots
- Pit stop frequency
- Circuit-level lap boxplots
- 3D clustering of race circuits

---

## 💡 Author

**Santhakumar Ramesh**  
MPS in Data Science and Applications  
University at Buffalo  
[GitHub](https://github.com/Santhakumarramesh)

---
