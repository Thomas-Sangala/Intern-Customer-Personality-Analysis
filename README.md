# Intern-Customer-Personality-Analysis

After importing my customer personality data into Power BI, I launched the Power Query Editor to clean and prepare the dataset for analysis. The steps I followed were:

Standardizing Column Values:
I ensured consistency across the dataset by standardizing the text format in each column. For columns containing text data, I used the "Capitalize Each Word" option. This step makes the data uniform and improves readability. To do this, I selected the relevant columns, right-clicked, and chose "Transform" > "Capitalize Each Word."

Checking for and Removing Duplicates:
Next, I checked the dataset for duplicate rows, as duplicates can lead to inaccuracies in data analysis. Using Power Query Editor, I selected all columns, went to the "Remove Rows" section, and clicked on "Remove Duplicates" to eliminate any repeated entries.

Identifying and Handling Null Values:
After cleaning duplicates, I inspected the dataset for missing or null values. On reviewing the Income column, I discovered several null entries. To handle these, I used the "Replace Values" feature in Power Query. Specifically, I replaced all null values in the Income column with 0. This step ensures that subsequent calculations (such as total or average income) do not encounter errors due to missing data.

