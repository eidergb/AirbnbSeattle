# Seattle Airbnb Data Analysis

## Motivation
This project aims to analyze the Airbnb listings in Seattle to uncover insights about the rental market. By examining various datasets, we can understand the distribution of listings, pricing trends, availability, and other factors that influence the Airbnb market in Seattle.

## Libraries Used
The following libraries were used in this project:
- `numpy`: For numerical computations.
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating visualizations.
- `seaborn`: For advanced visualizations.
- `scikit-learn`: For machine learning models and evaluation metrics.

## Repository Files
- `Proyecto1_Seattle_Airbnb.ipynb`: The Jupyter notebook containing all the code and analysis for this project.
- `Airbnb_Seattle/listings.csv`: The dataset containing detailed information about each Airbnb listing in Seattle.
- `Airbnb_Seattle/calendar.csv`: The dataset containing information about the availability and pricing of the listings over time.

## Summary of Analysis
1. **Listings**:
    - A unique count of Airbnb listings.
    - Count of the number of available listings per month/year
2. **Reservations Period**:
    - The analysis covers the period from the minimum to the maximum date available in the calendar dataset.
3. **Missing Data Analysis**:
    - The percentage of missing values was calculated, and the analysis of some os the NaN fields was done to see how to fill them.
4. **Price Analysis**:
    - The maximum, minimum and average of the price was calculated. 
    - The price distribution in a graph is drawn. 
    - The average price group by day of the week was calculated.
    - The average price group by month and year was calculated.
    - The average price by neighbourhood was calculated.
    - The average price by property type was calculated.
    - The difference in the average price, due to the presence of amenities was calculated.
    - Correlation between price and other colums was calculated.

    Key findings:
    - A certain percentage of `price` and `available` columns have missing values.
    - The percentage of missing `price` values is different when the listing is available compared to when it is not.

## Results
- The analysis revealed important insights into the distribution of Airbnb listings in Seattle.
- It highlighted the periods with the highest availability and pricing trends over time.
- A clear relationship between listing availability and price was observed.
- The neighborhood and property type also have a relationship with the price.
- There are amenities that add value and increase the price.

## Acknowledgments
I would like to acknowledge the sources of the datasets and the open-source libraries that made this analysis possible.

- The Airbnb dataset for Seattle.
- The contributors to the `numpy`, `pandas`, `matplotlib`, `seaborn`, and `scikit-learn` libraries.
