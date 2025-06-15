# High-Press, Transition-Oriented Teams Analysis (2024/25 Season)

This project explores the relationship between pressing intensity and offensive transition play across teams in Europe's top 5 football leagues (Premier League, La Liga, Bundesliga, Serie A, and Ligue 1) during the 2024/2025 season.

## 🔍 Objective

To identify and visualize clubs that exemplify **high-pressing**, **direct attacking football** — often associated with managers like Jürgen Klopp — by intersecting two key metrics:

- **PPDA (Passes Per Defensive Action)**: A lower value indicates higher pressing intensity.
- **Direct Attack Goals**: Goals scored from fast, vertical attacks (used as a proxy for counterattacking/transition goals).

## 📊 Data Sources

- **PPDA**: Obtained from Opta Analyst and FBref for each league.
- **Direct Attack Goals**: Also from Opta Analyst, used as an alternative to hard-to-find counterattack goal data.

## 🧠 Methodology

1. Collected PPDA and Direct Attack Goal stats for the top-performing teams in each metric.
2. Intersected both sets to retain only teams that appeared in **both** lists.
3. Visualized the final set using a **scatter plot** where:
   - X-axis = PPDA
   - Y-axis = Direct Attack Goals
   - Each point = A team
   - Quadrants added to distinguish styles

## 📐 Interpretation

- **Top-left quadrant**: High press, high direct goals — ideal *transition-oriented systems*.
- **Bottom-right quadrant**: Low press, low direct goals — typically slower buildup, possession-based systems.

## 📎 Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `matplotlib`
  - `numpy`

Install using:

```bash
pip install pandas matplotlib numpy
