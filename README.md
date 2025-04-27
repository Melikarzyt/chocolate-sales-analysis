# chocolate-sales-analysis
This project analyzes chocolate companies based on their ratings since 2012. We identified the top 10 companies with the highest average ratings, filtered their products, and calculated the total sales price. The goal is to better understand the best-performing chocolate brands and estimate potential revenues based on selected products.

# Project Overview

This project focuses on analyzing and filtering high-quality dark chocolates based on various features, especially from the year 2012 onwards.  
First, we performed preprocessing to standardize the price per 100g and selected chocolates with a cocoa percentage above 70%, particularly those made with Trinitario beans known for their superior quality.  
Afterwards, we focused on identifying the top 10 chocolate companies based on their average ratings, extracted relevant products, and calculated the total potential revenue.  
The final dataset (`chocolates_to_sell`) contains the best products for business insight and sales decision-making.

# Tasks Completed

- Performed preprocessing to calculate the price per 100g of each chocolate type.
- Filtered and stored dark chocolates in a separate dataset (`dark_chocolate`).
- Converted the cocoa percentage from a string format (like `'70%'`) to a numeric value.
- Filtered chocolates with a cocoa percentage of at least 70%.
- Extracted chocolates with `Trinitario = True` for higher quality selection.
- Filtered the dataset to include only records from 2012 onwards.
- Calculated the average rating for each chocolate company based on post-2012 data.
- Selected the top 10 companies with the highest mean ratings.
- Extracted all chocolate products related to these top companies.
- Calculated the total price of the selected chocolates to estimate potential revenue.
- Prepared a clean dataset named `chocolates_to_sell` containing the selected products.
- Summarized the findings to provide business insights and assist decision-making.
