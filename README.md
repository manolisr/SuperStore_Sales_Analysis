# Import necessary modules
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Introduction
"""
This script is designed to perform an exploratory data analysis (EDA) on the sales and profitability of a global superstore.
The main objectives are as follows:

1. Identify the most and least profitable product categories.
2. Analyze sales and profit by segments.
3. Examine geographical sales and profit distribution.
4. Explore performance trends over the years.

The insights gained from this analysis can guide decision-making to optimize sales and profitability for the superstore.
"""


## Categories and Subcategories
- The Technology category accounts for 37.5% of sales and 45.2% of profits.
- Furniture contributes 32.5% to sales but has a lower profit margin at 19.4%.
- Office Supplies represent 30% of sales and 35.3% of profits.
- Among Furniture subcategories, only 'Furnishes' has a profit margin above the sub-category average (12.2%).
- 'Bookcases' have an 11% profit margin, 'Chairs' 9.3%, and 'Tables' suffer a loss with a -8.5% profit margin.

## Segments
- The superstore has three main segments: Consumer (51.5% of sales), Corporate (30.3% of sales), and Home Office (18.3% of sales).
- Profit margins are almost equal among segments: Consumer and Corporate at 11.5%, and Home Office at 12.5%.
- Technology, Furniture, and Office Supplies follow the same sales demand pattern in all segments.

## Geographical Markets
- The superstore's largest market is APAC, followed by the US, EMEA, and Canada.
- Canada has the lowest sales but the highest profit margins.
- The superstore operates in major markets with profit margins mainly ranging between 10% to 14%.
- EMEA stands out with lower profits and profit margins compared to other markets.

## Time Series
- Sales and profits have gradually increased from 2011 to 2014, indicating a positive trend.

# Limitations
- The data lacks population numbers for regions, making it challenging to assess market popularity.
- Demographic information would provide a better understanding of market share.

# Recommendations
- Consider discontinuing the sale of unprofitable tables and focus on the 20 most profitable table types to enhance profitability.
"""
