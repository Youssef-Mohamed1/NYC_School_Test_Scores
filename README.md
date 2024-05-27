# NYC_School_Test_Scores
This project analyzes SAT scores of various schools across different boroughs in New York City. The main objectives are to identify the top-performing schools based on their combined SAT scores and to determine which borough has the highest variability in SAT scores. The analysis is performed using Python and the pandas library.
# Objectives
1- Top 10 Schools by Total SAT Score

Calculate the combined SAT scores for each school.

Save the results as a pandas DataFrame named top_10_schools.

The DataFrame contains:

  "school_name": Name of the school.

  "total_SAT": Combined SAT score.

The results are ordered by "total_SAT" in descending order.


2- Borough with Largest Standard Deviation in SAT Scores

Determine which single borough has the largest standard deviation in combined SAT scores.

Save the results as a pandas DataFrame named largest_std_dev.

The DataFrame contains one row with the following columns:

"borough": The name of the NYC borough with the largest standard deviation of "total_SAT".

"num_schools": The number of schools in the borough.

"average_SAT": The mean of "total_SAT" scores in the borough.

"std_SAT": The standard deviation of "total_SAT" scores in the borough.

All numeric values are rounded to two decimal places.

# Methodology
1- Data Cleaning and Preparation:

Load the data into pandas DataFrames.

Clean and preprocess the data to ensure accuracy and completeness.

2- Calculations:

Compute the total SAT score for each school by summing the individual section scores.

Identify the top 10 schools with the highest total SAT scores.

Calculate the standard deviation of total SAT scores for each borough and identify the borough with the largest value.

3- Results Storage:

Store the top 10 schools in the top_10_schools DataFrame.

Store the borough with the largest standard deviation in the largest_std_dev DataFrame.

# Installation

To run this project, you will need Python 3.x and the following libraries:

pandas,
numpy. 
Install the required packages using pip:

    pip install pandas numpy
Running the Analysis
Run the Jupyter notebooks or Python scripts in the notebooks or src directory to reproduce the analysis and generate the results.
and make sure to have the csv file in the same directory as the python file.
