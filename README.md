 <h1 align = "center"> AIRBNB DATA ANALYSIS (EDA)</h1>
<p align="center">  
  <img width="600" height=" 400" src="https://media.istockphoto.com/id/1045287634/photo/airbnb-amazon-ebay-news-and-other-apps-on-iphone-screen.jpg?s=612x612&w=0&k=20&c=f0e0WqGf9KZ12Cxg-Eg383aKuzbyamYsJWrkchWQ75w=">
</p>

Description of the AIRBNB Dataset :
-
Airbnb is a popular online marketplace and hospitality service that enables people to list, discover, and book accommodations around the world. Founded in 2008 by Brian Chesky, Joe Gebbia, and Nathan Blecharczyk, Airbnb has revolutionized the way people travel by providing a platform for individuals to rent out their homes, apartments, or spare rooms to guests seeking lodging.

Here's an introduction to some key aspects of Airbnb data:

1. **Listing Data**: This includes information about the properties available for rent on Airbnb. It typically contains details such as the property type (e.g., entire home, private room, shared room), location, amenities, pricing, availability, and host information.

2. **Booking Data**: Booking data encompasses information about reservations made by guests. It includes details like the dates of stay, guest information, total cost, and any special requests or requirements.

3. **Host Data**: Host data provides information about individuals who list properties on Airbnb. This may include details about the host's profile, reviews from previous guests, response rates, and any additional services or experiences offered by the host.

4. **Guest Data**: Guest data consists of information about the individuals who book accommodations through Airbnb. This may include demographic information, booking history, reviews left for hosts, and preferences for travel experiences.

5. **Reviews and Ratings**: Airbnb collects reviews and ratings from both guests and hosts. These reviews provide valuable feedback about the quality of accommodations and the overall hosting experience, helping users make informed decisions when booking or hosting.

6. **Geospatial Data**: Geospatial data is used to represent the locations of Airbnb listings and help users search for accommodations based on their desired location. This includes latitude and longitude coordinates, neighborhood boundaries, and maps.

7. **Pricing Data**: Pricing data provides insights into the cost of accommodations on Airbnb. This may include average nightly rates, seasonal fluctuations in pricing, and any discounts or promotions offered by hosts.

8. **Trends and Insights**: Analyzing Airbnb data can reveal trends and patterns in travel behavior, such as popular destinations, peak booking times, and preferences among different demographic groups. These insights can be valuable for both hosts and travelers.

Following Steps for EDA :
-
- Load the Dataset: Begin by loading the Airbnb dataset into your preferred data analysis environment, such as Python (using libraries like Pandas) or R.
- Examine the Data Structure: Check the basic structure of the dataset, including the number of rows and columns, and preview the first few rows to get an initial understanding of the data.
- Handle Missing Values: Identify and handle missing values appropriately. Depending on the extent of missing data, you may choose to drop rows or columns, impute missing values, or employ 
  more sophisticated techniques.
- Data Cleaning: Clean the data by addressing inconsistencies, errors, or anomalies. This may involve tasks such as correcting data types, standardizing formats, and removing duplicate 
  records.
- Statistical Summaries: Compute descriptive statistics for numerical variables (e.g., mean, median, standard deviation) and explore distributions. For categorical variables, examine 
  frequency distributions and value counts.
- Correlation Analysis: Explore correlations between variables to understand relationships and dependencies. This can be done using correlation matrices or visualizations like heatmaps.
- Outlier Detection: Identify outliers in the data that may skew analysis results. Outliers can be detected using statistical methods or visual inspection of the data distribution.
- Visualizations: Create visualizations to gain insights into the data. This could include histograms, box plots, scatter plots, and bar charts to visualize distributions, relationships, and 
  patterns within the data.

Explanation of columns :
-

- Listing_id :- This is a unique identifier for each listing in the dataset.
- Listing_name :- This is the name or title of the listing, as it appears on the Airbnb website.
- Host_id :- This is a unique identifier for each host in the dataset.
- Host_name :- This is the name of the host as it appears on the Airbnb website.
- Neighbourhood_group :- This is a grouping of neighborhoods in New York City, such as Manhattan or Brooklyn.
- Neighbourhood :- This is the specific neighborhood in which the listing is located.
- Latitude :- This is the geographic latitude of the listing.
- Longitude :- This is the geographic longitude of the listing.
- Room_type :- This is the type of room or property being offered, such as an entire home, private room, shared room.
- Price :- This is the nightly price for the listing, in US dollars.
- Minimum_nights :- This is the minimum number of nights that a guest must stay at the listing.
- Total_reviews :- This is the total number of reviews that the listing has received.
- Reviews_per_month :- This is the average number of reviews that the listing receives per month
- Host_listings_count :- This is the total number of listings that the host has on Airbnb.
- Availability_365 :- This is the number of days in the next 365 days that the listing is available for booking.

