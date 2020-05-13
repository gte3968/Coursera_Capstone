# Bay Area Info - Capstone project for IBM Data Science Professional Certificate course 

In this project, data from online sources are collected for every zip code of the San Francisco bay area:
1. Geographical data (longitude, latitude, and GeoJson files)
2. Population per zip code
3. Per captita income per zip code
4. Housing price per zip code

Data are loaded, cleaned, and analyzed for the parameters of interest and displayed on the map using folium. Main outcome include:
1. Clustering was tried for population, per capita and housing price, using KMeans and DBSCAN, but no clear winner due to the actual distritbuion of the data.
2. Binning and labeling of Population, per capita income, and housing price for each zip code was instead used.
3. Per captita income and housing was found to have good correlation as expected.
4. Population and per capita income were used as indicators for business opportunities assessment. 
5. Zip codes were grouped by population and per capita income combo. The zip codes with reasonable (not too low) population and per capita income are identified as better candidates for potential business. 
