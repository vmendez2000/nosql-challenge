# nosql-challenge
# UK Food Hygiene Database Analysis
### This project involves analyzing data from the UK Food Standards Agency on food hygiene ratings for various establishments. The analysis is done using MongoDB and PyMongo to interact with the data and perform various queries and aggregations. The goal is to explore different aspects of the hygiene ratings and analyze establishments based on their geographical locations, rating values, and hygiene scores.

## Table of Contents
* 1.Project Overview
* 2.Installation Instructions
* 3.Usage
* 4.Code Source and References
## Project Overview
### This project explores the UK Food hygiene ratings of establishments using MongoDB as the database and PyMongo for querying and manipulation. The analysis includes:

* Importing data into a MongoDB collection.
* Performing updates to the database.
* Answering specific queries such as finding establishments with certain hygiene scores and sorting by distance.

## Installation Instructions
### Follow the steps below to set up the project locally:

* Clone the repository: (https://github.com/vmendez2000/nosql-challenge)
* Install required dependencies: You will need PyMongo and other necessary libraries for this project. To install them, run the following command:

* Set up MongoDB: Ensure MongoDB is installed and running on your local machine. 
*Import the data: Import the dataset into MongoDB by running the mongoimport command in your terminal: mongoimport --drop --db uk_food --collection establishments --file establishments.json --jsonArray
## Usage
### Run Jupyter Notebook:

* Once the data is imported, you can run the Jupyter notebook to perform the analysis.
* The notebook contains several queries and aggregation operations to analyze the data.
## Code Source
### The following external sources were referenced or used during the development of this project:

#### ChatGPT for help coding and debugging. 

#### UK Food Standards Agency API:

* The dataset was sourced from the UK Food Hygiene Ratings dataset provided by the UK Food Standards Agency.
