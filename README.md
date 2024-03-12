
# Data Cleaning :sponge:	

This project aimed to clean and preprocess data in the `store_income_data_task.csv` file. Specifically, the tasks involved cleaning the `country` column and parsing the `date` column.

## Task 1: Cleaning the Country Column

- First, I loaded the dataset using Pandas and inspected the unique values in the `country` column.
- Then, I converted all entries in the `country` column to lowercase and removed any trailing white spaces.
- After that, I identified variations of countries and narrowed them down to three main countries: 'United States', 'United Kingdom', and 'South Africa'.

## Task 2: Parsing the Date Column

- I converted the `date_measured` column to datetime format to facilitate date calculations.
- Then, I created a new column called `days_ago` to calculate how many days ago each measurement was taken from the current date.

## Code Execution

To execute the code and reproduce the results:

1. Ensure you have Python and the necessary libraries (Pandas, NumPy, fuzzywuzzy) installed.
2. Clone the repository and navigate to the project directory.
3. Run the provided Python script or execute the code cells in a Jupyter notebook environment.

## Notes

- The code utilizes various Pandas functionalities for data manipulation and cleaning.
- Fuzzy string matching was employed to identify similar country names and consolidate them.
- The project ensures data consistency and prepares the dataset for further analysis or modeling tasks.

## 🛠 Skills
- Data Cleaning
- Data Manipulation with Pandas
- Datetime Handling
- String Matching and Text Processing
- Version Control with Git
- Documentation

