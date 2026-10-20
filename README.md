# Superstore Data Cleaning & Preparation

## Project Overview

This personal practice project demonstrates basic data inspection,
formatting, and validation techniques using Microsoft Excel.

The dataset contains 21 columns covering orders, customers, products,
shipping, sales, and profit.

## Tools Used

- Microsoft Excel
- Conditional Formatting
- Remove Duplicates
- Go To Special
- ISNUMBER() function

## Data Cleaning Process

### 1. Dataset Inspection
Reviewed the dataset structure and column headers.

### 2. Duplicate Checks
Used Conditional Formatting to check for duplicate Row IDs.
Also used Excel's Remove Duplicates tool to check for duplicate
records across the selected columns.

No duplicates were detected in either check.

### 3. Missing-Value Check
Checked the dataset for blank cells using Excel's Go To Special feature.
No blank cells were found during the check.

### 4. Date Formatting
Adjusted the Order Date and Ship Date column widths to display
the dates properly.

### 5. Date Data-Type Validation
Used the ISNUMBER() function to verify the Order Date and Ship Date
values in the first data row.

Both checks returned TRUE.

## Project Files

- `01_Raw_Data/` — Original dataset, if redistribution is permitted.
- `02_Cleaned_Data/` — Excel workbook.
- `03_Screenshots/` — Screenshots documenting the process.

## Project Outcome

This project provided practical experience with Excel data inspection,
duplicate checking, missing-value detection, date formatting,
and basic data-type validation.

## Dataset Source

The dataset used in this project was obtained from Kaggle:

- **Dataset:** Superstore Dataset - Final
- **Author:** Vivek468
- **Source:** [Superstore Dataset - Final on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

This project was created for personal learning and portfolio purposes.
Credit for the original dataset belongs to its respective creator.

## Project Type

Personal practice project using a publicly available dataset.
This was not paid client work.
