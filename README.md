# Exploratory Data Analysis (EDA) of "Restaurant Ratings" Dataset

This repository contains code for performing Exploratory Data Analysis (EDA) on a restaurant ratings dataset from Kaggle. The code is written in Python and uses libraries such as pandas, numpy, matplotlib, and seaborn for data manipulation, visualization, and analysis.

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

4. Run the provided Jupyter Notebook to execute the EDA code.

## Code Explanation

The provided Jupyter Notebook `EDA_Restaurant_Ratings.ipynb` performs the following steps:

1. Import necessary libraries: pandas, numpy, matplotlib, and seaborn.
2. Load the dataset from 'zomato.csv' using pandas.
3. Display basic information about the dataset, such as column names and data types.
4. Check for missing values in the dataset and visualize them using a heatmap.
5. Merge additional country information from 'Country-Code.xlsx' into the main dataset.
6. Analyze the distribution of restaurant data among different countries using pie charts.
7. Group and aggregate data based on aggregate rating, rating color, and rating text.
8. Visualize the relationship between aggregate ratings and the number of restaurants using bar plots.
9. Create a count plot to visualize the distribution of different rating colors.
10. Identify countries with zero queries (white rating color).
11. Analyze relationships between countries, currencies, and online delivery options.
12. Visualize the distribution of restaurants among different cities using a pie chart.

## Credits

This repository is maintained by 4Pranjal. Feel free to use and modify the code for educational and research purposes.

For any questions or suggestions, you can contact me through my GitHub profile: [@4Pranjal](https://github.com/4Pranjal).

Made with ❤️ by [Pranjal Jain](https://github.com/4Pranjal)
