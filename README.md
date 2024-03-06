# Video Game Sales Analysis

## Project Overview
This project involves an analytical exploration of a video game sales dataset, focusing on sales trends, influential game publishers, and platform-specific bestsellers. The analysis aims to uncover insights into the global distribution of video game sales, identify leading publishers, and understand market preferences across different geographic regions and platforms.

## Dataset
The dataset comprises historical sales data of video games, including the following attributes:

- `Name`: The name of the video game.
- `Platform`: The platform on which the game was released (e.g., PC, PS4, XBox).
- `Year`: The release year of the game.
- `Genre`: The genre of the game (e.g., Action, Adventure, Sports).
- `Publisher`: The publisher of the game.
- `NA_Sales`: Sales in North America (in millions).
- `EU_Sales`: Sales in Europe (in millions).
- `JP_Sales`: Sales in Japan (in millions).
- `Other_Sales`: Sales in other regions (in millions).
- `Global_Sales`: Total global sales (in millions).

## Data Preprocessing
The dataset is initially loaded into a Pandas DataFrame for cleaning and preprocessing. This step involves handling missing values to ensure data quality.

## Exploratory Data Analysis (EDA)
A comprehensive EDA is conducted to visualize sales distributions and trends across different dimensions, including publishers, platforms, and geographical regions. Key analyses include:

- **Nintendo Global Sales**: Summation of global sales for games published by Nintendo, providing insight into the market impact of one of the industry's major players.
- **Data Temporal Coverage**: Identification of the range of years covered in the dataset, establishing the temporal context of the sales data.
- **Publisher Sales Analysis**: Aggregation of global sales by publisher to rank top-performing publishers and visualize their market share using bar plots.
- **Sales Trends Over Decades**: Examination of sales trends over decades, enabling the identification of shifts in market dominance among publishers and the evolution of consumer preferences.

## Feature Engineering
The dataset is enriched with derived features to facilitate more in-depth analysis:

- **Decade**: The release year is transformed into a categorical feature representing the decade, aiding in the examination of sales trends over longer time periods.

## Regional Sales Analysis
Sales data are analyzed across different geographic regions to identify the largest markets and understand regional preferences. This involves:

- **Regional Sales Aggregation**: Calculation of total sales per region, followed by comparative analysis to ascertain the largest markets for video games.
- **Decade-wise Regional Trends**: Exploration of how sales in different regions have evolved over the decades, highlighting shifts in market dynamics.

## Best-selling Games and Platforms
Focused analysis on identifying best-selling games and the most successful platforms, including:

- **Top-selling Games**: A ranking of games based on global sales to pinpoint the highest-grossing titles.
- **Platform Bestsellers**: Determination of the best-selling game for each platform, offering insights into platform-specific consumer preferences.

## Visualization
Data visualizations play a crucial role in this analysis, with the use of:

- **Bar Plots**: To represent sales figures and rankings in a clear, comparative format.
- **Line Plots**: To illustrate sales trends over time, particularly for decade-wise analysis.
- **Scatter Plots**: To explore correlations between different sales regions or attributes.

## Tools and Libraries
The analysis is conducted using Python, with the following key libraries:

- `pandas`: For data manipulation and analysis.
- `matplotlib.pyplot` and `seaborn`: For data visualization.
- `numpy`: For numerical computations.
- `glob` and `re`: For file manipulation and regular expressions, respectively.

## Usage
To replicate this analysis, ensure the `vgsales.csv` dataset is located within the `data` directory. Run the Jupyter Notebook to execute the code blocks sequentially, from data loading to visualization.
