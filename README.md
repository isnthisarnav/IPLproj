# IPL Data Analysis (2008–2025)
Exploratory data analysis on 1100+ IPL matches to uncover what actually decides a match outcome.

## Questions Answered
### 1. Does the toss decide the match winner?
- Toss winner won **50.8%** of matches
- Conclusion: **No** — toss has virtually no impact, it's essentially a coin flip

### 2. Does home ground decide the match winner?
- Home team won **52.6%** of matches
- Conclusion: **No significant advantage** — home ground plays a minor role at best
- Note: A large portion of IPL matches are played at neutral venues (UAE, South Africa)

### 3. Top performing teams by season
- Win counts for all teams across every season (2008–2025)
- Top 5 teams per season visualized
- All-time rankings by total wins

### 4. Are scores increasing across seasons?
- Average combined match score (both innings) tracked per season
- Line chart showing scoring trends from 2008 to 2025

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset

Ball-by-ball IPL data from 2008 to 2025.

Download the dataset from Kaggle: [IPL Ball-by-Ball Dataset]https://www.kaggle.com/datasets/chaitu20/ipl-dataset2008-2025
> The dataset is not included in this repo due to size constraints (>100MB). Download and place the CSV in the same directory as the notebook before running.


## How to Run
1. Clone the repo
2. Download the dataset from Kaggle (link above)
3. Open `IPL_Analysis.ipynb` in Jupyter Notebook or Google Colab
4. Place the CSV in the same directory
5. Run all cells top to bottom

---

## Key Findings

| Question | Finding |
|---|---|
| Does toss matter? | No — 50.8% win rate, essentially random |
| Does home ground matter? | Slightly — 52.6% win rate, not significant |
| Most successful team? | Mumbai Indians — most wins all-time |
| Are scores increasing? | Yes — average match scores have trended upward over the years |

---

##  Author

**Arnav Mhatre**  
B.E. Mathematics & Computing — BITS Pilani Hyderabad  
[LinkedIn](https://linkedin/in/arnav-mhatre.com) | [GitHub](https://github.com/isnthisarnav)
