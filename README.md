# Bay Area Info - Capstone project for IBM Data Science Professional Certificate course 

In this project, data from online sources are collected for every zip code of the San Francisco bay area:
1. Geographical data (longitude, latitude, and GeoJson files)
2. Population per zip code
3. Per captita income per zip code
4. Housing price per zip code

Data are loaded, cleaned, and analyzed for the parameters of interest and displayed on the map using folium. 
Main outcome include:
1. Clustering was tried for population, per capita and housing price, using KMeans and DBSCAN, but no clear winner due to the near-continuous distritbuion of the data.
2. Binning and labeling of Population, per capita income, and housing price for each zip code was instead done using manually defined ranges.
3. Per captita income and housing was found to have good correlation as expected.
4. Population and per capita income were used as indicators for business opportunities assessment. 
5. Zip codes were grouped by population and per capita income combo. The zip codes with reasonable (mid to high) population and per capita income are identified as better candidates for potential business. 32 out of 171 zip codes were found to be in this bucket.
6. Foursquare API calls were made for the 32 zip code to further gain understanding of business distributions. Total number of venues within 1000 meters of the center of the zip code, as well as the breakdown into each high level category, such as food, shops, travel, were summarized.
7. Within the 32 zip codes, the top 8 with most venues were identified, with further ranking of the number of food related venues summarized. 
8. All bay area zip codes are displayed, with color coding representing the binning labels for population, per capita income, housing price, as well as the identified 8 zip codes with top interest for potential business owners, are displayed with clickable markers showing the corresponding data, using folium calls. 

