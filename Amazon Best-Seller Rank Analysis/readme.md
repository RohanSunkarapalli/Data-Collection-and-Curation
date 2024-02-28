# Data Analysis and Visualization of Book Sales Data

## Overview

This repository contains Python code for (1) scraping books written by Steven S. Skiena on Amazon and (2) analysis of book ranking and recommendation to a friend as a gift.

## Instructions

#### Libraries Used:
- pandas
- matplotlib.pyplot
- seaborn
- beautifulsoup
- selenium

#### Files:
- `data_scaper.ipynb`: Python Jupyter notebook to scrape Skiena's books from his webpage on Amazon.
- `steven_skiena_books_amazon.csv`: CSV file containing data on Skiena's books and their best-seller rank from amazon.in (not used for analysis)
- `Steven_S_Skiena_books.csv`: CSV file containing data on Skiena's books and their attributes from amazon.com (used for the analysis by manually entering the data)
- `amazon_books.ipynb`: Python Jupyter notebook for analyzing and visualizing best-seller ranks.

#### Execution:
1. Ensure you have the necessary libraries installed: `pandas`, `matplotlib`, `seaborn`, `BeautifulSoup`, `Selenium`
2. Run `data_scaper.py` notebook to scrape data from Amazon.
3. Run `amazon_books.ipnpy` for analysis and visualization.

## Details

#### Web Scraping
Utilized BeautifulSoup and Seaborn to scrape attributes of the author's published books listed on Amazon. We have 8 books in the dataset with attributes including Amazon's rank, average user rating, number of users rated, publication date, and price for hardcover, kindle edition, and paperback. We utilize the relative path of each attribute. The data is saved in csv format for analysis and visualization. However, the data is not used for analysis because it is gathered from amazon.in and the book ranking is different from Amazon.com. We were not able to scrape the data from Amazon.com because of the security issues disallowed from scraping data. 

#### Analysis and visualization
1. Read book data from `Steven_S_Skiena_books.csv`
2. Perform data cleanup. It includes converting string date to pandas date format. 
3. Visualized best seller rank and user rating over time on individual bar and line plots, respectively.
4. Visualized inverse relationship between estimated best seller rank and weighted average rating.
5. Recommended a book for purchase based on the high rating on aggregate across the platforms and ranked low on Amazon.
6. Outputs the recommended book with justification.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests. Please follow coding standards and provide clear documentation for any changes.

## License

This project is licensed under the [MIT License] (LICENSE).
