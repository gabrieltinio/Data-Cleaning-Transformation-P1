# Data Analyst Portfolio | Data Cleaning and Transformation

### Project Purpose
To demonstrate data cleaning and data transformation skills using Python (Pandas + Jupyter Notebook). The goal is to prepare the data for further analysis or visualization creation.

### Project Dataset Background
I will be using a dataset showing the video game sales across the world overtime. Incomplete records have already been dropped and there are no duplicates. This dataset has information on the video game itself such as the platform it was on, release date, genre, publisher, and sales.  
You can download the Kaggle dataset at the following link: https://www.kaggle.com/datasets/gregorut/videogamesales?resource=download

### Project Guiding Questions
_These are the following guiding questions I will be using for this project:_  
- Are all columns in the correct data type? If not, how can we convert them into the appropriate type?
- Can we combine the North American sales (NA_Sales) & European sales (EU_Sales) column into one column by sum then group the dataset by Platform?
- How can we manipulate the dataset to show the Top 25 games by North American sales (NA_Sales) with a release date of 2010 onwards?
- How can we rename the column headers to make them more digestable for the user?

### Project Steps Performed  
1. Import pandas
2. View dataset to gain context on values
3. View the data type of each column
4. Analyze if data types are appropriate
5. Change data types accordingly while accounting for NA values
6. Combine NA_Sales and EU_Sales and create a new column
7. Group by Platform
8. Create a new dataframe containing only games released in 2010 onwards
9. Show the top 25 games by NA_Sales
10. Analyze column names
11. Rename columns to add clarity
