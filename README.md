\# **IPL Cricket Data Analysis (2007–2024)
**


Exploratory data analysis on 17 seasons of IPL ball-by-ball data

(260,000+ deliveries across 1095 matches) using Python, Pandas and Seaborn.


\# **Charts Preview**

\[Top Run-Scorers](images/chart1\_top\_scorers.png)

\[Win Percentage](images/chart4\_win\_pct.png)


\# **Key Findings**

1\. \*\*V Kohli is the all-time top scorer\*\* with 7,987 runs across 17 seasons

2\. \*\*YS Chahal leads wicket-takers\*\* with 209 wickets

3\. \*\*Gujarat Titans are the most dominant team\*\* with a 62.2% win rate

4\. \*\*Winning the toss barely matters\*\* — toss winners win only 50.8% of matches

5\. \*\*Wankhede Stadium produces the highest scores\*\* among all top venues


\# **Dataset**

\- Source: IPL Complete Dataset (Kaggle)

\- Size: 1095 matches, 260,920 ball-by-ball records

\- Files: matches.csv + deliveries.csv (merged on match\_id)


\# **Tech Stack**

\- Python 3.x

\- Pandas — data wrangling, merging, groupby

\- NumPy — numerical operations

\- Seaborn + Matplotlib — 6 visualizations

\- Jupyter Notebook


\# **Analyses Performed**

| # | Analysis | Method |


| 1 | Top 10 run-scorers | groupby + sum + sort |

| 2 | Top 10 wicket-takers | filter + groupby + count |

| 3 | Season-wise run trends | groupby + line chart |

| 4 | Win % by team | value\_counts + normalize |

| 5 | Toss decision impact | crosstab + bar chart |

| 6 | Score distribution by venue | groupby + boxplot |


\# **How to Run**

```bash

git clone https://github.com/yourusername/ipl-analysis.git

cd ipl-analysis

pip install -r requirements.txt

jupyter notebook notebooks/ipl\_eda.ipynb

```


\*Analysis by Parth Nayyar | Mahindra University\*

