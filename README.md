# Exploratory Data Analysis (EDA) of Restaurant Ratings Dataset

Welcome to the Exploratory Data Analysis (EDA) of a restaurant ratings dataset from Kaggle. This repository contains code and information to help you gain insights into the dataset and understand its characteristics.

## Overview

The provided code is written in Python and uses libraries such as pandas, numpy, matplotlib, and seaborn for data manipulation, visualization, and analysis. The EDA process involves exploring the dataset's features, identifying trends, and uncovering useful information for decision-making.

## Getting Started

1. Clone this repository to your local machine:

```sh
git clone https://github.com/4Pranjal/Restaurant-Ratings-EDA.git
```

2. Navigate to the cloned repository directory:

```sh
cd Restaurant-Ratings-EDA
```

3. Install the required libraries using pip:

```sh
pip install pandas numpy matplotlib seaborn
```

4. Run the provided Jupyter Notebook `EDA_Restaurant_Ratings.ipynb` to execute the EDA code and visualize the results.

## Code Explanation

The Jupyter Notebook performs the following steps:

1. **Data Loading**: Import the required libraries and load the dataset 'zomato.csv'.
2. **Basic Information**: Display the column names, data types, and overall structure of the dataset.
3. **Missing Value Analysis**: Identify missing values in the dataset and visualize their distribution using a heatmap.
4. **Data Enrichment**: Merge additional country information from 'Country-Code.xlsx' to enhance analysis.
5. **Country Distribution**: Visualize the distribution of restaurants among different countries using pie charts.
6. **Aggregate Rating Analysis**: Group and analyze data based on aggregate ratings and rating attributes.
7. **Aggregate Rating Visualization**: Create bar plots to visualize the relationship between ratings and restaurant counts.
8. **Rating Color Analysis**: Analyze the distribution of different rating colors using a count plot.
9. **Zero Query Countries**: Identify countries with no queries (white rating color).
10. **Currency-Country Analysis**: Explore currency usage based on different countries.
11. **Online Delivery Analysis**: Investigate countries with online delivery options.
12. **City Distribution**: Visualize the distribution of restaurants among different cities using a pie chart.

## Results and Insights

- The dataset contains information about restaurants, including their ratings, locations, and online delivery options.
- The majority of the restaurants have not been rated, and the highest ratings are in the range of 2.5 to 3.4.
- UAE and India offer online delivery options.
- Different cities have varying numbers of restaurants, with the top cities being well-represented in the dataset.

## Author's Notes

- Feel free to explore the code and adapt it to your own analysis needs.
- Consider further analysis, such as cuisine-based insights or sentiment analysis of user reviews.
- Experiment with different visualizations to gain a deeper understanding of the data.
- If you encounter any issues or have questions, please feel free to reach out.

## Author

This repository is maintained by 4Pranjal. Feel free to use and modify the code for educational and research purposes.

For any questions or suggestions, you can contact me through my GitHub profile: [@4Pranjal](https://github.com/4Pranjal).

Made with ❤️ by [Pranjal Jain](https://github.com/4Pranjal)
