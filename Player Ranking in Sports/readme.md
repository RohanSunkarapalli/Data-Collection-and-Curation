# Data Analysis and Visualization of Cricket's T20-International Format Batting Records

## Overview

This repository contains Python code to analyze and visualize rank of the batsmen.

## Instructions

#### Libraries Used:
- pandas
- matplotlib.pyplot
- seaborn

#### Files
- `t20I.csv`: For the assignment, we selected players batting records from the game of Cricket in the T20 International format. The data is acquired from Cricinfo.com (https://www.espncricinfo.com/records/most-runs-in-career-282827) and saved in csv format.
- `t20I_batting.ipynb`: Python Jupyter notebook for analysis and ranking the players.

#### Execution:
- Run `t20I_batting.ipynb` to complete the analysis and rank the players in one weighted ranking system combining three criteria: average score, strike rate, and proportion of runs in boundaries.

#### Analysis and visualization
1. Read data from `t20I_batting.csv` file
2. Perform data cleanup
3. Consider players who scored more than 1000 career runs in the format.
4. Ranked players on three criteria's: average score, strike rate, and proportion of runs in boundaries.
5. Estimated player weighted rank with 0.5, 0.4, and 0.1 ratio for each rank, respectively.
6. Visualize individual rank (3 metrics) and weighted rank for top-20 players.
7. Discussed limitation of the ranking system.


## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests. Please follow coding standards and provide clear documentation for any changes.

## License

This project is licensed under the [MIT License] (LICENSE).
