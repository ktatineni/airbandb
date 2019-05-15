# Project-1-Group-2


In 2017, Washington D.C welcomed almost 23 million visitors, 91% of those from the US. Domestic travelers stayed an average of 2.6 nights in the city, while visitors from overseas enjoyed the nation’s capital for an average of six nights.  Traditionally, tourists would avail themselves of hotel rooms – and the District of Columbia has plenty to offer with 33,000+ rooms in 140 hotels. Despite record-breaking visitation, both the hotel occupancy and the average daily rate dropped (down 1.3% and 5.3%, respectively) in 2017. 

Short-term rental sites like VRBO and AirBnB are providing alternatives for the app-savvy traveler. Washington DC boasted 21,870 listings on AirBnB in 2017 (Our data set included 9000 rentals). The number of listings is likely to continue to rise as people venture into becoming AirBnB investors (Full Disclosure: One of our teammates is exploring this as we data crunch!). 

AirBnBs rely on the hosts to set the per night price of the rental. Current rates are anywhere from $53 to $1200 per night. Hotels and other tourism-based business have embraced the laws of economics and regularly raise rates during peak seasons (Christmas, summer, Cherry Blossom, etc.). Using data from Insider AirBnB, our team will try to respond to the following questions:

Question 1: What is the distribution of AirBnB rentals throughout the District's neighborhoods? Are there certain areas with concentrated rentals?

Question 2: What is the average price of an AirBNB in relation to neighborhoods in D.C.?

Question 3: Which neighborhoods present the best opportunities for a successful AirBnB investment?

Description of Jupyter Notebook files:

We reviewed the data using pandas dataframes. We renamed columns and removed columns that would not be useful to the intended analysis as well as merged files based on the Listings ID.

Our focus was really on neighborhood trends, so we focused on visualizing neighborhood trends for the remainder of the analysis.

Visualization included dataframes grouped by neighborhoods to analyze rental medians, means, max, and min values as well as rental density. We also looked at ratings, but all ratings seemed to trend high. Finally, we created a folium map of DC that leverages a geojson file to outline neighborhoods (based on Air BnB definitions). We overlayed a heat map to demonstrate rental density by neighborhood and added markers to show key landmarks that may interest visitors to the city.


