# Introduction-To-Pandas-Leetcode-Study-Plan

This repository contains solutions to various LeetCode problems related to Pandas, focusing on essential DataFrame operations. Each solution demonstrates a key concept in Pandas, helping users understand and apply these techniques effectively.

## Table of Contents

1. [Create a DataFrame from List](#create-a-dataframe-from-list)
2. [Get the Size of a DataFrame](#get-the-size-of-a-dataframe)
3. [Display the First Three Rows](#display-the-first-three-rows)
4. [Select Data](#select-data)
5. [Create a New Column](#create-a-new-column)
6. [Drop Duplicate Rows](#drop-duplicate-rows)
7. [Drop Missing Data](#drop-missing-data)
8. [Modify Columns](#modify-columns)
9. [Rename Columns](#rename-columns)
10. [Change Data Type](#change-data-type)
11. [Fill Missing Data](#fill-missing-data)
12. [Reshape Data - Concatenate](#reshape-data---concatenate)
13. [Reshape Data - Pivot](#reshape-data---pivot)
14. [Reshape Data - Melt](#reshape-data---melt)
15. [Method Chaining](#method-chaining)

## Problem Solutions

### Create a DataFrame from List
- **File:** `2877-Create a DataFrame from List.py`
- **Function:** `createDataframe(student_data: List[List[int]]) -> pd.DataFrame`
- **Description:** Creates a Pandas DataFrame from a list of lists with `student_id` and `age` as column names.

### Get the Size of a DataFrame
- **File:** `2878-Get the Size of a DataFrame.py`
- **Function:** `getDataframeSize(players: pd.DataFrame) -> List[int]`
- **Description:** Returns the shape (rows, columns) of the given DataFrame.

### Display the First Three Rows
- **File:** `2879-Display the first three rows.py`
- **Function:** `selectFirstRows(employees: pd.DataFrame) -> pd.DataFrame`
- **Description:** Returns the first three rows of the given DataFrame.

### Select Data
- **File:** `2880-Select Data.py`
- **Function:** `selectData(students: pd.DataFrame) -> pd.DataFrame`
- **Description:** Filters rows where `student_id` equals 101 and selects `name` and `age` columns.

### Create a New Column
- **File:** `2881-Create a New Column.py`
- **Function:** `createBonusColumn(employees: pd.DataFrame) -> pd.DataFrame`
- **Description:** Creates a new column `bonus`, which is double the `salary`.

### Drop Duplicate Rows
- **File:** `2882-Drop Duplicate Rows.py`
- **Function:** `dropDuplicateEmails(customers: pd.DataFrame) -> pd.DataFrame`
- **Description:** Removes duplicate rows based on the `email` column.

### Drop Missing Data
- **File:** `2883-Drop Missing Data.py`
- **Function:** `dropMissingData(students: pd.DataFrame) -> pd.DataFrame`
- **Description:** Drops rows where the `name` column has missing values.

### Modify Columns
- **File:** `2884-Modify Columns.py`
- **Function:** `modifySalaryColumn(employees: pd.DataFrame) -> pd.DataFrame`
- **Description:** Doubles the values in the `salary` column.

### Rename Columns
- **File:** `2885-Rename Columns.py`
- **Function:** `renameColumns(students: pd.DataFrame) -> pd.DataFrame`
- **Description:** Renames columns (`id` to `student_id`, `first` to `first_name`, `last` to `last_name`, `age` to `age_in_years`).

### Change Data Type
- **File:** `2886-Change Data Type.py`
- **Function:** `changeDatatype(students: pd.DataFrame) -> pd.DataFrame`
- **Description:** Converts the `grade` column to an integer data type.

### Fill Missing Data
- **File:** `2887-Fill Missing Data.py`
- **Function:** `fillMissingValues(products: pd.DataFrame) -> pd.DataFrame`
- **Description:** Replaces missing values in the `quantity` column with 0.

### Reshape Data - Concatenate
- **File:** `2888-Reshape Data Concatenate.py`
- **Function:** `concatenateTables(df1: pd.DataFrame, df2: pd.DataFrame) -> pd.DataFrame`
- **Description:** Concatenates two DataFrames vertically.

### Reshape Data - Pivot
- **File:** `2889-Reshape Data-Pivot.py`
- **Function:** `pivotTable(weather: pd.DataFrame) -> pd.DataFrame`
- **Description:** Creates a pivot table to display maximum `temperature` for each `month` across `city` columns.

### Reshape Data - Melt
- **File:** `2890-Reshape Data-Melt.py`
- **Function:** `meltTable(report: pd.DataFrame) -> pd.DataFrame`
- **Description:** Converts wide format data into long format using `product` as an identifier variable.

### Method Chaining
- **File:** `2891-Method Chaining.py`
- **Function:** `findHeavyAnimals(animals: pd.DataFrame) -> pd.DataFrame`
- **Description:** Filters animals weighing more than 100, sorts by `weight` in descending order, and selects only the `name` column.

## How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/zogratis17/Introduction-To-Pandas-Leetcode-Study-Plan.git
   ```
2. Navigate into the directory:
   ```sh
   cd Introduction-To-Pandas-Leetcode-Study-Plan
   ```
3. Install Pandas if not already installed:
   ```sh
   pip install pandas
   ```
4. Run any Python file to test the corresponding functionality:
   ```sh
   python 2877-Create\ a\ DataFrame\ from\ List.py
   ```

## Contributions
Feel free to fork this repository, improve the solutions, and submit pull requests. Any contributions that enhance readability, efficiency, or documentation are welcome!

## License
This repository is licensed under the MIT License. See `LICENSE` for details.

