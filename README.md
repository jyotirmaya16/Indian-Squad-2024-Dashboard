# Indian Squad 2024 Dashboard
### Preview 
#### Link to site: [click her👆🏻](https://public.tableau.com/app/profile/jyotirmaya.maharana/viz/indiasquaddashboard/Dashboard1)

![ipl preview 1](https://github.com/jyotirmaya16/Indian-Squad-2024-Dashboard/assets/146333462/d0a2aa09-ea8e-4f0a-87dc-cdbe8c385a9a)

## Project Overview
This project visualizes the IPL statistics of Indian players who are nominated for the T20 World Cup 2024. The dashboard is created using Tableau and provides dynamic insights into player performance through various KPIs and charts.

The dashboard includes:
- Dynamic player images that change based on the selected player.
- KPIs for batting and bowling statistics.
- Visualizations for the number of 4s, 6s, not outs (NO), matches played, and more.
- Line charts comparing various metrics like runs made, strike rate, wickets taken, and economy rate.

## Data Preparation

1. **Data Source:** The dataset was downloaded from Kaggle and imported into VS Code for data cleaning in Python.
2. **Data Cleaning:**
    - Converted mixed columns (integers and strings) to integers by removing strings using regular expressions.
    - Removed unnecessary columns.
    - Filtered data to include only players participating in the 2024 T20 World Cup.

## Tableau Visualizations

### KPIs
- **Batting:**
  - Highest Runs
  - Number of Centuries
  - Number of Half Centuries
  - Number of Catches Taken
- **Bowling:**
  - Average Economy Rate
  - Number of Wickets Taken

### Charts
1. **Bar Charts:**
   - Number of 4s hit
   - Number of 6s hit
   - Number of times not out (NO)
   - Number of matches played

2. **Line and Dot Dual Axis Chart:**
   - Balls Bowled vs. Economy Rate

3. **Line Chart:**
   - Runs Made
   - Strike Rate
   - Number of Wickets Taken
   - Economy Rate

## Dynamic Features
- The player image dynamically changes based on the selected player from the filter.
- All KPIs and charts are filterable by player name and year.

## Usage

### Prerequisites
- Tableau Desktop or Tableau Public
- Python (for data cleaning)
- Required Python libraries: `pandas`, `numpy`,`re`

## License

This project is licensed under the MIT License.
