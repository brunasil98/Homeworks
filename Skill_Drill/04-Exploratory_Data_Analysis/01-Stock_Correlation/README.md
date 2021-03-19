# 4.2 Skill Drill: Stock Correlation 

In this activity, you will analyze the following five semiconductor stocks: `HD`, `INTC`, `AMD`, `MU`, `NVDA`, and `TSM`. Then you'll choose the stock with the least correlation to `JNJ` in order to diversify a portfolio. 

To learn more about diversification and how correlation in a portfolio helps to minimize risk, review this [article on diversification](https://www.investopedia.com/terms/d/diversification.asp).

## Instructions

1. Import the Pandas and Plotly Express libraries.

1. Read the CSV file into a DataFrame and set the `date` column as the index.

1. Use the `pct_change` function to calculate the daily returns. Drop `n/a` values. 

1. Use the `corr` function on the combined DataFrame to calculate and output a correlation table of each stock-to-stock pair.

1. Use the `imshow` function from the Plotly library to create a heatmap of correlation values. **Hint:** You can read more about creating heatmaps in the [Plotly documentation](https://plotly.com/python/heatmaps/).

---

© 2021 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
