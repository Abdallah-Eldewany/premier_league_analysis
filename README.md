# 📊 FPL Data Analysis Project (2024-25)

An automated data analysis pipeline designed to explore, clean, and extract actionable insights from Fantasy Premier League (FPL) player statistics for the 2024-25 season. This project identifies top-performing assets, evaluates value-for-money metrics, and assists in data-driven squad selection.

---

## 🚀 Features

* **Data Cleaning & Preprocessing:** Handles missing values, filters out inactive players, and formats data types for analysis.
* **Value Metric Calculation:** Introduces custom metrics like `value_for_money` calculated as:
  $$\text{Value For Money} = \frac{\text{Total Points}}{\text{Player Cost}}$$
* **Performance Benchmarking:** Ranks and filters players by total points, position, and cost brackets.
* **Exploratory Data Analysis (EDA):** Generates statistical summaries (mean, median, mode) across different teams and positions.

---

## 📊 Dataset Overview

The project utilizes the `fpl_playerstats_2024-25.csv` dataset, which contains **661 player records** with key performance indicators including:
* **Player Basics:** `first_name`, `second_name`, `team_name`, `player_position`
* **Financials:** `player_cost`
* **Performance:** `minutes`, `total_points`, and other underlying match statistics.

---

## 📈 Key Insights Found

### 1. Top Point Scorers 🎯
The highest-earning premium assets dominating the early stretch of the season:
* **Erling Haaland** (Man City, FWD, £15.3m) – **63.0 pts**
* **Luis Díaz** (Liverpool, MID, £7.9m) – **51.0 pts**
* **Mohamed Salah** (Liverpool, MID, £12.8m) – **49.0 pts**

### 2. Best Value-for-Money Picks 💰
By filtering for players with a minimum of 90 minutes played, the best budget enablers emerge:
* **Robert Sánchez** (Chelsea, GKP, £4.6m) – Value Ratio: **6.52**
* **Luis Díaz** (Liverpool, MID, £7.9m) – Value Ratio: **6.46**
* **André Onana** (Man United, GKP, £5.0m) – Value Ratio: **6.00**

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook / Google Colab

---

## 💻 How to Run

1. Clone this repository:
```bash
   git clone [https://github.com/your-username/fpl-data-analysis.git](https://github.com/your-username/fpl-data-analysis.git)
