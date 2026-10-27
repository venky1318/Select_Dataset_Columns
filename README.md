# Task 18 — Select Dataset Columns Using Pandas

## Project Overview

This project demonstrates how to select specific rows and columns from a dataset using Pandas `loc` and `iloc`.

The project uses the Iris dataset to illustrate label-based and integer-position-based selection, including selecting individual columns, multiple columns, specific rows, and rows matching a condition.

## Objective

To learn how to access specific parts of a Pandas DataFrame using `loc` and `iloc`.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab
- GitHub

## Dataset Description

The Iris dataset contains 150 observations with four numerical measurement columns and one categorical species column.

The columns are sepal length, sepal width, petal length, petal width, and species.

## Concepts Demonstrated

### Label-Based Selection with loc

The `loc` accessor selects data based on row and column labels. It supports selecting specific labels, column names, and rows that satisfy Boolean conditions.

### Position-Based Selection with iloc

The `iloc` accessor selects data using integer row and column positions. It is useful when selecting rows or columns by their position in a DataFrame.

## Examples

- Selecting the first five rows and specific columns with `loc`.
- Selecting particular row labels with `loc`.
- Filtering setosa observations with a condition.
- Selecting rows and columns using integer positions with `iloc`.
- Selecting a single column or multiple columns.

## How to Run

1. Open the notebook in Google Colab.
2. Run the cells from top to bottom.
3. Examine the selected DataFrame outputs.
4. Download the notebook and `iris_dataset.csv`.

## Project Files

- `Task_18_Select_Dataset_Columns.ipynb` — Notebook and code.
- `iris_dataset.csv` — Exported dataset.
- `requirements.txt` — Python dependencies.
- `project_report.pdf` — Formatted project report.
- `screenshots/` — Actual notebook output screenshots.

## Key Learning

`loc` uses labels, whereas `iloc` uses integer positions. Both can select specific rows and columns, but their indexing rules differ.

In particular, label-based slices with `loc` include the ending label, while position-based slices with `iloc` exclude the ending position.

## Conclusion

This project demonstrates how Pandas can select specific parts of a DataFrame and how label-based and position-based indexing differ. These skills are useful in data analysis and preparing datasets for machine learning.
