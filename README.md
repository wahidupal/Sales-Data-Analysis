# Sales-Data-Analysis
12 months' worth of sales data was analyzed here
Here is a comprehensive summary of the project
1.	**Import Necessary Libraries**: The project began by importing essential Python libraries, pandas and os.
2.	**Data Collection and Merging**: I collected and merged 12 months of sales data from separate CSV files into a single panda DataFrame.
3.	**Data Cleaning**: The data was cleaned by handling missing values, erroneous entries, and data type conversions.
4.	**Data Augmentation**: I augmented the data with additional columns that could be useful for analysis. These included:
a.	'Month': Extracted from the 'Order Date' column.
b.	'Sales': Calculated by multiplying 'Quantity Ordered' and 'Price Each'.
c.	'City': Extracted from the 'Purchase Address' column, including the state to handle cities with the same name in different states.
d.	'Hour' and 'Minute': Extracted from the 'Order Date' column to identify the time of purchase.
5.	**Data Analysis**: I performed various analyses on the augmented data to answer specific business questions. These included:
e.	What was the best month for sales and how much was earned?
f.	Which city had the highest number of sales?
g.	What time should advertisements be displayed to maximize the likelihood of customers buying a product?
h.	Which products were most often sold together?
i.	Which product was sold the most and why?
Each of these questions was addressed using a combination of pandas functions to manipulate the data and matplotlib to visualize the results. I also used methods from itertools and collections to identify frequently bought-together items.
6.	**Conclusions**: Based on the analyses, I drew several conclusions about the dataset:
-	The best month for sales was December.
-	The city with the highest sales was San Francisco, CA.
-	Advertisements should be displayed around 11 am and 7 pm for maximum impact.
-	iPhone and Lightning Charging Cable were often sold together.
-	AAA Batteries were the most sold product, likely due to their low price.

This project demonstrates the proficient use of Python libraries such as pandas and matplotlib for data manipulation, analysis, and visualization. The findings could provide valuable insights for the company to drive its sales strategy.
