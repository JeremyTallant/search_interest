# Comparing Search Interest with Google Trends
## Description
Time series data is everywhere; from temperature records, to unemployment rates, to the S&P 500 Index. Another rich source of time series data is Google Trends, where you can freely download the search interest of terms and topics from as far back as 2004. This project dives into manipulating and visualizing Google Trends data to find unique insights.

In this project, we will explore the search data underneath the Kardashian family's fame and make custom plots to find how the most famous Kardashian/Jenner sister has changed over time. 
## Contents 
1. **The sisters and Google Trends:** Load and inspect the data.
2. **Better "kolumn" names:** Improve the column names.
3. **Pesky data types:** Inspect the data types.
4. **From object to integer:** Remove the "<" characters and cast the columns to integer.
5. **From object to datetime:** Cast the month column to the datetime.
6. **Set month as index:** Set the DataFrame index to month.
7. **The early Kim hype:** Plot search interest vs. month.
8. **Kylie's rise:** Plot search interest vs. month from January 2014 onward.
9. **Smooth out the fluctuations with rolling means:** Plot a twelve-month rolling mean for search interest vs. month.
10. **Who's more famous? The Kardashians or the Jenners?** Create columns for each family line then plot search interest vs. month for each.