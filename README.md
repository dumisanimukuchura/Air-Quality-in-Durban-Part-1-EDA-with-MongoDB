# Air Quality in Durban - Part 1: EDA with MongoDB

This project explores a time series dataset for air quality in Durban, South Africa, using MongoDB for data storage and analysis. The dataset contains air quality readings, including particulate matter (P1 and P2), humidity, and temperature, collected from sensors in Durba

- **Dataset Source:** [Open Africa - Sensors.Africa Air Quality Archive (Durban)](https://open.africa/dataset/sensorsafrica-airquality-archive-durban)
- **Tools Used:** Python, Pandas, MongoDB, Jupyter Notebook
- **Author:** Dumisani Maxwell Mukuchura
- **Contact:** dumisanimukuchura@gmail.com | [LinkedIn](https://www.linkedin.com/in/dumisani-maxwell-mukuchura-4859b7170/)
n.

## Dataset Source
The dataset is sourced from [Sensors.Africa Air Quality Archive - Durban](https://open.africa/dataset/sensorsafrica-airquality-archive-durban).

## Project Overview
The project focuses on Exploratory Data Analysis (EDA) of the air quality dataset. It includes:
- Connecting to a locally hosted MongoDB database.
- Exploring the dataset structure.
- Analyzing distinct types of readings and their distributions.
- Importing data into a Pandas DataFrame for further analysis.

## Tools and Technologies
- **MongoDB**: A NoSQL database used to store and query the dataset.
- **MongoDB Compass**: A GUI for MongoDB to visualize and interact with the data.
- **MongoDB Shell (`mongosh`)**: A command-line interface for MongoDB.
- **Python**: Used for data analysis and visualization.
- **Pandas**: A Python library for data manipulation and analysis.
- **PyMongo**: A Python driver for MongoDB to interact with the database.

## Project Structure
The project is divided into the f1ollowing steps:

### 1. Prepare Data
- **Connect to MongoDB**: Establish a connection to the locally hosted MongoDB instance.
- **Explore Databases and Collections**: List available databases and collections in MongoDB.
- **View Document Structure**: Examine the structure of a single document to u1.nderstand the dataset.

### 2. Exploratory Data Analysis (EDA)
- **Count Documents**: Determine the total number of documents in the Durban collection.
- **Distinct Value Types**: Identify the distinct types of readings (e.g., P1, P2, humidity, temperature).
- **Distinct Sensor Types**: Identify the types of sensors used in the dataset.
- **Group Documents by Value Type**: Count the number of do2uments for each value type.

### 3. Import Data into Pandas DataFrame
- **Projection**: Focus on specific fields (e.g., `value` and `timestamp`) for analysis.
- **Create DataFrame**: Import the filtered data into a 
- 
## Folder Structure

Air-Quality-in-Durban-Part-1-EDA-with-MongoDB/ 
│── data/ # Contains the CSV dataset 
│── notebook/ # Jupyter Notebook with code and analysis 
│── README.md # Project documentationPandas DataFrame for further analysis.