## Football Player & Team Analytics (2014–2020)

Advanced football analytics and visualizations using **player-level data** from
**EPL, Bundesliga, and LaLiga (2014–2020)**.

This project focuses on **modern metrics** such as **xG, xA, xG Chain, xG Buildup**, and provides **SofaScore-style insights** through Python visualizations.

## Key Features

###  Player Analytics

* Goals, assists, shots, minutes
* Advanced metrics:

  * **xG (Expected Goals)**
  * **xA (Expected Assists)**
  * **xG Chain** – total attacking involvement
  * **xG Buildup** – pre-assist & buildup contribution
* Per-90 normalization
* Over / under-performance analysis (Goals − xG)

---

###  Visualizations Included

#### Player Level

* Top players by:

  * Goals
  * Goals per 90
  * Assists
  * Assists per 90
  * xG Chain
  * xG Buildup
* Goals per shot efficiency (attackers)
* Player profile charts:

  * Bar charts
  * Radar / spider charts

#### Team Level

* **Team goals by unit** (Attacking / Midfield / Defence)
* Tactical fingerprints:

  * Goals, assists, shots by unit
* Team style comparison using xG Chain & xG Buildup

#### League Level

* League-wise attacking output
* Tactical identity comparison across leagues
* Separate visualizations for:

  * EPL
  * Bundesliga
  * LaLiga
* Selected cross-league comparison charts


### 🔍 Advanced Analysis

* Correlation analysis between key metrics
* Player clustering using **K-Means**
* Scout-style similarity search using **cosine similarity**
* Identification of:

  * Finishers
  * Creators
  * Hybrid attackers

---

## 🛠 Tech Stack

* **Python**
* **Pandas** – data processing
* **Matplotlib & Seaborn** – visualization
* **Scikit-learn** – clustering & similarity

---

## 📁 Project Structure

```text
├── data/
│   ├── EPL_14_20_players_stat.csv
│   ├── Bundesliga_14_20_players_stat.csv
│   └── laliga_14_20_players_stat.csv
│
├── notebooks/
│   └── player_stat_visualization.ipynb

## ▶️ How to Run

### 1️⃣ Install dependencies

```bash
pip install pandas matplotlib seaborn scikit-learn
```

### 2️⃣ Run the notebook

```bash
jupyter notebook player_stat_visualization.ipynb
```

or run the Python script.


## 📈 Example Insights

* **xG Chain** correlates more strongly with goals than shots
* **xG Buildup** highlights creative midfielders often missed by raw stats
* Bundesliga teams show higher shot volume
* LaLiga emphasizes midfield creativity
* EPL displays balanced attacking contribution

---

## 🎯 Use Cases

* Football analytics and insights projects
* Scouting & recruitment analysis
* Tactical team profiling

---

## 🚀 Future Improvements

* Interactive dashboards (Plotly / Dash)
* Match-level integration
* Player movement tracking integration
* Position-specific player clustering
* Automated player scouting reports
* Season-wise trend analysis

---
