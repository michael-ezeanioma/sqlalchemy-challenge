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

Climate Data Analysis

Used SQLAlchemy to connect and reflect database tables.

Performed precipitation and station analysis using SQL queries.

Visualized results using Matplotlib.

Flask API

Created endpoints to serve precipitation, station, and temperature data.

Used Flask jsonify() to return data in JSON format.

Implemented dynamic routes for querying temperature statistics based on user-provided date ranges.

# Dependencies

Database Connection: SQLAlchemy for database integration.

Data Analysis: Pandas for data manipulation and Matplotlib for visualization.

Flask API: Flask to serve climate data via API.

SQLite: Relational database for storing climate records.

# Technologies Used

Python: Primary programming language.

SQLAlchemy: Database connection and ORM.

SQLite: Relational database for climate data storage.

Pandas: Data analysis and manipulation.

Matplotlib: Data visualization.

Flask: API development framework.

 # How to Use

Clone this repository to your local machine.

Install dependencies using pip install -r requirements.txt.

Open climate_starter.ipynb and run the analysis.

Start the Flask API with python app.py.

Access API endpoints through a web browser or Postman.

# Conclusion

This project demonstrates climate data analysis using SQLAlchemy, Pandas, and Matplotlib, along with developing a RESTful API using Flask to serve climate-related data from an SQLite database.

<!--Mod 10-->
