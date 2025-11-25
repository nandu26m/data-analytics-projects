# Netflix Data Cleaning & Transformation using Pandas

This project focuses on cleaning and transforming the Netflix Movies & TV Shows dataset using Python and Pandas in Google Colab. The goal is to prepare the dataset for analysis by removing unnecessary information, fixing inconsistencies, and standardizing the data.

---

## Dataset Description

The dataset used in this project is `netflix.csv`, which contains 8,790 records and 10 columns.
It includes metadata about Movies and TV Shows available on Netflix.

### Dataset Columns

| Column       | Description                  |
| ------------ | ---------------------------- |
| show_id      | Unique ID for each title     |
| type         | Movie or TV Show             |
| title        | Title of the content         |
| director     | Director name                |
| country      | Country of origin            |
| date_added   | Date Netflix added the title |
| release_year | Year of release              |
| rating       | Age rating (e.g., PG, TV-14) |
| duration     | Runtime or number of seasons |
| listed_in    | Genre categories             |

---

## Project Objectives

This project performs structured data cleaning operations, including:

### 1. Loading and Inspecting the Dataset

* Read the CSV file
* Display first and last rows
* Show dataset shape, summary statistics, and data types

### 2. Deleting Redundant Columns

* Identify and remove unnecessary columns
* For this project, the column `rating` is removed

### 3. Renaming Columns

* Rename selected columns for clarity
* Standardize all column names (capitalize formatting)

### 4. Dropping Duplicate Records

* Remove any duplicate rows to ensure data accuracy

### 5. Handling Missing Values

* Remove rows containing NaN values
* Ensure the dataset has complete records

### 6. Additional Transformations

Possible optional steps:

* Converting `date_added` to datetime format
* Standardizing duration column
* Cleaning inconsistent text formatting
* Splitting multi-category fields (e.g., genres)

These steps improve dataset quality for further analysis or machine learning tasks.

---

## Expected Output

After performing all cleaning steps, the final dataset will:

* Have no redundant columns
* Contain consistent and properly formatted column names
* Be free from duplicate records
* Have no missing values
* Be prepared for analysis and modeling

---

## Technologies and Modules Used

### Python Libraries

| Library      | Purpose                                    |
| ------------ | ------------------------------------------ |
| pandas       | Data loading, cleaning, and transformation |
| numpy        | Optional additional computation            |
| Google Colab | Executing the notebook                     |

### Version Information

* Python 3.x
* Pandas 2.2.2

---

## Project Structure

```
├── netflix.csv                # Raw dataset
├── notebook.ipynb             # Google Colab or Jupyter Notebook work
├── README.md                  # Documentation
```

---

## How to Run This Project

1. Open Google Colab.
2. Upload the `netflix.csv` file.
3. Run all cells in the provided notebook.
4. Review the cleaned dataset at the end of execution.

---

## Conclusion

This project demonstrates key data cleaning and transformation techniques using Pandas.
The cleaned dataset is suitable for exploratory data analysis, reporting, or further machine learning workflows.

---
