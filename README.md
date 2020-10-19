# WEDGE DATA ENGINEERING PROJECT

This is the completed project from Hongshen Lee

**In this practice,I complete the whole task with three notebooks:**
- Wedge Project_Task1.ipynb: Clean and upload the data into GBQ
- Wedge Project_Task2.ipynb: Carry out GBQ query and load the data into the local files, re-upload into the GBQ(in Wedge Project_Task1.ipynb)
- Wedge Project_Task3.ipynb: Create three summary tables and sqlite database.
    This task include serval files to submit：
    - sales_by_date_by_hour.csv: summary table data
    - sales_by_owner_by_year_by_month.csv:summary table data
    - sales_by_product_by_year_by_month.csv: summary table data
    - wedge_summary.db: summary db

**Also,I provide the authentication file:**
- Hong-Wedge-8a5b036bb32c.json


All task files have notes in the first cell, please task a little time to read it, thanks for that! If I made anything wrong or bad, please let me know, both slack or github is ok.(prefer slack)


## Feedback

* Don't include your raw data or your authentication file in your repo. I'd urge you to delete the .json file
soon, since that can be abused by others downloading it and using your billing information. 

* Part 1: Great use of printing to update the user. Everything looks great. 
* Part 2: Don't print those owners to the screen for final submission (but no need to change now).
That writing out part could be done more tersely with something like this: 
`text_file.write("\t".join([str(item) for item in row]) + "\n")`
* Part 3: Looks great.

Nice job, consider this **complete**.


 
