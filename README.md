# Airbnb Price Prediction, A Case of Boston vs Seattle
# Table of Contents

1. Installations
2. Project Motivation
3. File Descriptions
4. Key Findings
5. Licensing, Authors, Acknowledgements

# Installations
Python (version 3.8.8)

Python libraries needed for the analysis:Pandas, Numpy, Matplotlib, Seaborn, SciKit-Learn

# Project Motivations
For this project, spatiotemporal analyses and predictive modelings were applied for data on AirBnB homes located in Boston and Seattle. 

Three business questions were used to motivate the analyses:

- Does location pose potential impacts on price variation?
- Does time pose potential impacts on price variation?
- What may be the main factors used to predict price after all?

# File Descriptions
The following are the files available in this repository:

` Airbnb_Explorer.ipynb` : the jupyter notebook used to perform analyses following the CRISP-DM process

` Airbnb_Explorer.html` : the analysis file in html format

` Boston` : the folder that contains all the data of Boston Airbnb homes for analyses 

` Seattle` : the folder that contains all the data of Seattle Airbnb homes for analyses 

` calendar.csv` : csvs containing home_id, date, availability, and price for each home

` listings.csv` : csvs containing id (listing ID), name (name of the listing), host_id (host ID), host_name (name of the host), room_type (listing space type), neighbourhood_cleansed (the communities where Airbnb homes locate), and price.

` reviews.csv` : csvs containing home_id, date of review, reviewer_id, reviewer_name, and reviewer comments for the reviewed stays.

# Key Findings
- Locations of Airbnb can impact prices. Generally, the closer to urban centers the pricier the Airbnb can be. And the most rated Airbnb neighborhoods are usually not distant from urban centers as well.
- Time of bookings (or checked-in) can impact prices. Generally, prices in weekends are pricier than prices on weekdays. In addition, price variation displays distinct seasonality --- which means some seasons of a city are more visited/ welcomed than other seasons. However, specific performances of seasonality may vary by cities.
- Factors such as accomodates (visitor capacity), locations (latitudes, longitudes), bathrooms, reviews per month are more associated with price variations than other factors.

A detailed version the analyses and insights can be found at [this blog post](https://medium.com/@btiangis91/airbnb-price-prediction-a-case-of-boston-vs-seattle-e5bdf023d169) on Medium: .

# Licensing, Authors, Acknowledgements
Credits are given to AirBnB for the data. Data licensing and other descriptive information can be reached at [InsideAirbnb](http://insideairbnb.com/get-the-data/).