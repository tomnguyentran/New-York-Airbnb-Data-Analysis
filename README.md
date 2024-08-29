# New-York-Airbnb-Data-Analysis

## Project Overview

This project involves analyzing Airbnb listing data for New York City to identify cost-effective accommodation options. The project utilizes spatial and non-spatial visualization techniques to display price distributions across different neighborhoods, with a focus on updating visualizations as new data is generated.

## Datasets

The dataset contains 48,897 Airbnb listings in New York City, each with the following attributes:


    •	neighbourhood_group: The borough where the listing is located (e.g., “Manhattan”).
    •	neighbourhood: The specific neighborhood within the borough (e.g., “Midtown”).
    •	latitude & longitude: Geographical coordinates of the listing.
    •	room_type: Type of room offered (e.g., “Entire home/apt”).
    •	price: Price per night in USD.
    •	minimum_nights: Minimum number of nights required for booking.
    •	availability_365: Number of days the listing is available in a year.

# Methodology

#### Data Preprocessing

    •	The dataset is cleaned by removing outliers, specifically in the price column, to ensure accurate visualizations.

#### Data Generation

    •	A data generator was designed to create new, realistic entries based on the statistical characteristics (mean, standard deviation) of the existing dataset. 
        This simulates the impact of adding new data points.

#### Visualization

    •	Spatial Visualization: Folium is used to create an interactive map that displays Airbnb listings by neighborhood, highlighting price variations across different areas of New York City.
    •	Non-Spatial Visualization: Matplotlib is used to create bar charts of Airbnb data, visualizing the average prices by borough.

# Conclusion

This project demonstrates the capability to analyze and visualize large datasets, highlighting the importance of data generation to understand trends. The combination of spatial and non-spatial techniques ensures a comprehensive analysis of the data, which can be used for better decision-making in various applications, such as real estate investment or travel planning.
