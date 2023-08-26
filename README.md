# Cognifyz-Internship-Task-DATA-SCIENCE-
**Problem Statement:**

The problem presented by this dataset is to analyze and gain insights from a collection of restaurant data. The data includes various attributes such as restaurant name, location, cuisine type, average cost for two, rating, and more. The goal is to perform exploratory data analysis and potentially build predictive models to answer questions such as what factors influence restaurant ratings, how different cuisines are received by customers, and whether there are correlations between certain attributes.

**Data Description:**

The dataset consists of information related to various restaurants. The columns present in the dataset are as follows:

- `Restaurant ID`: Unique identifier for each restaurant.
- `Restaurant Name`: Name of the restaurant.
- `Country Code`: Code representing the country where the restaurant is located.
- `City`: City in which the restaurant is situated.
- `Address`: Address of the restaurant.
- `Locality`: Specific locality within the city.
- `Locality Verbose`: Verbose description of the locality.
- `Longitude`: Longitude coordinate of the restaurant's location.
- `Latitude`: Latitude coordinate of the restaurant's location.
- `Cuisines`: Type of cuisines offered by the restaurant.
- `Average Cost for two`: Estimated cost for two people to dine at the restaurant.
- `Currency`: Currency used for cost values.
- `Has Table Booking`: Whether the restaurant accepts table bookings (Yes/No).
- `Has Online Delivery`: Whether the restaurant offers online delivery (Yes/No).
- `Is delivering now`: Whether the restaurant is currently delivering orders (Yes/No).
- `Switch to order menu`: N/A for this dataset.
- `Price range`: Range indicating the affordability of the restaurant.
- `Aggregate rating`: Average rating of the restaurant.
- `Rating color`: Color representation of the rating.
- `Rating text`: Textual description of the rating (e.g., Excellent, Very Good, etc.).
- `Votes`: Number of votes the restaurant has received.

**Data Processing:**

Understanding and Cleaning the data

**Data Exploration:**

Analyze the data through Visualization

**Model Performed:**

Linear Regression, Decision Tree, Random Forest

**Conclusion:**

After analyzing the dataset, several conclusions can be drawn:

1. **Rating Distribution:** The distribution of ratings varies, with some restaurants having high ratings and others having lower ratings.

2. **Cuisine and Ratings:** Certain cuisines tend to receive higher ratings than others. Customers' preferences for different cuisines impact the average ratings of restaurants.

3. **City-wise Distribution:** Restaurants are spread across different cities, with varying densities. This could reflect population density and urbanization.

4. **Correlation Analysis:** There is a mild correlation between certain attributes like the cost for two and the rating, as well as potential correlations between location (latitude, longitude) and ratings.

5. **Popularity vs. Ratings:** The number of votes a restaurant receives seems to impact its rating. More popular restaurants tend to have higher ratings.

6. **Online Services and Ratings:** Restaurants offering online delivery or table booking tend to have higher ratings, suggesting a correlation between these features and customer satisfaction.

7. **Price Range and Ratings:** Restaurants with moderate price ranges (neither too cheap nor too expensive) tend to receive higher ratings.

8. **Visualization:** Visualizations such as histograms, bar plots, and box plots helped depict the distribution of ratings, cuisines, and other variables, aiding in understanding patterns.

**ML Classification:**

Random forest and decision tree is the best performing model out of all models.

Linear regression is the worst performing model for our dataset
