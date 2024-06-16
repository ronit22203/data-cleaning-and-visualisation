Project Overview
This project focuses on cleaning and visualizing Airbnb data from New York City for the year 2019. The dataset includes information on various Airbnb listings in New York, such as prices, number of reviews, and host details. The primary goals are to clean the data, handle missing values, and perform exploratory data analysis through visualizations.

Files in the Repository
AB_NYC_2019.csv: The original dataset containing Airbnb listings data.
project_script.py: The Python script containing the data cleaning and visualization code.
README.md: This file providing an overview and instructions for the project.
Requirements
To run the code in this project, you need the following Python libraries:

pandas
seaborn
matplotlib
statistics
numpy
You can install these libraries using pip:

bash
Copy code
pip install pandas seaborn matplotlib numpy
Instructions
Load the Dataset: Place the AB_NYC_2019.csv file in the same directory as the project_script.py.
Run the Script: Execute the project_script.py script to perform data cleaning and generate visualizations.
Visualizations: The script will generate several plots, including box plots, violin plots, scatter plots, and count plots, to explore the data.
Data Cleaning Steps
Handling Missing Values:

Filled missing values in the reviews_per_month column with 0.
Dropped rows with missing name values.
Filled missing host_name values with "Unknown".
Created a new column last_review_missing to indicate missing last_review values and filled missing dates with '1900-01-01'.
Removing Outliers and Irrelevant Data:

Removed listings with prices above $1000 and prices equal to $0.
Removed listings with zero reviews.
Exploratory Data Analysis
The following visualizations were created to explore the cleaned data:

Box Plot of Prices by Neighbourhood: Shows the distribution of prices in different neighbourhoods.
Violin Plot of Prices by Room Type: Visualizes the distribution of prices for different room types.
Scatter Plot of Price vs. Reviews: Examines the relationship between listing prices and the number of reviews.
Count Plot of Reviews by Neighbourhood Group: Compares the number of reviews across different neighbourhood groups.
Correlation Analysis
A correlation analysis was conducted to determine the relationship between the number of reviews and the price of listings. The correlation coefficient value of -0.041 indicates a very weak negative correlation, suggesting that as the price increases, the number of reviews tends to decrease, but the relationship is very weak.

Conclusion
This project successfully cleaned and visualized the New York Airbnb dataset, providing valuable insights into the Airbnb market in New York City. The exploratory analysis and visualizations offer a deeper understanding of the data, helping to uncover patterns and trends in the Airbnb listings.






