# Mudano_GDP_assignment
File submission for Mudano Data Engineering assignment

For this assignment, the data I used was first aggregated in a Jupyter Notebook. I used a Python package called wbgapi to download GDP income data directly into a Pandas dataframe.
Region and IncomeGroup data was taken from the CSV file that was sent in the email. 

I used Pandas to concatenate the data on the three letter ISO country codes and removed any data that would not be necessary for the assignment.
This data was then exported to a CSV file, which was then stored in a PostgreSQL database locally and SQL queries were performed.

The Jupyter Notebook and the CSV file generated can be found attached.
SQL scripts for each questions and for the creation of the table in PGAdmin 4 can be found in the 'SQL Scripts' folder.
An explanation for my answers can be found in 'Assignment questions.docx'.
