

# IPL 2022 Auction Analysis

## Overview

This project analyzes the player auction data for the 2022 Indian Premier League (IPL). It includes information about the players, their base prices, types (batsman, bowler, all-rounder, wicketkeeper), costs in ₹ (CR.) and $ (000), their 2021 squad, and the team they were drafted to in 2022.

## Project Structure

The project is organized as follows:

- `ipl2022.csv`: The dataset containing the auction data.
- `ipl_analysis.ipynb`: The Jupyter Notebook with the Python code for data analysis.
- `README.md`: This README file.

## Requirements

To run the Jupyter Notebook, you'll need the following Python libraries installed:

- pandas
- numpy
- seaborn
- matplotlib

You can install these libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib
```

## Usage

1. Clone the repository:

```bash
git clone <repository_url>
```

2. Navigate to the project directory:

```bash
cd ipl-2022-auction-analysis
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook ipl_analysis.ipynb
```

4. Execute the cells in the Notebook to perform the analysis.

## Data Cleaning

The project involves cleaning the dataset by handling missing values and converting data types. Key data cleaning steps include:

- Dropping the 'Unnamed: 0' column.
- Filling missing values in 'COST IN ₹ (CR.)', 'Cost IN $ (000)', and '2021 Squad'.
- Categorizing base prices and extracting numeric values.

## Data Analysis

The Notebook provides various insights into the IPL 2022 auction, such as:

- Number of players retained and bought by each team.
- Types of players participating (e.g., all-rounders, bowlers, batsmen, wicketkeepers).
- Visualization of sold and unsold players.
- Players bought by each team.
- Highest amount spent on a single player by each team.
- Top players in each category (batsman, bowler, all-rounder).

## Conclusion

This project offers a comprehensive analysis of the IPL 2022 player auction, providing valuable insights into player distribution, team strategies, and the overall auction landscape.

---

You can customize this README file to include any additional information or details specific to your project.
