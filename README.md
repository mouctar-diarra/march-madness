# march-madness
This repository consolidates code to examine and predict mens college basketball wins and culminates in a prediction of a winning NCAA March Madness bracket. I created this as a fun way to stay engaged with basketball, deepen my data science skills, and improve my chances in lighthearted office bracket pools.

---

## Project Overview

This repository contains two Jupyter notebooks:  

### Key Factors in College Basketball Wins
- Builds and evaluates a **Random Forest model** to uncover the most important factors influencing the **win/loss percentage** of men’s college basketball teams.
- Identifies key statistical features (e.g., offensive/defensive metrics) that correlate with team success.
- Uses web-scraped data from [sports-reference.com](https://www.sports-reference.com/cbb/).

### Predicting March Madness Wins
- Builds and evaluates a **Logistic Regression model** to predict **which team will win** a given matchup in the NCAA March Madness tournament.
- Uses the findings from the first notebook to engineer features and improve predictions.
- Also relies on web-scraped data from [sports-reference.com](https://www.sports-reference.com/cbb/).
- **Note:** If you use this notebook to predict brackets for seasons other than 2025, you’ll need to manually adjust certain team mappings in **Step 2** and **Step 7**.

---

## Data Source
Both notebooks rely on publicly available, web-scraped statistics from:  
[sports-reference.com/cbb](https://www.sports-reference.com/cbb/)  

This includes regular season and tournament performance data for NCAA Division I men’s teams.
