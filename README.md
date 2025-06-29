# Business-Intelligence-for-Restaurant-Location-Decisions
This project applies geospatial data analysis, clustering algorithms, and business intelligence to identify optimal locations for opening Italian restaurants in Toronto. It uses data from public sources and the Foursquare API to uncover patterns in venue density and competition.

Objective
To determine the best neighborhoods in Toronto to open a new Italian restaurant using data-driven methods and clustering techniques.

Problem Statement
Investors and restaurant owners often struggle with selecting high-potential, low-competition areas. This project clusters neighborhoods based on venue types and frequencies to recommend suitable locations with high opportunity and minimal risk.

Data Sources

Wikipedia: Neighborhoods and postal codes in Toronto

Geocoder: Latitude and longitude data for each neighborhood

Foursquare API: Venue information including category, location, and density

Tools and Technologies

Python

Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn for K-Means clustering and silhouette evaluation

Folium for interactive mapping

Foursquare API for real-world venue data

Methodology

Scraped and cleaned neighborhood data from Wikipedia

Merged geolocation data using Geocoder

Retrieved venue data using Foursquare API within 500 meters of each neighborhood

Applied one-hot encoding to venue categories

Clustered neighborhoods using K-Means (k=4 via Elbow Method)

Evaluated clustering quality using silhouette score

Visualized results using interactive maps

Results

Clustered 103 Toronto neighborhoods across 45+ venue categories

Identified high-opportunity zones with limited Italian restaurant presence

Achieved approximately 80 percent reduction in manual site evaluation time

Provided a repeatable framework for location-based business intelligence

Key Learnings

Hands-on experience with API data integration and geospatial analysis

Practical application of unsupervised learning and clustering techniques

Enhanced ability to connect data insights to real-world business decisions

Project Output

Clustered neighborhood groups by venue profiles

Final report highlighting optimal areas for Italian restaurant placement

Interactive map visualizing restaurant density and competition
