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

![Screen Shot 2021-05-03 at 9 18 50 PM](https://user-images.githubusercontent.com/23372412/116951175-2fdad400-ac55-11eb-9d53-9fa843d18139.png)

Using the same DataFrame, I created the following charts:
    - Bar Chart to show number of mice tested per treatment
    - Pie Chart to show the number of female mice vs male mice tested

![Screen Shot 2021-05-03 at 9 19 22 PM](https://user-images.githubusercontent.com/23372412/116951216-3e28f000-ac55-11eb-85c4-56033cb05a90.png)
![Screen Shot 2021-05-03 at 9 19 44 PM](https://user-images.githubusercontent.com/23372412/116951231-4a14b200-ac55-11eb-9b04-d6c852d27964.png)


After narrowing down our DataFrame to 4 different treatments, I created a box plot to show potential outliers found in the final tumor volume after all 4 treatments.

After narrowing down our DataFrame to just a single treatment (Capomulin), I created the following:
    - Line Chart to show a random mouse's tumor volume over the course of all timepoints
    - Scatter Plot to show the average tumor volume vs weight for all mice treated with the drug
    - Using the scatter plot, defined the correlation coefficient & linear regression to show a postive correlation between tumor volume and weight.

![Screen Shot 2021-05-03 at 9 20 01 PM](https://user-images.githubusercontent.com/23372412/116951252-5436b080-ac55-11eb-81af-1e1e462850dd.png)
![Screen Shot 2021-05-03 at 9 20 14 PM](https://user-images.githubusercontent.com/23372412/116951267-5bf65500-ac55-11eb-8620-8f4ecaaef896.png)
![Screen Shot 2021-05-03 at 9 20 28 PM](https://user-images.githubusercontent.com/23372412/116951276-63b5f980-ac55-11eb-91ba-144183c31137.png)
