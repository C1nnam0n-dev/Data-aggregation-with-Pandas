# Data-aggregation-with-Pandas
This program analyzes a dataset from the 2018 Central Park Squirrel Census. It summarizes the data by counting how many squirrels have each primary fur color and creates a new CSV file with the results.

# How the program works:

- The program imports the pandas library to work with the dataset.
- It reads the squirrel census CSV file into a DataFrame.
- It filters the data by the Primary Fur Color column.
- It counts how many squirrels have the following fur colors:
  - Gray
  - Cinnamon
  - Black
- It stores these counts in a dictionary.
- The dictionary is converted into a new DataFrame.
- The program exports the summarized results into a new CSV file called squirrel_count.csv.

# What I learnt:

- How to use pandas to read CSV files
- How to filter data in a DataFrame
- How to count and summarize specific values in a dataset
- How to create a new DataFrame from a dictionary
- How to export summarized data to a CSV file
