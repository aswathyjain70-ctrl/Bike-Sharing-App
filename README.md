# Bike-Sharing-App

Data source is the Bike Sharing Dataset (specifically loaded from /content/hour.csv). This dataset is typically sourced from the UCI Machine Learning Repository and originates from the Capital Bikeshare system in Washington, D.C.This dataset is an industry favorite for data engineering and machine learning portfolios because:

Rich feature set: It combines temporal data (hourly timestamps) with environmental/weather factors, making it perfect for demonstrating end-to-end ETL (Extract, Transform, Load) pipelines.

Clear targets: Having separate columns for casual and registered users allows for interesting multi-target analysis and aggregation.

Manageable size: At 17,379 records, it’s large enough to be meaningful but small enough to process instantly in a Colab environment. The dataset captures hourly counts of rental bikes along with contextual weather and seasonal information. Specifically, it includes:

Core Identifiers & Time: Record ID, date, season, year, month, hour, and day flags (holiday, weekday, working day).

Weather Metrics: Weather situation (clear, mist, rain/snow), normalized temperature, normalized "feels-like" temperature, humidity, and wind speed.

Rental Counts: A breakdown of casual users, registered users, and the total count (cnt) of rentals.It is structured data. Every record follows a rigid, predefined schema where rows represent specific hourly observations and columns represent clearly defined variables with strict data types
