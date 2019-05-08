# KickStarter Analysis

Using the Excel table, analyze the data of four thousand past Kickstarter projects.

Use conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was "successful," "failed," "cancelled," or is currently "live".

Create a new column at column O called percent funded that uses a formula to uncover how much money a campaign made towards reaching its initial goal.

Use conditional formatting to fill each cell in the percent funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and then moving towards blue at 200.
Create a new column at column P called average donation that uses a formula to uncover how much each backer for the project paid on average.

Create two new columns, one called category at Q and another called sub-category at R, which use formulas to split the Category and Sub-Category column into two parts.

Create a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were "successful," "failed," "cancelled," or are currently "live" per category.

Create a stacked column pivot chart that can be filtered by country based on the table you have created.

Create a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were "successful," "failed," "cancelled," or are currently "live" per sub-category.

Create a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.
The dates stored within the deadline and launched_at columns are using unix timestamps. Fortunately for us, there is a formula out there that can be used to convert these timestamps into a normal date.

Create a new column named Date Created Conversion that will use this formula to convert the data contained within launched_at into Excel's Date format

Create a new column named Date Ended Conversion that will use this formula to convert the data contained within deadline into Excel's Date format
