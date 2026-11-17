# Analysing Pharmaceutical Sales Data

## Project overview

This project explores pharmaceutical sales data using Python, Pandas and Matplotlib. The daily dataset contains sales values for eight ATC drug categories from 2 January 2014 to 8 October 2019.

The analysis compares total and average daily sales, checks the leading categories in selected months and in 2017, and looks at monthly patterns for respiratory drugs (R03).

## Project questions and results

### 1. What are the total sales quantities for each drug category?

| ATC category | Total sales |
|---|---:|
| N02BE | 63,005.4027 |
| N05B | 18,645.7375 |
| R03 | 11,608.8229 |
| M01AB | 10,600.9371 |
| M01AE | 8,204.6186 |
| N02BA | 8,172.2090 |
| R06 | 6,107.8175 |
| N05C | 1,249.9583 |

N02BE has the highest total sales in the dataset.

### 2. Which individual drug brands have the highest total sales?

The dataset does not include individual product or brand names. It contains ATC category columns, so brand sales cannot be ranked from this data.

### 3. Which three categories had the highest sales in the selected months?

| Month | Top three categories by total sales |
|---|---|
| January 2015 | N02BE (1,044.24), N05B (463.00), R03 (177.25) |
| July 2016 | N02BE (652.36), N05B (240.00), M01AB (194.53) |
| September 2017 | N02BE (863.75), N05B (223.00), R03 (139.00) |

### 4. Which category had the most sales in 2017?

N02BE had the highest recorded sales in 2017, at approximately 9,258.80.

### 5. Which category had the highest average daily sales?

N02BE had the highest average daily sales, at approximately 29.92.

### 6. Are respiratory drugs (R03) sold more during specific months?

R03's average daily sales were highest in December (about 7.92) and October (about 7.21). They were lowest in July (about 2.96). This suggests R03 sales tend to be higher in some cooler months in this dataset.

## Tools used

- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook

## Files

- `Analysing_Pharmaceutical_Sales_Data.ipynb` — analysis, results and charts
- `data/salesdaily.csv` — daily sales data used for the main analysis
- `data/saleshourly.csv` — hourly sales data
- `data/salesweekly.csv` — weekly sales data
- `data/salesmonthly.csv` — monthly sales data

## How to run

Install the required libraries:

```bash
pip install pandas matplotlib

````
## What I learned
I used Pandas to explore the sales data and compare ATC categories. 
I used Matplotlib to create charts and look at monthly patterns in R03 sales.


## Project brief

https://roadmap.sh/projects/pharmaceutical-sales-data


