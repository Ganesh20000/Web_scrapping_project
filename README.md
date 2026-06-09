# World Richest People 2026 – Web Scraping & Data Analysis

## 📌 Project Overview

This project extracts data on the **Top 50 Richest People in the World (2026)** from a public website using Python web scraping techniques. The collected data is cleaned, transformed, and analyzed using Pandas, followed by visualizations to uncover insights about billionaire wealth distribution and wealth sources.

## 🎯 Objectives

* Scrape billionaire data from a website.
* Store and preprocess the extracted data.
* Perform exploratory data analysis (EDA).
* Visualize wealth distribution using charts.
* Calculate statistical measures such as mean, quartiles, and IQR.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **Requests**
* **BeautifulSoup**
* **Regex**

## 📂 Dataset Attributes

| Column | Description                 |
| ------ | --------------------------- |
| NAME   | Billionaire Name            |
| WORTH  | Net Worth (in Billions USD) |
| SOURCE | Primary Source of Wealth    |

## 🔍 Project Workflow

### 1. Web Scraping

* Sent HTTP requests using `requests`.
* Parsed HTML using `BeautifulSoup`.
* Extracted billionaire information from table rows.
* Stored data in a Pandas DataFrame.

### 2. Data Cleaning

* Removed special characters (`$`, `B`) from wealth values using Regex.
* Converted wealth values into numeric format.
* Handled unnecessary rows and formatted columns.

### 3. Data Analysis

Performed:

* Mean Wealth
* Quartile Calculation (Q1, Q3)
* Interquartile Range (IQR)
* Source-wise Wealth Aggregation
* Distribution Analysis

### 4. Data Visualization

Generated:

* Bar Chart of Total Wealth by Source
* Wealth Distribution Histogram
* Box Plot for Outlier Detection
* Area Chart for Wealth Trends

## 📊 Key Insights

* Technology-related businesses contribute significantly to billionaire wealth.
* Wealth distribution is highly skewed.
* Several extreme outliers exist among the world's richest individuals.
* A small number of industries account for most billionaire wealth.

## 🚀 How to Run

### Install Dependencies

```bash
pip install pandas requests beautifulsoup4 matplotlib seaborn
```

### Run Notebook

```bash
jupyter notebook project.ipynb
```

## 📁 Project Structure

```text
├── project.ipynb
├── bloomberg.csv
├── bloomberg2.csv
├── README.md
```

## 📈 Sample Visualizations

* Source-wise Wealth Bar Chart
* Wealth Histogram
* Box Plot
* Area Plot

## 👨‍💻 Author

**Ganesh Karli**

* Data Analytics
* Business Intelligence

