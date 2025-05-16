# Sugarcane-Production
##Overview
This Jupyter Notebook analyzes global sugarcane production data, focusing on production metrics across different countries and continents. The dataset includes information such as production in tons, production per person, acreage, and yield per hectare.

##Dataset
The dataset used is List of Countries by Sugarcane Production.csv, which contains the following columns:

*Country: Name of the country.
*Continent: Continent where the country is located.
*Production(Tons): Total sugarcane production in tons.
*Production_per_person(Kg): Sugarcane production per person in kilograms.
*Acreage(Hectare): Total land area used for sugarcane cultivation in hectares.
*Yield(Kg/Hectare): Yield of sugarcane per hectare in kilograms.

##Data Cleaning
*Removed Non-Numeric Characters: Cleaned columns by removing periods and commas to convert them into numeric values.
*Renamed Columns: Simplified column names for easier reference.
*Handled Missing Values: Dropped rows with missing values in Acreage(Hectare) and Yield(Kg/Hectare).
*Converted Data Types: Ensured all numerical columns are of the correct data type (float).

##Key Analyses
*Contribution by Continent: Visualized the number of sugarcane-producing countries per continent.
*Distribution of Metrics: Examined the distributions of production, production per person, acreage, and yield.
*Top Producers: Identified the top sugarcane-producing countries globally.

##Visualizations
*Bar plot showing the number of sugarcane-producing countries per continent.
*Distribution plots for key metrics (production, production per person, acreage, and yield).

##Dependencies
Python 3.x
pandas
seaborn
matplotlib

##Usage
Clone the repository.
Install the required dependencies.
Run the Jupyter Notebook to reproduce the analysis.

##Contributions
Feel free to contribute by opening issues or submitting pull requests. Suggestions for additional analyses or visualizations are welcome!

##License
This project is open-source 
