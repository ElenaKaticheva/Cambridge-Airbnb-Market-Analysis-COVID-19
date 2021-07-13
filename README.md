## Cambridge Airbnb Market Analysis During COVID-19
The COVID-19 pandemic has disrupted many businesses and industries, including but not limited to the hospitality and aviation industries. The number of lodging reservations have gone down rapidly and significantly since March 2020. This project analyzes Airbnb data from Cambridge, MA and explore and investigate this market in the past 12 months.
Airbnb, Inc. is an American vacation rental online marketplace company accessible to consumers on its website or via an app.
The main objective of this project is to analyze the data to find any trend, seasonality, neighborhood differences, etc. in the market chosen, and to propose indicator(s) to quantify listings ‘performance; as well as to provide recommendations such as additional data sources that can be considered for future analysis.

# Data source and metadata

Data was acquired directly from the Airbnb website (http://insideairbnb.com/get-the-data.html). We worked with monthly detailed listings (listings.csv.gz), calendar (calendar.csv.gz), and review data (reviews.csv.gz) for Cambridge, MA. After data download, it needs to be extracted using any unzip package.
- listings - Detailed listings shows attributes for each of the listings. Some of the attributes used in our analysis are price (continuous), longitude (continuous), latitude (continuous), listing_type (categorical), is_superhost (categorical), neighborhood (categorical), ratings (continuous) among others.
- calendar - Provides details about booking for the next year by listing. Four attributes in total including listing_id (discrete), date (datetime), available (categorical) and price (continuous).
- reviews - Detailed reviews given by the guests. Key attributes include date (datetime), listing_id (discrete), reviewer_id (discrete) and comment (textual).
