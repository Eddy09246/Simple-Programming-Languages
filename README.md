# Stack Overflow Programming Language Trends Analysis

This project analyzes the popularity of programming languages over time using data from Stack Overflow.  The analysis is performed using Python with Pandas and Matplotlib.

## Data Source

The data used in this analysis comes from a StackExchange query ([link](https://data.stackexchange.com/stackoverflow/query/675441/popular-programming-languages-per-over-time-eversql-com)).  You can run this query to obtain your own CSV file.

## Project Structure

The analysis is divided into the following stages:

1. **Data Exploration**: Initial examination of the dataset, including checking dimensions, column names, and basic statistics.

2. **Data Cleaning**: Addressing missing values (NaN) and formatting date values for consistency.

3. **Data Manipulation**: Pivoting the dataset to facilitate analysis of programming language trends over time.

4. **Data Visualization**: Creating various charts to visualize trends, including:
    - Bar chart of total posts per programming language.
    - Line charts to track individual language popularity.
    - Rolling mean plots to visualize smoothed trends.

## Key Insights (Examples)

-  The analysis identifies which programming language has the highest total number of posts across the entire dataset.
-  The visualization allows for clear comparison of the popularity trends of different languages over time.
-  Smoothing the time series data reveals long-term trends in language usage.

## Tools & Libraries

- Python
- Pandas: For data manipulation and analysis.
- Matplotlib: For data visualization.

## Usage

1. Obtain the data from the StackExchange query.
2. Save the data as `QueryResults.csv` in the same directory as the Python script.
3. Run the script to generate the analysis and visualizations.


## Contributing

Contributions to improve this analysis are welcome! Please feel free to open issues or submit pull requests.
