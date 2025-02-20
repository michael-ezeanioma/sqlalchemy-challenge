# Overview

This project involves analyzing climate data for Honolulu, Hawaii, using Python and SQLAlchemy. The project consists of climate data exploration, precipitation and station analysis, and the development of a Flask API to serve climate-related data.

# Project Components

__1. Climate Data Analysis__: Analyzed climate data involved connecting to an SQLite database using SQLAlchemy, reflecting tables into ORM classes, and retrieving key climate metrics. Precipitation and station analysis included extracting the last 12 months of data, calculating temperature statistics, and visualizing trends using Pandas and Matplotlib.

__2. Flask API Development__: Developed to provide access to climate data through multiple endpoints, including a homepage listing all available routes. Routes were implemented to return the last 12 months of precipitation data, a list of all stations, and temperature observations for the most active station. Additionally, dynamic endpoints were created to allow users to query temperature statistics (minimum, maximum, and average) for a specific start date or a defined date range, delivering all data in JSON format.

# Files

__climate_starter.ipynb__: Jupyter Notebook containing climate data analysis and visualizations.

__hawaii.sqlite__: SQLite database storing climate data.

__app.py__: Flask application to serve climate data via API routes.

# Key Features

- Climate Data Analysis

- Used SQLAlchemy to connect and reflect database tables.

- Performed precipitation and station analysis using SQL queries.

- Visualized results using Matplotlib.

Flask API

Created endpoints to serve precipitation, station, and temperature data.

Used Flask jsonify() to return data in JSON format.

Implemented dynamic routes for querying temperature statistics based on user-provided date ranges.

# Dependencies

__Database Connection__: SQLAlchemy for database integration.

__Data Analysis__: Pandas for data manipulation and Matplotlib for visualization.

__Flask API__: Flask to serve climate data via API.

__SQLite__: Relational database for storing climate records.

# Technologies Used

__Python__: Primary programming language.

__SQLAlchemy:__ Database connection and ORM.

__SQLite__: Relational database for climate data storage.

__Pandas__: Data analysis and manipulation.

__Matplotlib__: Data visualization.

__Flask__: API development framework.

 # How to Use

1. Clone this repository to your local machine.

2. Install dependencies using pip install -r requirements.txt.

3. Open climate_starter.ipynb and run the analysis.

4. Start the Flask API with python app.py.

5. Access API endpoints through a web browser or Postman.

# Conclusion

This project demonstrates climate data analysis using SQLAlchemy, Pandas, and Matplotlib, along with developing a RESTful API using Flask to serve climate-related data from an SQLite database.

<!--Mod 10-->
