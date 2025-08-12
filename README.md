# Power-Query-Data-Preparation-
This project involves preparing and restructuring raw data into a clean, organized format suitable for analysis. Using Power Query, the process includes splitting and normalizing column values, unpivoting time-based data, filtering relevant records, and reshaping the dataset for clarity.

---

## 1. Split Column by Character Transition  
Separate text and numeric parts in mixed columns (e.g., `Sales11` → `Sales`, `11`) to normalize identifiers.

## 2. Remove Numbers for Column Use  
Keep only the text part (e.g., `Sales`, `Margin`) to serve as a clean categorical column.

## 3. Unpivot Date and Value Columns  
Transform all date-related columns (monthly, quarterly, yearly) into rows to reduce column count and standardize structure.

## 4. Pivot Metric Rows  
Pivot the normalized metric column (e.g., `Sales`, `Margin`) to create individual columns for each metric.

## 5. Filter Quarters  
Filter rows to retain only those where the date column contains `"Q"` — representing quarterly values.

## 6. Reorder and Rename Columns  
Organize columns into logical order (e.g., `Store`, `Category`, `Quarter`, `Sales`, `Margin`) and apply clear, consistent naming.

## 7. Snippet 

Raw data

![Raw Data View](https://raw.githubusercontent.com/sufrimo/Power-Query-Data-Preparation-/main/Raw%20data.jpg)

Cleaned data

![Cleaned Data View](https://raw.githubusercontent.com/sufrimo/Power-Query-Data-Preparation-/main/Cleaned%20data.jpg)


---
