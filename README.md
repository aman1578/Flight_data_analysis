### Flight_data_analysis
# Project Description
This project focuses on analyzing flight price data sourced from an Excel file (flight_price.xlsx). The dataset contains information about flights, including airline names, source and destination cities, departure and arrival times, duration, total stops, and ticket prices. The goal of this project is to preprocess the data, perform exploratory data analysis (EDA), and prepare it for potential machine learning tasks using Python libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn.

The analysis involves cleaning and transforming the data (e.g., splitting dates, encoding categorical variables), visualizing key trends (e.g., airline distribution), and summarizing the dataset's statistical properties. This project serves as a foundation for understanding flight pricing patterns and can be extended for predictive modeling or further statistical analysis.

# Features
Data Loading and Preprocessing: Load flight data from an Excel file and clean it for analysis.
Feature Engineering: Extract day, month, and year from the Date_of_Journey column and drop redundant columns.
Exploratory Data Analysis (EDA):
Summary statistics of flight prices.
Visualization of airline distribution using histograms with kernel density estimation (KDE).
Count of flights per airline.
Categorical Encoding: Use Scikit-learn's OneHotEncoder to transform categorical variables (Airline, Source, Destination) into a numerical format suitable for machine learning.
Dataset Overview: Display the first and last few rows, column names, and data types.
# Tools and Libraries Used
NumPy: For numerical operations and array handling.
Pandas: For data manipulation and analysis.
Matplotlib: For creating static visualizations.
Seaborn: For enhanced statistical visualizations.
Scikit-learn: For one-hot encoding of categorical features.
Openpyxl: For reading Excel files.
# Dataset
The dataset (flight_price.xlsx) contains 10,683 entries with the following key columns:

Airline: Name of the airline (e.g., IndiGo, Air India).
Source: Departure city (e.g., Bangalore, Kolkata).
Destination: Arrival city (e.g., New Delhi, Cochin).
Dep_Time: Departure time.
Arrival_Time: Arrival time.
Duration: Flight duration.
Total_Stops: Number of stops (e.g., non-stop, 1 stop).
Price: Ticket price (target variable).
Additional columns like Route and Additional_Info.
# Installation
To run this project locally, follow these steps:

1.Clone the Repository:

git clone https://github.com/your-username/flight-data-analysis.git
cd flight-data-analysis

2.Set Up a Virtual Environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3.Install Dependencies:

pip install -r requirements.txt

4.Requirements File (requirements.txt):

numpy
pandas
matplotlib
seaborn
scikit-learn
openpyxl

5.Run the Notebook: Ensure you have Jupyter Notebook installed, then launch it:

jupyter notebook
Open the flight_data_analysis.ipynb file and execute the cells.
# Usage
Place the flight_price.xlsx file in the project directory.
Open the Jupyter Notebook (flight_data_analysis.ipynb) and run the cells sequentially to:
Load and preprocess the data.
Perform EDA with visualizations.
Encode categorical variables for further analysis.
# Results
EDA Insights: Jet Airways has the highest flight count (3,849), followed by IndiGo (2,053) and Air India (1,752).
Price Statistics: The average flight price is approximately ₹9,087, with a minimum of ₹1,759 and a maximum of ₹79,512.
Visualizations: A histogram with KDE shows the distribution of airlines.
# Future Improvements
Add more visualizations (e.g., price vs. duration, source-destination trends).
Implement a machine learning model to predict flight prices.
Handle missing values and outliers in the dataset.
Expand feature engineering (e.g., convert Duration to minutes).
