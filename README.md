# IAIP — Indian Premier League Analysis & Insights Project

> Exploratory Data Analysis on the Indian Premier League (IPL) dataset using Python.  
> EDA on Sports Data | Tool: Python (pandas, matplotlib, seaborn)

---

## Project Overview

This project performs a comprehensive Exploratory Data Analysis (EDA) on the IPL dataset covering **12 seasons (2008–2019)**, analyzing **756 matches** and **179,078 deliveries** to uncover:

- The most successful teams and their winning patterns
- Top-performing batsmen and bowlers
- Key factors contributing to wins and losses
- Data-driven endorsement recommendations for brands

---

## Dataset

- **Source:** [IPL Dataset](https://bit.ly/34SRn3b)
- **Files used:**
  - `matches.csv` — match-level data (756 rows, 18 columns)
  - `deliveries.csv` — ball-by-ball data (179,078 rows, 21 columns)

---

## Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python 3 | Core programming language |
| pandas | Data loading, cleaning, aggregation |
| matplotlib | Charts and visualizations |
| seaborn | Statistical plots |
| Jupyter Notebook | Interactive analysis environment |

---

## Key Findings

### Team Success
- **Mumbai Indians** lead with **109 total wins** across all seasons
- **Chennai Super Kings** have the highest win percentage at **61%**
- Teams batting second (chasing) win **55%** of matches — field first if you win the toss

### Top Batsmen
| Player | Total Runs | Strike Rate |
|--------|-----------|-------------|
| V Kohli | 5,434 | 130.0 |
| SK Raina | 5,415 | 136.7 |
| RG Sharma | 4,914 | 130.5 |
| DA Warner | 4,741 | 140.8 |
| CH Gayle | 4,560 | 153.0 |

### Top Bowlers
| Player | Wickets | Economy |
|--------|---------|---------|
| SL Malinga | 170 | 7.14 |
| A Mishra | 156 | 7.35 |
| Harbhajan Singh | 150 | 7.10 |
| PP Chawla | 149 | 8.02 |
| DJ Bravo | 147 | 8.54 |

### Win Factors
- Toss winners go on to win the match **52%** of the time
- **406 matches** won by wickets (batting 2nd) vs **337** by runs (batting 1st)
- Eden Gardens (77), M Chinnaswamy (73), and Wankhede (73) are the most active venues

---

## Endorsement Recommendations

### Tier 1 — Marquee
| Player | Why |
|--------|-----|
| **Virat Kohli** | Most runs (5,434), highest recognition, universal appeal |
| **MS Dhoni** | 17 POM awards, CSK captain, most trusted cricket brand |
| **AB de Villiers** | 20 POM awards, SR 152+ — unique lifestyle brand fit |

### Tier 2 — High Value
| Player/Team | Why |
|------------|-----|
| **Chris Gayle** | Most POM awards (21), SR 153 — youth & energy brands |
| **Rohit Sharma** | MI captain, 4,914 runs — premium segment brands |
| **Mumbai Indians** | 109 wins, most followed franchise — widest visibility |

---

## Project Structure

```
IAIP/
├── matches.csv              # Match-level dataset
├── deliveries.csv           # Ball-by-ball dataset
├── ipl_eda.ipynb            # Jupyter notebook with full analysis
├── ipl_eda.py               # Python script version
├── README.md                # Project documentation
└── charts/
    ├── team_wins.png
    ├── top_batsmen.png
    ├── top_bowlers.png
    └── endorsements.png
```

---

## How to Run

```bash
# 1. Clone the repository
git clone https://github.com/YOUR-USERNAME/IAIP.git
cd IAIP

# 2. Install dependencies
pip install pandas matplotlib seaborn jupyter

# 3. Run Jupyter Notebook
jupyter notebook ipl_eda.ipynb

# OR run Python script directly
python ipl_eda.py
```

---

## Author

**Yamini Puppala**  
Data Science Intern | Task 2 — EDA on Sports Data

---

## License

This project is for educational purposes only. Dataset credits to the original providers.
