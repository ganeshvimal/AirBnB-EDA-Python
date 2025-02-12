# Executive Summary
## Introduction
This project performs Exploratory Data Analysis (EDA) to analyze Airbnb rental listings using Python, Pandas, NumPy, Matplotlib and Seaborn. The goal is to extract meaningful insights, visualize patterns, and understand factors influencing Airbnb Market

## Key Objectives
- Perform data cleaning and preprocessing to handle missing values and inconsistencies
- Conduct exploratory data analysis (EDA) to visualize distributions, trends, and correlations
- Use NumPy for numerical operations, including statistical calculations and data transformations
- Apply visualization techniques (histograms, scatter plots, word clouds, etc.) to showcase insights
- Identify price trends, availability patterns, and potential outliers affecting rental pricing
## Dataset
The dataset contains 20,765 entries and 22 features, including:
- id: Unique identifier for each listing
- name: Title of the Airbnb listing
- host_name: Name of the host
- neighborhood_group: Group (borough) where the listing is located
- latitude/longitude: Geolocation of listings
- price: Nightly rental price
- room_type: Type of accommodation (e.g., entire home, private room)
- reviews_per_month: Average monthly reviews for the listing
- availability_365: Number of available days in the year

## Data Cleaning 
The **null values** in the price, neighborhood, and beds columns were fixed. Also **duplicates** were removed from the dataset. Additionally, **outliers** were managed by capping listings with prices above $1,000 to prevent them from skewing visualizations and analysis. This ensures more accurate and reliable insights when examining trends in the dataset. Also the data type format of id and hostid was changed

## Exploratory Data Analysis (EDA) Key Findings -
- Price Variability: Prices fluctuate across different months, with peaks in February, April and July
- Availability Trends: A significant number of properties are either available for a short period or all year round
- Common Listing Keywords: Keywords like "bedroom," "rental," "bath," and "New York" frequently appear in listing titles
- Price Distribution: Many listings are concentrated in lower price ranges, but some expensive outliers exist
- Correlation Analysis: Certain features, such as availability and price, show weak correlations

## Technologies Used
1. Python (Pandas, NumPy, Matplotlib, Seaborn, WordCloud)
2. Jupyter Notebook for interactive data analysis

## Recommendations
- **For Guests**
  1. Choose listings with high availability and positive reviews for a better experience
  2. Private rooms in Brooklyn provide a budget-friendly alternative to Manhattan
- **For Hosts**
  1. Improve availability and review response rates to attract more bookings
  2. Manage pricing effectively to compete within the borough's market
     
## Conclusion 
This project provides valuable insights into the New York Airbnb market, enabling both guests and hosts to make informed decisions. Through exploratory data analysis (EDA), we uncovered key trends and developed actionable recommendations. Future enhancements could include advanced analytics and predictive modeling to further refine the findings.








