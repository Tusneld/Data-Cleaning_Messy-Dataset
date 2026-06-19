# Excel Data Cleaning & Preparation Project

## Project Overview
This repository showcases a comprehensive data cleaning workflow performed in Microsoft Excel. The goal of this project was to transform a raw, inconsistent dataset into a professional, analysis-ready format. By addressing common data quality challenges, I have ensured the dataset is reliable for downstream visualization and decision-making.

---

## Problem Statement
The initial raw dataset contained several structural and quality issues that hindered accurate analysis, including:

* **Alignment:** Inconsistent row/column alignment.
* **Casing:** Irregular name and text casing.
* **Formatting:** Non-standardized ID formats and date inconsistencies (mixed dots/dashes).
* **Anomalies:** Duplicate records and negative financial outliers.
* **Gaps:** Unmanaged blank cells.

---

## Process & Methodology
I utilized a systematic approach, leveraging key Excel efficiency shortcuts to clean the data accurately and efficiently without manual entry errors:

### 1. Data Structuring & Alignment
* Used `Alt + H + O + I` and `Alt + H + O + A` to auto-fit row and column dimensions for immediate readability.

### 2. Standardization & Transformation
* Employed `Ctrl + E` (Flash Fill) to normalize name casing and standardize categorical entries like payment methods and region codes.

### 3. Data Correction
* Applied `Ctrl + H` (Find and Replace) to unify record IDs and transform inconsistent date formats (e.g., converting dots to slashes).

### 4. Data Integrity & Validation
* Implemented **Conditional Formatting** (`Alt + H + L`) to identify and highlight negative values in financial columns.
* Executed duplicate record removal to ensure data uniqueness.
* Adopted a non-destructive approach for missing values by flagging blank cells with conditional formatting rather than deleting data.

---

## Key Learnings
* **Efficiency:** Mastering advanced Excel shortcuts heavily minimizes manual labor and human error.
* **Data Integrity:** Understanding the strategic importance of flagging or isolating issues rather than deleting data prematurely.
* **Preparation:** Developing a keen eye for how raw data requires significant, structured preprocessing before it is ready for BI dashboards or statistical modeling.

---

## Repository Contents
* `Messy Excel Dataset.xlsx`: The original, uncleaned dataset.
* `Messy Excel Dataset_Cleaned.xlsx`: The processed, final version of the file.

