# 05-Matplotlib-Homework

In the event that my Jupyter Notebook file does not load correctly on GitHub, please follow the link below for better readability:
https://nbviewer.jupyter.org/github/Tgreenhu/05-Matplotlib-Homework/blob/main/05-Matplotlib-Homework.ipynb

In this assignment, we were given two CSV files, one containing meta mouse data and the other container the results of many tests ran on the mice.  To better analyze the data I first combined the 2 files together.  Noticing there was a mouse that had multiple values, I dropped both rows out of our DataFrame to eliminate and further confusion.  This DataFrame is the base of my analysis.

Using the combined DataFrame above, I created a summary of statistics DataFrame two different ways.  This included:
    - Mean
    - Median
    - Variance
    - Standard Deviation
    - SEM

Using the same DataFrame, I created the following charts:
    - Bar Chart to show number of mice tested per treatment
    - Pie Chart to show the number of female mice vs male mice tested

After narrowing down our DataFrame to 4 different treatments, I created a box plot to show potential outliers found in the final tumor volume after all 4 treatments.

After narrowing down our DataFrame to just a single treatment (Capomulin), I created the following:
    - Line Chart to show a random mouse's tumor volume over the course of all timepoints
    - Scatter Plot to show the average tumor volume vs weight for all mice treated with the drug
    - Using the scatter plot, defined the correlation coefficient & linear regression to show a postive correlation between tumor volume and weight.