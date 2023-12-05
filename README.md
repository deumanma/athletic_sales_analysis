# athletic_sales_analysis
Module 5 work

This weeks activity covered groupby, pivot tables, some binning to look at the sales data for athletic apparel for brands. I started by importing the starter code into my repository and then imported the CSVs and read in the CSV files 

Did some data cleanup and analysis to check what type of data was in the csv files, before concatenating the two data frames from 2020 and 2021 into one data frame. I used an example from the class work as noted in my code to help frame the code. 

I checked for any null values and converted the invoice_date to datetime and confirmed that worked. 

Then using groupby and pivot i determined which regions sold the most products, which regions had the most sales, and which retailer had the most sales. Even though we had to get the same data in two different ways for all three of these it was easy to re-use code for groupby's and pivot tables from the previous example so this didn't take too long. 

Then I looked at which retailer sold the most women's athletic footwear and used the groupby and pivot table to get the same data. After setting up the new total_womens_footwear_sold_df it was easy to re-use my code from the section above as well. 

Finished it off by finding out which day had the most sales based on the index date that we had reset to datetime previously. 

**Resources**

I mostly used the Class 5 activities as a reference for how to do pivots, groupby's and determining what would be the best method of joining the data. 

I had too google the syntax for binning to make sure I was getting it right, but the google top result was the information I used. 