Summarizing the report findings, here are the results of the analysis :
-

(1) Find Distribution Of Airbnb Bookings Price Range.

(2) Find Total Listing/Property count in Each Neighborhood Group in NYC.

(3) Find Average Price Of listings/property in each Neighborhood Groups and also Neighborhoods.

(4) Find Top Neighborhoods and Hosts by Listing/property in entire NYC.

(5) Find the Number Of Active Hosts Per Location by Each Neighborhood Groups.

(6) Find Total Counts Of Each Room Types in entire NYC.

(7) Find Stay Requirement counts by Minimum Nights.

(8) Find the total numbers of Reviews and Maximum Reviews by Each Neighborhood Group.

(9) Find Most reviewed room type in Neighborhood groups per month.

(10) Find Best location listing/property location for travelers.

(11) Find Best Location Listing/Property Location For Travelers and Hosts.

(12) Correlation Heatmap Visualization.


Based on the report insights ,here are the outcomes of the Dataset :
-
(1) Find Distribution Of Airbnb Bookings Price Range.

<p align="center">
  <img width="600" height="300" src="Airbnb img/q1.png">
</p>

(2) Find Total Listing/Property count in Each Neighborhood Group in NYC.

<p align="center">
  <img width="600" height="300" src="Airbnb img/q2.png">
</p>

(3) Find Average Price Of listings/property in each Neighborhood Groups and also Neighborhoods.

<p align="center">
  <img width="600" height="300" src="Airbnb img/q3.png">
</p>

(4) Find Top Neighborhoods and Hosts by Listing/property in entire NYC.

<p align="center">
  <img width="600" height="300" src="Airbnb img/q4.png">
</p>

(5) Find the Number Of Active Hosts Per Location by Each Neighborhood Groups.

<p align="center">
  <img width="600" height="300" src="Airbnb img/q5.png">
</p>

(6) Find Total Counts Of Each Room Types in entire NYC.

<p align="center">
  <img width="600" height="500" src="Airbnb img/q6.png">
</p>

(7) Find Stay Requirement counts by Minimum Nights.

<p align="center">
  <img width="600" height="300" src="Airbnb img/q7.png">
</p>

(8) Find the total numbers of Reviews and Maximum Reviews by Each Neighborhood Group.

<p align="center">
  <img width="600" height="300" src="Airbnb img/q8.png">
</p>

(9) Find Most reviewed room type in Neighborhood groups per month.

<p align="center">
  <img width="600" height="300" src="Airbnb img/q9.png">
</p>

(10) Find Best location listing/property location for travelers.

<p align="center">
  <img width="600" height="300" src="Airbnb img/q10.png">
</p>

(11) Find Best Location Listing/Property Location For Travelers and Hosts.

<p align="center">
  <img width="600" height="300" src="Airbnb img/q11.png">
</p>

(12) Correlation Heatmap Visualization.

<p align="center">
  <img width="600" height="300" src="Airbnb img/q12.png">
</p>


Conclusion :
-
The Airbnb dataset analysis reveals insights into rental trends, pricing dynamics, and guest preferences. Key findings include seasonal demand fluctuations, location-based pricing variations, and factors influencing rental popularity. These insights can inform strategic decisions for hosts, such as optimizing pricing strategies and enhancing guest experiences to maximize rental profitability.

Tools used :
-
<p align="left" <a target="_blank" rel="noreferrer"> <img src="https://camo.githubusercontent.com/60ef9d8e7273373857bd6fb871678ef4fc5367433589be0da330d6972a305bda/68747470733a2f2f70616e6461732e7079646174612e6f72672f7374617469632f696d672f70616e6461735f77686974652e737667" alt="Pandas" width="100" height="100" /> </a> <a align="left" <a target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/numpy/numpy/main/branding/logo/primary/numpylogo.svg" alt="NumPy" width="100" height="100" /> </a> 


Crafted by :
-
-[@Sanjudebnath123](https://github.com/Sanjudebnath123)

Sanju Debnath - Data Analyst









