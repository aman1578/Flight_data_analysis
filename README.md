### Flight_data_analysis
# Project Description
This project focuses on analyzing flight price data sourced from an Excel file (flight_price.xlsx). The dataset contains information about flights, including airline names, source and destination cities, departure and arrival times, duration, total stops, and ticket prices. The goal of this project is to preprocess the data, perform exploratory data analysis (EDA), and prepare it for potential machine learning tasks using Python libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn.

The analysis involves cleaning and transforming the data (e.g., splitting dates, encoding categorical variables), visualizing key trends (e.g., airline distribution), and summarizing the dataset's statistical properties. This project serves as a foundation for understanding flight pricing patterns and can be extended for predictive modeling or further statistical analysis.

# Features
Load and clean flight data.
Extract date components (day, month, year).
EDA: Price stats, airline distribution (histogram + KDE).
One-hot encode Airline, Source, Destination.

# Tools and Libraries Used
NumPy: For numerical operations and array handling.
Pandas: For data manipulation and analysis.
Matplotlib: For creating static visualizations.
Seaborn: For enhanced statistical visualizations.
Scikit-learn: For one-hot encoding of categorical features.
Openpyxl: For reading Excel files.

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
Place flight_price.xlsx in the directory and run the notebook to preprocess the data and perform EDA with visualizations
# Results
EDA Insights: Jet Airways has the highest flight count (3,849), followed by IndiGo (2,053) and Air India (1,752).
Price Statistics: The average flight price is approximately ₹9,087, with a minimum of ₹1,759 and a maximum of ₹79,512.
Visualizations: A histogram with KDE shows the distribution of airlines.
# Future Improvements
Add more visualizations (e.g., price vs. duration, source-destination trends).
Implement a machine learning model to predict flight prices.
Handle missing values and outliers in the dataset.
Expand feature engineering (e.g., convert Duration to minutes).
