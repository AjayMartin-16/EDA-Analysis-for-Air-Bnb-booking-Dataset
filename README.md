# Airbnb Exploratory Data Analysis (EDA)

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on an Airbnb dataset containing approximately 49,000 listings in New York City from 2019. The dataset consists of 16 variables, including listing details such as price, location, room type, host information, and guest reviews. The objective is to uncover insights that can help optimize Airbnb's pricing, property distribution, and marketing strategies to increase bookings and improve customer satisfaction.

## Dataset Used
- **Dataset Name:** Airbnb NYC 2019
- **Source:** Provided by AlmaBetter
- **Size:** ~49,000 rows and 16 columns
- **Key Features:**
  - Listing details (price, room type, location, availability)
  - Host information (host name, host ID, number of listings)
  - Guest engagement (reviews per month, number of reviews, last review date)

## Objectives
- Identify pricing trends based on location, property type, and amenities.
- Analyze guest engagement through reviews and availability.
- Discover demand patterns across different neighborhoods.
- Provide actionable insights for Airbnb's business strategy.

## Methodology
### 1. Data Preprocessing
- Handled missing values in `reviews_per_month` and `last_review` columns.
- Dropped duplicates to ensure data quality.
- Standardized numerical values for price analysis.
- Identified and removed outliers in extreme price values.

### 2. Exploratory Data Analysis (EDA)
- **Univariate Analysis:** Distribution of price, reviews, and availability.
- **Bivariate Analysis:** Correlations between numerical variables and categorical variables.
- **Multivariate Analysis:** Pair plots and correlation heatmaps to identify complex relationships.
- **Visualization Techniques:**
  - Count plots for room types and neighborhood distributions.
  - Box plots for price variations across room types and boroughs.
  - Heatmaps for correlation between price, availability, and reviews.
  - WordCloud for frequently used words in customer reviews.

## Key Findings
- **Price Trends:**
  - Manhattan listings have the highest average price, while Staten Island is the most affordable.
  - Entire homes/apartments are the most expensive, while private/shared rooms are cheaper.
- **Guest Engagement:**
  - Listings with lower prices receive more reviews, indicating higher guest turnover.
  - Private rooms and shared spaces tend to have more frequent reviews compared to entire homes.
- **Neighborhood Analysis:**
  - Manhattan and Brooklyn have the most listings, while Staten Island has the least.
  - High engagement levels in Brooklyn and Queens indicate opportunities for expansion.
- **Availability Trends:**
  - Hotel rooms and entire homes tend to have high availability, while private rooms are more frequently booked.
  - Listings with high availability in less popular boroughs suggest lower demand, requiring targeted marketing strategies.

## Tools & Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, NLTK, WordCloud
- **Visualization:** Tableau (for dashboard insights)

## Business Insights & Recommendations
- **Dynamic Pricing:** Implement AI-driven pricing models to optimize rental prices based on demand, location, and seasonality.
- **Marketing Expansion:** Promote listings in less popular boroughs (Queens, Bronx) to attract budget-conscious travelers.
- **Host Engagement Strategies:** Encourage hosts to lower minimum stay requirements and improve listing quality for higher guest engagement.
- **Targeted Promotions:** Offer discounts and incentives for listings in areas with low demand to improve occupancy rates.

## Future Enhancements
- Use **machine learning models** to predict optimal pricing strategies.
- Implement **geospatial analysis** to further understand listing distribution.
- Apply **sentiment analysis** on guest reviews for deeper insights into customer preferences.

## Author
B. Ajay Martin Ferdinand

## Acknowledgments
- Data provided by AlmaBetter.
- Thanks to the data science community for insights and guidance.


