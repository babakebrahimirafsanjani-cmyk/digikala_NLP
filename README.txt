## Data Preparation

The `digikala-comments` file was initially inspected, and some columns that were not relevant to the project were removed. However, several columns were retained despite having a high number of missing values, as they may contribute useful information to the text-processing model.

The main column, `body`, was cleaned to retain only the users’ comments and remove irrelevant characters. The cleaned data was then saved as a new CSV file.
