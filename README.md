# Data Analysis & Visualization Program

## Overview

This project is a **menu-driven Data Analysis & Visualization program**
built using Python and Pandas.\
It allows users to load a dataset, explore its contents, perform
DataFrame operations, handle missing values, generate descriptive
statistics, create visualizations, and save the generated visualization.

The screenshots show the program running successfully with a sample
sales dataset.

------------------------------------------------------------------------

## Features

The main menu provides the following options:

1.  **Load Dataset**
2.  **Explore Data**
3.  **Perform DataFrame Operations**
4.  **Handle Missing Data**
5.  **Generate Descriptive Statistics**
6.  **Data Visualization**
7.  **Save Visualization**
8.  **Exit**

------------------------------------------------------------------------

## Dataset Preview

The sample dataset contains the following columns:

  Column          Description
  --------------- ----------------------
  Date            Date of the sale
  Product         Product name
  Category        Product category
  Price           Price of the product
  Quantity Sold   Number of units sold
  Total Sales     Total sales amount

### Sample Records

  Date         Product      Category        Price   Quantity Sold   Total Sales
  ------------ ------------ ------------- ------- --------------- -------------
  2026-01-05   Laptop       Electronics     55000               2        110000
  2026-01-08   Phone        Electronics     25000               5        125000
  2026-01-12   Headphones   Electronics      2000              10         20000
  2026-01-15   Chair        Furniture        4500               6         27000
  2026-01-20   Table        Furniture        8000               3         24000

------------------------------------------------------------------------

## 1. Load Dataset

The **Load Dataset** option loads the dataset into a Pandas DataFrame.

After loading, the program displays:

-   A success message
-   A preview of the dataset
-   The first five rows of the DataFrame

Example:

``` text
== Load Dataset ==
Dataset loaded successfully!
```

------------------------------------------------------------------------

## 2. Explore Data

The Explore Data menu provides different ways to inspect the dataset.

### Available Options

``` text
1. Display the first 5 rows
2. Display the last 5 rows
3. Display column names
4. Display data types
5. Display basic info
6. Back to Main Menu
```

### Data Types

The displayed dataset has these data types:

``` text
Date            object
Product         object
Category        object
Price            int64
Quantity Sold    int64
Total Sales      int64
```

This option helps understand the structure and data types of each
column.

------------------------------------------------------------------------

## 3. Perform DataFrame Operations

This section is used for performing operations on the Pandas DataFrame.

Typical DataFrame operations can include:

-   Selecting columns
-   Filtering rows
-   Sorting data
-   Creating or modifying columns
-   Performing calculations
-   Grouping data

These operations help transform and analyze the dataset.

------------------------------------------------------------------------

## 4. Handle Missing Data

The program provides a separate menu for handling missing values.

### Available Options

``` text
1. Display rows with missing values
2. Fill missing values with mean
3. Drop rows with missing values
4. Replace missing values with a specific value
5. Back to Main Menu
```

The screenshot shows:

``` text
No missing values found in the dataset!
```

This means the sample dataset does not currently contain missing values.

------------------------------------------------------------------------

## 5. Generate Descriptive Statistics

The program can generate descriptive statistics for numerical columns.

This analysis can provide values such as:

-   Count
-   Mean
-   Standard deviation
-   Minimum
-   Maximum
-   Quartiles

These statistics help summarize the numerical data and understand its
distribution.

------------------------------------------------------------------------

## 6. Data Visualization

The visualization menu provides multiple chart types.

### Available Charts

``` text
1. Bar plot
2. Line plot
3. Scatter plot
4. Pie chart
5. Histogram
6. Stack plot
```

These charts can be used to visually analyze relationships, trends,
distributions, and comparisons within the dataset.

### Example Uses

-   **Bar Plot:** Compare sales between products or categories.
-   **Line Plot:** Display sales trends over time.
-   **Scatter Plot:** Show the relationship between two numerical
    columns.
-   **Pie Chart:** Display category-wise proportions.
-   **Histogram:** Show the distribution of numerical values.
-   **Stack Plot:** Compare multiple quantities across a sequence.

------------------------------------------------------------------------

## 7. Save Visualization

The **Save Visualization** option is used to save the generated chart.

If no visualization has been created, the program displays:

``` text
No visualization available to save!
Please generate a visualization first using option 6.
```

Therefore, the user should first create a chart using **Data
Visualization (option 6)** and then use **Save Visualization (option
7)**.

------------------------------------------------------------------------

## 8. Exit

The Exit option closes the program.

The program displays:

``` text
Exiting the program. Goodbye!
```

------------------------------------------------------------------------

## Program Flow

``` text
Start
  |
  v
Load Dataset
  |
  v
Explore / Analyze Data
  |
  +--> DataFrame Operations
  |
  +--> Handle Missing Data
  |
  +--> Descriptive Statistics
  |
  +--> Data Visualization
              |
              v
        Save Visualization
  |
  v
Exit
```

------------------------------------------------------------------------

## Technologies Used

-   **Python**
-   **Pandas** -- Data loading, cleaning, and analysis
-   **Matplotlib** -- Data visualization
-   **NumPy** -- Numerical operations (if used in the implementation)

------------------------------------------------------------------------

## Requirements

Install the required Python libraries using:

``` bash
pip install pandas matplotlib numpy
```

------------------------------------------------------------------------

## How to Run

1.  Open the project folder in a terminal or command prompt.
2.  Make sure the required dataset is available.
3.  Run the Python program:

``` bash
python your_program_name.py
```

4.  Select an option from the main menu.
5.  Follow the instructions displayed by the program.

------------------------------------------------------------------------

## Example Output

``` text
========== Data Analysis & Visualization Program ==========

Please select an option:
1. Load Dataset
2. Explore Data
3. Perform DataFrame Operations
4. Handle Missing Data
5. Generate Descriptive Statistics
6. Data Visualization
7. Save Visualization
8. Exit
```

After loading the dataset:

``` text
== Load Dataset ==
Dataset loaded successfully!
```

For missing-data checking:

``` text
== Handle Missing Data ==
No missing values found in the dataset!
```

For visualization:

``` text
== Data Visualization ==
1. Bar plot
2. Line plot
3. Scatter plot
4. Pie chart
5. Histogram
6. Stack plot
```

------------------------------------------------------------------------

## Conclusion

This project demonstrates the basic workflow of **data analysis and
visualization using Python**. It provides a simple interactive interface
for loading data, exploring a DataFrame, cleaning missing values,
generating statistics, creating different visualizations, and saving
results.

It is useful as a beginner-friendly project for understanding **Pandas,
data cleaning, statistical analysis, and Matplotlib visualization**.
