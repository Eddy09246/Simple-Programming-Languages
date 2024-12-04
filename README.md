# Stack Overflow Programming Language Trends Analysis

This project analyzes the popularity of programming languages over time using data from Stack Overflow.  The analysis is performed using Python with Pandas and Matplotlib.

## Data Source

The data used in this analysis comes from a StackExchange query ([link](https://data.stackexchange.com/stackoverflow/query/675441/popular-programming-languages-per-over-time-eversql-com)).  You can run this query to obtain your own CSV file.

## Project Structure

The analysis is divided into the following stages:

1. **Data Exploration**: Initial examination of the dataset, including checking dimensions, column names, and basic statistics.

2. **Data Cleaning**: Addressing missing values (NaN) and formatting date values for consistency.

3. **Data Manipulation**: The dataset is reshaped using the pivot function. This transformation creates a table where each row corresponds to a date and each column represents a programming language. The values represent the number of posts for that language on that date.

4. **Data Visualization**: Creating various charts to visualize trends, including:
    - Bar chart of total posts per programming language.
    - Line charts to track individual language popularity.
    - Rolling mean plots to visualize smoothed trends.

## Key Insights (Examples)

-  The analysis identifies which programming language has the highest total number of posts across the entire dataset.
-  The visualization allows for clear comparison of the popularity trends of different languages over time.
-  Smoothing the time series data reveals long-term trends in language usage.

## Popularity of Python

While the provided data spans several years, the visualization strongly suggests Python's rise in popularity around 2019 and beyond. Although the dataset itself doesn't pinpoint a definitive moment, the project's visualization tools allow for an in-depth analysis and easy confirmation of this pattern within the data.  The rolling mean visualization especially helps to smooth out short-term noise and more clearly reveals long-term upward trends.  The provided visualization tools can be readily applied to other languages, making it easy to compare their relative popularity with that of Python.

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



