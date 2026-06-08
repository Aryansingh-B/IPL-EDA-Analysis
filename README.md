# IPL Data Analysis — Exploratory Data Analysis (2008–2024)

> *Uncovering patterns, trends, and insights from a decade of Indian Premier League cricket data.*

> *I've been following IPL since 2015 and wanted to put data behind my cricket intuitions*

---

## Problem Statement

The IPL generates massive amounts of match and ball-by-ball data every season. As a data analyst, the goal of this project is to explore and analyze 10+ years of IPL data to answer real cricketing questions:

- Does winning the toss actually help win the match?
- Which teams and players dominate across seasons?
- How does home ground advantage influence results?
- What does the run-scoring and wicket-taking landscape look like?

This project demonstrates end-to-end EDA — from raw data cleaning to publication-quality visualizations and storytelling.

---

## Folder Structure

```
ipl-eda-analysis/
│
├── data/                   ← Raw CSV files (not pushed to GitHub)
│   ├── matches.csv
│   └── deliveries.csv
│
├── notebooks/
│   └── ipl_eda.ipynb       ← Main analysis notebook
│
├── images/                 ← All exported plots (PNG)
│   ├── toss_analysis.png
│   ├── top_teams.png
│   └── ...
│
├── requirements.txt        ← Python dependencies
├── .gitignore
└── README.md
```

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| pandas | Data wrangling & aggregation |
| numpy | Numerical operations |
| matplotlib | Base plotting |
| seaborn | Statistical visualizations |
| Jupyter Notebook | Interactive analysis environment |

---

## Dataset

- **Source:** [Kaggle — IPL Complete Dataset 2008–2020](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)
- `matches.csv` — 950+ rows, one per match (teams, venue, toss, winner, etc.)
- `deliveries.csv` — 180,000+ rows, one per ball (batsman, bowler, runs, dismissal, etc.)

> Data files are not included in this repo due to size. Download from the Kaggle link above and place in the `data/` folder.

---

## Key Questions Explored

1. Does winning the toss give a match-winning advantage?
2. Which teams have been most consistent across seasons?
3. Who are the top run-scorers and wicket-takers all time?
4. How does home ground advantage vary across venues?
5. What types of dismissals and extras are most common?
6. Who wins the most Player of the Match awards?

---

## Key Insights

- Toss winners go on to win the match only ~52% of the time — barely better than a coin flip
- Mumbai Indians lead all-time wins by a significant margin
- Virat Kohli is the highest run-scorer across all IPL seasons
- Lasith Malinga holds the record for most wickets
- Home advantage is strongest at Wankhede (Mumbai) and Chepauk (Chennai)
- Teams increasingly prefer fielding first after winning the toss (post-2015 trend)

---

## Visualizations Included

- Toss win vs match win correlation (bar + pie)
- Matches per season trend
- Top 10 teams by total wins
- Top 10 run-scorers (all time)
- Top 10 wicket-takers (all time)
- Home advantage heatmap by venue
- Run distribution per ball
- Extra runs breakdown by type
- Player of the Match leaderboard
- Season-wise batting/bowling trends

---

## How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/aryansinghbais/ipl-eda-analysis.git
cd ipl-eda-analysis

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Download dataset from Kaggle and place CSVs in data/

# 5. Launch notebook
jupyter notebook notebooks/ipl_eda.ipynb
```

---

## Connect With Me

**Aryan Singh Bais**  
[GitHub](https://github.com/Aryansingh-B) · [LinkedIn](https://www.linkedin.com/in/aryansinghbais8/) · [Kaggle](https://www.kaggle.com/)