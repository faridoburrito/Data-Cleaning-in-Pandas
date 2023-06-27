# Project Name

## Description

This project focuses on data analysis using the Python Pandas library. It includes code snippets that demonstrate various data manipulation and cleaning operations on a customer call list dataset.

## Installation

To run this project, you need to have Python installed. Additionally, make sure to install the required dependencies by executing the following command:

```
pip install pandas openpyxl
```

## Usage

1. Clone the repository:

   ```
   git clone https://github.com/faridoburrito/Data-Cleaning-in-Pandas.git
   ```

2. Navigate to the project directory:

   ```
   cd Data-Cleaning-in-Pandas

   ```

3. Execute the Python script:

   ```
   python script.py
   ```

## Code Explanation

The code performs the following operations:

1. Imports the required `pandas` library.
2. Installs the `openpyxl` library using `pip`.
3. Reads the customer call list data from an Excel file.
4. Removes duplicate entries from the dataset.
5. Drops the "Not_Useful_Column" from the dataset.
6. Cleans the "Last_Name" column by stripping characters from the beginning and end of each value.
7. Cleans the "Phone_Number" column by removing non-word characters.
8. Converts the "Phone_Number" values from float to string.
9. Formats the "Phone_Number" column to have the desired format (XXX-XXX-XXXX).
10. Cleans up the "Phone_Number" column by removing specific patterns.
11. Splits the "Address" column into separate columns for "Street Address", "State", and "Zip".
12. Fills empty cells in the dataset with an empty string.
13. Standardizes the values in the "Paying Customer" column.
14. Standardizes the values in the "Do_Not_Contact" column.
15. Removes rows where "Do_Not_Contact" is set to "Yes".
16. Replaces empty values in the "Do_Not_Contact" column with "No".
17. Removes rows with empty phone numbers.
18. Drops the "Address" and "Zip" columns from the dataset.
19. Resets the index and drops the old index column.

Please note that some lines of code are commented out and provide alternative approaches or explanations for certain operations.

## Contributing

Contributions to this project are welcome. If you find any issues or want to add new features, feel free to submit a pull request.

## Contact

For any questions or inquiries, please contact farid.fatalizade@gmail.com.
