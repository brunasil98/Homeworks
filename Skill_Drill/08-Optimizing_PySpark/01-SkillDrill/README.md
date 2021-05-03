# Skill Drill

In this skill drill, you will revisit an activity from a previous unit - Looking at Zillow Housing Prices. Instead of using core PySpark, you will run the same workflow using your newfound SparkSQL skills!

## Instructions


1. Read the [zillow_housing_prices.csv](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-netflix/unit-7/zillow_housing_prices.csv) file into a PySpark DataFrame.

2. Create a temporary view of the DataFrame.

3. Cast the `2020-01` column to a float and display the average price per state for the month of `2020-01` using SparkSQL.

4. Repeat the same cast and average price per state calculation for the month of February (using `2020-02` column) in SparkSQL.

5. Create a SparkSQL statement that averages the price per state in February, but filters out states that are greater than $200,000 average price

6. Convert your SparkSQL DataFrame into a Pandas DataFrame, then save your Pandas DataFrame into a CSV file. Download the CSV file to your computer.

     * **Hint:** You can access your save files from clicking on the folder icon on left-hand sidebar of Google Colab.

---

© 2021 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
