# AirBnB-Market-Insights

## Project Description

This project analyzes Airbnb listings data in Paris to explore various aspects such as price trends, neighborhood pricing, and the impact of regulations on new hosts. The analysis involves data cleaning, transformation, and visualization to derive meaningful insights from the dataset.

### Key Tasks

1. **Data Import and Preparation**
   - Imported the `Listings.csv` file.
   - Casted any date columns to datetime format.
   - Filtered data to include only listings in Paris and retained the relevant columns: `host since`, `neighbourhood`, `city`, `accommodates`, and `price`.

2. **Data Quality Analysis**
   - Checked for missing values in the Paris listings data.
   - Calculated the minimum, maximum, and average for each numeric field.

3. **Grouped Data Tables**
   - Created a table named `paris_listings_neighbourhood` that groups listings by `neighbourhood` and calculates the mean price (sorted from low to high).
   - Created a table named `paris_listings_accommodations` that filters down to the most expensive neighborhood, groups by the `accommodates` column, and adds the mean price for each value of `accommodates` (sorted from low to high).
   - Created a table named `paris_listings_over_time` that groups data by the year of `host since`, calculating the average price and counting the number of new hosts.

4. **Data Visualization**
   - Created a horizontal bar chart of the average price by neighborhood in Paris, including titles and properly labeled axes.
   - Created a horizontal bar chart of the average price by `accommodates` in the most expensive neighborhood, with titles and labeled axes.
   - Developed two line charts: one showing the count of new hosts over time and another showing average price trends, with the y-axis limited to 0, titles, and labeled axes.

5. **Insights**
   - Provided insights on the impact of the 2015 regulations on new hosts and pricing based on the findings.

## Project Link

You can view and interact with the analysis in this [Google Colab notebook](https://colab.research.google.com/drive/1sjLGydKt4mui3cIA5Bfu1lTOiXfbcetl?usp=sharing).
