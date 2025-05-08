
---

## File Descriptions

### Data/
- `player_stats.csv`: Player performance stats for the 2022-2023 NBA season, collected from Basketball Reference.
- `player_salaries.csv`: Salary data for NBA players for the 2022-2023 season, scraped from HoopsHype.
- `team_standings.csv`: Team standings data, including wins and losses for each NBA team.
- `merged_data.csv`: The final dataset that combines player stats, salaries, and team standings, cleaned and ready for analysis.

### Notebooks/
- `01_data_collection.ipynb`: Web scraping player salary data using Selenium. Outputs `player_salaries.csv`.
- `02_data_cleaning.ipynb`: Cleans and merges player stats, salary data, and team standings into a unified dataset.
- `03_exploratory_analysis.ipynb`: Generates visualizations to explore data relationships, including heatmaps and scatter plots.
- `04_ml_analysis.ipynb`: Implements machine learning models (linear regression, logistic regression, k-NN, decision tree).
- `05_final_analysis.ipynb`: Final analysis, model evaluation, and summary of findings.

### Visualizations/
- `heatmap.png`: Displays correlations between key metrics such as points, minutes played, and salary.
- `salary_vs_performance.png`: Visualizes the relationship between player salary and performance index.
- `efficiency_vs_minutes.png`: Shows how playing time impacts player efficiency.
- `model_performance.png`: Comparison of model accuracy across different machine learning methods.

### Report/
- `NBA_Analytics_Report.docx`: The final project report with introduction, data analysis, visualizations, model results, and conclusions.

### Code/
- `scraping_script.py`: Selenium-based web scraping script to collect player salary data.
- `data_processing.py`: Data processing functions for cleaning and merging the datasets.

---

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/NBA-Analytics-2022-2023.git
   cd NBA-Analytics-2022-2023

