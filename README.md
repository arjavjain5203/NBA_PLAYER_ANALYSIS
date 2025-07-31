# NBA Player Analysis

This project analyzes NBA player statistics from a raw CSV dataset, cleans the data, ranks top performers, and visualizes shooting percentages.

## Project Structure

- `main.ipynb`: Jupyter notebook containing all analysis code.
- `nba_dirty_stats.csv`: Raw player statistics with missing and invalid entries.
- `top_performers.csv`: Cleaned and sorted list of top NBA performers.
- `readme`: Project documentation (this file).

## Workflow

1. **Data Cleaning**  
   The notebook loads `nba_dirty_stats.csv`, removes rows with missing or invalid data, and creates a clean DataFrame.

2. **Ranking Top Performers**  
   Players are sorted by Points Per Game (PPG) in descending order to identify top performers.

3. **Visualization**  
   Shooting percentages (FG%, 3P%, FT%) for top players are visualized using bar charts.

4. **Exporting Results**  
   The sorted and cleaned data is exported to `top_performers.csv`.

## Usage

Open `main.ipynb` in Jupyter or VS Code and run the cells sequentially to reproduce the analysis and plots.

## Requirements

- Python 3
- pandas
- numpy
- matplotlib

Install dependencies with:

```sh
pip install pandas numpy matplotlib
```
