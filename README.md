# sqlalchemy-challenge
Overview

This project involves analyzing climate data for Honolulu, Hawaii, using Python and SQLAlchemy. The project consists of climate data exploration, precipitation and station analysis, and the development of a Flask API to serve climate-related data.

Project Components

1. Climate Data Analysis

Database Connection

Connected to an SQLite database using SQLAlchemy.

Reflected tables into ORM classes.

Established a session to interact with the database.

Precipitation Analysis

Identified the most recent date in the dataset.

Retrieved the last 12 months of precipitation data.

Stored the results in a Pandas DataFrame and sorted by date.

Plotted precipitation data.

Generated summary statistics of the precipitation data.

Station Analysis

Queried the total number of stations.

Identified the most active station based on observation count.

Retrieved the minimum, maximum, and average temperature for the most active station.

Queried the last 12 months of temperature observations for the most active station.

Plotted the temperature observations as a histogram.

2. Flask API Development

API Endpoints

Route

Description

/

Lists all available routes.

/api/v1.0/precipitation

Returns last 12 months of precipitation data as JSON.

/api/v1.0/stations

Returns a JSON list of all stations.

/api/v1.0/tobs

Returns temperature observations for the most active station for the past year as JSON.

/api/v1.0/<start>

Returns min, max, and avg temperature from the given start date onward.

/api/v1.0/<start>/<end>

Returns min, max, and avg temperature between specified start and end dates.

Files

climate_starter.ipynb: Jupyter Notebook containing climate data analysis and visualizations.

hawaii.sqlite: SQLite database storing climate data.

app.py: Flask application to serve climate data via API routes.

Key Features

Climate Data Analysis

Used SQLAlchemy to connect and reflect database tables.

Performed precipitation and station analysis using SQL queries.

Visualized results using Matplotlib.

Flask API

Created endpoints to serve precipitation, station, and temperature data.

Used Flask jsonify() to return data in JSON format.

Implemented dynamic routes for querying temperature statistics based on user-provided date ranges.

Dependencies

Database Connection: SQLAlchemy for database integration.

Data Analysis: Pandas for data manipulation and Matplotlib for visualization.

Flask API: Flask to serve climate data via API.

SQLite: Relational database for storing climate records.

Technologies Used

Python: Primary programming language.

SQLAlchemy: Database connection and ORM.

SQLite: Relational database for climate data storage.

Pandas: Data analysis and manipulation.

Matplotlib: Data visualization.

Flask: API development framework.

How to Use

Clone this repository to your local machine.

Install dependencies using pip install -r requirements.txt.

Open climate_starter.ipynb and run the analysis.

Start the Flask API with python app.py.

Access API endpoints through a web browser or Postman.

Conclusion

This project demonstrates climate data analysis using SQLAlchemy, Pandas, and Matplotlib, along with developing a RESTful API using Flask to serve climate-related data from an SQLite database.Mod 10
